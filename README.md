# csn-dx24tt3-nguyenvannghi-drivingschool
<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <title>Trung Tâm Đào Tạo Lái Xe ABC</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }

        body {
            line-height: 1.6;
        }

        header {
            background: #003366;
            color: white;
            padding: 20px;
            text-align: center;
        }

        nav {
            background: #0055aa;
            padding: 10px;
            text-align: center;
        }

        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
            font-weight: bold;
        }

        nav a:hover {
            color: yellow;
        }

        .banner {
            background: url('https://images.unsplash.com/photo-1503376780353-7e6692767b70') no-repeat center/cover;
            height: 300px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            font-size: 28px;
            font-weight: bold;
        }

        .container {
            padding: 30px;
        }

        .section {
            margin-bottom: 40px;
        }

        .courses {
            display: flex;
            gap: 20px;
            flex-wrap: wrap;
        }

        .course {
            flex: 1;
            min-width: 250px;
            background: #f4f4f4;
            padding: 20px;
            border-radius: 10px;
            transition: 0.3s;
        }

        .course:hover {
            transform: scale(1.05);
        }

        .btn {
            display: inline-block;
            padding: 10px 20px;
            background: red;
            color: white;
            text-decoration: none;
            border-radius: 5px;
            margin-top: 10px;
        }

        footer {
            background: #003366;
            color: white;
            text-align: center;
            padding: 15px;
        }

        .contact input, .contact textarea {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
        }

        .contact button {
            padding: 10px 20px;
            background: green;
            color: white;
            border: none;
            cursor: pointer;
        }
    </style>
</head>
<body>

<header>
    <h1>TRUNG TÂM ĐÀO TẠO LÁI XE ABC</h1>
    <p>Uy tín - Chất lượng - Nhanh chóng</p>
</header>

<nav>
    <a href="#">Trang chủ</a>
    <a href="#gioithieu">Giới thiệu</a>
    <a href="#khoahoc">Khóa học</a>
    <a href="#lienhe">Liên hệ</a>
</nav>

<div class="banner">
    Học lái xe dễ dàng - Nhận bằng nhanh chóng
</div>

<div class="container">

    <div class="section" id="gioithieu">
        <h2>Giới thiệu</h2>
        <p>Trung tâm đào tạo lái xe ABC với nhiều năm kinh nghiệm, đội ngũ giảng viên chuyên nghiệp, cam kết mang lại chất lượng đào tạo tốt nhất.</p>
    </div>

    <div class="section" id="khoahoc">
        <h2>Các khóa học</h2>
        <div class="courses">
            <div class="course">
                <h3>Bằng B1</h3>
                <p>Học lái xe số tự động, phù hợp cho người mới.</p>
                <a href="#" class="btn">Đăng ký</a>
            </div>

            <div class="course">
                <h3>Bằng B2</h3>
                <p>Học lái xe số sàn, phổ biến nhất hiện nay.</p>
                <a href="#" class="btn">Đăng ký</a>
            </div>

            <div class="course">
                <h3>Bằng C</h3>
                <p>Dành cho lái xe tải chuyên nghiệp.</p>
                <a href="#" class="btn">Đăng ký</a>
            </div>
        </div>
    </div>

    <div class="section contact" id="lienhe">
        <h2>Liên hệ</h2>
        <input type="text" placeholder="Họ và tên">
        <input type="email" placeholder="Email">
        <textarea placeholder="Nội dung"></textarea>
        <button onclick="guiThongTin()">Gửi</button>
    </div>

</div>

<footer>
    <p>© 2026 Trung Tâm Đào Tạo Lái Xe ABC</p>
</footer>

<script>
function guiThongTin() {
    alert("Cảm ơn bạn đã liên hệ! Chúng tôi sẽ phản hồi sớm.");
}
</script>

</body>
</html>
