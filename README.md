# 1. ohmyfood

- [1. ohmyfood](#1-ohmyfood)
  - [1.1. ***Index***](#11-index)
    - [1.1.1. Découpage sémantique](#111-découpage-sémantique)
    - [1.1.2. Heading-level outline](#112-heading-level-outline)
    - [1.1.3. Découpage des tâches](#113-découpage-des-tâches)
      - [1.1.3.1. `feature/btn`](#1131-featurebtn)
      - [1.1.3.2. `feature/index-header`](#1132-featureindex-header)
      - [1.1.3.3. `feature/index-information-section`](#1133-featureindex-information-section)
      - [1.1.3.4. `feature/index-navigation`](#1134-featureindex-navigation)
      - [1.1.3.5. `feature/footer`](#1135-featurefooter)
      - [1.1.3.6. `feature/index`](#1136-featureindex)
  - [1.2. `release/v1.0.0`](#12-releasev100)
  - [1.3. ***Menu 1***](#13-menu-1)
    - [1.3.1. Découpage sémantique](#131-découpage-sémantique)
    - [1.3.2. Heading-level outline](#132-heading-level-outline)
    - [1.3.3. Découpage des tâches](#133-découpage-des-tâches)
      - [1.3.3.1. `feature/menu-header`](#1331-featuremenu-header)
      - [1.3.3.2. `feature/menu-section-header`](#1332-featuremenu-section-header)
      - [1.3.3.3. `feature/menu-stage-section`](#1333-featuremenu-stage-section)
      - [1.3.3.4. `feature/menu`](#1334-featuremenu)
  - [1.4. `release/v1.1.0`](#14-releasev110)
  - [1.5. Effets `feature/effects`](#15-effets-featureeffects)
  - [1.6. `release/v1.2.0`](#16-releasev120)

## 1.1. ***Index***

### 1.1.1. Découpage sémantique

```html
<header>
  <h1>ohmyfood</h1>
  <div class="search">Paris, Belleville</div>
  <h2>Réservez le menu qui vous convient</h2>
  <p>Découvrez des restaurants d'exception, sélectionnés par nos soins.</p>
  <div class="btn">Explorer nos restaurants</div>
</header>

<main>

  <section class="information">
    <h3>Fonctionnement</h3>
    <div class="one"></div>
    <div class="two"></div>
    <div class="three"></div>
  </section>

  <nav>
    <h3>Restaurants</h3>
    <div class="menu-1"><a href="#"><h4>resto1</h4></a></div>
    <div class="menu-2"><a href="#"><h4>resto2</h4></a></div>
    <div class="menu-3"><a href="#"><h4>resto3</h4></a></div>
    <div class="menu-4"><a href="#"><h4>resto4</h4></a></div>
  </nav>

</main>

<footer>
  <h3>ohmyfood</h3>
  <h4>Proposer un restaurant</h4>
  <h4>Devenir partenaire</h4>
  <h4>Mentions légales</h4>
  <h4>Contact</h4>
</footer>
```

### 1.1.2. Heading-level outline

![Headin-level outline](supply/hlo-index.png)

### 1.1.3. Découpage des tâches

#### 1.1.3.1. `feature/btn`

- \[FEAT\](#1): develop the btn module ***`close`***

#### 1.1.3.2. `feature/index-header`

- \[FEAT\]header(#6): develop the search module ***`open`***

- \[FEAT\]header(#17): add fonts ***`open`***

- \[FEAT\]header(#7): do general layout of header ***`open`***

#### 1.1.3.3. `feature/index-information-section`

- \[FEAT\]section(#8): develop the step module ***`open`***
  
- \[FEAT\]section(#9): add steps ***`open`***  
  Three differents types

- \[FEAT\]section(#10): do general layout of section ***`open`***

#### 1.1.3.4. `feature/index-navigation`

- \[FEAT\]nav(#11): develop the thumbnail template ***`open`***

- \[FEAT\]nav(#12): integrate the four thumbnails ***`open`***

- \[FEAT\]nav(#13): do general layout of navigation ***`open`***

#### 1.1.3.5. `feature/footer`

- \[FEAT\]footer(#14): add footer ***`open`***

#### 1.1.3.6. `feature/index`

- \[FEAT\](#15): do general layout of index ***`open`***

- \[REFACTOR\](#16): clean code ***`open`***

## 1.2. `release/v1.0.0`

Publication de _index.html_  

## 1.3. ***Menu 1***

### 1.3.1. Découpage sémantique

```html
<header>
  <h1>ohmyfood</h1>
</header>

<main>

  <section class="menu">

    <header class="menu__header">  
      <h2>&Agrave; la française</h2>
    </header>

    <section class="stage">
      <h3>ENTR&Eacute;ES</h3>
    </section>

    <section class="stage">
      <h3>PLATS</h3>
    </section>

    <section class="stage">
      <h3>DESSERTS</h3>
    </section>

  </section>

</main>

<footer>
  <h3>ohmyfood</h3>
  <h4>Proposer un restaurant</h4>
  <h4>Devenir partenaire</h4>
  <h4>Mentions légales</h4>
  <h4>Contact</h4>
</footer>
```

### 1.3.2. Heading-level outline

![Headin-level outline](supply/hlo-menu.png)

### 1.3.3. Découpage des tâches

#### 1.3.3.1. `feature/menu-header`

- \[FEAT\]header(#): add h1 title and back arrow 

#### 1.3.3.2. `feature/menu-section-header`

- \[FEAT\]section(#): add h2 title and heart  
    Don't forget top border radius.

- \[FEAT\]section(#): add background and layout

#### 1.3.3.3. `feature/menu-stage-section`

- \[FEAT\]section(#): develop the dish template

- \[FEAT\]section(#): integrate three stages

- \[FEAT\]section(#): do general layout of section

#### 1.3.3.4. `feature/menu`

- \[FEAT\](#): add bnt and footer

- \[FEAT\](#): do general layout of page

- \[REFACTOR\](#): clean code

## 1.4. `release/v1.1.0`

Publication de _menu_1.html_

## 1.5. Effets `feature/effects`

- \[FEAT\](#): add effect on btn

- \[FEAT\](#): add effect on heart

- \[FEAT\]menu(#): add slide effect

- \[FEAT\]menu(#): add effect "hide and show"

- \[FEAT\]index(#): add effect "loading spinner"

## 1.6. `release/v1.2.0`

Publication de _index.html et _menu_1.html_ avec les effets.