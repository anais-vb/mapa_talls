## Mapa de barrios afectados por los cortes de luz

<!-- Google map code from EZ Map - https://ezmap.co -->
<script src='https://maps.googleapis.com/maps/api/js?key=AIzaSyDyZn6KD7PRvTMyrZnzvGq-AEMDMZHB7eM'></script>
<script>
  function init() {
    var mapOptions = { "center": {  "lat": 40.48523835118751,  "lng": -3.7962554556462846 }, "clickableIcons": true, "disableDoubleClickZoom": false, "draggable": true, "fullscreenControl": true, "keyboardShortcuts": true, "mapTypeControl": false, "mapTypeControlOptions": {  "text": "Default (depends on viewport size etc.)",  "style": 0 }, "mapTypeId": "roadmap", "rotateControl": true, "scaleControl": true, "scrollwheel": true, "streetViewControl": false, "styles": [  {   "featureType": "landscape.natural",   "elementType": "geometry.fill",   "stylers": [    {     "visibility": "on"    },    {     "color": "#e0efef"    }   ]  },  {   "featureType": "poi",   "elementType": "geometry.fill",   "stylers": [    {     "visibility": "on"    },    {     "hue": "#1900ff"    },    {     "color": "#c0e8e8"    }   ]  },  {   "featureType": "road",   "elementType": "geometry",   "stylers": [    {     "lightness": 100    },    {     "visibility": "simplified"    }   ]  },  {   "featureType": "road",   "elementType": "labels",   "stylers": [    {     "visibility": "off"    }   ]  },  {   "featureType": "transit.line",   "elementType": "geometry",   "stylers": [    {     "visibility": "on"    },    {     "lightness": 700    }   ]  },  {   "featureType": "water",   "elementType": "all",   "stylers": [    {     "color": "#7dcdcd"    }   ]  } ], "zoom": 6, "zoomControl": true};
    var mapElement = document.getElementById('ez-map');
    var map = new google.maps.Map(mapElement, mapOptions);
    var marker0 = new google.maps.Marker({title: "Font de la Pólvora (Girona)", icon: "https://ezmap.co/icons/svgs/location-1-black.svg", position: new google.maps.LatLng(41.976392, 2.845221), map: map});
var infowindow0 = new google.maps.InfoWindow({content: "<h3 class=\"infoTitle\">Font de la Pólvora </h3><p><span class=\"infoWebsite\"><a href=\"https://www.elpuntavui.cat/societat/article/5-societat/1905380-la-font-de-la-polvora-en-guerra-pels-talls-de-llum-avisa-que-la-sectoritzacio-no-funciona.html\">https://www.elpuntavui.cat/societat/article/5-societat/1905380-la-font-de-la-polvora-en-guerra-pels-talls-de-llum-avisa-que-la-sectoritzacio-no-funciona.html</a><br></span></p>",map: map});
marker0.addListener('click', function () { infowindow0.open(map, marker0) ;});infowindow0.close();
var marker1 = new google.maps.Marker({title: "Sant Roc (Badalona)", icon: "https://ezmap.co/icons/svgs/location-1-black.svg", position: new google.maps.LatLng(41.4350685, 2.225798), map: map});
var infowindow1 = new google.maps.InfoWindow({content: "<h3 class=\"infoTitle\">Sant Roc (Badalona)</h3><p><span class=\"infoWebsite\"><a href=\"https://www.ara.cat/societat/barri-sant-roc-badalona-talls-indiscriminats-fred-dificultats-malalts-criatures_1_2544706.html\">https://www.ara.cat/societat/barri-sant-roc-badalona-talls-indiscriminats-fred-dificultats-malalts-criatures_1_2544706.html</a><br></span></p>",map: map});
marker1.addListener('click', function () { infowindow1.open(map, marker1) ;});infowindow1.close();

    google.maps.event.addDomListener(window, "resize", function() { var center = map.getCenter(); google.maps.event.trigger(map, "resize"); map.setCenter(center); });
  }
google.maps.event.addDomListener(window, 'load', init);
</script>
<style>
  #ez-map { min-height:150px; min-width:150px; height: 420px; width: 100%; }
  #ez-map .infoTitle { /*marker window title styles*/ }
  #ez-map .infoWebsite { /*marker window website styles*/ }
  #ez-map .infoEmail { /*marker window email address styles*/ }
  #ez-map .infoTelephone { /*marker window telephone styles*/ }
  #ez-map .infoDescription { /*marker window description styles*/ }
</style>
<div id='ez-map'></div>
<!-- End of EZ Map code - https://ezmap.co -->
