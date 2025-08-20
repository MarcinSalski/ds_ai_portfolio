# Analiza danych dotyczących pasażerów Titanica

To jeden z pierwszych projektów analitycznych, które wykonałem z wykorszystaniem notebooka stworzonego w środowisku Jupiter Lab. Jak widać, jest to ćwiczenie - odrabianie zadania domowego - a nie analiza nakierowana na poszukiwanie konkretnych informacji. Mimo to, myślę, że udało mi się dojść do ciekawych wniosków.

<a href="titanic.ipynb" class="md-button md-button--primary">Pobierz Notebook</a>

<iframe
    id="content"
    src="titanic.html"
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
