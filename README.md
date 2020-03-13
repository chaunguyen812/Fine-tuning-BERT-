# Fine-tuning-BERT-
Fine tuning de modèle de pré-entrainement BERT pour classification des sentiments des commentaires des clients
Dans le cas qu'on a pas assez des données pour entrainer notre propre modèle. On peut penser au technique de Transfere Learning. 
En fin 2018, BERT est présenté, c'est un modèle de pré-entrainement par Google qui est entrainé sur Wikimédia en cent heures sur GPU,
ce qui permet BERT d'avoir un grande dictionaire de token. On peut fine-tuning BERT, ajouter ensuite des couches supplémentaires et 
entrainé sur notre data set. Avec quelque époches (de 2 à 4), on peut améliorer la qualité de notre modèle. 
