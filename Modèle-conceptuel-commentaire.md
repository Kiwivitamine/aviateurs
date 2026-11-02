Ce document contient le commentaire, avec exemples, du modèle conceptuel
# Person
Tout être humain. Donc dans mon cas il s'agit de pilotes de la seconde guerre mondiale.
## Propriétés
Nom standard, date de naissance, formation, date de décès. Il s'agit d'une classe objet (persistent item)
# Grade
Le grade de la personne .Il s'agit d'une classe objet (persistent item)
## Propriétés
Nom standard, notice
## (Relations)
(Une relation réfléxive de spécialisation, termes plus génériques associés à des termes plus précis. Par exemple 'épicier' spécialise le terme de 'négociant'.)
# Conflit
Le fait d'avoir participé à tel conflit pendant la guerre.
## Propriétés
Date de début, date de fin, nom standard
## (Relations)
(Une Pursuit peut comprend une et une seule personne, une et une seule occupation (ces deux relations sont nécessaires) et éventuellement on peut associer une (et une seule) organisation auprès de laquelle l'activité est exercée.
Si plusieurs organisation sont concernées par une activité, plusieurs individus de la classe Pursuit seront créées.)
# Compagnie
Le fait d'avoir servi pour tel compagnie durant la guerre
## Propriétés
Nom standard, date de création, type
## (Relations)
(Relation reflexive (d'un classe vers elle même) qui créer une taxonomie (i.e. une hiérarchie) de mots clés, les plus généraux étant les parents ou ancêtres des plus spécifiques.)
# Distinctions françaises
Les récompenses données aux aviateurs. Un aviateur peut avoir plusieurs récompenses.
## Propriétés
Nom standard, décerné par, décerné pour, éligibilité
# Lieu géographique
## Propriétés
Nom standard, longitude, latitude
