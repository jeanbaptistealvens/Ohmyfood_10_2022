https://jeanbaptistealvens.github.io/Ohmyfood_10_2022/

Notes sur l'évaluation concernant les points 3. et 5. à corriger :

.3 Après vérification, aucune marge blanche droite n'est visible dans les dernières versions de Microsoft Edge, Mozilla et Chrome. Ce site est compatible via le préfixe automatique pour 103 versions de navigateurs web.
Pour des raisons de lisibilité, les tailles de police des pages restaurant pour la version tablette [media="screen only and (min-width : 710px) and (max-width : 799px)"], celui-ci a été optimisé. En effet, une correction a été apportée : l'ancienne version intégrant la propriété de grille à 3 colonnes a été passée à la nouvelle version à une colonne.
De plus, les tailles de police sont toutes lisibles. Il n'y a pas ce problème sur la version desktop. Je ne favoriserais pas les pixels pour des tailles cohérentes. Il est clairement mentionné dans le brief ci-dessous que sur tablette et desktop, le site devra s'adapter, mais ces supports ne sont pas prioritaires, leur mise en page est libre et il n'y a aucune obligation d'utiliser des pixels.
Le cœur est en dégradé de couleur comme le montre le modèle.
Les 3 points du loader sont visibles et centrés sur les versions mobile, tablette et desktop.

.5 Le code CSS ne génère aucune erreur, passé au W3C. Je ne supprimerais pas le fichier all.min.css car il est nécessaire et ne pose pas de problème.


Brief créatif du site Ohmyfood

Identité

    Ohmyfood est une entreprise de commande de repas en ligne.
    Notre concept permet aux utilisateurs de composer leur propre menu et réduire leur temps d’attente dans les restaurants car leur menu est préparé à l’avance.
    Plus de perte de temps à consulter la carte !

Proposition

    Nous souhaitons proposer à nos clients les menus de restaurants gastronomiques.
    Développé à New-York dans un premier temps, nous souhaitons désormais élargir notre concept à la capitale de la gastronomie : Paris.

Positionnement

    Nous nous positionnons sur un marché de niche, avec les restaurants luxueux des villes dans lesquelles nous sommes établis.
    Nous souhaitons être identifiés comme une entreprise proposant des services haut de gamme.

Concurrence

Mylittlefoodie :

    Environ 50 salariés d’après leur site web.
    Réservation de tables dans les palaces parisiens.
    Bonne implémentationen France.
    Tarifs préférentiels sur les menus.
    Site web très dynamique.
    Bon référencement.
    Pas de possibilité de voir les menus.
    Dates de réservation limitées à 2 jours par semaine.

Tandis que :

LebonParis :

    15 salariés.
    Classement des restaurants en fonction de leurs menus.
    Beaucoup de choix de restaurants.
    Menus très bien mis en avant sur la page d’accueil.
    Pas de possibilité de réservation.
    Pas de possibilité d’agrandir les menus.

Cible

    Classes moyennes et supérieures, connectées et souvent pressées, souhaitant déguster des produits de qualité.

Identité graphique

    Polices
    Logo et titres: Shrikhand
    Texte: Roboto

Couleurs

    Primaire Secondaire Tertiaire
    #9356DC #FF79DA #99E2D0

Problématique

    Nous souhaitons ouvrir nos services à la capitale française.

Objectifs

    Phase 1 : Développer un site proposant le menu de 4 grands restaurants parisiens.
    Phase 2 : Permettre la réservation en ligne et la composition de menus.

Fonctionnement

    Budget 20 000 €

Planning

    Date de livraison de la première version du site : sous 1 mois.
    Date de livraison de la deuxième version du site : sous 6 mois.

Technologies

    Le développement devra se faire en CSS, sans JavaScript.
    Aucun framework ne devra être utilisé, en revanche l’utilisation de SASS serait un plus.
    Aucun code CSS ne devra être appliqué via un attribut style dans une balise HTML.
    Tout le code doit être versionné sur GitHub et le site devra être accessible sur Github Pages une fois terminé.

Compatibilité

    La cible étant les personnes connectées et pressées, le site sera développé en utilisant l’approche mobile-first.
    Pour cette raison, seules des maquettes mobiles seront réalisées.
    Sur tablette et desktop, le site devra s’adapter, mais ces supports n’étant pas prioritaires, leur mise en page est libre.
    L’ensemble du site devra être responsive sur mobile, tablette et desktop.
    Les pages devront passer la validation W3C en HTML et CSS sans erreur.
    Le site doit être parfaitement compatible avec les dernières versions desktop de Chrome et Firefox.

Livrables attendus

🟣 Contenu des pages

Page d’accueil (x1)

    Affichage de la localisation des restaurants. À terme il sera possible de choisir sa localisation pour trouver des restaurants proches d’un certain lieu.
    Une courte présentation de l’entreprise.
    Une section contenant les 4 menus sous forme cartes. Au clic sur la carte,l’utilisateur est redirigé vers la page du menu.

Pages de menu (x4)

    4 pages contenant chacune le menu d’un restaurant.

Footer

    Le footer est identique sur toutes les pages.
    Au clic sur “Contact”, un renvoi vers une adresse mail est effectué.

Header

    Le header est présent sur toutes les pages.
    Sur la page d’accueil, il contient le logo du site.
    Sur les pages de menu, il contient en plus un bouton de retour vers la page d’accueil.

🟣 Effets graphiques et animations

    Les effets accessibles au clic ou au survol sont visibles sur la maquette.
    Ils devront utiliser les animations ou transitions CSS, pas de JavaScript ni de librairie.

Boutons

    Au survol, la couleur de fond des boutons principaux devra légèrement s’éclaircir.
    L’ombre portée devra également être plus visible.
    À terme, les visiteurs pourront sauvegarder leurs menus préférés. Pour ça, un bouton "J’aime" en forme de coeur est présent sur la maquette.
    Au clic, il devra se remplir progressivement. Pour cette première version, l’effet peut être apparaître au survol sur desktop au lieu du clic.

Page d’accueil

    Quand l’application aura plus de menus, un “loading spinner” sera nécessaire. Sur cette maquette, nous souhaitons en avoir un aperçu.
    Il devra apparaître pendant 1 à 3 secondes quand on arrive sur la page d'accueil, couvrir l'intégralité de l'écran, et utiliser les animations CSS (pas de librairie).
    Le design de ce loader n’est pas défini, toute proposition est donc la bienvenue tant qu’elle est cohérente avec la charte graphique du site.

Pages de menu

    À l’arrivée sur la page, les plats devront apparaître progressivement avec un léger décalage dans le temps. Ils pourront soit apparaître un par un, soit par groupe “Entrée”, “Plat” et “Dessert”. Un exemple de l’effet attendu est fourni.
    Le visiteur peut ajouter les plats qu'il souhaite à sa commande en cliquant dessus.
    Cela fait apparaître une petite coche à droite du plat. Cette coche devra coulisser de la droite vers la gauche. Pour cette première version, l’effet peut apparaître au survol sur desktop au lieu du clic. Si l’intitulé du plat est trop long, il devra être rogné avec des points de suspension.
    Un exemple de l’effet attendu est fourni.

Organisation interne du projet

    Chef de projet : Paul
    UX Designer : Fanny
    Circuit de validation : toutes les étapes du projet seront validées par Paul.
