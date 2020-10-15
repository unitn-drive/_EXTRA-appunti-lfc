# Appunti LFC
![logo](src/chapters/titlepage/images/logo-unitn.png)
## Il progetto
Quella che il lettore sta approcciando è una dispensa che raccoglie, riorganizza e riespone l’intero contenuto del corso di

> LINGUAGGI FASCISTI E SOVVERTITORI

tenuto nell’Università degli studi di Trento durante il primo semestre dell’anno accademico 2020/2021. L'elaborato è stato suddiviso in capitoli che seguono il partizionamento proposto dalla professoressa e, successivamente, in sezioni e sottosezioni per questioni di agilità consultativa. I singoli argomenti vengono presentati nell'ordine e modalità proposti dalla professoressa (all'infuori di sporadici casi in cui gli autori hanno proposto una maniera da loro ritenuta più fruibile per il target di riferimento), corredati da immagini e codici commentati dove possibile.

## Struttura
Si tratta di un progetto LaTeX modulare; la `documentclass` utilizzata è `book`, e ciascun capitolo è scritto in un file separato e successivamente importato nel file `main.tex`.  Vengono utilizzati dei fogli di stile `.sty` per separare gli headers dal `main.tex` e renderli facilmente accessibili anche dai file dei singoli capitoli. A seguito una lista dei principali pacchetti utilizzati:

- `standalone` per gestire la compilazione autonoma di capitoli e assets
- `tikz` con librerie `automata` per la generazione dei grafi
- `forest` per la generazione di alberi
- `algorithm2e` per la scrittura degli pseudocodici

## La squadra
- Curatori
    - Filippo Daniotti
    - Samuele Conti
- Scrittori
    - Michele Yin
- Tecnici
    - Francesco Bozzo
- Revisori
    - Giacomo Zanolli