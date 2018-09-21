+++
aliases = [
    "/archive.html"
]

+++
<!DOCTYPE html>
<html lang="de">
{{ partial "head.html"  }}

  <body id="page-top">
  
    <!-- Navigation -->
    {{ partial "nav.html" . }}
  

    <!-- News Grid -->
    {{ partial "news.html" . }}

  
    <!-- Contact -->
    {{ partial "contact.html" . }}
  
    <!-- Footer -->
    {{ partial "footer.html" . }}
  
    <!-- Portfolio Modals -->
    {{ partial "modals.html" . }}
  
    <!-- JS -->
    {{ partial "js.html" . }}
  
  </body>

</html>
