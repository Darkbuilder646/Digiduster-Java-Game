<a name="readme-top"></a>

<!-- PROJECT INTRO -->
<div align="center">

  <h1 align="center">DigiDuster</h1>

  <p align="center">
    <h3>Un jeu de Roguelike à l'interieur d'un ordinateur</h3>
    un projet Epitech de
    <br />
    <a href="https://github.com/Darkbuilder646">Darkbuilder646</a>
    ·
    <a href="https://github.com/Sainseya">Sainseya</a>
    ·
    <a href="https://github.com/Natchii59">Natchii59</a>
  </p>
</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Sommaire</summary>
  <ol>
    <li>
      <a href="#about-the-project">A propos du jeu</a>
      <ul>
        <li><a href="#built-with">Techonologie</a></li>
        <li><a href="#features">Caractéristiques</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Pour commencer</a>
      <ul>
        <li><a href="#prerequisites">Prérequis</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#utilisation">Utilisation</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->
## A propos du jeu
Incarnez un curseur de souris héroïque dans <strong>DigiDuster</strong>, un rogue-like captivant où vous explorez un bureau virtuel Windows, détruisez des virus cachés, améliorez vos capacités grâce aux icônes et traquez la source mère pour sauver le système d'une menace informatique imminente.

<p align="right">(<a href="#readme-top">haut de page</a>)</p>

### Techonologies

Le projet à été créer en utilisant ces langages, librairies et logiciels

<strong>Programming :</strong>

* [![Java][Java]][Java-url]
* [![LibGDX][LibGDX]][LibGDX-url]
* [![Gradle][Gradle]][Gradle-url]

<strong>Art et sons :</strong>

* [![Adobe Illustrator][Illustrator]][Illustrator-url]
* [![Audacity][Audacity]][Audacity-url]

<strong>Organisation :</strong>

* [![Notion][Notion]][Notion-url]
* [![Git][Git]][Git-url]


<p align="right">(<a href="#readme-top">haut de page</a>)</p>

<!-- USAGE EXAMPLES -->
### Caractéristiques

* <strong>Immersion dans un ordinateur :</strong> Voyagez à travers des dossiers dans un ordinateur virtuel afin de trouver et éliminer des virus.

* <strong>Des combinaisons d'objets :</strong> Récupérez des objets grâce aux icônes du bureau pour créer votre propre stratégie afin de venir à bout de vos ennemis.

* <strong>Combat de boss :</strong> Trouvez et détruisez le boss de chaque niveau, représentant une menace connue des ordinateurs.

* <strong>Génération aléatoire:</strong> Chaque partie est différente avec une génération aléatoire du niveau et des endroits à explorer.

<p align="right">(<a href="#readme-top">haut de page</a>)</p>

<!-- Installation -->
## Pour commencer

Pour utiliser ou jouer à DigiDuster, suivez les étapes suivantes :

### Prérequis

Avant de commencer, assurez-vous d'avoir les éléments suivants installés :

* Java : Téléchargez la version la plus récente de Java depuis : https://www.oracle.com/java/technologies/downloads.
* Gradle : Assurez-vous d'avoir aussi Gradle installé, vous pouvez le télécharger depuis : https://gradle.org/install.

### Installation

1. <strong>Clonez le dépôt :</strong> 

    ```bash
    git clone https://github.com/EpitechMscProPromo2026/T-JAV-501-LIL_16.git
    ```
2. <strong>Configuration de Gradle :</strong> Accédez au répertoire du projet et exécutez la commande suivante :

    ```sh
    gradle init
    ```
    Cela permet de générer les fichiers nécessaires de configuration de Gradle, ensuite suivez les instructions pour configurer Gradle selon vos besoins.
    
<br/>

3. <strong>Lancement de l'application :</strong>

    Pour lancer l'application, utilisez la commande Gradle suivante à la racine du projet :
    ```sh
    gradle run
    ```
    Cela compilera et exécutera votre application LibGDX.

5. <strong>Accès au jeu :</strong>

    Ouvrez votre navigateur web et allez à l'URL du serveur de développement pour accéder à votre jeu.

<p align="right">(<a href="#readme-top">haut de page</a>)</p>

## Utilisation

1. <strong>Menu principal :</strong>

* Lancez le jeu et arrivez sur le menu principal.
* Vous pouvez ajustez le niveau sonore du jeu ici. 
* Lorsque vous êtes prêt, cliquez sur "Jouer"

2. <strong>Contrôles du joueur :</strong>

* Pour vous déplacer, utilisez les touches du clavier <strong>ZQSD</strong>.
* Vous pouvez attquer avec la barre d'<strong>Espace</strong>.
* Entrer dans un dossier avec la touche <strong>Entrée</strong> si votre curseur est dessus.
* Pour quitter un dossier, utilisez la touche <strong>Echap</strong>.

3. <strong>Combat contre des virus :</strong>

* En entrant dans un dossier, il se peut que vous deviez combattre des virus.
* Tant que les virus sont en vie, vous ne pouvez pas quitter le dossier
* Après l'élimination des virus grâce à vos projectiles, vous obtenez un objet qui vous offre un bonus

4. <strong>Combat de boss :</strong>

* Certains dossier contient à boss à détruire
* Si vous parvenez à tuer le boss, vous obtenez un objet et vous pouvez passer au niveau suivant

<p align="right">(<a href="#readme-top">haut de page</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
[Java]: https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white
[Java-url]: https://www.java.com/en/

[LibGDX]: https://img.shields.io/badge/LibGDX-White?style=for-the-badge&color=F43434
[LibGDX-url]: https://libgdx.com/

[Gradle]: https://img.shields.io/badge/Gradle-02303A.svg?style=for-the-badge&logo=Gradle&logoColor=white
[Gradle-url]: https://gradle.org/


[Illustrator]: https://img.shields.io/badge/adobe%20illustrator-%23FF9A00.svg?style=for-the-badge&logo=adobe%20illustrator&logoColor=white
[Illustrator-url]: https://www.adobe.com/products/illustrator.html

[Audacity]: https://img.shields.io/badge/Audacity-0000CC?style=for-the-badge&logo=audacity&logoColor=white
[Audacity-url]: https://www.audacityteam.org/


[Notion]: https://img.shields.io/badge/Notion-%23000000.svg?style=for-the-badge&logo=notion&logoColor=white
[Notion-url]: https://www.notion.so/

[Git]: https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white
[Git-url]: https://git-scm.com/
