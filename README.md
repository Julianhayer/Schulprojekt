# Informatikprojekt : Mario Kart
*von Julian und Enis, 12bc*
## Inhaltsverzeichnis
 
 * [Programm](#Programm)
 
 * [Aufbau des Spiels](#AufbaudesSpiels)
    * [Spielidee](#Spielidee)
    * [verschiedene Spielmodi](#Spielmodi)
    * [Steuerung](#Steuerung)
 
 * [wichtige Objekte](#wichtigeObjekte)
    * [Karte](#Karte)
    * [Rundenzähler](#Rundenzähler)
    * [Items](#Items)
    * [Timer](#Timer)

 * [Arbeitstagebuch](https://github.com/EnisAdzessi/Arbeitstagebuch.git)



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





### Beginn des Spiels
Das Spiel beginnt mit einem Startbildschirm, der den Namen des Spiels enthält mit den Auswwahlmöglichkeiten "Play" und "Steuerung". Wenn man mit dem Mauszeiger über die einzelnen Auswahlmöglichkeiten geht wechselt sich ihre Farbe. 

![3axvaw9y](https://user-images.githubusercontent.com/88385824/143930741-8400e1e9-f838-405a-899e-0f3b96b0459c.gif)

Wenn man auf das "Play" drückt bekommt man die Möglichkeit im Einzelspieler oder Mehrspieler zu spielen. Auch hier ändert sich die Farbe wenn man mit dem Mauszeiger über die einzelnen Möglichkeiten geht.

![d6br25m6](https://user-images.githubusercontent.com/88385824/143944069-054079aa-4086-47dd-91d8-e7b39558e1cf.gif)

Das Ändern der Farbe wird durch veschiedene Kostüme erreicht, die sich ändern, wenn der Mauszeiger den Sprite berührt. 

![Kostum switch Startbildschirm](https://user-images.githubusercontent.com/88385824/143945077-8ad9b1f4-dac3-4f29-ab06-99e1742a2248.PNG)

## Verschiedene Spielmodi <a name="Spielmodi">
Es gibt zwei Spielmodi, einen Einzelspieler und einen Mehrspieler, der von zwei gleichzeitig gespielt werden kann.

### Einzelspieler
Zunächst befindet man sich im Startmenü mit den Auswahlmöglichkeiten "Play" und "Steuerung". Wenn man auf Play drückt wird man zur Auswahl der Spielmodi gebracht. Sobald der Button vom Einzelspieler bei der Auswahl der Spielmodi angeklickt wird, erhält man eine Erklärung der Steuerung. Wenn man weiterklickt beginnt das Spiel. Hier kann man dann nur mit Mario spielen und es handelt sich um ein Zeitrennen.

![IMG_0777](https://user-images.githubusercontent.com/88385824/144026395-f4bea4f4-80bd-4806-8e86-fbd5a35d184b.jpeg)                                                                 
<details>
 <summary>Genauer</summary>

![Moduswahl github](https://user-images.githubusercontent.com/88385824/144619938-ac11314f-15e0-4c48-aac2-4fef3de331ca.PNG)

Wenn der "Play" Button angeklickt wird, erscheint ein neues Menu mit den Möglichkeiten Einzelspieler und Mehrspieler.

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
 
### Mehrspieler  
Wenn man sich im Menü zur Auswahl des Spielmodis befindet und den Mehrspieler anklickt, kommt man wieder in das Steuerungsmenü. Hier wird alllerdings anders als beim Einzelspieler die Steuerung vom Spieler 1 und Spieler 2 erklärt. Mario wird mit den Pfeiltasten und der Leertaste gelenkt. Luigi mit A,D und B. Beide Speieler haben die gleiche Geschwindigkeit und müssen versuchen durch geschicktes Lenken und Einsetzen der Items das Rennen zu gewinnen. Die Items des Spieler 1 befinden sich oben und die Items von Spieler 2 unten. Wie auch im Einzelspieler fährt man drei Runden. 

![Multiplayer screen github](https://user-images.githubusercontent.com/88385824/144643014-d492eb0b-f9fe-4e4b-bdc6-5acc1d62b520.PNG)

<details>
 <summary>Genauer</summary>
 
 Wenn der Mehrspielermodus im Menü ausgewählt wird, broadcastet dieser die Message "Steuerung".
 
 ![Steuerung multiplayer](https://user-images.githubusercontent.com/88385824/144657877-7b0f812d-be20-43b8-9e3d-5716b1d013ed.PNG)
 
 Diese Message zeigt dann zuerst den Sprite mit der Steuerung von Spieler 1 und dann anschließend von Spieler 2.
 ![Steurung Multiplayer Mario](https://user-images.githubusercontent.com/88385824/144657879-cd0d55f4-78ff-4364-8fec-79a853bb0956.PNG)

 ![Steuerung Luigi](https://user-images.githubusercontent.com/88385824/144657884-4db91a3d-99a2-49ba-9cbd-b4cec2f81fe0.PNG)

![Countdown Multiplayer](https://user-images.githubusercontent.com/88385824/144657886-ba05d0be-0939-496d-8fd3-599f20d7677b.PNG)
 
Wenn dann weitergeklickt wird, startet sich der Countdown, dieser zählt von 3 runter und startet das Spiel. Anders als beim Einzelspieler werden erscheinen hier Mario und Luigi, da beide durch die jeweiligen Messages "Spieler 1 Start" und "Spieler 2 Start" erscheinen. Außerdem erscheinen beide Item Reels der jeweiligen Spieler. Das von Spieler 1 oben und das von Spieler 2 unten. Diese werden durch die Message "Item Reel Spieler 1 Start" und "Item Reel Spieler 2 Start" getriggert.  

 ![Start game multiplayer](https://user-images.githubusercontent.com/88385824/144657891-43f16acb-5136-4d4e-95ad-df61e6e93419.PNG)

 ![damvh6fk](https://user-images.githubusercontent.com/88385824/144660494-baf4601b-3b52-4baf-9097-b3349891e36f.gif)


</details> <hr>

## Steuerung
Der Spieler 1, der Mario steuert, lenkt mit den Pfeiltasten <-- und -->.Die Items kann man mit der Leertaste auslösen. Der Spieler 2 lenkt mit A und D und löst seine Items mit B aus. Die Geschwindigkeit kann ohne das Verwenden von Items oder das Nichtfahren auf der Straße nicht verändert werden. 

 <details>
 <summary>Genauer</summary>
 
 Bei den spielbaren Figuren handelt es sich um rote Punkte, die gelenkt werden. Der Mario Sprite befindet sich dauerhaft auf diesem roten Punkt und dreht sich mit dem Punkt zusammen. 

![Player 1](https://user-images.githubusercontent.com/88385824/144681851-56a816db-7852-4eff-8161-f310cb56ca7f.PNG)

![Mario Sprite](https://user-images.githubusercontent.com/88385824/144682098-96a9a5de-6844-498c-b312-6cbf0e26be27.PNG)

  Wenn der Mario Sprite die Message "Countdown" erhält, wird sein Größe um 50 % reduziert und zeigt in 0 Grad Richtung, damit er nach vorne schaut. Außerdem muss der Rotationstil nicht rotieren ausgewählt werden, damit sich der Sprite zweidimensional nach links oder rechts dreht. Andernfalls dreht er sich um seine eigene Achse. Der Mario Sprite befindet sich durch den forever Block immer auf dem roten Punkt, dessen Sprite Player 1 ist.

 
 
![links mario](https://user-images.githubusercontent.com/88385824/144681318-b38ab456-16a1-4555-98bd-5a8b552f4d3b.PNG)
![rechts mario](https://user-images.githubusercontent.com/88385824/144681326-21a88f42-9690-41d4-869e-bbccbeab9187.PNG)

Wenn die rechte oder linke Pfeiltaste gedrückt wird drehen sich der rote Punkt und Mario um jeweils 7 Grad. 
  
Beim Spieler 2 funktioniert das Lenken identisch, nur das man A und D zum Lenken verwendet.
  
![links rechts luigi](https://user-images.githubusercontent.com/88385824/144685119-124041a2-7dc0-426c-9ab8-e9a925ac35ae.PNG)

![luigi sprite](https://user-images.githubusercontent.com/88385824/144709098-ee67fcd0-529d-4df1-bb5f-152dcd48c34d.PNG)

Auch hier befindet sich der Luigi Sprite dauerhaft auf einem roten Punkt, dessen Sprite "Player 2" heißt. 

 </details> <hr>

## Wichtige Objekte

### Karte
Es handelt sich bei der Karte um Marios Piste 1 aus Super Mario Kart, dass im Jahr 1992 auf dem Super Nintendo Entertainment System (kurz:SNES) veröffentlicht wurde. Der Spieler ist auf dem Asphalt am schnellsten und die Geschwindigkeit nimmt ab, wenn man die Strecke verlässt und auf dem Sand fährt. Bei der regenbogenfarbedenen Fahrbahnumrandung handelt es sich um Wände gegen die man fährt, durch die zweidimensionale Darstellung wird dies beim ersten Blick nicht direkt klar. Wenn der Spieler die Fahrbahnumrandung berührt wird seine Geschwindigkeit durch den Abprall negative gesetzt, kurz danach beschleunigt er wieder und der Prozess wiederholt sich, wodurch man nicht an dieser Wand vorbei fahren kann, man aber durch den Abprall nicht unendlich lange nach hinten fährt. 
Aufgrund der Items ensteht aber leider manchmal das Problem, dass Farben nicht erkannt werden. Dies geschiet nur wenn ein Spieler ein tems trägt.
 
 
 <details>
 <summary>Genauer</summary>
 
![map github](https://user-images.githubusercontent.com/88385824/143918804-346d21d4-c54f-4d47-b981-a4b120c6014d.png)
 
 Die Karte besteht aus dem Asphalt, dem Sand und der Rasen, der durch eine Spielfeldumrandung von der Piste getrennt ist. Alle Bereiche unterscheiden sich in ihrer Farbe, Grau, braun und grün. Damit der Sprite die einzelnen Bereiche der Karte erkennt haben wir eine zweite Map, die von der Größe her mit de3r Originalkarte übereinstimmt und auf die regenbogenfarbende Fahrbahnumrandung verzichtet. Sie erhält lediglich die drei Farben, damit Mario und Luigi erkenne, wenn sie die Fahrbahn verlassen. 
  
![Map2](https://user-images.githubusercontent.com/88385824/144713770-98de3a32-a69a-4356-a4f6-a6dc4138ee14.png)
  
Dies ist die zweite Karte.


![Speed Player 1](https://user-images.githubusercontent.com/88385824/144713990-170ef1c4-3157-40f6-958d-44632e519deb.PNG) 
![speed player 1  s](https://user-images.githubusercontent.com/88385824/144714451-ea5d9eb0-82ea-4335-babd-da4215999b6d.PNG)


Es handelt sich bei der Geschwindigkeit, um eine Variable, die bei Beginn des Spiels, bis maximal 5 erhöht wird. Sofern man sich auf dem Asphalt befidnet erhöht sie sich jede Sekunde um 0,5 bis sie 5 erreicht. Der Spieler bewegt sich in Speed Steps, was bedeutet, dass er immer so viele Schritte macht, wie die Variable hoch ist. Wenn man sich auf dem Sand befindet wird die Speed Variable mit 0,8 multipliziert wodurch sich die Speed Variable verringert und man langsamer wird. Wenn man die Fahrbahnumrandung oder den Rasen berührt, wird die Variable *(-0,5) multipliziert und man fährt rückwärts. Berührt man dann nur noch den Sand wird die Variable positiv und man fährt wieder nach vorne.

![map2 ghost effect](https://user-images.githubusercontent.com/88385824/144714520-7ca50408-65f4-4a36-ab6b-0473e3911192.PNG)

Damit die zweite Karte nicht zu sehen ist, gibt es in Scratch einen "Ghost Effect" wodurch die Karte nicht zu sehen ist, die Sprite aber dennoch mit ihm interagieren können. Demnach erkennen der "Player 1" und "Player 2", dass sie die Farbe berühren, wodurch die Speed Varible verändert wird.
 

  
</details> <hr>

### Rundenzähler 
Rechts oben sind die Rundenzahlen der beiden Spieler zu sehen. Es handelt sich hierbei um eine Variable, die sich erhöht wenn man über den gelben Checkpoint und die Ziellinie gefahren ist. Beide Spieler starten mit einer Rundenzahl von -1, da bei einer Rundenzahl von 0 das Problem auftetren würde, dass man beim ersten Kontakt mit der Zielinie die Variable auf 1 wäre. Es ist zu empfehlen kein Item beim Spieler zu tragen, wenn man den Checkpoint oder die Zielinie berührt.


![5wlj4y1p](https://user-images.githubusercontent.com/88385824/144714988-9ba78389-1753-4ba0-87f8-166aea3852d0.gif)

<details>
 <summary>Genauer</summary>
 Um dem Problem aus dem Weg zu gehen, dass man mehrmals über die Zielinie fährt,um den die Rundenvariable zu erhöhen, gibt es einen gelbe Checkpoint, über den man fahren muss, erst dann ist er sich bei Kontakt mit der Zielinie die Rundenvariable. Zu Beginn ist die Checkpoint auf 1, und wird beim Überfahrren der Ziellinie runtergesetzt. 

![Checkpoint start](https://user-images.githubusercontent.com/88385824/144715222-411e3734-37fb-4c70-8070-e7d70e0a86c5.PNG)

Bei der Zielinie handelt es sich um eine Schwarze Linie, die sich durch den "Ghost Effect" nicht zu sehen ist, wenn Mario und Luigi ihn jedoch berühren können sie dennoch mit ihm interagieren und die Rundenvariable wird, sofern der Checkpoint vorher berührt wurde, hochgesetzt. 


![Checkpoint](https://user-images.githubusercontent.com/88385824/144715352-c5e7871c-5150-47bc-b8b5-31ed76ffa4bf.PNG)
 ![touch checkpoint](https://user-images.githubusercontent.com/88385824/144715219-977fd39d-45fe-4e83-8bb8-7fbed5639c91.PNG)

![finish line](https://user-images.githubusercontent.com/88385824/144715338-fd3b96d6-85a8-4241-b9e4-318efa24d256.PNG)
![finish line ghost effect](https://user-images.githubusercontent.com/88385824/144715340-47a54ec0-7864-49b6-beb2-598680c1b211.PNG)
![touch finish](https://user-images.githubusercontent.com/88385824/144715220-28a22637-7d73-4680-8ab3-7ed51ebf1a56.PNG)

Aufgrund des Problems mit den Items und der Farberkennung wird während ein Item vom Spieler getragen wird manchmal nicht erkannt, dass der Checkpint oder die Zielinie berührt wurde.
 
 </details> <hr>
 
 
 ## Items
 Die Items sind das Herzstück von Mario Kart und unterscheiden es von anderen Rennspielen. Man kann sie verwenden, um schneller zu werden oder seinen Gegner zu sabotieren. Es gibt 4 verschiedenene Items:

 Die Mushrooms, die kurzzeitig deine Geschwindigkeit verändern. 

 ![mushroom](https://user-images.githubusercontent.com/88385824/144716204-17780753-1208-434a-9356-d192825c8179.PNG)

Die Bananen, die hinter den Spieler plaziert werden. Wenn man über eine Banane fährt, dreht man sich um 720 Grad.

![banana](https://user-images.githubusercontent.com/88385824/144716205-cb97903c-d801-4206-aa0e-300091881b58.PNG)

Die Green Shell, die nach vorne geschossen wird. Wenn man von ihr getroffen wird dreht man sich um 720 Grad.

![green shell](https://user-images.githubusercontent.com/88385824/144716207-0fc5d1c5-a2b1-417e-ae81-9516ce6a4ff2.PNG)

Die Red Shell, die den Gegner verfolgt. Wenn man von ihr getroffen wird dreht man sich ebenfalls um 720 Grad.

![red shell](https://user-images.githubusercontent.com/88385824/144716208-ab4b0820-0cb6-4195-a849-44f0338341e2.PNG)

### Auswahl der Items
Die Auswahl der Items erfolgt über das Item Reel. Bei Beginn des Spiel erscheint das Item Reel und beginnt zwischen dem Mushroom, der Banane, der Green Shell und der Red Shell zufällig ein Item auszuwählen. Wenn ein Item ausgewählt wird, stoppt das Item Reel bis zur Benutzung des Items. Nach 3 Sekunden beginnt es dann wieder mit der zufälligen Auswahl der Items. 
 
![nzk71frc](https://user-images.githubusercontent.com/88385824/144742282-2ec8de41-2d22-4c97-848e-0e5f55f4d588.gif)

Das Item Reel besteht aus dieses 4 Items und das Item, dass als letztes erscheint, erhält der Spieler.
 
<details>
 <summary>Genauer</summary>
 
![Kostüme Item Reel Sprite](https://user-images.githubusercontent.com/88385824/144742464-4d9649ba-794c-49be-8c73-27e952d4b194.PNG)
 
 Der Item Reel Sprite besteht aus diesen 5 Kostümen.
 
 
Wenn das Spiel beginnnt erscheint das Item Reel des Spieler 1 oben neben der Rundenanzahl. Das Item Reel des Spieler 2 befindet sich unten neben dem Timer. Sobald das Item Reel erscheint wählt es zwischen einer zufälligen Zahl zwischen 60 bis 64. Wenn eine Zahl X ausgehwählt wurde geht der Sprite X mal zum nächsten Kostüm. Wenn es sich beim 2. Kostüm befindet wird das Kostüm mit dem Green Shell ausgewählt, beim 3. der Mushroom, beim 4. die Red Shell und beim 5. die Banane. Wenn ein Kostüm ausgewählt wird, broadcastet dies die Message des jeweiligen Items, wodurch das Item hinter dem Spieler erscheint. Das 1.Kostüm ist ein leeres Item Reel, wenn dieses ausgewählt wird, wird die Message "leeres Item Reel" gebroadcastet, was dazu führt, dass das Item Reel eine neue Zahl zwischen 60 bis 64 auswählt. 

![Item Reel Code](https://user-images.githubusercontent.com/88385824/144742466-dd0377a4-8bed-4923-963e-86791ade7f3b.PNG)
![leeres Item Reel Code](https://user-images.githubusercontent.com/88385824/144742465-dec91992-2b2e-4ae7-82a8-43371787a077.PNG)



 
 #### Mushrooms
Die Mushrooms werden verwendet, um einen Geschwindigkeitsboost zu erhalten. Dieser erfolgt nur kurzeitig und währenf des Geschwindkeitsboostes erscheint ein anderes Kostüm, dass ein einen Feuerball darstellt. Wenn das Item Reel die Message "Mushroom" broadcastet, erscheitn der Mushroom hinter dem Spieler, wenn dann Leertaste oder b gedrückt wird, wechselt sich das Kostüm und die Message "Mushroom Speedboost2" wird gebroadcastet. Dies erzeugt beim Player eine Erhöhung der Speedvariable für 2 Sekunden. 
 
![mushroom code ende](https://user-images.githubusercontent.com/88385824/144920078-99740913-7a48-48da-8959-2ef34584a175.PNG)
![mushroom code player 1](https://user-images.githubusercontent.com/88385824/144920083-0a4bce8b-39c2-4466-a59e-8711a0b985d3.PNG)
 
 #### Banane
Die Banane wird verwendet, um den gegnerischen Spielr bei Kontakt zum Drehen zu bringen. Wenn Leertaste oder B gedrückt wird, wird die Banane ein wenig hinter dem Spieler plaziert und kreiert einen Klon von sich. Wenn dieser Klon sich dem gegnerischen Spieler nähert, wird die Message "Banana hit" gebroadcastet, die den Spieler zum Drehen bringt. Dieser löst dann widderum eine Message aus, die die Banane zum Verschwinden bringt. Man kann nur eine Banane zur Zeit auf der Rennstrekce haben.
 
 
![banane code ende](https://user-images.githubusercontent.com/88385824/144920897-6974def2-a43f-40e3-a94e-18b265b29c14.PNG)
![banane code ende 2](https://user-images.githubusercontent.com/88385824/144920902-70a2b951-01fb-4912-8f2c-8614740a750c.PNG)

![banane code player](https://user-images.githubusercontent.com/88385824/144920904-d5a2e47e-6546-4d52-9f16-063985e3fdb7.PNG)


 #### Red Shell
 Die Red Shell verfolgt bei Verwendung des Items den gegnerischen Spieler und bringt ihn dazu sich zu Drehen. Auch sie kreiert beim Auslösen einen Klon. Dieser triggert beim Annähern vom gegenerischen Spieler eine Message "Red Shell Hit", die diesen zum Drehen bringt. Der Klon wird nach Berührung des gegnerischen Spielers gelöscht.

![Red Shell code ende](https://user-images.githubusercontent.com/88385824/144921628-fac85cd1-9f72-4f5b-b4ed-bb6a864ba41c.PNG)

![red shell ende player](https://user-images.githubusercontent.com/88385824/144921631-3d3c961d-dcce-4a7f-81d8-01bb6c9357c2.PNG)

 
#### Green Shell
 Die Green Shell wird auch verwendet um den Spieler zum Drehen zu bringen. Dieses Item wird jedoch anders als die Red Shell nach vorne geschossen und der gegnerische Spielr wird nur gedreht, wenn er getroffen wird. Wir haben versucht die Green Shell an der Wand abprallen zu lassen, indem die Variable bei jedem Kontakt mit der Fahrbahnumrandung hochgesetzt wird und nach 4 Kontakten die Green Shell verschwindet. Außerdem soll bei Berührung der Green Shell mit der Wand die Richtung um 180 Grad verädnert werden. Dies hat allderings nicht funktioniert, leider hatten wir keinen anderen Lösungsansatz. Wie auch die Red Shell wird der wird der gegnerische Spieler gedreht, wenn der Spieler sich der Green Shell nähert. Wenn dies passiert wird der Klon gelöscht. 
 
 
![Abprallen](https://user-images.githubusercontent.com/88385824/144922509-6588b509-8084-401d-b18b-765e450b427f.PNG)

![green shell code](https://user-images.githubusercontent.com/88385824/144922515-5593cf7c-6d1d-4d82-bf2c-cb454ede6095.PNG)



  
  </details> <hr> 
 
 ## Timer
 Der Timer zeigt dem Spieler an wie viel Zeit vergangen ist. Am Ende des Spiel wird die Zeit in der Mitte des Bilschirms angezeigt, um zu zeigen wie schnell man war. Der Timer besteht aus 3 verschiedenen Sprites, die für verschiedene Zehnerpotenzen stehen. Der Rechte ändert jede Sekunde zum nächsten Kostüm nach 10 Sekunden broadcastet er die Message "10 Sekunden", die den mittleren Sprite ein Kostüm weitergehen lässt. Wenn diser Sprite seine Rotation einmal durchgegangen ist und wieder beim ersten Kostüm angekommen, also der 0 angekommen ist, setzt er die  100 Sekunden Variable um einen hoch, was die Message "100 Sekunden" broadcastet. Dies sorgt dafür, dass der linke Sprite auf 1 gesetzt wird. 
 
![1 sekunde](https://user-images.githubusercontent.com/88385824/144924127-0d434baa-fd00-45a2-abbd-533dadf0e0ac.PNG)

![10 sekunden](https://user-images.githubusercontent.com/88385824/144924132-7518edc4-e70f-40d6-870a-21da166aae90.PNG)

![100 sekunden](https://user-images.githubusercontent.com/88385824/144924138-a55963be-51d9-47f0-9ba8-b1aede33c0e3.PNG)

![Endscreen Player 1with timer ](https://user-images.githubusercontent.com/88385824/144924579-7e17eb11-8e11-4855-ac1d-eb4895599128.PNG)

 In der Mitte des Endscreens kann man seine Zeit sehen.
 
 


 

 
