<h1>Project Overview</h1>
<img src="\BP_Screen\menu.png" width="400px" height="550px">
<p>
PurrChaser is a mobile game developed in Unreal Engine 5.
This project was created during the "Classe X" week, a week in which all students at BigRock are divided into groups and have to do a project commissioned by an external client.
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
  Once I created an M-matrix(i,j), the objects spawned with a probabilistic logic.
  <ul>
    <li><p>Firstly, I calculate the spawn probability based on the row where I am (compared to the matrix); the central rows have a higher spawn probability than the outer ones.
    </p></li>
    <li> I then calculate which object to spawn.</li>
  </ul>
</p>
<img src="\BP_Screen\SpawnProbability.png" width="700px" height="400px">
<img src="\BP_Screen\ProbabilityObstacleSpawn.png" width="700px" height="400px">


<h2>Coins spawn</h2>
<p>
  I calculated where and for how many rows to spawn the coins.
  I used a Vector3 array to save the positions of the spawned obstacles to avoid spawning the coins beneath them.

</p>
<img src="\BP_Screen\SpwanCoinPt1.png" width="700px" height="400px">
<img src="\BP_Screen\SpawnCoinPt2.png" width="700px" height="400px">

<h2>Shop</h2>
<p>The shop was managed through the buying and storage process of the skins bought by the player, using a Game Manager to save the buying information and the coins collected. </p>
<img src="\BP_Screen\Shop.png" width="400px" height="550px">
<img src="\BP_Screen\Screenshot 2024-02-17 145308.png" width="700px" height="400px">

<h2>Game Play</h2>
<p>The gameplay can be found in the PurrChaser repository </p>

<h3>For more information: casazzagabriele@gmail.com</h3>


