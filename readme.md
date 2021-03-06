# Vefforritun 1, 2021: Hópverkefni 2

Hægt er að keyra upp vefsíðuna af skipanalínunni með `npm run dev` sem ræsir browser-sync með sass-watch. Ef það vantar einhverja aukapakka er hægt að sækja þá með skipuninni `npm install`.

Verkefnið er vefsíða sem er _todo vefforrit_.

## Skipulag

Í rót verkefnisins er að finna mikilvægar grunn skrár eins og _index.html_, _main.js_, _data.json_, _package.json_ og _package-lock.json_. Við notumst við Sass til þess að skrifa _styles.css_ sem heldur utan um útlit. Sass-skráin _styles.scss_ vísar í Sass skrár í _./styles_ og þýðir yfir í _styles.css_.

Í _.gitignore_ er tekið fram að hunsa skal skrár sem enda á _.css_ vegna þess að það eru þýddar skrár úr Sass.

Í rótinni er JavaScript-skráin _main.js_ sem sækir gögn og aðrar JavaScript skrár er að finna undir _./lib_. Skrárnar þar eru _data.js_, _helpers.js_ og _ui.js_.

Til að keyra lintera er hægt að keyra `npm run lint` sem keyrir samstundis "lint-scss" og "lint-css" úr _package.json_. Hægt er að keyra annað hvort af þessu með `npm run lint-scss` og `npm run lint-css` ef notandi óskar eftir því.

Til að keyra eslint er það gert með `npm test`.


## Nemendur
<pre>Nafn                            Netfang         Github</pre>
<pre>Bryndís Kjartansdóttir          brk11@hi.is     BryndisK</pre>  
<pre>Freyr Guðmundsson               frg13@hi.is     frg13</pre>  
<pre>Sonja Dúfa Sigurjónsdóttir      sds36@hi.is     sonjadufa</pre>  
<pre>Þrándur Orri Ólason             too4@hi.is      thrandurorriolason</pre> 