# AI-based-FPGA-on-vivado

Implémentation des réseaux de neurone permettant de reconnaitre les chiffres allant de 0 à 9.

Les étapes de développement de ce système sont les suivants :

-	Apprendre un système de neurone utilisant la base de données MNIST sur Python.
La base de donnée MNIST est ouverte aux grands publique.\
-	Sauvegarde des paramètres tels que : les Weights & Biases
-	Implémentation des réseaux de neurone sur vivado en utilisant verilog.
La connexion des neurones est basée sur le FSM (Finie State Machine)
La figure suivante représente un neurone : 

Neurone vu de manière générale：

![Untitled Diagram drawio(2)](https://user-images.githubusercontent.com/22806623/191124260-796cc4e6-5215-4d31-8854-17c491b29e44.png)

Neurone vu en détaille ：

![Untitled Diagram drawio(5)](https://user-images.githubusercontent.com/22806623/191124444-0c85a9b4-1000-4b92-b541-ab68d740a67e.png)


-	Implémentation du testbench pour comparer la précision obtenue de vivado à celle obtenue de python
-	Implémentation du côté software sur vivado IDE
-	Conversion d’une image en text et la passée en entrée de la carte zybo20 pour valider le système.
-	La figure suivante est le résultat obtenu au niveau de vivado :


![image](https://user-images.githubusercontent.com/22806623/191125334-0e22c08b-0c4d-4548-96b9-1af172ab7343.png)


Le système complet avec le processeur Zynq :

![image](https://user-images.githubusercontent.com/22806623/191125514-8ae686dc-4445-481f-bb2e-45aa7a5c88f5.png)
