<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Binga Fish & Tourism</title>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
    <link rel="stylesheet" href="https://unpkg.com/leaflet/dist/leaflet.css" />
    <style>
        #map { height: 400px; }
    </style>
</head>
<body>
    <header class="bg-primary text-white text-center p-4">
        <h1>Binga Fish & Tourism</h1>
    </header>
    
    <main class="container">
        <h2>Welcome to Binga</h2>
        <p>Explore fish listings and tourism spots!</p>
        
        <div id="map"></div>

        <h3>Fish Listings</h3>
        <ul id="fish-listings">
            <!-- Fish listings will be dynamically inserted here -->
        </ul>
    </main>

    <footer class="text-center p-4">
        <p>&copy; 2025 Munkuli, All rights reserved.</p>
    </footer>

    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.2/dist/umd/popper.min.js"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
    <script src="https://unpkg.com/leaflet/dist/leaflet.js"></script>
    <script>
        // Initialize the map
        var map = L.map('map').setView([-17.6, 27.3], 8);
        L.tileLayer('https://{s}.tile.openstreetmap.org/{z}/{x}/{y}.png', {
            maxZoom: 19,
        }).addTo(map);

        // Example fish listings data
        const fishListings = [
            { type: "Bream", price: "$5", weight: "1kg" },
            { type: "Tigerfish", price: "$10", weight: "2kg" }
        ];

        // Populate fish listings
        fishListings.forEach(fish => {
            $('#fish-listings').append(`<li>${fish.type} - ${fish.price} (${fish.weight})</li>`);
        });
    </script>
</body>
</html>
