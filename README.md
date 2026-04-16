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
<html>
<head>
<title>Khóa học</title>
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
</head>

<body>

<div class="container mt-5">
<h2>Danh sách khóa học</h2>

<table class="table table-bordered">

<tr>
<th>Khóa học</th>
<th>Thời gian</th>
<th>Học phí</th>
</tr>

<tr>
<td>B1</td>
<td>3 tháng</td>
<td>8.000.000</td>
</tr>

<tr>
<td>B2</td>
<td>3 tháng</td>
<td>9.000.000</td>
</tr>

<tr>
<td>C</td>
<td>5 tháng</td>
<td>12.000.000</td>
</tr>

</table>

</div>

</body>
</html>
<html>
<head>
<title>Lịch khai giảng</title>
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
</head>

<body>

<div class="container mt-5">
<h2>Lịch khai giảng</h2>

<table class="table table-striped">
<tr>
<th>Khóa</th>
<th>Ngày khai giảng</th>
<th>Ghi chú</th>
</tr>

<tr>
<td>B2</td>
<td>10/05/2026</td>
<td>Còn chỗ</td>
</tr>

<tr>
<td>C</td>
<td>20/05/2026</td>
<td>Còn chỗ</td>
</tr>

</table>

</div>

</body>
</html>
<html>
<head>
<title>Kết quả thi</title>
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
</head>

<body>

<div class="container mt-5">
<h2>Kết quả thi</h2>

<table class="table table-bordered">
<tr>
<th>Họ tên</th>
<th>Khóa</th>
<th>Kết quả</th>
</tr>

<tr>
<td>Nguyễn Văn A</td>
<td>B2</td>
<td>Đậu</td>
</tr>

</table>

</div>

</body>
</html>
