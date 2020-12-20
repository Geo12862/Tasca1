# Tasca1 (treball de classe ED)
***
## Descripcio
IMPORTANT: Totes les comandes de git que utilitzeu s'han de fer a traves de la terminal.

1 - Crear una pàgina web a github pages amb un index.html que contingui un llistat de totes les assignatures de primer del cicle formatiu que esteu cursant.

2 - Crear per cada una dels mòduls una branca de git al vostre repositori local, després en aquesta branca crear l'arxiu html del mòdul posant el títol i una breu descripció del mòdul.

     Veure les branques
          git branch

     Crear una nova branca a partir de la branca en qué esteu
          git branch nom_branca

     Crear una nova branca a partir de la master
          git branch nom_branca nom_branca_master

     Entrar a una branca determinada
          git checkout nom_branca

     Una vegada hem acabat els canvis hem de fer un merge a master local
          Primer feim el checkout a la branca que volem fer el merge
               git checkout master

          Després feim el merge.
               git merge nom_branca

3 - Pujar tots els canvis de la branca master al github per poder visualitzar la vostra web.
***
## Contingut
### Pases a seguir
- Me ficu en el cmd de git Bash
- Introdueix cd i la direccio dorigen del projecte Tasca1
- Amb el programa Atom he creat dins la carperta Tasca1 un index.html i un README.md, que el puc comprobar en el git Bash amb el comandament ls.
- Ficu el comandament git init per controlar les versions.
- Faig servir el comandament git status per comprovar els arxius amb els que hi treball.
- Amb git add ficu els archius que vull agregar a l'area de treball (commit)
- Al posar un git commit, quan he agregat els 2 arxius, me indica que em idenfiqui.
- Me demana que fiqui el email i l'usuari
- Faig una altre vegada el git commit i m'obre un bin, on pos de titol Tasca1, despres pitjo la tecla esc i ficu el comandament :wq per sortir del bin, i me surt en pantalla que s'han canviat 2 arxius i m'ha creat aquest 2 arxius.
- A partir d'ara per no ficarme al bin posare git commit -m "Titol descriptiu"
- Ara ficu les branques de cada asignatura amb:
git branch nomAsignatura i per comprobar les branques ficu git branch.
- Per poder mourer-me per les branques pos: git checkout nomBranca
- Dins de cada branca he utilitzat el comandament vim nomArxiu per crea el seu arxiu html amb la seva descripcio. Despres e fet el git add i el git commit de cada une de les branques.
- Per acabar me possat a la branca master i he fet merge amb cadacuna de les branques per juntarles am la branca master.
- Per finalitzar feim un git push per pujarlo al github amb cada branca, les branques que no hi eran al principe es crearan.

### Error fets en el projecte
- Vaig comensar feren tot al Visual Studio Code i no vaix sebre com ficar les branques una vegada fet tota la part web a un projecte en el git i nomes me surtia tot en el directori master.
Aixi que vaig comensar desde un principi tot el projecte amb les caracteristiques que es demanaven.
- Aquest projecte esta en catala, pero al ferlo amb un teclat angles no he pogut possar accents ni c trancada, lo qual aquesta l'he canviada per una s normal.
***
