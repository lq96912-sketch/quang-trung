
<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <title>KẾT QUẢ HỌC TẬP</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f5f5f5;
        }

        .title {
            text-align: center;
            font-size: 20px;
            font-weight: bold;
            margin: 20px 0;
        }

        table {
            border-collapse: collapse;
            margin: 0 auto;
            width: 800px;
            background-color: white;
        }

        th, td {
            border: 1px solid black;
            padding: 8px 12px;
            text-align: center;
        }

        th {
            background-color: yellow;
        }

        .footer {
            background-color: yellow;
            font-weight: bold;
        }

        a {
            color: blue;
            text-decoration: underline;
            display: block;
            width: 800px;
            margin: 10px auto;
            text-align: left;
        }
    </style>
</head>
<body>

    <div class="title">KẾT QUẢ HỌC TẬP</div>

    <table>
        <tr>
            <th rowspan="2">Họ và tên HS</th>
            <th colspan="2">Năm Sinh</th>
            <th rowspan="2">Điểm TB</th>
            <th rowspan="2">Xếp Loại</th>
        </tr>
        <tr>
            <th>Nam</th>
            <th>Nữ</th>
        </tr>
        <tr>
            <td>Lê Thanh Xuân</td>
            <td></td>
            <td>1988</td>
            <td>8.5</td>
            <td>Giỏi</td>
        </tr>
        <tr>
            <td>Phan Thế Hạ</td>
            <td></td>
            <td>1990</td>
            <td>6.5</td>
            <td>Khá</td>
        </tr>
        <tr>
            <td>Trần Hoài Thu</td>
            <td></td>
            <td>1991</td>
            <td>9.5</td>
            <td>Xuất Sắc</td>
        </tr>
        <tr>
            <td>Trương Lưu Đồng</td>
            <td>1989</td>
            <td></td>
            <td>6.0</td>
            <td>Trung Bình</td>
        </tr>
        <tr>
            <td>Nguyễn Trung Trực</td>
            <td>1988</td>
            <td></td>
            <td>4.5</td>
            <td>Kém</td>
        </tr>
        <tr class="footer">
            <td colspan="4">Tổng số học sinh đạt:</td>
            <td>4 Học sinh</td>
        </tr>
    </table>

    <a href="#">Quay về trang chủ</a>

</body>
</html>

