
<pre class="mermaid">
      graph LR
    A@{ shape: circle, label: "Start" } --> B(Lancio Steam)
	B --> C(Login Steam)
	C --> D{Seleziono Bastalon}
	D --> E(Lancio Bastalon)
	D --> F@{ shape: dbl-circ, label: "Stop" }
	E --> G@{ shape: fork, label: "Fork or Join" }
	G --> H(Gioco Bastalon)
	G --> I(Raccolta Statistiche)
	H --> L@{ shape: fork, label: "Fork or Join" }
	I --> L
	L --> M(Chiudo Bastalon)
	M --> F
               </pre>