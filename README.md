<h1>Project Overview</h1>
<img src="\BP_Screen\menu.png" width="400px" height="550px">
<p>
PurrChaser is a mobile game developed in Unreal Engine 5.
This project was created during the "Classe X" week, a week in which all the students at BigRock are divided into groups and have to realize a project commissioned by an external client.
</p>

<p>
I was in charge of the realization of the gameplay mechanics, such as: 
<ul>
  <li>Procedural spawn of the object to dodge</li>
  <li>Procedural spawn of the rows of collectable coins</li>
  <li>Organization of the shop</li>
</ul>
</p>

<h2>Obstacles spawn</h2>
<img src="\BP_Screen\SpawnObstaclept1.png" width="700px" height="400px">
<img src="\BP_Screen\SpawnObstaclept2.png" width="700px" height="400px">
<p>
  Once I created an M-matrix(i,j), the objects spawn with a probabilistic logic.
  <ul>
    <li><p>Firstly, I calculate the spawn probability based on the row where I am (compared to the matrix),
    le file centrali haano una probabilità di spawn più alta riepstto le file esterne</p></li>
    <li> Poi vado a calocalere quale oggetto spawnare</li>
  </ul>
</p>
<img src="\BP_Screen\SpawnProbability.png" width="700px" height="400px">
<img src="\BP_Screen\ProbabilityObstacleSpawn.png" width="700px" height="400px">


<h2>Spawn Delle monete</h2>
<p>
  Questa volta vado a calcolare in quale fila e per quante righe spawnare le monete.
  Utilizzando un array di Vector3 per salvare le posizione dove ho spawnato gli ostacoli evito di spawnare le monete sotto di essi.
  <ul>
    <li><p>In primo luogo vado a calocalarmi la probabilità di spawn in mase alla fila in cui mi trovo (rispetto alla matrice),
    le file centrali haano una probabilità di spawn più alta riepstto le file esterne</p></li>
    <li> Poi vado a calocalere quale oggetto spawnare</li>
  </ul>
</p>
<img src="\BP_Screen\SpwanCoinPt1.png" width="700px" height="400px">
<img src="\BP_Screen\SpawnCoinPt2.png" width="700px" height="400px">

<h2>SHOP</h2>
<p>Per lo shop ho gestito tramite tutto il processo di buyng e storage delle skin comprate dal player, utilizzando un Game Manager per salvarmi tutte le informazione di acqiosto e di raccolata delle monete</p>
<img src="\BP_Screen\Shop.png" width="400px" height="550px">
<img src="\BP_Screen\Screenshot 2024-02-17 145308.png" width="700px" height="400px">

<h2>Game Play</h2>
<p>Puoi trovare il gameplay nella repository PurrChaser </p>

<h3>Per maggiori infformazioni casazzagabriele@gmail.com</h3>


