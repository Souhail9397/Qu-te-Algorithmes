$argent = 43,26  
$prixBonbon = 2,11  
$nombreBonbons = 0

début acheterBonbons ($prixBonbon, $argent)

	Tant que $prixBonbon ≤ $argent
		$argent <- $argent - $prixBonbon
  			$nombreBonbons <- $nombreBonbons + 1
	Fin Tant que
	retourner entier

fin acheterBonbons
