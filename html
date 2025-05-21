// Get the map element
const mapElement = document.getElementById('map');

// Create a Leaflet map
const map = L.map(mapElement).setView([51.505, -0.09], 13);

// Add a tile layer to the map
L.tileLayer('https://{s}.tile.openstreetmap.org/{z}/{x}/{y}.png', {
    attribution: '&copy; <a href="https://www.openstreetmap.org/">OpenStreetMap</a>',
    subdomains: ['a', 'b', 'c']
}).addTo(map);

// Get the user's location button
const getLocationButton = document.getElementById('get-location');

// Add an event listener to the button
getLocationButton.addEventListener('click', () => {
    // Use the Geolocation API to get the user's location
    navigator.geolocation.getCurrentPosition((position) => {
        // Get the user's latitude and longitude
        const latitude = position.coords.latitude;
        const longitude = position.coords.longitude;

        // Create a Leaflet marker at the user's location
        const marker = L.marker([latitude, longitude]).addTo(map);

        // Set the map view to the user's location
        map.setView([latitude, longitude], 13);

        // Add a popup to the marker with the user's location
        marker.bindPopup(`Your location: ${latitude}, ${longitude}`).openPopup();
    }, (error) => {
        console.error('Error getting location:', error);
    });
});
