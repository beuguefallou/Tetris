# Tetris
A vanilla javascript game


Dans ce cours, vous apprendrez comment mettre en place un projet à partir de zéro en utilisant l'éditeur de code Atom et votre outil d'invite de commande, ainsi que d'acquérir une compréhension fondamentale de JavaScript en construisant votre propre version de Tetris.

C'est un excellent cours pour ceux d'entre vous qui n'ont jamais touché le code auparavant ou ceux d'entre vous avec une certaine compréhension de base de JavaScript, qui voudrait refaire en revue les fondamentaux.

Ce cours consiste en des vidéos explicatives qui vous parcourront des concepts tels que "Expliquer les variables", "Qu'est-ce qu'une fonction et comment nous l'utilisons", "Comprendre les réseaux", et bien d'autres. Ces vidéos explicatives sont en pointillés tout au long du projet Tetris et jouent lorsque nous commençons à découvrir chaque concept ou méthode javaScript. Ces vidéos explicatives consistent en des images et des diagrammes pour ceux d'entre vous qui sont des apprenants visuels. Il y a aussi des questions à choix multiples à la fin de certaines conférences.



<h2>Brief</h2>
 
* The game should stop if a Tetrimino fills the highest row of the game board
* The player should be able to rotate each Tetrimino about its own axis
* If a line is completed it should be removed and the pieces above should take its place
* Render a grid-based game in the browser
* Include separate HTML / CSS / JavaScript files
* Use Javascript for DOM manipulation
* Deploy your game online, using Github Pages, where the rest of the world can access it
* Use semantic markup for HTML and CSS (adhere to best practices)

<h2>Dans ce jeu de Tetris, nous couvrirons les méthodes JavaScript ci-après:</h2>

* HTML5
* CSS3
* JavaScript
* Git
* GitHub
* Google Fonts



```

<h2>Features piece of code no.2</h2>


```
  //Add score
  function addScore() {
    for (currentIndex = 0; currentIndex < 199;currentIndex += width) {
      const row = [currentIndex,currentIndex+1,currentIndex+2,currentIndex+3,currentIndex+4,currentIndex+5,currentIndex+6,currentIndex+7,currentIndex+8,currentIndex+9]
      if(row.every(index => squares[index].classList.contains('block2'))) {
        score += 10
        lines +=1
        scoreDisplay.innerHTML = score
        linesDisplay.innerHTML = lines
        row.forEach(index => {
          squares[index].style.backgroundImage = 'none'
          squares[index].classList.remove('block2') || squares[index].classList.remove('block')

        })

```

