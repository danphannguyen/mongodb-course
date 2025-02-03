=== MONGODB ===

(Commande avec mongodb et leur utilité)

`mongosh` -> lance le serveur mongo
`show databases` -> voir toutes les BDD
`use mmi` -> selectionne la bdd a utiliser
`show collections` -> montre toute les collections de la bdd utiliser
`db.items.find({})` -> renvoie les données de la collections

`db.items.remov({})`-> supprime toute les données de la collections


=== Info Utile ===

= package =
`dotenv` permet d'importer les variables du .env
`mongoose` permet de faire le pont entre le server mongodb et mon application ( sait comment communiquer )

= mongodb =
`.find({})` renvoie toute les occurences en BDD
`.find({ price: { $gte: min, $lte: max } })` renvoie toute les occurences entre les prix définis
`.sort({ price: -1 })` trie selon un ordre ASC = 1 ou DESC = -1


