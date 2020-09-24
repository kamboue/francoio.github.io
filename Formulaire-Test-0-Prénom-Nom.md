---
title: "Formulaire de réponse pour le test 0 -- TD-1"
output: pdf_document
---

** **



#### Problème 1 



##### Question 1

* Déterminer la probabilité de l'événement $(N_E > k)$, pour tout $k \geq 1$. Quelle est la loi de $N_E$ ?

###### Réponse :
P($(N_E > k)$)=\sum_k^\infty(\frac{5}{6})^{n-1}\time\frac{1}{6} \\(elle\,le\,tire\,a\,la\,nieme\,partie\,n>k\,et\,donc\,rate\,les\,precedents)\\et\,donc\,par\,calcul\,de\,somme\,infini\,on\,a\,:\,P($(N_E > k)$)=(\frac{5}{6})^{k}

##### Question 2

* Calculer la probabilité de l'événement $(N > k)$, pour tout $k \geq 1$. Quelle est la loi de $N$ ?

###### Réponse :
par\,calcul\,similaire\,et\,sachant\,que:\:P(Eva\,ou\,Ralph\,tire\,1)=\frac{2}{7}\,on\,obtient\,P($(N > k)$)=\frac{5}{7}
##### Question 3

* Quelle est la probabilité pour que Eva gagne ? 

###### Réponse : 
EG=<<Eva\,gagne>>\\ c_a_d\,soit\,au\,1er\,lancer\,...\,ou\,au\,ieme\,lancer\,avec\,des\,nuls\,entre-temps\\
P(nul)=\frac{1}{42}\\
P(EG)=\sum_1^\infty(\frac{1}{42})^{k-1}\time\frac{1}{7}=\frac{6}{41}

##### Question 4

* Quelle est la probabilité de match nul ?


###### Réponse : 
comme\,dit\,precedemment\,P(NUL)=\frac{1}{6\times7}=\frac{1}{42}\\car\,les\,evenements\,Eva\,tire\,1\,et\,Ralph\,tire\,1\,sont\,independants
##### Question 5

* Calculer la probabilité que la partie a duré moins de 3 manches sachant qu'Eva a gagné.


###### Réponse : 
M3=<<moins\,de\,3\,manche>>\\
EG=<<Eva\,gagne>>
P(M3)_{EG}=\frac{P(M3\cap EG)}{P(EG)}\\
P(M3\cap EG)=\frac{1}{6}\timesfrac{5}{7}+\frac{1}{42}\timesfrac{1}{6}\times\frac{6}{7}+\frac{1}{42}\timesfrac{1}{42}\times\frac{1}{6}\timesfrac{5}{7}

** **

#### Problème 2


  
##### Question 1

*  Calculer la probabilité que la variable aléatoire $W$ soit inférieure ou égale à $1/3$.  

###### Réponse : 
P(W \preceq \frac{1}{3})=P(((U\prec\frac{1}{4})\cap(V\prec\frac{1}{3}))\cup(U\geq\frac{1}{4})\cap(V\prec\frac{1}{9})))\\
par\,independance\,et\,incompatibilte\,on\,a\,:P(W \preceq \frac{1}{3})=\frac{1}{4}\times\frac{1}{3}+\frac{3}{4}\times\frac{1}{9}=\frac{1}{6}
  
##### Question 2

*  Calculer l'espérance de la variable aléatoire $W^2$.  

###### Réponse :
E(w^{2})= \int_0^1 xF_{w^{2}}'(x)dx\\
avec F_{w^{2}}(x)=P(w\preceq\sprt{x})=\frac{\sqrt{x}}{4}+\frac{3x}{4}\\
par\,calcul\,on\,a\,donc\,E(w^{2})=\frac{11}{24}
** **

#### Problème 3 


##### Question 1

*  Calculer l'espérance de la variable aléatoire $Z$.  

###### Réponse : 
E(Z)=E(X)+E(Y)\\
avec\,E(X)=\frac{1}{2}\,et\,E(Y)=\frac{x}{2}=\frac{E(X)}{2}=\frac{1}{4}
