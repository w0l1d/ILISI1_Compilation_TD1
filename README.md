# ILISI1_Compilation_TD1


## Exercices 1 : Trouver un automate reconnaissant :
### Question 1 :
L'ensemble de nombres entiers (signés ou non) sur l'alphabet A = {+, -,0, . . . ,9}.
![image](https://user-images.githubusercontent.com/49680822/166982004-166a23ba-4e9f-447e-a3ac-703455760341.png)


### Question 2 :
L = l'ensemble des mots sur A = {a, b}. Terminant par aba.
i.e. L = {waba|w𝜖A*}.
![image](https://user-images.githubusercontent.com/49680822/166982357-a673918f-eeac-4be8-92e1-154d31d6726d.png)


## Exercice 2 :
### a.Donnez un automate déterministe qui reconnait un message composé d’une suite de 0 et de 1,
et ne contenant pas de séquence « 000 » celle-ci indique la fin d’un message.
La longueur <30 ;



### b.Ecrire un algorithme qui reconnait un message correct, sachant que la fin d’une chaine est un
blanc et qu’une chaine est composée d’un seul message.


## Exercice 3 : Donner une expression régulière ainsi qu'un automate déterministe qui représentent
les langages suivants :
### Question 1 : Donner une expression régulière ainsi qu'un automate déterministe qui représentent
les langages suivants :

#### a) L = { m | m ∈ {a, b}* et m contient ‘ba’ comme sous-mot }
![image](https://user-images.githubusercontent.com/49680822/166959176-4b1af8de-fc1b-44ba-ad55-43c7a1e05e06.png)


#### b) L = { m | m ∈ {a, b, c}* et m commence par un ‘a’ et se termine par ‘bc’ }
![image](https://user-images.githubusercontent.com/49680822/166960789-cb87e0f8-6568-48c7-ae30-ba927d532f95.png)


#### c) L = { m | m ∈ {a, b}* et m ne contient PAS un nombre de ‘b’ égal à 2 }
![image](https://user-images.githubusercontent.com/49680822/166961509-4f160f35-9703-4f6c-8e48-5fe169268d1d.png)


#### d) L = { m | m ∈ {a, b}* et m contient un nombre de ‘b’ égal à 2 }
![image](https://user-images.githubusercontent.com/49680822/166961818-87724da1-2782-4637-a33e-0a6ec8f17c29.png)



#### e) L = { m | m ∈ {a, b}* et m se termine par ‘bab’ OU ‘bb’ }
![image](https://user-images.githubusercontent.com/49680822/166963012-8fa4f92d-0654-43fc-bf3f-9afbbfd6a133.png)



#### f) L = { m | m ∈ {a, b}* et m contient au plus 2 ‘a’ et au moins 2 ‘b’ }
![image](https://user-images.githubusercontent.com/49680822/166972270-0e25a658-a6f3-4666-b6cb-03de27ab5d5b.png)




### Question 2. Ecrivez une expression régulière sur l’alphabet Σ = {a, b, c} dont le langage associé est
exactement l’ensemble des mots ou a est toujours suivi de b et b est toujours suivi de a, sauf
éventuellement pour le dernier symbole du mot.

### Question 3. Ecrivez une expression régulière sur l’alphabet Σ = {a, b} dont le langage associé est
exactement l’ensemble des mots qui ne contiennent jamais deux a consécutifs.

### Question 4. Est-ce que les expressions régulières suivantes contiennent le mot vide ε ?
#### - (a+ba*)*+b(a+(b+aba)*)*
##### Oui

#### - (1 + b)(aa*+bb*a)*
##### Non

#### - (1 + a)(1 + b)(1 + c)(1 + d)(e+f)
##### Non

#### - (a+ (b+ (c+d)*)*)*
##### Non


## Exercice 4. Soit A = {a, b, c}. Pour chacun des langages suivants, donner un automate fini
déterministe (AFD) le reconnaissant :
### a) l’ensemble des mots dont la longueur est un multiple de 3 ;
![image](https://user-images.githubusercontent.com/49680822/166954320-044e3632-4053-4d0c-aeff-7b4fb040ddb3.png)

### b) l’ensemble des mots dans lesquels chaque occurrence du motif ab (s’il y en a), est suivie
de ccc ;
#### REGEX : ((b|c)|((a+bccc)|a+c))*|(a|c)* 
![image](https://user-images.githubusercontent.com/49680822/166952607-d622015e-1c0a-402c-b812-8c41a45e1f81.png)


### c) l’ensemble des mots se terminant par b ;
![image](https://user-images.githubusercontent.com/49680822/166955215-f0bae7f5-18cb-4e8f-be01-08b77b0c2aa6.png)


### d) l’ensemble des mots ne se terminant pas par b ;
![image](https://user-images.githubusercontent.com/49680822/166954996-62b23611-dd0c-4a50-83af-42129516b346.png)


### e) l’ensemble des mots contenant exactement un b ;
![image](https://user-images.githubusercontent.com/49680822/166955576-6adbe04e-b54b-4118-8129-91878f256094.png)


### f) l’ensemble des mots ne contenant aucun b ;
![image](https://user-images.githubusercontent.com/49680822/166955786-5abd3607-d014-4089-a4e9-85e18c6d1fc5.png)


### h) l’ensemble des mots comportant au moins 3 lettres et dont la troisième lettre à partir de la fin est
un a ou un c ;
![image](https://user-images.githubusercontent.com/49680822/166956809-6712d3c6-ae60-4544-97aa-3b3419a12ddf.png)




## Exercice 5. Déterminiser l’automate suivant :
![image](https://user-images.githubusercontent.com/49680822/166952094-66120544-6b53-45ef-91d6-d9f760f49358.png)

![image](https://user-images.githubusercontent.com/49680822/166983257-90db154a-176e-4c65-94b7-4b73474e35c8.png)



## Exercice 6. Construire l’automate fini correspondant aux expressions régulières suivantes.
### a) (a + b)*c
![image](https://user-images.githubusercontent.com/49680822/166957330-4dec87d0-02c7-415a-878f-f45740e00a9e.png)



### b) a* (ε + bb)a + ε
![image](https://user-images.githubusercontent.com/49680822/166958407-ab7c97e1-17b7-498d-834a-d92f342e1887.png)



