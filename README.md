# websemantique

le fichier donneesIn.csv est le dataset que nous proposons.
indices.ttl est le fichier rdf correspodant à notre dataset. Ce fichier est construit à partir de la requête construct qui est dans construct.sparql sous la commande ./tarql ./construct.sparql ./donneesIn.csv > indice.ttl
requête1.rq et requête2.rq sont les deux requêtes exécutées sur notre fichier indice.ttl

ens1.ttl et ens2.ttl sont successivement les fichiers résultant de la liaison entre CO2.ttl vs indice.ttl et happiness.ttl vs indice.ttl.
qens1.rq requête sur ens1.ttl et qens2.rq requête sur ens2.ttl
