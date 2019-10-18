FR: White Label

L'objectif de ce projet est de créer un site de commerce électronique en marque blanche. La pratique de la marque blanche 
consiste à créer un produit ou un service que d'autres entreprises vont prendre en charge et commercialiser sous leur 
propre nom. Il s'agit donc d'un mécanisme commercial de mise à disposition d'outils ou de produits, sans mentionner la 
marque ou l'origine des informations transmises.

Afin de rendre le site operationnel il est conseillé de suivre les étapes suivantes:

1- En tout premier lieu, vous allez devoir laisser l'url du repo github dans le fichier "gatsby-config.js". Pour cela, au niveau du plugin intitulé "gatsby-source-git" vous écrivez l'adresse du repo face à la variable "remote".

2- Remplir le fichier "config.md" situé à la racine du projet. Pour cela indiquer le nom de l'entreprise, la description et
l'url du logo.

3- Il vous faut ensuite ajouter vos produits, pour ce faire vous allez créer un .md pour chaque fichier souhaité dans le 
dossier "content". Renseigner ensuite le fichier par les caractéristiques du produit (name, price, description, type et
l'image). Pour les images il vous faut renseigner le nom de l'image et sauvegarder celle-ci dans le dossier "img".

4- Vous pouvez désormais lancer le site en utilisant yarn et gatsby. Pour cela dans votre terminal apres vous être déplacé 
dans le dossier jamstack entrer la commande "yarn" puis "gatsby build" pour lancer le site

5- Regarder le resultat en vous rendant sur l'adress localhost:8000/




EN: White Label

The objective of this project is to create a white label e-commerce site. The practice of white labeling 
is to create a product or service that other companies will support and market under their 
own name. It is therefore a commercial mechanism for making tools or products available, without mentioning the 
brand or origin of the information transmitted.

In order to make the site operational it is advisable to follow the following steps:

1- First of all, you will have to leave the url of the github repo in the "gatsby-config.js" file. To do this, in the plugin called "gatsby-source-git" you write the repo address in front of the "remote" variable.

2- Fill in the "config.md" file located at the root of the project. To do so, indicate the name of the company, the description and
the logo url.

3- You must then add your products, to do this you will create an.md for each desired file in the 
"content" folder. Then fill in the file with the product characteristics (name, price, description, type and
the image). For images you must enter the name of the image and save it in the "img" folder.

4- You can now launch the site using yarn and gatsby. To do this in your terminal after you have moved 
in the jamstack folder enter the command "yarn" then "gatsby build" to launch the site

5- Look at the result by going to the local addresshost:8000/
