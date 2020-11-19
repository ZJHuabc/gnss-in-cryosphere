---
title: "Sites"
layout: sites
sitemap: false
permalink: /sites
---

# Usable sites for using GNSS-IR to study frozen ground

<div style="width:100%; height:400px; border:none; text-align:center">
	<iframe 
	src = src="https://maps.googleapis.com/maps/api/js?key=AIzaSyD10Fid-ovVypHgfvy9OqRDNz65arl-lP8&callback=initMap&libraries=&v=weekly"
	defer
	></iframe>
	<script>
      // Initialize and add the map
      function initMap() {
        // The location of Uluru
        const uluru = { lat: -25.344, lng: 131.036 };
        // The map, centered at Uluru
        const map = new google.maps.Map(document.getElementById("map"), {
          zoom: 4,
          center: uluru,
        });
        // The marker, positioned at Uluru
        const marker = new google.maps.Marker({
          position: uluru,
          map: map,
        });
      }
    </script>
</div>