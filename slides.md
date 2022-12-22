---
# try also 'default' to start simple
theme: default
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
# background: https://source.unsplash.com/collection/94734566/1920x1080
# apply any windi css classes to the current slide
class: 'text-center'
# https://sli.dev/custom/highlighters.html
highlighter: shiki
# show line numbers in code blocks
lineNumbers: false
# some information about the slides, markdown enabled
info: |
  ## Et si on parlait des sols ?
# persist drawings in exports and build
drawings:
  persist: false
# use UnoCSS
css: unocss
---

# Et si on parlait des sols ? 🪱


---

# Avertissements

Syndrome de l'imposteur...

Je suis développeur logiciel.

Je ne suis **pas** un expert dans l'étude des sols ([Pédologie](https://fr.wikipedia.org/wiki/P%C3%A9dologie_(g%C3%A9oscience))).

Ce que je vais vous raconter est une compilation de mes apprentissages que j'ai essayé d'ordonner.


<div class="absolute left-60px bottom-20px text-xs">
La pédologie (du grec πέδον / pédon, « sol », et λόγος / lógos, « étude ») est une science ayant pour but d’étudier la pédogenèse, c'est-à-dire la formation et l'évolution des sols, notamment au travers de plusieurs taxonomies des sols.
</div>

---

# "Sols" & "décroissance" ?

Le lien n'est pas évident au premier abord... 🤔

<v-click>

Un peu de code à la rescousse... (désolé, pas pu m'en empêcher... 😊)

</v-click>

<v-click>

```ts {1-4|5|6|7|8|9|10-15|all}
/* fonction: decroître() pour l'utilisateur "Peio",
   TODO: à adapter pour son cas perso
   Licence: Libre de droits */
function decroître() {
  const conscience = prendreConscience(livres, Internet); // ah oui, quand même 😲...
  const fragilités = analyzerLesFragilités(conscience); // par où je commence ? 🤔
  const alimentation = prioriserMesActions(fragilités); // pour moi, ce sera l'alimentation 🥕 🥒
  const savoir = apprendre(alimentation); // apprentissage sur le fonctionnement des sols 🪱 🍂
  const resultats = faire(savoir);        // échecs/réussites 😅
  reduireMonEmpreinteEcologique(          // Youpie ! 🎉 🌳 😋
    { 
      mangerLocal: resultats.legumes,
      lowTech: resultats.techniques
    }
  ); 
}
```
</v-click>

<div class="absolute left-60px bottom-10px text-xs">
Appuyer sur la touche ➡️
</div>

---

# Quelques pointeurs

- Prise de conscience: [Mon petit guide sur l'effondrement](https://www.peio.dev/posts/guide-effondrement/)
- Analyse des fragilités: [Et si on se préparait… ensemble !](https://www.peio.dev/posts/si-on-se-preparait/)
- Apprendre: [Nos amis les vers de terre](https://www.peio.dev/posts/lombriciens/)

---

# Etat des lieux

Photos de deux champs situés à 10 m l'un de l'autre (Lasseube - 64)

<div class="grid grid-cols-2">
  <div>
    <img src="/sol-sain.jpg" class="h-55 rounded" />
    <span class="text-xs">sol sain</span>
  </div>
  <div>
    <img src="/sol-inonde.jpg" class="h-55 rounded" />
    <span class="text-xs">sol asphyxié</span>
  </div>
</div>

---

# Les vers de terre 🪱

- 1ère masse animale de loin: <span class="text-lime-500">20 fois le poids des hommes</span> et sont sur Terre depuis des centaines de millions d'années (Anélides)
- En France, en moyenne, il y en a environ <span class="text-lime-500">1,2 tonne par hectare</span>
- Ils creusent <span class="text-lime-500">4000 km de galeries par hectare</span>, soit 400m sous un seul m2 de votre pelouse
- Leurs galeries <span class="text-lime-500">multiplient la surface d'échange par 5</span> ! Ce qui signifie que lorsque vous avez 1 m2 de pelouse qui échange avec l'air, en fait, vous avez 5 m2 de surface d'échange.
- Ces galeries permettent d'améliorer la capacité de percolation d'un facteur 30 ! <span class="text-lime-500">Un sol vivant permet d'absorber 160 L/heure/m2</span>, soit 160 mm de pluie par heure ! (Comparés aux 5 à 7 mm par heure pour les sols sans vie...)
- Les vers de terre retournent, ingèrent et fertilisent <span class="text-lime-500">300 tonnes de terre par hectare par an</span>. Travail d'ingestion phénoménal produisant du lombrimix (Matière organique et minérale sortie du tube digestif d'un lombric), élément absolument central pour les micro-organismes et donc les cycles de l'azote, phosphore, potassium...

---

# Décroître Ensemble

Reprise de notre fonction `decroître()`... 😉

<v-click>

```ts {1-5|6|7-12|13|14|15|16|17|all}
/* fonction: decroîtreEnsemble()
   Evolution de: decroïtre()
   WARNING: pas de retour possible
   Licence: Libre de droits */
function decroîtreEnsemble() {
  while (1) { // toute la vie !
    savoir = apprendreEnsemble(
      { 
        sujetsPossibles: ["alimentation", "travail du bois", "mecanique", "musique", ...],
        avecQui: { famille, copains }
      }
    );
    resultats = faireEnsemble({savoir, avecQui: { famille, copains }});
    reduireEmpreinteEcologique({resultats, pourQui: { famille, copains }}); // Youpie ! 🎉 🌳 💯
    copains = partager(savoir, resultats);
    bienEtre = jouerDeLaMusique(copains); // 🎵 🎻 🎸
    bonheur = sommeIncalculable(copains + savoir + resultats + bienEtre ); // 💓
  }
}  
```
</v-click>

<div class="absolute left-60px bottom-10px text-xs">
Appuyer sur la touche ➡️
</div>
