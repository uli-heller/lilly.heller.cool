<img src="mini-torte.png" width=70/>

# Liebe Tochter!

Heute hast Du Geburtstag und ich freue mich sehr für Dich!
Natürlich sollst Du dafür auch eine Belohnung erhalten.
Aber: Ohne Fleiß kein Preis! Deshalb führt der Weg zur Belohnung
über ein schwieriges Quiz. Mal sehen, ob Du es schaffst!

Hier noch einige "Regeln" (die mußt Du Dir alle merken):

- Das Quiz besteht aus Frageseiten ähnlich dieser
- "Unten" kannst Du die Antwort eintippen
- Die Antwort besteht entweder aus einer Ziffernfolge oder aus einer Folge von Kleinbuchstaben oder aus einer Kombination von beidem
- Nicht enthalten sind Großbuchstaben - nimm stattdessen Kleinbuchstaben!
- Nicht enthalten sind auch Umlaute - nimm stattdessen die "Zweier-Umschreibung"
- Auch nicht enthalten sind Leer- und Satzzeichen - lass die einfach weg
- Wenn Du die richtige Antwort eintippst, dann "geht es weiter"
- Wenn Du die falsche Antwort eintippst, dann gibt es eine Art Fehlerseite
- Bei der Fehlerseite mußt Du zurück zur Frageseite und dort einen neuen Versuch unternehmen

Hier nun eine erste Testfrage. Am besten beantwortest Du sie probehalber
mal falsch, damit Du die Art von Fehlerseite schonmal gesehen hast.

Dein wievielter Geburtstag ist heute?

<script type="text/javascript">
function updateFooter(url) {
  var divElement = document.getElementById('dynamic');
  var answerElement = document.getElementById('answer');
  answerElement.value = '';
  var footerUrlElement = document.getElementById('footerUrl');
  footerUrlElement.value = url;
  if (url.endsWith('-')) {
    divElement.style.display = "block";
  } else {
    divElement.style.display = "none";  
  }
}

function weiter() {
  var answerElement = document.getElementById('answer');
  var footerUrlElement = document.getElementById('footerUrl');
  var count='01'  
  var answer=answerElement.value;
  var url = footerUrl.value;
  var lnk=url+count+'-'+answer+'.html';
  window.location.href = lnk;
}

updateFooter(nextUrl);
</script>

<input id="footerUrl" type="text" style="display:none;"/>
<div id="dynamic" display="block">Erste Antwort:  <input type="text" id="answer" value=""/></div> <input type="button" onclick="weiter()" value="Weiter" />
