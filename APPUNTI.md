IMPOSTAZIONI DI BASE

1. dentro (src -> app.vue) cancello tutto ciò che trovo dentro "script", "template" e "style". poi la proprietà “setup” dallo "script". poi elimino la cartella "style.css"

2. dentro (src -> main.js) cancello (import './style.css’)

3. creo poi a pari della cartella “components” una nuova cartella chiamata "style". al suo interno creo il file “general.scss” e una cartella chiamata “partials” in cui andrò a inserire i file ( _nomefile.scss ) da collegare ai componenti 

4. dentro (src) creo un file chiamato "store.js" per creare un file che condivida informazioni tra i vari "file.vue"