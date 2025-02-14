<!DOCTYPE html>
<html lang="vi">
<head>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tam Quốc Diễn Nghĩa</title>
    <link href="https://fonts.googleapis.com/css2?family=Hanalei&display=swap" rel="stylesheet">

    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-image: url('https://i.pinimg.com/736x/59/74/ac/5974ac54f77d6b98a55e6a0604e59360.jpg');
            background-size: cover; 
            background-position: center; 
            background-attachment: fixed; 
        }

        h1 {
            font-family: 'Noto Serif SC', serif; 
            font-size: 100px; 
            font-weight: bold; 
            color: red; 
            text-align: center; 
            text-shadow: 0 0 10px rgba(255, 255, 255, 0.7), 0 0 20px rgba(255, 0, 0, 0.7), 0 0 30px rgba(255, 0, 0, 0.5); 
            margin-top: 100px; 
            animation: glow 2s infinite, fadeIn 3s ease-in-out;
        }

        @keyframes glow {
            0%, 100% {
                text-shadow: 0 0 5px rgba(255, 255, 255, 0.5), 0 0 10px rgba(255, 0, 0, 0.5), 0 0 15px rgba(255, 0, 0, 0.4);
            }
            50% {
                text-shadow: 0 0 20px rgba(255, 255, 255, 0.8), 0 0 30px rgba(255, 0, 0, 0.8), 0 0 40px rgba(255, 0, 0, 0.7);
            }
        }

        @keyframes fadeIn {
            from {
                opacity: 0;
            }
            to {
                opacity: 1;
            }
        }

          .menu {
            text-align: center;
            background-color: red;
            padding: 10px 0;
            position: fixed;
            width: 100%;
            top: 0;
            left: 0;
            z-index: 1000;
            cursor: url('https://banner2.cleanpng.com/20180426/ogq/kisspng-sword-mod-db-weapon-sword-harrow-5ae197bb115524.253621851524733883071.jpg'), auto;
        }

        .dropdown {
            display: inline-block;
            position: relative;
            margin: 0 10px;
        }

        .dropdown button {
            font-size: 30px;
            background-color: rgba(255, 0, 0, 0.7);
            color: white;
            border: none;
            padding: 10px 20px;
            cursor: pointer;
        }

        .dropdown-content {
            display: none;
            position: absolute;
            background-color: rgba(255, 255, 255, 0.8);
            min-width: 250px;
            box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.1);
            z-index: 1;
        }

        .dropdown-content a {
            display: block;
            padding: 10px;
            color: black;
            font-size: 24px;
        }

        .dropdown-content a:hover {
            background-color: #ddd;
        }

        .dropdown:hover .dropdown-content {
            display: block;
        }

        .content {
            padding-top: 70px;
            text-align: center;
        }

        a {
            text-decoration: none;
        }
    </style>
</head>
<body>
    
    <div class="menu">
        <div class="dropdown">
            <button><a href="ngocminh.html"><font size="6" color="black">Trang chủ</font></a></button>
        </div>
        <div class="dropdown">
            <button><a href="gt.html"><font size="6" color="black">Giới thiệu</font></a></button>
        </div>
        <div class="dropdown">
            <button><a href="Cottruyen.html"><font size="6" color="black">Cốt truyện</font></a></button>
        </div>

        <div class="dropdown">
            <button><font size="6" color="black">Chủ đề ▼</font></button>
            <div class="dropdown-content">
                <a href="vi.html">Các vị tướng tiêu biểu</a>
                <a href="minh1.html">Các trận chiến kinh điển nhất</a>
                <a href="caunoi.html">
                    Những câu nói kinh điển nhất
                </a>
            </div>
        </div>
    </div>

    <div class="content">
        <h1>Tam Quốc Diễn Nghĩa</h1>
        <center>
            <img src="—Pngtree—sword and wood shield mascot_5901934.png" alt="Ảnh" width="20%">
        </center>
    </div>
</body>
</html>
