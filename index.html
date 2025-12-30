# dacruzmilena-sudo.github.io
transit guide map 
<!DOCTYPE html>
<html>
  <head>
    <title>Transit Restaurants Map</title>
    <style>
      #map { height: 100vh; width: 100vw; margin: 0; padding: 0; }
      body { margin: 0; }
    </style>
    <script src="https://maps.googleapis.com/maps/api/js?key=AIzaSyDFcNl93cbmd4rEBcfj4a9tlup1dpfa4wQ&libraries=places"></script>
    <script>
      const stations = [
        { name: "Brickell", lat: 25.7610, lng: -80.1950 },
        { name: "Vizcaya", lat: 25.7537, lng: -80.2074 },
        { name: "Government Center", lat: 25.7791, lng: -80.1979 }
      ];

      function initMap() {
        const map = new google.maps.Map(document.getElementById("map"), {
          center: { lat: 25.7743, lng: -80.1937 },
          zoom: 13
        });

        stations.forEach(station => {
          const position = { lat: station.lat, lng: station.lng };

          new google.maps.Circle({
            map,
            center: position,
            radius: 800,
            strokeColor: "#007BFF",
            strokeOpacity: 0.5,
            fillColor: "#007BFF",
            fillOpacity: 0.1
          });

          new google.maps.Marker({
            position,
            map,
            title: station.name,
            icon: {
              path: google.maps.SymbolPath.CIRCLE,
              scale: 6,
              fillColor: "#FF0000",
              fillOpacity: 1,
              strokeWeight: 0
            }
          });

          const service = new google.maps.places.PlacesService(map);
          service.nearbySearch({
            location: position,
            radius: 800,
            type: "restaurant"
          }, (results, status) => {
            if (status === google.maps.places.PlacesServiceStatus.OK) {
              results.forEach(place => {
                new google.maps.Marker({
                  position: place.geometry.location,
                  map,
                  title: place.name
                });
              });
            }
          });
        });
      }
    </script>
  </head>
  <body onload="initMap()">
    <div id="map"></div>
  </body>
</html>
