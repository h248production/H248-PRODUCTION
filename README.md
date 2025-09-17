<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Frame - Cho thuê thiết bị quay phim</title>
    <style>
        @import url('https://fonts.googleapis.com/css?family=Roboto:400,700&display=swap');
        body {
            font-family: 'Roboto', Arial, sans-serif;
            background: #e9ebee;
            margin: 0;
            color: #222;
        }
        .header {
            background: #23272b;
            color: #fff;
            padding: 36px 0 18px 0;
            text-align: center;
            box-shadow: 0 2px 8px rgba(0,0,0,0.08);
        }
        .header h1 {
            margin: 0;
            font-size: 2.7em;
            letter-spacing: 2px;
            font-weight: 700;
        }
        .header p {
            margin: 10px 0 0 0;
            font-size: 1.15em;
            color: #bfc7d5;
        }
        .container {
            max-width: 950px;
            margin: 36px auto;
            background: #fff;
            border-radius: 12px;
            box-shadow: 0 4px 24px rgba(0,0,0,0.10);
            padding: 36px 28px 32px 28px;
        }
        .container > h2 {
            color: #23272b;
            font-size: 1.4em;
            margin-bottom: 24px;
            letter-spacing: 1px;
        }
        .device-list {
            display: flex;
            flex-wrap: wrap;
            gap: 24px;
        }
        .device {
            flex: 1 1 260px;
            background: #f7f8fa;
            border-radius: 10px;
            padding: 22px 18px 18px 18px;
            margin-bottom: 16px;
            box-shadow: 0 2px 8px rgba(0,0,0,0.06);
            transition: box-shadow 0.2s, transform 0.2s;
            border: 1px solid #e3e6ea;
        }
        .device:hover {
            box-shadow: 0 8px 24px rgba(45,108,223,0.10);
            transform: translateY(-2px) scale(1.02);
            border-color: #b3c6f7;
        }
        .device h2 {
            font-size: 1.13em;
            margin: 0 0 8px 0;
            color: #2d6cdf;
            font-weight: 700;
            letter-spacing: 0.5px;
        }
        .device .price {
            font-weight: bold;
            color: #e67e22;
            margin-bottom: 6px;
            font-size: 1.08em;
        }
        .device .accessory {
            font-size: 0.97em;
            color: #555;
            margin-bottom: 4px;
        }
        .footer {
            background: #23272b;
            color: #fff;
            text-align: center;
            padding: 28px 0 10px 0;
            margin-top: 44px;
            font-size: 1.05em;
        }
        .contact, .social {
            margin: 14px 0;
        }
        .contact a, .social a {
            color: #fff;
            text-decoration: underline;
            margin: 0 8px;
            transition: color 0.2s;
        }
        .contact a:hover, .social a:hover {
            color: #2d6cdf;
        }
        @media (max-width: 700px) {
            .container { padding: 10px; }
            .device-list { flex-direction: column; }
        }
    </style>
</head>
<body>
    <div class="header">
        <h1>Frame</h1>
        <p>Perfect in every single frame</p>
        <p>Cung cấp thiết bị sản xuất video chuyên nghiệp: máy ảnh, máy quay, ống kính, gimbal, chân máy, đèn, mic thu âm,...</p>
    </div>
    <div class="container">
        <h2>Danh sách thiết bị cho thuê</h2>
        <div class="device-list">
            <div class="device" data-img="sony-a7m4.jpg">
                <div class="device-img"></div>
                <h2>Sony Alpha A7 Mark IV</h2>
                <div class="price">500.000 VNĐ/ngày</div>
                <div class="accessory">Phụ kiện: 2 x pin FZ100, 1 x Thẻ nhớ 64G</div>
            </div>
            <div class="device" data-img="sony-a7m3.jpg">
                <div class="device-img"></div>
                <h2>Sony Alpha A7 Mark III</h2>
                <div class="price">350.000 VNĐ/ngày</div>
                <div class="accessory">Phụ kiện: 2 x pin FZ100, 1 x Thẻ nhớ 64G</div>
            </div>
            <div class="device" data-img="sony-fx30.jpg">
                <div class="device-img"></div>
                <h2>Máy quay Cinema Sony FX30 (liên hệ)</h2>
                <div class="price">600.000 VNĐ/ngày</div>
                <div class="accessory">Phụ kiện: 2 x pin FZ100, 1 x Thẻ nhớ 64G</div>
            </div>
            <div class="device" data-img="sony-24-70gm.jpg">
                <div class="device-img"></div>
                <h2>Lens Sony FE 24-70mm GM F2.8</h2>
                <div class="price">300.000 VNĐ/ngày</div>
                <div class="accessory">Phụ kiện: Filter chống bụi</div>
            </div>
            <div class="device" data-img="dji-mini3.jpg">
                <div class="device-img"></div>
                <h2>Flycam DJI Mini 3 Pro Combo</h2>
                <div class="price">500.000 VNĐ/ngày</div>
                <div class="accessory">Phụ kiện: 3 x pin, 1 x Thẻ nhớ 64G</div>
            </div>
            <div class="device" data-img="ronin-s4.jpg">
                <div class="device-img"></div>
                <h2>Gimbal DJI Ronin S4</h2>
                <div class="price">350.000 VNĐ/ngày</div>
                <div class="accessory">Phụ kiện: Cable type C</div>
            </div>
            <div class="device" data-img="nanlite-60b.jpg">
                <div class="device-img"></div>
                <h2>Đèn Led NANlite Forza 60B Bi Color</h2>
                <div class="price">250.000 VNĐ/ngày</div>
                <div class="accessory">Phụ kiện: 1 x Chân đèn</div>
            </div>
            <div class="device" data-img="rode-go2.jpg">
                <div class="device-img"></div>
                <h2>Microphone Rode Wireless Go II</h2>
                <div class="price">300.000 VNĐ/ngày</div>
                <div class="accessory">Phụ kiện: 2 x TX, 1 x RX, Cable SC2</div>
            </div>
            <div class="device" data-img="ninja-v.jpg">
                <div class="device-img"></div>
                <h2>Monitor Ninja V (ngừng cung cấp)</h2>
                <div class="price">350.000 VNĐ/ngày</div>
                <div class="accessory">Phụ kiện: Nguồn, 2 x Pin F970</div>
            </div>
            <!-- Thêm các thiết bị khác tương tự ở đây -->
        </div>
    </div>
    <div class="footer">
        <div class="contact">
            <strong>LIÊN HỆ:</strong><br>
            <span>Nhà 110 khu tập thể Văn Nghệ Sỹ (tập thể Bộ Văn Hóa), P.Kim Mã, Q.Ba Đình, TP.Hà Nội</span><br>
            <a href="tel:0325417624">0325.417.624</a> | <a href="tel:0967404932">0967.404.932</a>
        </div>
        <div class="social">
            <strong>MẠNG XÃ HỘI:</strong><br>
            <a href="https://www.facebook.com/frameprodvn/" target="_blank">Facebook</a> |
            <a href="https://www.instagram.com/frameprodvn/" target="_blank">Instagram</a> |
            <a href="mailto:frameprodvn@gmail.com">Email</a>
        </div>
        <div style="margin-top: 12px; font-size: 0.95em;">© 2021 · Bản quyền thuộc về <a href="https://www.facebook.com/frameprodvn/" style="color:#fff;">Frame</a></div>
    </div>
</body>
<script>
// Hàm tự động chèn ảnh vào từng thiết bị dựa vào thuộc tính data-img
document.querySelectorAll('.device').forEach(function(device) {
    var imgName = device.getAttribute('data-img');
    var imgDiv = device.querySelector('.device-img');
    if (imgName && imgDiv) {
        imgDiv.innerHTML = '<img src="images/' + imgName + '" alt="Ảnh thiết bị" style="width:100%;max-width:160px;display:block;margin:0 auto 12px auto;border-radius:8px;box-shadow:0 2px 8px rgba(0,0,0,0.10);background:#fff;object-fit:cover;">';
    }
});
</script>
        .device-img {
            min-height: 110px;
            margin-bottom: 8px;
            display: flex;
            align-items: center;
            justify-content: center;
        }
</html>
