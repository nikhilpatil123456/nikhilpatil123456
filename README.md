- 👋 Hi, I’m @nikhilpatil123456
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
nikhilpatil123456/nikhilpatil123456 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
<!DOCTYPE html>
<html>
<head>
    <script src="http://code.jquery.com/jquery-latest.js"></script>
    <script src="http://maps.google.com/maps/api/js?key=YOUR_API_KEY&sensor=true"></script>
    <script src="js/gmaps.js"></script>
    <script>
        $(document).ready(function() {
            var map = new GMaps({
                div: '#basic_map',
                lat: 51.5073346,
                lng: -0.1276831,
                zoom: 12,
                zoomControl: true,
                zoomControlOpt: {
                    style: 'SMALL',
                    position: 'TOP_LEFT'
                },
                panControl: false,
            });
        });
    </script>
</head>
<body>
    <div id="basic_map"></div>
</body>
</html>
