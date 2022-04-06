
#Relational database:
En informatique, une [DATA BASE] est simplement une collection structurée de données auxquelles il est possible d'accéder électroniquement et d'y écrire.
[DB] peuvent stocker toutes les informations que vous pouvez représenter dans une application utilisant Kotlin.

Sur les appareils mobiles, les [DB] sont couramment utilisées pour enregistrer les data d'une app en cours d'exécution afin qu'elles
soient accessibles la prochaine fois que l'application est ouverte, sans récupérer les données d'une autre source, comme Internet.
C'est ce qu'on appelle [data persistence]

#data persistence
Lorsque vous parlez de [data persistence], vous entendrez souvent le terme [Relational database] .
[Relational DB] est un type courant de [DB] qui organise les données en [tables, colonnes et lignes.]

#table
 Une table dans une [Relational DB] fonctionne de la même manière, qu'une [class] (représentent des objets)
 En plus de représenter des données, les [tables] peuvent également référencer d'autres tables afin que vous puissiez avoir des relations entre elles.
 Les relations du monde réel peuvent être représentées par des relations entre les tables.

#Tables, columns, and rows
Définir les tables, ou les données que vous représentez, n'est que la première étape de la création d'une [Relational DB].
Vous devez également réfléchir aux informations spécifiques stockées dans chaque table.

Les [proprieties] spécifiques sont représentées par des [columns] . Une colonne se compose d'un [name et data type].
Une [columns] est une propriété spécifique de la "chose" créée avec chaque entrée de la table.

Les entrées de table individuelles sont appelées [rows] . C'est comme une instance d'une classe dans Kotlin. 
Chaque [row] contient des données correspondant à chaque [columns]. 
La table fournit le modèle, mais les [rows] définissent les données réelles stockées dans la table.

# Primary Key:
Identifiant unique pour chaque ligne de la table.

# Data types:
Tout comme avec la définition des propriétés des classes Kotlin, les colonnes d'une base de données peuvent être l'un des nombreux types de données possibles.
Lorsque vous travaillez avec [Room], vous travaillez principalement avec des types Kotlin, mais ils correspondent à des types SQL en arrière-plan.


# SQL :
Lorsque vous accédez à une [Relational DB], que ce soit seule ou à l'aide d'une bibliothèque telle que [Room], vous aurez besoin de quelque chose appelé [SQL].
[SQL (Structured Query Language)]  vous permet de lire et de manipuler des données dans une [Relational DB]

#SQL statements(Instructions):

[SELECT] { Obtient des informations spécifiques à partir d'une table de données et les résultats peuvent être filtrés et triés de différentes manières. }

[INSERT] { Ajoute une nouvelle ligne à un tableau. }

[UPDATE] { Met à jour une ligne (ou des lignes) existante(s) dans une table. }

[DELETE] { Supprime une ligne (ou des lignes) existante(s) d'un tableau. }
