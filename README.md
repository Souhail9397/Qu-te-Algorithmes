# Quete-Algorithmes

CREER L'ALGORITHME

- nombre de bonbons max qu'on peut acheter en fonction argent en possession et prix du bonbon

-  entrée : réel argent (argent dispo) = 43,26        réel prix (prix d'1 bonbon) = 2,11


===> Utiliser une BOUCLE

$argent = 43,26
$bonbon = 2,11

début acheterBonbons ($bonbon)

	Tant que $bonbon < $argent
		$bonbon <- $argent - $bonbon
	Fin Tant que
	retourner entier

fin acheterBonbons
