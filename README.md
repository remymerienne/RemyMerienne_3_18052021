# 1. ohmyfood

Projet N°3 du parcours _Développeur Front-End_ [OpenClassrooms](https://openclassrooms.com/fr/).

OHMYFOOD est une entreprise de commande de repas en ligne. Le site permet aux utilisateurs de commander leur menu à l'avance.

Lien vers le site : 
[*ohmyfood*](https://remymerienne.github.io/RemyMerienne_3_18052021/)

***

<img alt="HTML5" src="https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white"/><img alt="CSS3" src="https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white"/><img alt="SASS" src="https://img.shields.io/badge/Sass-CC6699?style=for-the-badge&logo=sass&logoColor=white"/>

<img alt="Git" src="https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white"/><img alt="GitHub" src="https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white"/>![GitKraken](https://img.shields.io/badge/GitKraken-179287?style=for-the-badge&logo=GitKraken&logoColor=white)![Shell Script](https://img.shields.io/badge/shell_script-%23121011.svg?style=for-the-badge&logo=gnu-bash&logoColor=white)

![FontAwesome](https://img.shields.io/badge/Font_Awesome-339AF0?style=for-the-badge&logo=fontawesome&logoColor=white)

![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)![Google Chrome](https://img.shields.io/badge/Google%20Chrome-4285F4?style=for-the-badge&logo=GoogleChrome&logoColor=white)

## 1.1. Dynamiser une page web avec des animations CSS

- Mettre en place son environnement Front-End
- Assurer la cohérence graphique d'un site Web
- Mettre en place une structure de navigation pour un site Web
- Mettre en oeuvre des effets CSS graphiques avancés
- Utiliser un système de gestion de versions pour le suivi du projet et son hébergement

L'intégration du site a été réalisée en HTML5, CSS3 et SASS sans Framework.  
Le cahier des charges est consultable [ici](supply/Brief-creatif-ohmyfood.pdf) et les maquettes [ici](supply/Maquettes-Ohmyfood)

***

- [1. ohmyfood](#1-ohmyfood)
  - [1.1. Dynamiser une page web avec des animations CSS](#11-dynamiser-une-page-web-avec-des-animations-css)
    - [1.1.1. Accueil](#111-accueil)
      - [1.1.1.1. Découpage sémantique](#1111-découpage-sémantique)
      - [1.1.1.2. Heading-level outline](#1112-heading-level-outline)
      - [1.1.1.3. Découpage des tâches](#1113-découpage-des-tâches)
        - [1.1.1.3.1. Développement des éléments du site par `feature`](#11131-développement-des-éléments-du-site-par-feature)
        - [1.1.1.3.2. Commits réalisés par branche (_GitKraken)_](#11132-commits-réalisés-par-branche-gitkraken)
      - [1.1.1.4. SASS](#1114-sass)
    - [1.1.2. Menu](#112-menu)
      - [1.1.2.1. Découpage sémantique](#1121-découpage-sémantique)
      - [1.1.2.2. Heading-level outline](#1122-heading-level-outline)
      - [1.1.2.3. Découpage des tâches](#1123-découpage-des-tâches)
        - [1.1.2.3.1. Développement des éléments du site par `feature`](#11231-développement-des-éléments-du-site-par-feature)
        - [1.1.2.3.2. Commits réalisés par branche (GitKraken)](#11232-commits-réalisés-par-branche-gitkraken)
      - [1.1.2.4. SASS](#1124-sass)

***

### 1.1.1. Accueil

#### 1.1.1.1. Découpage sémantique

```html
<!-- Header -->
<header>
  <h1>ohmyfood</h1>
</header>
<!-- Header END -->

<!-- Bloc-introduction -->
<div class="introduction" role="complementary">
  <!-- Search-module -->
  Recherche de la ville et du quartier
  <!-- Search-module END -->
  <h2>Réservez le menu qui vous convient</h2>
  <p>Découvrez des restaurants d'exception, sélectionnés par nos soins.</p>
  <!-- Button -->
  <!-- Button END-->
</div>
<!-- Bloc-introduction END-->

<main>
  <section class="operation">
    <h2>Fonctionnement</h2>
    <!-- Step-module-N°1 -->
    <!-- Step-module-N°1 END -->
    <!-- Step-module-N°2 -->
    <!-- Step-module-N°2 END -->
    <!-- Step-module-N°3 -->
    <!-- Step-module-N°3 END -->
  </section>

  <nav class="navigation">
    <h2>Restaurants</h2>
    <!-- Restaurant-module-1 -->
    <!-- Restaurant-module-1 END -->
    <!-- Restaurant-module-2 -->
    <!-- Restaurant-module-2 END -->
    <!-- Restaurant-module-3 -->
    <!-- Restaurant-module-3 END -->
    <!-- Restaurant-module-4 -->
    <!-- Restaurant-module-4 END -->
  </nav>
</main>

<footer>
  <h2>ohmyfood</h2>
</footer>
```

#### 1.1.1.2. Heading-level outline

![Headin-level outline](supply/hlo-index.png)

#### 1.1.1.3. Découpage des tâches

##### 1.1.1.3.1. Développement des éléments du site par `feature`

Chaque partie de l'accueil a été développée dans sa propre branche _Git-flow_

- `feature/btn`

- `feature/index-header`

- `feature/index-information-section`

- `feature/index-navigation`

- `feature/footer`

- `feature/index`

##### 1.1.1.3.2. Commits réalisés par branche (_GitKraken)_

![Apperçu des branches et des commits sur GitKraken](supply/kraken-index.png)

#### 1.1.1.4. SASS

La feuille de style **index.css** a été générée par _SASS_.  
Ci-dessous, les différents fichiers contenant le code _SCSS_ et compilés vers **index.css**

```scss
@charset "UTF-8";

@import 
'abstracts/variables',
'abstracts/mixins',
'abstracts/placeholders';

@import 
'base/base',
'base/fonts',
'base/typography';

@import 
'animations/loader',
'animations/transition';

@import 
'layout/header',
'layout/footer',
'layout/page';

@import 
'components/button',
'components/loader';

@import 
'pages/index';
```

Chaque fichier _SCSS_ peut être consulté dans le repertoire [**stylesheets**](stylesheets/)

### 1.1.2. Menu

#### 1.1.2.1. Découpage sémantique

```html
<!-- Header -->
<header>
  <h1>ohmyfood</h1>
</header>
<!-- Header END -->

<main>
  <section class="menu">
    <!-- Menu-header -->
    <header>
      <h2>A la française</h2>
    </header>
    <!-- Menu-header END-->

    <section>
      <h3>ENTREES</h3>
    </section>

    <section>
      <h3>PLATS</h3>
    </section>

    <section>
      <h3>DESSERTS</h3>
    </section>

    <!-- Button -->
    <!-- Button END-->
  </section>
</main>

<footer>
  <h2>ohmyfood</h2>
</footer>
```

#### 1.1.2.2. Heading-level outline

![Headin-level outline](supply/hlo-menu.png)

#### 1.1.2.3. Découpage des tâches

##### 1.1.2.3.1. Développement des éléments du site par `feature`

Chaque partie des menus ont été développées comme l'**index**, dans leurs propres branches _Git-flow_

- `feature/menu-header`

- `feature/menu-stage-section`

- `feature/menu`

##### 1.1.2.3.2. Commits réalisés par branche (GitKraken)

![Apperçu des branches et des commits sur GitKraken](supply/kraken-menu.png)

#### 1.1.2.4. SASS

La feuille de style **menu.css** a été générée par _SASS_.  
Ci-dessous, les différents fichiers contenant le code _SCSS_ et compilés vers **menu.css**

```scss
@charset "UTF-8";

@import 
'abstracts/variables',
'abstracts/mixins',
'abstracts/placeholders';

@import 
'base/base',
'base/fonts',
'base/typography';

@import 
'animations/gradual-onset';

@import 
'layout/header',
'layout/footer',
'layout/page';

@import 
'components/button';

@import 
'pages/menu';
```

Afin d'avoir un code _CSS_ le plus léger possible et afin d'éviter les répétitions, chaque menu possède sa propre feuille de style.

Chaque fichier _SCSS_ peut être consulté dans le repertoire [**stylesheets**](stylesheets/).

***
