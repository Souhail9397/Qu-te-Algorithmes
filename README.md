$argent = 43,26  
$bonbon = 2,11

début acheterBonbons ($bonbon)

	Tant que $bonbon < $argent
		$bonbon <- $argent - $bonbon
	Fin Tant que
	retourner entier

fin acheterBonbons
