---
# try also 'default' to start simple 
theme: seriph
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: https://cover.sli.dev
# some information about your slides (markdown enabled)
title: Welcome to Slidev
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
# apply UnoCSS classes to the current slide
class: text-center
# https://sli.dev/features/drawing
drawings:
  persist: false
# slide transition: https://sli.dev/guide/animations.html#slide-transitions
transition: slide-left
# enable Comark Syntax: https://comark.dev/syntax/markdown
comark: true
selectable: true
download: true
# duration of the presentation, default is '30min'
duration: 30min
# timer mode, can be 'countdown' or 'stopwatch', default is 'stopwatch'
timer: countdown
---

# Exam Instructions <br> Instructions d'examen

<!-- 
Presentation slides for developers 
-->

<div @click="$slidev.nav.next" class="mt-12 py-1" hover:bg="white op-10">
  Press Space for next page <carbon:arrow-right />
</div>

<div class="abs-br m-6 text-xl">
  <button @click="$slidev.nav.openInEditor()" title="Open in Editor" class="slidev-icon-btn">
    <carbon:edit />
  </button>
  <a href="https://github.com/slidevjs/slidev" target="_blank" class="slidev-icon-btn">
    <carbon:logo-github />
  </a>
</div>

<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)
-->

---
layout: two-cols
layoutClass: gap-4
---

# Read carefully

- Leave in front of you for the whole duration of the exam
  - Phone turned off facing down
  - Student card

- Take what you need (pencils, calculators, etc.) and bring everything else to the front of the room

- Take off your coats/jackets and hats/hoodies and hang them on the coat hangers or bring them to the front of the room

- Leave nothing on the seat/floor around you

- Never leave your seat without permission

- I won't answer questions already answered in the exam sheets


::right::

# Lisez attentivement

- À laisser devant vous pendant toute la durée de l'examen
  - Téléphone éteint, écran vers le bas
  - Carte d'étudiant

- Prenez vos besoins (crayons, calculatrices, etc.) et apportez tout le reste à l'avant de la salle

- Enlevez vos manteaux/vestes et vos chapeaux/capuches et accrochez-les aux cintres ou apportez-les à l'avant de la salle

- Ne laissez rien sur le siège/par terre autour de vous

- Ne quittez jamais votre place sans autorisation

- Je ne répondrai pas aux questions déjà répondues dans les feuilles d'examen

---
layout: two-cols
layoutClass: gap-4
---

# Time is up

- The TAs will pass around to collect the questionnaire AND the bubble sheet
- Then, they will count them
- During this time, the exam is still in session, and so the same exam rules concerning the student behavior still apply until students are explicitly allowed to leave


::right::

# Le temps est écoulé

- Les TAs feront le tour de la salle pour récupérer le questionnaire ET la feuille à bulles (bubble sheet) 
- Ensuite, ils les compteront
- Pendant ce temps, l'examen est toujours en cours ; les règles concernant le comportement des étudiants restent donc applicables jusqu'à ce qu'ils soient explicitement autorisés à quitter
