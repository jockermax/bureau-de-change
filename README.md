# bureau-de-change

Le projet bureau-de-change est une application de conversion de devises efficace et conviviale qui permet aux utilisateurs de convertir des montants entre différentes devises de manière transparente.

Avec une architecture bien conçue, le convertisseur de devises Java permet une conversion de devises précise et fiable. L'interface utilisateur est intuitive, permettant aux utilisateurs de sélectionner les devises source et cible, de saisir le montant et d'obtenir des résultats de conversion instantanés et précis.

Affichage des menus :

Le programme commence par afficher un menu avec trois options de devises : 1 pour les roupies, 2 pour les dollars et 3 pour les euros.
Entrée de l'utilisateur :

Le programme utilise la Scannerclasse pour prendre en compte les entrées de l'utilisateur concernant le choix de la devise (un entier) et le montant à convertir (un double).
Logique de conversion :

Selon le choix de l'utilisateur (1 pour les roupies, 2 pour les dollars ou 3 pour les euros), le programme appelle l'une des trois méthodes de conversion : Ruppe_to_other, Dollar_to_other, ou Euro_to_other.
Méthodes de conversion :

Ruppe_to_other(double amt): Cette méthode est appelée lorsque l'utilisateur sélectionne des roupies (choix 1). Il affiche les taux de conversion entre les roupies, les dollars et les euros et calcule les montants convertis en fonction du montant fourni par l'utilisateur.

Dollar_to_other(double amt): Cette méthode est appelée lorsque l'utilisateur sélectionne Dollars (choix 2). Il affiche les taux de conversion entre les dollars, les roupies et les euros et calcule les montants convertis en fonction du montant fourni par l'utilisateur.

Euro_to_other(double amt): Cette méthode est appelée lorsque l'utilisateur sélectionne Euros (choix 3). Il affiche les taux de conversion entre les euros, les roupies et les dollars et calcule les montants convertis en fonction du montant fourni par l'utilisateur.

Formules de conversion :

Les formules de conversion sont codées en dur dans chaque méthode de conversion en fonction des taux de change spécifiés dans le code. Par exemple, pour convertir des roupies en dollars, il multiplie le montant en roupies par le taux de conversion.
Sortir:

Le programme affiche les taux de conversion et les montants convertis dans les devises sélectionnées.
