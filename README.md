[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/l0Gmb2I0)
# Stationboard

## Vanilla JS
in app.js
1) für input und button JS element erstellen (querySelector/getElementById)
2) getData erstellen
3) displayData erstellen:

Was|Wie
--|--
Element finden| `document.querySelector()`
Inhalt ändern|`element.textContent = 'neuer Inhalt'`;
Input wert lesen|`inputElement.value`
Erreignis auswerten|`element.addEventListener(event, handler);`
Zeitobject umwandeln|`const timeString = time.toLocaleTimeString('de-CH');`
Tabelle reihe hinzufügen| `const row = tabelle.insertRow();`
Spalltenelement hinzufügen| `const cell = row.insertCell(0);`
|| folgendes funktioniert nur in `async` Function
API-Befehl auslösen|`const response = await fetch(url);`
API-Resultat lesen|`const data = await response.json();`


## VueJS
1) in index.html oberhalb app.js das ergänzen

```js
    <script src="https://cdn.jsdelivr.net/npm/vue@3"></script>
```

2) in app.js das

```js
Vue.createApp({
    data() {
        return{}
    },
    methods: {

    }
}).mount('#app');
```
