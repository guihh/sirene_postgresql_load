# sirene_postgresql_load
Requêtes pour charger la bdd SIRENE csv dans postgresql

Note : Le format de "ESAANN" est YYYY et "AMINTREN" est YYYYMM mais je n'ai pas encore réussi à le parser avec le type date donc pour le moment j'ai choisi d'utiliser character(4) character(6) comme type respectivement.
