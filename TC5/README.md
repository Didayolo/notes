# Traitement des images et du signal

Par Yohann Tendero.
Contact : yohann.tendero@telecom-paristech.fr

## Liens :

- http://perso.telecom-paristech.fr/%7Eytendero
- http://perso.telecom-paristech.fr/%7Eytendero/master_aic.html
- Un cours : http://users.polytech.unice.fr/~leroux/courssignal/courssignal.html

## TODO :

### Pour le 22/09 :

- Les exercices : http://perso.telecom-paristech.fr/%7Eytendero/documents_aic_2017/exercice_2.pdf (à rendreavant le matin du 22)
- Le TP : 

  - Écrire un programme mettant en oeuvre: la translation par TFD d'une image.

  Entrée image, coordonnées vecteur de translation. Sortie l'image translatée.
  Tester pour une translation à coordonnées non entières (unité le pixel) de votre choix.

    Hint: On se souviendra que lorsque l'ordinateur calcule une TFD on a: Des fréquences positives k/N dans la  première moitié du vecteur fft(u) rangées dans l'ordre croissant. La seconde moitié correspond aux fréquences négatives (k-N)/N.  Pour une image c'est la même chose pour les deux coordonnées.

  On testera le programme pour de petites valeurs, p. ex. T_x=1/2, T_y=0 et de plus plus grandes valeurs et tachera d'expliquer ce que l'on constate.

   - Écrire un programme mettant en oeuvre: le zoom par zero padding (TFD).

  Entrée: une image et le facteur de zoom (entier). Sortie: l'image zoomée. Tester et critiquer la méthode pour un zoom de 2 et/ou 4 par exemple.

  Attention, il pourra etre utile de prendre une image pas trop grande de sorte qu'après le zoom elle puisse s'afficher entièrement...

  Pour une image couleur on traitera chaque canal indépendamment.

###Pour le 29/09 :

- Les exercices de la feuille 3 :http://perso.telecom-paristech.fr/~ytendero/documents_aic_2017/exercice_3.pdf
