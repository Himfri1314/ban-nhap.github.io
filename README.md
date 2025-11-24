<html lang="vi">
  <head>
    <meta charset = "UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Wed báo cáo tin </title>
    <style>
        * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Arial, sans-serif;
}

body {
    background: #f0f0f0;
}

/* Căn hàng ngang */
.box-container {
    display: flex;
    justify-content: center;
    gap: 30px;
    margin-top: 50px;
}

/* Khung trắng bo góc */
.box {
    width: 250px;
    padding: 20px;
    background: white;
    border-radius: 20px;
    text-align: center;
    box-shadow: 0 0 10px rgba(0,0,0,0.1);
}

/* Ảnh tròn */
.avatar {
    width: 120px;
    height: 120px;
    border-radius: 50%;
    object-fit: cover;
    margin-bottom: 10px;
    border: 4px solid #87bfff;
}

/* Tên dưới avatar */
.box p {
    font-size: 18px;
    font-weight: 600;
    color: #1a365f;
}
</style>
</body>
<body>
    <div class="background"></div>
    <h2 class="title">Nhóm 1 (12 Văn)</h2>
    <div class="container">
        <div class="card">
            <img src="Phương Duyên.png" class="avatar">
            <a href="trangchu" style="text-decorating: none; color: dark blue; padding: 0 10px;">Nguyễn Ngọc Phương Duyên</a>
        </div>
        <div class="card">
            <img src="Minh Châu.png" class="avatar">
            <a href="trangchu" style="text-decorating: none; color: dark blue; padding: 0 10px;">Phùng Võ Minh Châu</a>
        </div>
        <div class="card">
            <img src="Khả Hân.png" class="avatar">
            <a href="trangchu" style="text-decorating: none; color: dark blue; padding: 0 10px;">Nguyễn Khả Hân</a>
        </div>
        <div class="card">
            <img src="Quỳnh Như.png" class="avatar">
            <a href="trangchu" style="text-decorating: none; color: dark blue; padding: 0 10px;">Trần Lê Quỳnh Như</a>
        </div>
</body>
</head>
</html>
