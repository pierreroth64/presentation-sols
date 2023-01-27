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
favicon: './favicon.ico'
---

# Et si on parlait des sols ? 🪱


---

# Avertissements

(L'imposteur du jour & la règle des 2 pieds)

Je ne suis un expert dans <span class="text-orange-400 underline decoration-solid">aucun</span> des domaines suivants:
- l'étude des sols (pédologie)
- la biologie des sols
- les cycles (eau, minéraux, carbone)

... mais ces sujets me passionnent...

<p class="text-orange-400">
<mdi-foot-print /> Si à n’importe quel moment, vous vous trouvez dans une situation où vous <span class="underline decoration-solid">n'apprenez plus rien</span>, <span class="underline decoration-solid">ni ne contribuez</span>, <span class="underline decoration-solid">ni ne vous faites plaisir</span>, servez vous de vos deux pieds.
</p>


<footer class="absolute bottom-10 left-20 right-20">
  <span class="text-xs italic"><mdi-wikipedia /> "<a href="https://fr.wikipedia.org/wiki/P%C3%A9dologie_(g%C3%A9oscience)">La pédologie</a> (du grec πέδον / pédon, « sol », et λόγος / lógos, « étude ») est une science ayant pour but d’étudier la pédogenèse, c'est-à-dire la formation et l'évolution des sols, notamment au travers de plusieurs taxonomies des sols."</span>
</footer>

---

# Navigation & diffusion

<div class="grid grid-cols-2">
  <div class="col-span-1">
  <p>
  Ne rien louper, touches: <mdi-keyboard-space /> ou <mdi-arrow-right />

  Revenir en arrière rapidement, touche <mdi-arrow-up />

  Avancer rapidement, touche <mdi-arrow-down />
  </p>
  </div>
  <div class="col-span-1">
    <p>
      <mdi-license /> Présentation libre de droits, Licence <a href="https://fr.wikipedia.org/wiki/Licence_MIT">MIT</a> (<mdi-wikipedia />) 
      <ul>
        <li>en ligne <a href="https://presentation-sols-peio.netlify.app">ici</a></li>
        <li>ses sources  <mdi-github /> <a href="https://github.com/pierreroth64/presentation-sols">là</a></li>
      </ul>
      <img src="/mit-license.png" class="h-20 rounded drop-shadow-xl" />
    </p>
  </div>
</div>

---

# Le plat du jour

- Sol & décroissance ?
- Etat des lieux
- La plante et ses besoins
- Les vers de terre
- Décroître ensemble

---

# Sol & décroissance ?

(quel est le rapport ?... 🤔)

<v-click>

Le lien n'est pas évident au premier abord alors un peu de code à la rescousse... (désolé, pas pu m'en empêcher... 😊)... pour présenter mon cheminement personnel.

</v-click>

<v-click>

```ts {1-4|5|6|7|8|9|10-16|all}
/* fonction: decroître() pour l'utilisateur "Peio",
   TODO: à adapter pour son cas perso
   Licence: Libre de droits */
function decroître() {
  const conscience = prendreConscience(livres, Internet); // ah oui, quand même 😲...
  const fragilités = analyzerLesFragilités(conscience); // par où je commence ? 🤔
  const alimentation = prioriserMesActions(fragilités); // pour moi, ce sera l'alimentation 🥕 🥒
  const savoir = apprendre(alimentation); // apprentissage sur le fonctionnement des sols 🪱 🍂
  const resultats = faire(savoir);        // échecs/réussites 😅
  reduireMonEmpreinteEcologique(          // le début de "ma" décroissance 🌳
    { 
      mangerLocal: resultats.legumes,
      lowTech: resultats.techniques,
      sequestrationCarbone: resultats.humification
    }
  ); 
}
```
</v-click>

---

# Etat des lieux...

Photos de deux champs situés à 10 m l'un de l'autre (18 décembre 2022 après une pluie < 10 mm).

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

...et quelques questions :

- Avez-vous déjà vu une forêt inondée après une pluie ?
- Pourquoi une forêt (avec de si grands sujets <mdi-tree />) pousse-t-elle toute seule ?

---

# La plante 🌱

rappels des cours de SVT (photosynthèse)

- Lumière <span class="text-xs">(on ne devrait pas en manquer)</span>
- CO2 <span class="text-xs">(on en a trop 🙄...)</span>
- H20 <span class="text-xs">(désormais: trop d'un coup ou pas assez)</span>
- Minéraux (N, P, K) <span class="text-xs">(Azote, Phosphore, Potassium)</span>
- Oligo-éléments <span class="text-xs">(Fer, Manganèse, Zinc, Cuivre, Bore, ...)</span>

Donc, on pourrait cultiver sur un support inerte...

<span class="text-red-500">..sauf que</span> dans une économie mondiale en contraction confrontée aux limites planétaires, <span class="text-orange-500">l'agriculture conventionnelle basée sur la mécanisation et l'apport d'intrants de synthèse est donc menacée.</span>

<span class="text-xl font-medium text-lime-500">Par nécessité ou conviction, nous devrons (re)faire confiance aux capacités du sol à nous nourrir.</span>

<!-- Le fer et le manganèse permettent le bon fonctionnement de la photosynthèse
Le zinc protège la plante des stress oxydants (lumière, sécheresse). Il intervient dans la synthèse des protéines et de l’amidon
Le cuivre renforce les parois ligno-cellulosiques et favorise la fertilité des épis
Le bore participe à la multiplication cellulaire et la croissance et conditionne la fertilité du pollen -->

---

# Le sol... cet inconnu

(une des solutions est sous nos pieds... si si, demandez à nos forêts !)

La question fondamentale:

<p class="text-lime-500 font-medium">
Comment sont produits/transformés/acheminés les sels minéraux et olligo-éléments solubles dans l'eau et ainsi directement assimilables par les plantes ?
</p>

Voyons sa composition:
- des <span class="text-lime-500">minéraux</span> (des roches s'altérant et se fragmentant, lui donnant différents aspects selon la taille des agrégats formés)
- des <span class="text-lime-500">constituants gazeux</span> (grâce à l'atmosphère du sol provenant de la respiration et de matières en décomposition)
- des <span class="text-lime-500">matières organiques</span> (grâce à la décomposition des plantes et êtres vivants morts)
- ... mais aussi des êtres vivants... <span class="text-lime-500">beaucoup d'êtres vivants !</span>

---

# Matière Organique

("MO" si vous voulez briller en soirée)

<p class="italic">
"Dans le sol, la matière organique assure de nombreuses fonctions: fourniture d'éléments minéraux nutritifs aux plantes, rétention d'eau, agrégation des particules du sol, nourriture d'une grande diversité d'organismes vivant dans le sol, etc.)."
</p>

<p class="italic">
"La matière organique (...) est un déterminant majeur de la capacité des sols à produire des aliments et des matériaux, et à fournir d’autres services écosystémiques comme la régulation du climat et des micro-climats, du cycle de l’eau ou de la qualité de l’air. "
</p>

La matière organique, c'est <span class="text-lime-500">le carburant</span> pour le <span class="text-lime-500">coeur du réacteur du sol</span>.

<mdi-information /> On exprime sa teneur en pourcentage de sol sec (sol "pauvre": MO < 2 %)


<div class="absolute right-60px bottom-10px text-xs italic">
Source: <mdi-wikipedia /> sur la <a href="https://fr.wikipedia.org/wiki/Mati%C3%A8re_organique">matière organique</a>
</div>

---

# La minéralisation (1/2)

<div class="grid grid-cols-3">
  <div class="col-span-2">
    <img src="/mineralisation.jpg" class="h-100 rounded drop-shadow-xl" />
  </div>
  <div class="col-span-1 italic">
  "La <span class="text-lime-500">matière organique</span> fraîche du sol subit une double transformation à travers deux processus parallèles:
  <ul>
    <li><span class="text-lime-500">la minéralisation primaire</span>, qui transforme la matière organique en eau, sels minéraux (nitrates, phosphates, soufre réduit) et CO2</li>
    <li><span class="text-lime-500">l'humification</span>, qui convertit les substances organiques n'ayant pas été directement détruites au cours de la minéralisation primaire"</li>
  </ul>
  </div>
</div>


<div class="absolute left-60px bottom-10px text-xs italic">
Source: <mdi-book-open-variant /> "Le jardin naturel" - Jean-Marie Lespinasse
</div>

<div class="absolute right-60px bottom-10px text-xs italic">
Source: article <mdi-wikipedia /> sur la <a href="https://fr.wikipedia.org/wiki/Min%C3%A9ralisation_(p%C3%A9dologie)">minéralisation</a>
</div>

---

# La minéralisation (2/2)

(minéralisation secondaire de l'humus)

<div class="grid grid-cols-3">
  <div class="col-span-2">
    <img src="/cycle-mineralisation-humification.png" class="h-100 rounded drop-shadow-xl" />
  </div>
  <div class="col-span-1">
  L'élément différentiant du cycle naturel <span class="text-xs">(par rapport aux apports direct de minéraux aux plantes en agriculture conventionnelle)</span> est l'entrée en jeu de <span class="text-lime-500 font-medium">l'humus</span>.

  La minéralisation de l'humus, appelée <span class="text-lime-500">minéralisation secondaire, est lente et libère en continu sur des dizaines d'années les minéraux nécessaires aux plantes</span>.

  <span class="text-lime-500 font-medium">L'humus</span> a de multiples qualités et est l'élément central de la <span class="text-lime-500 font-medium">fertilité</span> d'un sol.
  </div>
</div>


<div class="absolute right-60px bottom-10px text-xs italic">
Source: article <mdi-wikipedia /> sur la <a href="https://fr.wikipedia.org/wiki/Min%C3%A9ralisation_(p%C3%A9dologie)">minéralisation</a>
</div>

---

# L'humus (et le "CAH")

(La star de nos sols 😎)

<div class="grid grid-cols-3 gap-4">
  <div class="col-span-1">
    <p>
    L’humus et l’argile sont associés en un complexe : 
    <br />
    <br />
    Le <span class="font-medium text-lime-500">C</span>omplexe <span class="font-medium text-lime-500">A</span>rgilo-<span class="font-medium text-lime-500">H</span>umique
    <img src="/complexe-argilo-humique.svg" class="h-60 rounded drop-shadow-xl" />
    </p>
  </div>
  <div class="col-span-2">
  <p>
  Parce qu’il fixe les cations, <span class="text-lime-500">le CAH est le garde-manger de la plante</span>.

  <span class="italic">"La Capacité d’Echange en Cations (CEC) est la quantité maximale de cations qu’un poids déterminé de sol peut retenir. Elle joue un rôle fondamental pour l’alimentation en éléments minéraux de la plante.
  La CEC dépend essentiellement du CAH du sol."</span>
  </p>
  </div>
</div>

<div class="absolute right-60px bottom-10px text-xs italic">
Sources: 
<ul>
  <li>article <mdi-wikipedia /> sur le <a href="https://fr.wikipedia.org/wiki/Complexe_argilo-humique">complexe argilo-humique</a> </li>
  <li>chap. 2 de "Les produits organiques utilisables en agriculture en Languedoc-Roussillon - Tome 1"</li>
</ul>
</div>
---
layout: two-cols
---

# Les acteurs principaux 

... qui collaborent et s'entraident <mdi-handshake />

- l'arbre <mdi-tree />
- le ver de terre 🪱
- et les tout-petits :
  - le champignon <mdi-mushroom />
  - la bactérie <mdi-bacteria />
  - etc...

::right::

<img src="/livre-entraide.jpg" class="h-80 rounded drop-shadow-xl" />

<p class="text-sm italic">
"(...) Face au chacun pour soi et à la compétition, ce texte de philosophie sociale, d'une troublante actualité, nous rappelle que la solidarité est le meilleur chemin vers l'émancipation de toutes et tous."
<br />
<mdi-book-open-variant /> <a href="https://www.librairiesindependantes.com/product/9791092457391/">L'entraide - un facteur de l'évolution</a> - Pierre Kroptokine
</p>

---

# L'arbre 🌳

- au contact de la roche mère: capte des minéraux dans une source "infinie"
- nourrit le sol avec ses racines mortes, branches et feuilles qui tombent au sol. Nourriture apportée "par le dessus" et qui rentre dans la formation du complexe argilo-humique via l'intervention des micro-organismes (bactéries et champignons) et l'ingestion des vers de terre (lombrimix)
- communication inter-individus et symbiose avec les champignons
- pompe à eau, collaboration pour l'échange d'eau

---

# Les vers de terre 🪱

(Darwin avait vu juste...)

- 1ère masse animale de loin: <span class="text-lime-500">20 fois le poids des hommes</span> et sont sur Terre depuis des centaines de millions d'années (Anélides)
- En France, en moyenne, il y en a environ <span class="text-lime-500">1,2 tonne par hectare</span>
- Ils creusent <span class="text-lime-500">4000 km de galeries par hectare</span>, soit 400m sous un seul m2 de votre pelouse
- Leurs galeries <span class="text-lime-500">multiplient la surface d'échange par 5</span> ! Ce qui signifie que lorsque vous avez 1 m2 de pelouse qui échange avec l'air, en fait, vous avez 5 m2 de surface d'échange.
- Ces galeries permettent d'améliorer la capacité de percolation d'un facteur 30 ! <span class="text-lime-500">Un sol vivant permet d'absorber 160 L/heure/m2</span>, soit 160 mm de pluie par heure ! (Comparés aux 5 à 7 mm par heure pour les sols sans vie...)
- Les vers de terre retournent, ingèrent et fertilisent <span class="text-lime-500">300 tonnes de terre par hectare par an</span>. Travail d'ingestion phénoménal produisant du <span class="text-lime-500">**lombrimix**</span> (Matière organique et minérale sortie du tube digestif d'un lombric), élément absolument central pour les micro-organismes

<div class="absolute right-60px bottom-10px text-xs italic">
Source: <mdi-book-open-variant /> "Des vers de terre et des hommes"
</div>

---

# Les champignons et bactéries

## Les champignons

- [Mycorhize](https://fr.wikipedia.org/wiki/Mycorhize)
- vont chercher l'eau entre les feuillets d'argile là où les racines ne vont pas
- "Les champignons sont le réseau social des arbres forestiers"

## Les bactéries

- fixatrices d'azote (de l'air ! 😎)

---

# Le BRF

(Bois Raméal Fragmenté)

Pourquoi lui ?
C/N lignine => humus stable
Il faut un C/N haut car C = énergie et humification plutôt que minéralisation primaire rapide.

Le rapport <a href="https://fr.wikipedia.org/wiki/Rapport_C/N">C/N</a>
C/N est le rapport entre le carbone organique et l’azote total.
Il est couramment admis que, plus le C/N d’un produit est élevé, plus il se dégrade
lentement dans le sol et fournit de l’humus stable.

le BRF présente un C/N de 50, alors que le bois de tronc présente un C/N de 500. Schématiquement, on pourrait dire que le BRF est dix fois plus riche en azote que le bois de tronc, et cette propriété le rend très accessible pour les micro-organismes décomposeurs

---

# Le résumé (simplifié)

(au coeur du réacteur !)

<img src="/1024px-Microbiote_du_sol.gif" class="h-100 rounded drop-shadow-xl" />

<div class="absolute right-60px bottom-10px text-xs italic">
Source: article <mdi-wikipedia /> sur la <a href="https://fr.wikipedia.org/wiki/Rhizosph%C3%A8re">Rhizosphère</a>
</div>

---


# Se retrousser les manches: nourrir le sol

Merci à Régis (ami paysan à Lasseube) pour le transport 🚜

<div class="grid grid-cols-2">
  <div>
    <img src="/apport-broyat-remorque-regis.jpg" class="h-60 rounded drop-shadow-xl" />
    <span class="text-xs">Apport massif de broyat végétal (9 t, soit ~18 m3 sur 120 m2) </span>
  </div>
  <div>
    <img src="/paillage.jpg" class="h-60 rounded drop-shadow-xl" />
    <span class="text-xs">Paillage supplémentaire (occultation pour limiter adventices)</span>
  </div>
</div>


- 5 cm de feuilles mortes: tilleuls sur la propriété, transport par Arthur (8 ans) & Titouan (5 ans)
- 10 cm de broyat végétal: 19 m3 achetés à [Loreki](https://loreki.fr/), acheminés par Régis
- 10 cm de paille: 2 bottes rectangulaires (~ 2 x 200 kg) fournies par Régis

---

# Se retrousser les manches: la serre

Merci à: Pierrot, Sébastien et Vincent... sans oublier Arthur et Titouan!

<div class="grid grid-cols-2 gap-1">
  <img src="/serres-demontage-2.jpg" class="h-50 rounded drop-shadow-xl" />
  <img src="/serres-demontage-1.jpg" class="h-50 rounded drop-shadow-xl" />
  <img src="/serres-transport.jpg" class="h-50 rounded drop-shadow-xl" />
  <img src="/serres-stockees.jpg" class="h-50 rounded drop-shadow-xl" />
</div>

---

# A inclure quelque part

Pour chaque pourcent d'augmentation de Matière Organique, le sol stocke 20 tonnes de carbone de plus par hectare !

1 point de + de MO => 23 L d'eau stockée
5 points de + de MO => + de 100 L d'eau stockée !
Vidéo : ferme cagnolle + olivier (Source: <mdi-youtube /> [une des videos ferme de cagnolle](https://www.youtube.com/watch?v=fEUeLi9tv3Y))

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
        sujetsPossibles: ["culture légumes", "travail du bois", "production de miel", "conserves", ...],
        avecQui: { famille, copains }
      }
    );
    resultats = faireEnsemble({savoir, avecQui: { famille, copains }}); // meilleurs résultats que tout seul
    reduireEmpreinteEcologique({resultats, pourQui: { famille, copains }}); // Youpie ! 🎉 🌳 💯
    copains = partager(savoir, resultats); // nouveaux contacts.. potentiels nouveaux copains
    bienEtre = jouerDeLaMusique(copains); // 🎵 🎻 🎸
    bonheur = sommeIncalculable(copains + savoir + resultats + bienEtre ); // 💖 maîtrise de l'éco-anxiété
  }
}  
```
</v-click>

---

# Remerciements

- Marcel Bouché
- Konrad Schreiber
- François Mulet ([Ver de terre production](https://www.verdeterreprod.fr/) )
- Perrine & Charles Hervé-Gruyer ([Ferme du Bec Hellouin](https://www.fermedubec.com/))
- Damien Dekarz ([Permaculture & agroécologie](https://www.youtube.com/channel/UCsM4_jihNFYe4CtSkXvDR-Q))
- Benoit Le Baube ([Ferme de Cagnolle](https://fermedecagnolle.fr/))
- Eliot Coleman ([4 season farm](https://www.fourseasonfarm.com))
- Jean-Martin Fortier ([Le jardinier maraïcher](https://lejardiniermaraicher.com/))

---

# Quelques références

## Sols

- <span class="text-sm"><mdi-book-open-variant /> "Des vers de terre et des hommes" - Marcel Bouché</span>
- <span class="text-sm"><mdi-book-open-variant /> "De l'arbre au sol - Les Bois Raémaux Fragmentés" - Elea Asselineau & Gilles Domenech</span>
- <span class="text-sm"><mdi-book-open-variant /> "Le sol, la terre et les champs - Pour retrouver une agrilcuture saine" - Claude et Lydia Bourguignon</span>
- <span class="text-sm"><mdi-youtube /> ["600 Unités d'Azote grâce aux Vers de Terre"](https://www.youtube.com/watch?v=enGc4CLh_is) - Marcel Bouché</span>
- <span class="text-sm"><mdi-youtube /> ["Écologie des vers de terre & reconstruction de la fertilité des sols"](https://www.youtube.com/watch?v=NjeQU_yyDG4) - François Mulet</span>
- <span class="text-sm"><mdi-movie /> ["Kiss The Ground: l'agriculture régénératrice"](https://vimeo.com/ondemand/kisstheground) - aussi disponible sur Netflix</span>

## Maraîchage

- <span class="text-sm"><mdi-book-open-variant /> "Le jardin naturel" - Jean-Marie Lespinasse</span>
- <span class="text-sm"><mdi-book-open-variant /> "Vivre avec la Terre - Permaculture, microfermes, bio-abondance" - Perrine & Charles Hervé-Gruyer</span>
- <span class="text-sm"><mdi-book-open-variant /> "Des légumes en hiver - Produire en abondance, même sous la neig" - Eliot Coleman</span>
- <span class="text-sm"><mdi-book-open-variant /> "Le jardinier-maraîcher - Manuel d'agriculture biologique sur petite surface" - Jean-Martin Fortier</span>

---

# Merci

<div class="grid grid-cols-3 gap-4">
  <div class="col-span-2">
    <img src="/saunei-bauchon-darrer.jpeg" class="h-100 rounded drop-shadow-xl" />
  </div>
  <div class="col-span-1">
  <p class="text-sm italic">
  "Désormais la plus haute, la plus belle performance que devra réaliser l'humanité, sera de répondre à ses besoins vitaux avec les moyens les plus simples et le plus sains. Cultiver son jardin ou s'adonner à n'importe quelle activité créatrice d'autonomie sera considérée comme un acte politique, un acte de légitime résistance à la dépendance et à l'asservissement de la personne humaine."
  </p>
  <br />
  Pierre Rabhi 
  </div>
</div>
