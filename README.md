# misinform.app

Article-Generator testen:

1) misinform.app.articles/main.py starten.

2) Folgenden Command ausführen:
    
    ```bash
    curl -X POST "http://127.0.0.1:8000/render/buzzfeed" \
    -H "Content-Type: application/json" \
    -d @buzzfeed-neu.json \
    -o rendered.html

    open rendered.html   # macOS

  Nach dem -d die Input-JSON angeben.
