# 🚢 **Titanic**: opowieść o ludziach zapisana w danych
Gdy w 1912 roku Titanic wyruszał w swój pierwszy rejs, nikt nie przypuszczał, że stanie się symbolem marzeń, tragedii — i... danych, które przetrwają wszystko.

W tej analizie nie chodzi tylko o liczby.
To historia setek ludzi: kobiet, mężczyzn i dzieci — ich nadziei, decyzji i losów.

Titanic nie wybierał.
Ale dane pokazują, kto miał większą szansę.

Nie pytam: „czy zginął?”.

Pytam: „**dlaczego?**”.

🔍 Sprawdzam, jak klasa biletu, wiek i płeć decydowały o szansach na ocalenie.

📈 Dane, które przez dekady milczały, zaczynają mówić — o samotności na pokładzie i o podziałach, które nie znikają nawet w obliczu katastrofy.

*To nie jest zwykła analiza.*

*To historia opowiedziana przez liczby.*

*Statystyczna podróż przez pokład Titanica.*

Wejdź na pokład — i zobacz, co mówią liczby.

🎧 Usłysz historię.

*Utworzono: 2025-06-19*


<a href="eda_titanic.ipynb" class="md-button">Pobierz Notebook</a>

<a href="eda_titanic.slides.html" class="md-button md-button--primary">Zobacz prezentację w nowej karcie</a>

<iframe
    id="content"
    src="eda_titanic.html"
    width="100%"
    style="border:1px solid black;overflow:hidden;"
></iframe>
<script>
function resizeIframeToFitContent(iframe) {
    iframe.style.height = (iframe.contentWindow.document.documentElement.scrollHeight + 50) + "px";
    iframe.contentDocument.body.style["overflow"] = 'hidden';
}
window.addEventListener('load', function() {
    var iframe = document.getElementById('content');
    resizeIframeToFitContent(iframe);
});
window.addEventListener('resize', function() {
    var iframe = document.getElementById('content');
    resizeIframeToFitContent(iframe);
});
</script>


<p style="text-align: center; font-size: 0.85em; color: #999;">
© 2025 Mateusz Wilczewski
</p>