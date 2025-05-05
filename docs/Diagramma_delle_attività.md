<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Page Title</title>
    <script type="module">
        import mermaid from 'https://cdn.jsdelivr.net/npm/mermaid@latest/dist/mermaid.esm.min.mjs';
        mermaid.initialize({ startOnLoad: true });
    </script>
</head>
<body>
    <pre class="mermaid">
        graph LR
        A[Start] --> B(Lancio Steam)
        B --> C(Login Steam)
        C --> D{Seleziono Bastalon}
        D --> E(Lancio Bastalon)
        D --> F[Stop]
        E --> G[Fork or Join]
        G --> H(Gioco Bastalon)
        G --> I(Raccolta Statistiche)
        H --> L[Fork or Join]
        I --> L
        L --> M(Chiudo Bastalon)
        M --> F
    </pre>
</body>
</html>
