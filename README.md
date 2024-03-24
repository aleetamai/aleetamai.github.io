

<div id="image-table" align="center">
    <table>
        <tr>
        <div class="topnav">
        <a href="https://aleetamai.github.io">Home</a>
        <a href="https://aleetamai.github.io/talks&carrer">Talks & Career</a>
        <a href="https://www.sissa.it">SISSA</a>
        </div>
        </tr>
    </table>
</div>

# Alessandro Tamai

<br>

<img align="left" width="450" src="assets/Lie_groups.png" />

<img src="assets/sissalogo.png" width="180" />

-------

   ​_Ph.D. student at [SISSA](https://math.sissa.it/users/alessandro-tamai) in Geometry and Mathematical Physics, under the supervision of Antonio Lerario._

<br>

>_The cardinal notions of number, place, and combination...three intersecting but distinct spheres of thought to which all mathematical ideas admit of being referred._
><br>
>**James Joseph Sylvester**

<br>
<br>
<br>

## Research Interests:
My main research interest are on metric geometry, Morse theory and optimal transport for data analysis and machine learning.   
                                                                                                                               
Other interests cover differential topology, Riemannian and subRiemannian geometry, real algebraic geometry and Lie groups.
  

## Contacts:

email:  atamai@sissa.it
<br>
office: room 416, SISSA, Via Bonomea, 265, 34136, Trieste (TS)

<div class="split left">
  <div class="centered">
    <img src="img_avatar2.png" alt="Avatar woman">
    <h2>Jane Flex</h2>
    <p>Some text.</p>
  </div>
</div>

<div class="split right">
  <div class="centered">
    <img src="img_avatar.png" alt="Avatar man">
    <h2>John Doe</h2>
    <p>Some text here too.</p>
  </div>
</div>


<div class="row">
  <div class="column"></div>
  <div class="column"></div>
</div>


<body> 
<frameset cols="25%,75%"> 
   <frame src="left_frame.html" />
  ciao
   <frame src="right_frame.html" /> 
  blau
</frameset> 
</body> 

<div id="image-table" align="right">
    <table>
        <tr>
            <td style="padding:10px">
            mioa
            </td>
        </tr>
    </table>
</div>

<div id="container" style="width:100%;">                                   
  <div id="left" style="float:left; width:50%;">
    <h2>Research Interests:</h2>
    My main research interest are on metric geometry, Morse theory and optimal transport for data analysis and machine learning.                                                                                                      
    Other interests cover differential topology, Riemannian and subRiemannian geometry, real algebraic geometry and Lie groups.  
  </div>                     
  <div id="right" style="float:right; width:50%;">
      <h2>Contacts</h2>
      email:  atamai@sissa.it
      <br>
      office: room 416, SISSA, Via Bonomea, 265, 34136, Trieste (TS)
  </div>                   
</div> 

// Initialize and add the map
let map;
async function initMap(): Promise<void> {
  // The location of Uluru
  const position = { lat: -25.344, lng: 131.031 };

  // Request needed libraries.
  //@ts-ignore
  const { Map } = await google.maps.importLibrary("maps") as google.maps.MapsLibrary;
  const { AdvancedMarkerElement } = await google.maps.importLibrary("marker") as google.maps.MarkerLibrary;

  // The map, centered at Uluru
  map = new Map(
    document.getElementById('map') as HTMLElement,
    {
      zoom: 4,
      center: position,
      mapId: 'DEMO_MAP_ID',
    }
  );

  // The marker, positioned at Uluru
  const marker = new AdvancedMarkerElement({
    map: map,
    position: position,
    title: 'Uluru'
  });
}
initMap();






