<img src="mini-torte.png" width=70/>

# Schilderwald OK

Super, Du findest Dich im Schilderwald zurecht.
Und Du weißt, daß man statt "Ü" manchmal auch "Ue"
nutzt und daß "Ue" als Kleinbuchstaben zu "ue" wird.

Damit Du nicht einschläfst, ist jetzt ein wenig
Bewegung angesagt. Finde den Schatz im Holzstadel
und ermittle das Lösungswort! Trage es unten ein!

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
  var count='99'  
  var answer=answerElement.value;
  var url = footerUrl.value;
  var lnk=url+count+'-'+answer+'.html';
  window.location.href = lnk;
}

updateFooter(nextUrl);
</script>

<input id="footerUrl" type="text" style="display:none;"/>
<div id="dynamic" display="block">Lösungswort:  <input type="text" id="answer" value=""/></div> <input type="button" onclick="weiter()" value="Weiter" />
