Dyaa Abou Arida

# Rapport Labo 4


**Question 1 : Combien d'utilisateurs faut-il pour que le Store Manager commence à échouer dans votre environnement de test ? Pour répondre à cette question, comparez la ligne Failures et la ligne Users dans les graphiques.**

Dans mon environnement de test, le Store Manager commence à échouer autour de 140 utilisateurs simultanés. À environ 146 utilisateurs, la ligne des échecs commence à augmenter de façon visible.

![alt text](images/image-1.png)
<p align="center">1.1 Capture d'écran de Charts</p>

---------------------------------------
**Question 2 : Sur l'onglet Statistics, comparez la différence entre les requêtes et les échecs pour tous les endpoints. Combien d'entre eux échouent plus de 50 % du temps ?**

Les trois endpoints testés échouent plus de 50% du temps. Le endpoint POST /orders échoue même 100% du temps, tandis que les deux endpoints de rapports échouent environ 67% du temps.

![alt text](images/image-2.png)
<p align="center">2.1 Capture d'écran des statistiques</p>

---------------------------------------
**Question 3 : Affichez quelques exemples des messages d'erreur affichés dans l'onglet Failures. Ces messages indiquent une défaillance dans quelle(s) partie(s) du Store Manager ? Par exemple, est-ce que le problème vient du service Python / MySQL / Redis / autre ?**

![alt text](images/image-3.png)
<p align="center">3.1 Capture d'écran des failures</p>

---------------------------------------

---------------------------------------


---------------------------------------


## CI/CD

