<h1>Project Overview</h1>
<img src="\BP_Screen\menu.png" width="400px" height="550px">
<p>
PurrChaser è un gioco per mobile sviluppato in Unreal Enigne 5.
E' stato realizzato durante la classe X ( una settimana dove gli studenti di Bigrock si dividono in grupppi per realizzare un proggetto commisionato da un cliente esterno).
</p>

<p>
il mio compito è stato quello di proggetare e realizzare le meccaniche di gioco, quali: 
<ul>
  <li>Spawn procedurale delgi ostacli da evitare</li>
  <li>Spawn Delle file di monete da raccoglier</li>
  <li>Gestione dello shop per comprare le skin</li>
</ul>
</p>

<h2>Spawn Degli ostacoli</h2>
<img src="\BP_Screen\SpawnObstaclept1.png" width="700px" height="400px">
<img src="\BP_Screen\SpawnObstaclept2.png" width="700px" height="400px">
<p>
  Una volta creatami una matrice M(i,j), vado a spawnare gli ostacoli seguendo una logica probabilistica.
  <ul>
    <li><p>In primo luogo vado a calocalarmi la probabilità di spawn in mase alla fila in cui mi trovo (rispetto alla matrice),
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
<p> ecco qui sotto il gamplaye del gioco</p>
<img src="\BP_Screen\PurrChaserGamePlay.mp4" width="700px" height="400px">

