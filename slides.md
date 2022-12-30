---
theme: default
layout: cover
class: 'text-center'
highlighter: shiki
lineNumbers: false
info: |
  ## Et si on parlait des sols ?
drawings:
  persist: false
css: unocss
---

# Et si on parlait des sols ? 🪱


---

# Avertissements

Môa, imposteur...

Je travaille dans le développement logiciel.

Je ne suis **pas un expert** dans l'étude des sols (Pédologie [^1])... mais ce domaine me **passionne**.

Ce que je vais vous raconter est une compilation de mes apprentissages que j'ai essayé d'ordonner, mélange de faits <mdi-shield-check /> et d'expériences personnelles <mdi-shovel />


<style>
.footnotes-sep {
  @apply mt-20 opacity-10;
}
.footnotes {
  @apply text-sm opacity-75;
}
.footnote-backref {
  display: none;
}
</style>

<!-- <div class="absolute left-60px bottom-20px text-xs"> -->
[^1]: La [pédologie](https://fr.wikipedia.org/wiki/P%C3%A9dologie_(g%C3%A9oscience))) (du grec πέδον / pédon, « sol », et λόγος / lógos, « étude ») est une science ayant pour but d’étudier la pédogenèse, c'est-à-dire la formation et l'évolution des sols, notamment au travers de plusieurs taxonomies des sols.
<!-- </div> -->

---

# Le plat du jour

- Sols & décroissance ?
- Etat des lieux
- Les vers de terre
- Décroître ensemble

---

# Sols & décroissance ?

... 🤔 ...

<v-click>

Le lien n'est pas évident au premier abord alors un peu de code à la rescousse... (désolé, pas pu m'en empêcher... 😊)... pour présenter mon cheminement personnel.

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
Appuyer sur la touche <mdi-arrow-right />
</div>

---

# Etat des lieux...

Photos de deux champs situés à 10 m l'un de l'autre (Lasseube - 64), prises le 18 décembre 2022.

<div class="grid grid-cols-2">
  <div>
    <img src="/sol-sain.jpg" class="h-60 rounded drop-shadow-xl" />
    <span class="text-xs">prairie permanente</span>
  </div>
  <div>
    <img src="/sol-inonde.jpg" class="h-60 rounded drop-shadow-xl" />
    <span class="text-xs">champ travaillé mécaniquement (mono-culture maïs)</span>
  </div>
</div>

...et des questions :

- Avez-vous déjà vu une forêt inondée après une pluie ?
- Pourquoi une forêt (avec de si grands sujets <mdi-tree />) pousse toute seule ?

---

# Caractéristiques d'un sol

- géologique
- physique
- biologique - galeries des vers de terre: capacité de percolation, surface d'échange multipliée (x5), perméable à la progression des racines
- structure -
- taux d'humus - minéralisation lente adaptée aux plantes, rétention d'eau (23 L / m2 de plus par point de matière organique supplémentaire)

---

# Le grand cycle

Source <mdi-wikipedia />: [Rhizosphère](https://fr.wikipedia.org/wiki/Rhizosph%C3%A8re)

<img src="/1024px-Microbiote_du_sol.gif" class="h-100 rounded drop-shadow-xl" />

---
layout: two-cols
---

# Les acteurs principaux 

... qui collaborent et s'entraident <mdi-handshake />

- l'arbre <mdi-tree />
- le ver de terre 🪱
- et les tout-petits :
  - champignons <mdi-mushroom />
  - bactéries <mdi-bacteria />
  - etc...

::right::

<img src="/livre-entraide.jpg" class="h-80 rounded drop-shadow-xl" />

<span class="text-xs italic">"(...) Face au chacun pour soi et à la compétition, ce texte de philosophie sociale, d'une troublante actualité, nous rappelle que la solidarité est le meilleur chemin vers l'émancipation de toutes et tous" - [librairiesindependantes.com](https://www.librairiesindependantes.com/product/9791092457391/)</span>

---

# L'arbre 🌳

- au contact de la roche mère: capte des minéraux dans une source "infinie"
- nourrit le sol avec ses racines mortes, branches et feuilles qui tombent au sol. Nourriture apportée "par le dessus" et qui rentre dans la formation du complexe argilo-humique via l'intervention des micro-organismes (bactéries et champignons) et l'ingestion des vers de terre (lombrimix)
- communication inter-individues et symbiose avec les champignons
- pompe à eau, collaboration pour l'échange d'eau

---

# Les vers de terre 🪱

- 1ère masse animale de loin: <span class="text-lime-500">20 fois le poids des hommes</span> et sont sur Terre depuis des centaines de millions d'années (Anélides)
- En France, en moyenne, il y en a environ <span class="text-lime-500">1,2 tonne par hectare</span>
- Ils creusent <span class="text-lime-500">4000 km de galeries par hectare</span>, soit 400m sous un seul m2 de votre pelouse
- Leurs galeries <span class="text-lime-500">multiplient la surface d'échange par 5</span> ! Ce qui signifie que lorsque vous avez 1 m2 de pelouse qui échange avec l'air, en fait, vous avez 5 m2 de surface d'échange.
- Ces galeries permettent d'améliorer la capacité de percolation d'un facteur 30 ! <span class="text-lime-500">Un sol vivant permet d'absorber 160 L/heure/m2</span>, soit 160 mm de pluie par heure ! (Comparés aux 5 à 7 mm par heure pour les sols sans vie...)
- Les vers de terre retournent, ingèrent et fertilisent <span class="text-lime-500">300 tonnes de terre par hectare par an</span>. Travail d'ingestion phénoménal produisant du <span class="text-lime-500">**lombrimix**</span> (Matière organique et minérale sortie du tube digestif d'un lombric), élément absolument central pour les micro-organismes et donc les cycles de l'azote, phosphore, potassium...

---

# Les champignons et bactéries

## Les champignons

- [Mycorhize](https://fr.wikipedia.org/wiki/Mycorhize)
- vont chercher l'eau entre les feuillets d'argile là où les racines ne vont pas

## Les bactéries

- fixatrices d'azote (de l'air ! 😎)

---

# Se retrousser les manches: nourrir le sol

Merci à Régis (ami paysan à Lasseube) pour le transport 🚜

<div class="grid grid-cols-2">
  <div>
    <img src="/apport-broyat-remorque-regis.jpg" class="h-60 rounded drop-shadow-xl" />
    <span class="text-xs">Apport massif de broyat végétal (9 t sur 120 m2) </span>
  </div>
  <div>
    <img src="/paillage.jpg" class="h-60 rounded drop-shadow-xl" />
    <span class="text-xs">Paillage supplémentaire (adventices)</span>
  </div>
</div>


- 5 cm de feuilles mortes: tilleuls sur la propriété, transport par Arthur (8 ans) & Titouan (5 ans)
- 10 cm de broyat végétal: 19 m3 achetés à [Loreki](https://loreki.fr/), acheminés par Régis
- 10 cm de paille: 2 bottes carrées fournies par Régis

---

# Se retrousser les manches: la serre

Mercis à: Pierrot, Sébastien et Vincent... sans oublier Arthur et Titouan!

<div class="grid grid-cols-2 gap-1">
  <img src="/serres-demontage-2.jpg" class="h-50 rounded drop-shadow-xl" />
  <img src="/serres-demontage-1.jpg" class="h-50 rounded drop-shadow-xl" />
  <img src="/serres-transport.jpg" class="h-50 rounded drop-shadow-xl" />
  <img src="/serres-stockees.jpg" class="h-50 rounded drop-shadow-xl" />
</div>

---

# Décroître **Ensemble** <mdi-handshake /> <u>en faisant</u>

Reprise de notre fonction `decroître()`...

<v-click>

```ts {1-5|6|7-12|13|14|15|16|17|all}
/* fonction: decroîtreEnsemble()
   Evolution de: decroïtre()
   WARNING: ⚠️ pas de retour possible
   Licence: Libre de droits */
function decroîtreEnsemble() {
  while (1) { // toute la vie !
    savoir = apprendreEnsemble(
      { 
        sujetsPossibles: ["culture légumes", "travail du bois", "production de miel", "conserves", ...], // plus de sujets possibles
        avecQui: { famille, copains }
      }
    );
    resultats = faireEnsemble({savoir, avecQui: { famille, copains }}); // meilleurs résultats que tout seul
    reduireEmpreinteEcologique({resultats, pourQui: { famille, copains }}); // Youpie ! 🎉 🌳 💯
    copains = partager(savoir, resultats); // nouveaux contacts.. potentiels nouveaux copains
    bienEtre = jouerDeLaMusique(copains); // 🎵 🎻 🎸
    bonheur = sommeIncalculable(copains + savoir + resultats + bienEtre ); // 💖, maîtrise de l'éco-anxiété
  }
}  
```
</v-click>

<div class="absolute left-60px bottom-10px text-xs">
Appuyer sur la touche <mdi-arrow-right />
</div>

---

# Remerciements

On s'y attarde un peu car leur enseignement a changé le cour de ma vie

- Marcel Bouché
- Konrad Schreiber
- François Mulet ([Ver de terre production](https://www.verdeterreprod.fr/) )
- Damien Dekarz ([Permaculture & agroécologie](https://www.youtube.com/channel/UCsM4_jihNFYe4CtSkXvDR-Q))
- Jean-Martin Fortier ([Le jardinier maraïcher](https://lejardiniermaraicher.com/))
- Eliot Coleman ([4 season farm](https://www.fourseasonfarm.com))
- Perrine & Charles Hervé-Gruyer ([Ferme du Bec Hellouin](https://www.fermedubec.com/))

---

# Quelques références

### Sols

- <span class="text-sm"><mdi-book-open-variant /> "Des vers de terre et des hommes" - Marcel Bouché</span>
- <span class="text-sm"><mdi-book-open-variant /> "De l'arbre au sol - Les Bois Raémaux Fragmentés" - Elea Asselineau & Gilles Domenech</span>
- <span class="text-sm"><mdi-book-open-variant /> "Le sol, la terre et les champs - Pour retrouver une agrilcuture saine" - Claude et Lydia Bourguignon</span>
- <span class="text-sm"><mdi-youtube /> ["600 Unités d'Azote grâce aux Vers de Terre"](https://www.youtube.com/watch?v=enGc4CLh_is) - Marcel Bouché</span>
- <span class="text-sm"><mdi-youtube /> ["Écologie des vers de terre & reconstruction de la fertilité des sols"](https://www.youtube.com/watch?v=NjeQU_yyDG4) - François Mulet</span>

### Maraîchage

- <span class="text-sm"><mdi-book-open-variant /> "Le jardin naturel" - Jean-Marie Lespinasse</span>
- <span class="text-sm"><mdi-book-open-variant /> "Vivre avec la Terre - Permaculture, microfermes, bio-abondance" - Perrine & Charles Hervé-Gruyer</span>
- <span class="text-sm"><mdi-book-open-variant /> "Le jardinier-maraîcher - Manuel d'agriculture biologique sur petite surface" - Jean-Martin Fortier</span>
- <span class="text-sm"><mdi-book-open-variant /> "Des légumes en hiver - Produire en abondance, même sous la neig" - Eliot Coleman</span>

---

# Merci

<span class="text-xs">Présentation à retrouver en ligne [ici](https://presentation-sols-peio.netlify.app) (et son code <mdi-github /> [là](https://github.com/pierreroth64/presentation-sols))</span>

<img src="/saunei-bauchon-darrer.jpeg" class="h-100 rounded drop-shadow-xl" />

