
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>kompas.com</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            color: #333;
        }
        .container {
            width: 80%;
            margin: 0 auto;
            padding: 20px;
        }
        .header {
            background-color: #222;
            color: #fff;
            padding: 20px;
            text-align: center;
        }
        .header h1 {
            font-size: 2em;
        }
        .navbar {
            display: flex;
            justify-content: space-around;
            background-color: #333;
            padding: 10px 0;
        }
        .navbar a {
            color: white;
            text-decoration: none;
            padding: 10px;
            font-weight: bold;
        }
        .main-content {
            display: flex;
            gap: 20px;
            margin-top: 20px;
        }
        .main-content .left-section, .main-content .right-section {
            flex: 1;
        }
        .news-card {
            background-color: white;
            padding: 20px;
            margin-bottom: 20px;
            border-radius: 5px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
        }
        .news-card img {
            width: 100%;
            height: auto;
            border-radius: 5px;
        }
        .news-card h2 {
            font-size: 1.5em;
            margin: 10px 0;
        }
        .news-card p {
            font-size: 1em;
            color: #666;
        }
        .sidebar {
            background-color: #fff;
            padding: 20px;
            border-radius: 5px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
        }
        .sidebar h3 {
            margin-bottom: 15px;
        }
        .sidebar ul {
            list-style-type: none;
        }
        .sidebar ul li {
            margin-bottom: 10px;
        }
        .sidebar ul li a {
            text-decoration: none;
            color: #333;
        }
        .footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 20px;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <div class="container">
        <!-- Header Section -->
        <div class="header">
            <h1>kompas.com</h1>
        </div>

        <!-- Navigation Bar -->
        <div class="navbar">
            <a href="#">Home</a>
            <a href="#">World</a>
            <a href="#">Technology</a>
            <a href="#">Sports</a>
            <a href="#">Entertainment</a>
            <a href="#">Health</a>
        </div>

        <!-- Main Content -->
        <div class="main-content">
            <!-- Left Section (News Articles) -->
            <div class="left-section">
                <div class="news-card">
                    <img src="timnas indo.jpg" alt="timnas indonesia">
                    <h2>Susunan Pemain Timnas Indonesia VS jepang </h2>
                    <p>1-Maarten Paes; 2-Kevin Diks, 5-Rizky Ridho, 3-Jay Idzes, 23-Justin Hubner, 17-Calvin Verdonk;
					19-Thom Haye, 22-Nathan Tjoe-A-On; 14-Yakob Sayuri, 9-Rafael Struick, 11-Ragnar Oratmangoen.</p>
                </div>
                <div class="news-card">
                    <img src="pemerintah.jpg" alt="pemerintah">
                    <h2>Menteri Koordinator (Menko) Pemberdayaan Masyarakat Muhaimin Iskandar (Cak Imin) menyebut pemerintah
					akan memberi bantuan kepada para korban judi online.</h2>
                    <p>“Pasti (diberi bantuan), karena ini bagian dari korban sosial, dan tentu selain BPJS, kemudian kita
					juga ada berbagai bantuan-bantuan dari Kementerian Sosial,” kata Cak Imin di RS Cipto Mangunkusumo, Jakarta, Jumat (15/11/2024).</p>
                </div>
                <!-- More news cards can be added here -->
            </div>

            <!-- Right Section (Sidebar) -->
            <div class="right-section sidebar">
                <h3>Popular Topics</h3>
                <ul>
                    <li><a href="#">Politics</a></li>
                    <li><a href="#">Science</a></li>
                    <li><a href="#">Economy</a></li>
                    <li><a href="#">Education</a></li>
                </ul>
            </div>
        </div>

        <!-- Footer -->
        <div class="footer">
            <p>&copy; 2023 kompas.com All Rights Reserved.</p>
        </div>
    </div>
</body>
</html>

