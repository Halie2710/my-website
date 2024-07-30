# my-website
<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Trang web cá nhân</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Merriweather:wght@300;400;700&family=Poppins:wght@300;400;700&display=swap');

        body {
            font-family: 'Poppins', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f5f5f5;
        }
        header {
            background-color: #1e90ff;
            color: white;
            padding: 40px 0;
            text-align: center;
            font-family: 'Merriweather', serif;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #32cd32;
            padding: 10px 0;
        }
        nav a {
            color: white;
            padding: 15px 20px;
            text-decoration: none;
            font-family: 'Poppins', sans-serif;
            font-weight: bold;
            margin: 0 10px;
            transition: background-color 0.3s;
        }
        nav a:hover {
            background-color: #ffdd57;
            border-radius: 5px;
        }
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }
        .welcome {
            font-size: 56px;
            text-align: center;
            margin: 60px 0;
            color: #ffdd57; /* Màu hơi ngả vàng */
            font-family: 'Merriweather', serif;
        }
        h2 {
            font-family: 'Merriweather', serif;
            font-size: 32px;
            color: #1e90ff;
            border-bottom: 2px solid #1e90ff;
            padding-bottom: 10px;
            margin-bottom: 20px;
        }
        p {
            font-size: 18px;
            line-height: 1.6;
            color: #333;
        }
        .portfolio-item {
            margin: 20px 0;
            border: 1px solid #ddd;
            padding: 20px;
            border-radius: 10px;
            background-color: #fff;
        }
        .portfolio-item img {
            max-width: 100%;
            height: auto;
            border-radius: 10px;
            margin-top: 10px;
        }
        .contact-form {
            display: flex;
            flex-direction: column;
        }
        .contact-form label {
            font-size: 16px;
            margin: 10px 0 5px;
        }
        .contact-form input, .contact-form textarea {
            padding: 10px;
            font-size: 16px;
            margin-bottom: 20px;
            border: 1px solid #ddd;
            border-radius: 5px;
        }
        .contact-form button {
            padding: 10px 20px;
            font-size: 16px;
            background-color: #1e90ff;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            transition: background-color 0.3s;
        }
        .contact-form button:hover {
            background-color: #32cd32;
        }
        footer {
            background-color: #1e90ff;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>Trang web cá nhân của [Tên bạn]</h1>
    </header>
    <nav>
        <a href="#home">Trang chủ</a>
        <a href="#blog">Blog</a>
        <a href="#portfolio">Portfolio</a>
        <a href="#contact">Liên hệ</a>
        <a href="#about">Giới thiệu</a>
    </nav>
    <div class="container" id="home">
        <div class="welcome">Welcome!</div>
        <p>Chào mừng bạn đến với trang web cá nhân của tôi. Đây là nơi tôi chia sẻ các dự án, bài viết và thông tin liên hệ.</p>
    </div>
    <div class="container" id="blog">
        <h2>Blog</h2>
        <p>Nội dung blog sẽ được cập nhật ở đây. Theo dõi để biết thêm thông tin và cập nhật mới nhất từ tôi.</p>
    </div>
    <div class="container" id="portfolio">
        <h2>Portfolio</h2>
        <div class="portfolio-item">
            <h3>Dự án 1</h3>
            <p>Mô tả dự án 1.</p>
            <img src="duongdan/toi/hinhanh1.jpg" alt="Hình ảnh dự án 1">
        </div>
        <div class="portfolio-item">
            <h3>Dự án 2</h3>
            <p>Mô tả dự án 2.</p>
            <img src="duongdan/toi/hinhanh2.jpg" alt="Hình ảnh dự án 2">
        </div>
        <!-- Thêm nhiều dự án khác tại đây -->
    </div>
    <div class="container" id="contact">
        <h2>Liên hệ</h2>
        <form class="contact-form">
            <label for="name">Tên:</label>
            <input type="text" id="name" name="name">
            <label for="email">Email:</label>
            <input type="email" id="email" name="email">
            <label for="message">Tin nhắn:</label>
            <textarea id="message" name="message" rows="4"></textarea>
            <button type="submit">Gửi</button>
        </form>
    </div>
    <div class="container" id="about">
        <h2>Giới thiệu</h2>
        <p>Đoạn giới thiệu về bạn sẽ được đặt ở đây. Chia sẻ một chút về bản thân, kinh nghiệm và mục tiêu của bạn.</p>
    </div>
    <footer>
        <p>&copy; 2024 [Halie]. All rights reserved.</p>
    </footer>
</body>
</html>
