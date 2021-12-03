# Mario Kart
*von Julian und Enis, 12bc*
## Inhaltsverzeichnis
 
 * [Programm](#Programm)
 
 * [Aufbau des Spiels](#AufbaudesSpiels)
    * [Spielidee](#Spielidee) 
    * [Der Code](#DerCode)
    * [verschiedene Spielmodi](#verschiedeneSpielmodi)
    * [Steuerung](#Steuerung)

* [Stundenprotokoll](#Stundenprotokoll)




## Programm
![Scratchlogo svg](https://user-images.githubusercontent.com/88385822/143713115-9840c9ea-9b26-4cbf-aaf7-b0768424819b.png)
Als Programm für unser Spiel verwendeten wir "Scratch", eine besonders anfänderfreundliche Programiersprache, die keine Vorkenntnisse in einer Programmiersprache vorraussetzte. Ihr Ziel ist es Neueinsteiger, besonders Kinder und Jugendliche mit den Grundkonzepten des Programmieren vertraut zu machen. Hierbei wird der Quellcode in Blöcke vereinfacht, die nach Belieben zusammengeheftet werden können. Die verschiedenen Blockarten unterscheiden sich hier in der Farbe und macht Scratch zu einer sehr visuellen und optisch ansprechenden Programmiersprache. 


## Aufbau des Spiels

### Spielidee 
Bei unserem Spiel handelt es sich um das klassische Mario Kart, demnach versucht man wie jedem anderen Rennspiel auch, als erstes ins Ziel zu kommen. Die Besonderheit bei Mario Kart ist, dass man durch das Benutzen von verschiedenen Items sich einen Vorteil gegenüber seiner Mitstreiter erschaffen kann. Die Items haben dabei unterschiedliche Eigenschaften und ihre Auswahl passiert zufällig. Dies zeichnet Mario Kart aus und sorgt für ein kompetitives ein Wettbewerbgefühl, bei dem der Ausgangs des Spiel ein wenig von Glück abhängt und auch erfahrene Spieler gegen Anfänger verlieren können. 

![Item Reel github](https://user-images.githubusercontent.com/88385824/143916738-20c291af-9d69-458f-8c66-ebecc0e542f1.PNG)

*Beispiel für ein Item*

![map github](https://user-images.githubusercontent.com/88385824/143918804-346d21d4-c54f-4d47-b981-a4b120c6014d.png)

Das Rennen findet auf dieser Karte statt und der Gewinner ist der, der zuerst drei Runden absolviert.



### Der Code

#### Beginn des Spiels
Das Spiel beginnt mit einem Startbildschirm, der den Namen des Spiels enthäkt und die Möglichkeiten "Play" und "Steuerung". Wenn man mit dem Mauszeiger über die einzelnen Auswahlmöglichkeiten geht wechselt sich ihre Farbe. 

![3axvaw9y](https://user-images.githubusercontent.com/88385824/143930741-8400e1e9-f838-405a-899e-0f3b96b0459c.gif)

Wenn man auf das "Play" drückt bekommt man die Möglichkeit im Einzelspieler oder Mehrspieler zu spielen. Auch hier ändert sich die Farbe wenn man mit dem Mauszeiger über die einzelnen Möglichkeiten geht.

![d6br25m6](https://user-images.githubusercontent.com/88385824/143944069-054079aa-4086-47dd-91d8-e7b39558e1cf.gif)

Das Ändern der Farbe wird durch veschiedene Köstume erreicht, die sich ändern, wenn der Mauszeiger den Sprite berührt. 

![Kostum switch Startbildschirm](https://user-images.githubusercontent.com/88385824/143945077-8ad9b1f4-dac3-4f29-ab06-99e1742a2248.PNG)

### Verschiedene Spielmodi
Es gibt zwei Spielmodi, einen Einzelspieler und einen Mehrspieler, der von zwei gleichzeitig gespielt werden kann.

#### Einzelspieler
Zunächst befindet man sich im Startmenü mit den Auswahlmöglichkeiten "Play" und "Steuerung". Wenn man auf Play drückt wird man zur Auswahl der Spielmodi gebracht. Sobald der Button vom Einzelspieler bei der Auswahl der Spielmodi angeklickt wird, erhält man eine Erklärung der Steuerung. Wenn man weiterklickt beginnt das Spiel. Hier kann man dann nur mit Mario spielen und es handelt sich um ein Zeitrennen.

![IMG_0777](https://user-images.githubusercontent.com/88385824/144026395-f4bea4f4-80bd-4806-8e86-fbd5a35d184b.jpeg)                                                                 
<details>
 <summary>Genauer</summary>

![Moduswahl github](https://user-images.githubusercontent.com/88385824/144619938-ac11314f-15e0-4c48-aac2-4fef3de331ca.PNG)

Wenn der "Play" Button angeklickt wird, erscheint ein neues Menu mit den Möglichkeiten EInzelspieler und Mehrspieler.

![d6br25m6](https://user-images.githubusercontent.com/88385824/143944069-054079aa-4086-47dd-91d8-e7b39558e1cf.gif)

![Einzelspieler button click github](https://user-images.githubusercontent.com/88385824/144621952-2cc696a2-cf32-4e03-8829-da1f3b9cf907.PNG)

Beim Anklicken des Einzelspieler Buttons wird man zur Erklärung der Steuerung weitergeleitet.

![Steuerungsscreen 1 github](https://user-images.githubusercontent.com/88385824/144622218-eb25df75-4774-423e-b4c9-c22102e2bca4.PNG)

Das Steuerungsmenü entsteht durch die Message "Steuerung Einzelspieler", der Sprite wechselt dann zwischen zwei Kostümen. 

![86zvjvy1](https://user-images.githubusercontent.com/88385824/144624672-78c2392e-d530-4196-a554-8ecf6620ab23.gif)

![start einzelspieler github](https://user-images.githubusercontent.com/88385824/144624793-5b381323-dc19-4562-8130-c9df9ccccdd6.PNG)

Durch Anklicken des Steuerungsmenü wird der Countdownsprite gestartet, dieser startet widerrum das Spiel wenn das vierte Kostum, also die 0 ausgewählt wird. 

![Countdown start Einzelspieler](https://user-images.githubusercontent.com/88385824/144624800-d47a1fe1-3c13-4375-90d0-10a3b1477942.PNG)

![start game einzelspieler github](https://user-images.githubusercontent.com/88385824/144624803-fa104014-8bdb-4373-b8a0-c48ed1eaf237.PNG)

![h6js39kd](https://user-images.githubusercontent.com/88385824/144629680-ae08ace1-44c5-4e27-92cb-9026cdb70bdb.gif)

 </details> <hr>
 
#### Mehrspieler  
Wenn man sich im Menü zur Auswahl des Spielmodis befindet und den Mehrspieler anklickt, kommt man wieder in das Steuerungsmenü. Hier wird alllerdings anders als beim Einzelspieler die Steuerung vom Spieler 1 und Spieler 2 erklärt. Mario wird mit den Pfeiltasten und der Leertaste gelenkt. Luigi mit A,D und B. Beide Speieler haben die gleiche Geschwindigkeit und müssen versuchen durch geschicktes Lenken und Einsetzen der Items das Rennen zu gewinnen. Wie auch im Einzelspieler fährt man drei Runden. 

![Multiplayer screen github](https://user-images.githubusercontent.com/88385824/144643014-d492eb0b-f9fe-4e4b-bdc6-5acc1d62b520.PNG)

<details>
 <summary>Genauer</summary>
 
 ![Steuerung multiplayer](https://user-images.githubusercontent.com/88385824/144657877-7b0f812d-be20-43b8-9e3d-5716b1d013ed.PNG)
 
 ![Steurung Multiplayer Mario](https://user-images.githubusercontent.com/88385824/144657879-cd0d55f4-78ff-4364-8fec-79a853bb0956.PNG)

 ![Steuerung Luigi](https://user-images.githubusercontent.com/88385824/144657884-4db91a3d-99a2-49ba-9cbd-b4cec2f81fe0.PNG)


![Countdown Multiplayer](https://user-images.githubusercontent.com/88385824/144657886-ba05d0be-0939-496d-8fd3-599f20d7677b.PNG)
 
![Start game multiplayer](https://user-images.githubusercontent.com/88385824/144657891-43f16acb-5136-4d4e-95ad-df61e6e93419.PNG)


</details> <hr>

### Steuerung
## Stundenprotokoll

### Dienstag 3. August

Zunächst haben wir die Stunde mit einer Kurzen Einführung begonnen. Dann haben wir uns einen GitHub Account erstellt. Nachdem wir den GitHub Account erstellt haben haben wir ein Projekt erstellt. Dann haben wir uns mit GitHub bekannt gemacht und einen Dokument zur Einführung bekommen. Auf diesem waren einige Vorschläge für Anfänger im Programmieren. Wir haben uns dann ein programm namens Applab rausgesucht und mit diesem etwas geübt. Den rest der stunde haben wir damit verbracht uns ein Thema für unser Projekt zu überlegen. Wir haben uns dazu entschlossen ein Spiel zu programmieren uns ist aber noch nicht ganz bewusst wie dieses aufgebaut ist. Zuhause haben wir uns dann beide weiter mit dem Einstieg ins Programmieren beschäftigt.


### Mittwoch 4. August

Heute haben wir uns weiter mit dem Programmieren befasst, wir konnten uns jedoch noch nicht für eine Programmiersprache entscheiden. 

### Dienstag 10. August
Zuhause haben wir uns mit unteschiedlichen Programmeirsprachen befasst und haben uns schlußendlich für JavaScript entschieden, da Julian bereits einige Vorkenntnisse mit dieser Programmiersprache hat. Wir verbrachten den Großteil der Stunde damit, uns die Grundlagen anzueignen, um mit dem Programmieren des Spiel zu starten.

### Mittwoch 11. August 
Nach einer kurzen Rücksprache mit Herrn Buhl haben wir uns entschieden mit Scratch zu programmieren, da dies eine sehr anfängerfreundliche Programmiersprache ist. Wir trafen zur Beginn der Stunde die Entscheidung Mario Kart zu programmieren, da dies ein Spiel ist, dass wir gerne spielen. Außerdem waren wir davon überzeugt, dass es eine anpruchsvolle Aufgabe wird, die wir aber bewältigen können. 

### Dienstag 17. August
*Entfall* 

### Mittwoch 18. August 
*Entfall*
### Dienstag 24. August

### Mittwoch 25. August

### Dienstag 31. August 

### Mittwoch 1. September

### Dienstag 7. September

### Mittwoch 8. September

### Diesntag 14. September

### Mittwoch 15. September

### Dienstag 21. September

### Mittwoch 22. September

### Dienstag 28. September

### Mittwoch 29. September 
*Entfall*
### Dienstag 5. Oktober 
*Entfall*
### Mittwoch 6. Oktober
*Ferien*
### Dienstag 12. Oktober
*Ferien*
### Mittwoch 13. Oktober 
*Ferien*
### Dienstag 19. Oktober

### Mittwoch 20. Oktober

### Dienstag 26. Oktober 

### Mittwoch 27. Oktober 

### Dienstag 2. November 

### Mittwoch 3. November 

### Dienstag 9. November
*Entfall*
### Mittwoch 10. November 

### Dienstag 16. November 

### Mittwoch 17. November 

### Dienstag 23. November 

### Mittwoch 24. November 

### Dienstag 30. November 

### Mittwoch 1. Dezember 


