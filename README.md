<!DOCTYPE html>
<html lang="ja">

<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>biyousi</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            background-color: #f0f0f0;
            font-family: sans-serif;
        }

        .container {
            max-width: 1200px;
            width: 90%;
            margin: 0 auto;
            align-items: center;
        }

        .d,
        .f {
            border-radius: 5px;
            padding: 5px 10px;
            transition: all 0.4s ease;
            cursor: pointer;
        }

        .d:hover,
        .f:hover {
            color: #333;
            text-shadow: 0 0 10px rgba(255, 255, 255, 0.8);
            transform: scale(1.05) rotateX(5deg);
        }

        .f:hover {
            transform: scale(2) rotateX(5deg);
        }

        .senn {
            display: inline-block;
            width: 1px;
            height: 25px;
            background-color: black;
            margin: 0 10px;
            vertical-align: middle;
        }

        .bo {
            text-align: center;
            border: none;
            border-top: 2px solid #797575a9;
            width: 700px;
            max-width: 100%;
            margin: 20px auto;
        }

        .center-img {
            text-align: center;
        }

        img {
            max-width: 100%;
            height: auto;
        }

        .staff-section {
            display: flex;
            align-items: flex-start;
            gap: 20px;
        }

        .staff-section p {
            writing-mode: vertical-rl;
            margin: 10px;
            font-size: small;
            letter-spacing: -1px;
            transform: rotate(360deg);
        }

        @media(max-width:768px) {
            img {
                width: 700px;
            }

            @media (max-width: 768px) {
                img {
                    width: 100%;
                    /* スマホでは画面幅に合わせる */
                }
            }
        }
    </style>
</head>

<body>
    <div class="container">
        <!-- ヘッダー -->
        <div style="position: sticky">
            <img src="img/s＆ｗ.png" style=" max-width: 900px; height: auto;">
            <div class="f" style="position: absolute; top: 0px; left: 800px;">
                <img src="img/f81e2b41-8938-477d-94be-49c1ec9b28a9.png" width="50" alt="アイコン">
            </div>
        </div>

        <!-- BLOG セクション -->
        <h3>02<span class="senn"></span>BLOG</h3>

        <div style="display: flex; align-items: flex-start; gap: 20px;">
            <img src="img/美容院.jpg" style="width: 200px;">
            <p
                style="writing-mode: vertical-rl;margin: 10px; font-size: small; letter-spacing: -1px; transform: rotate(360deg);">
                2025.08.02</p>
        </div>

        <br><br><br>
        <h3>01 <span class="senn"></span>ABOUT</h3>
        <div style="display: flex; align-items: flex-start; gap: 20px;">
            <img src="img/美容院.jpg" style="width: 400px; height: auto;">
            <p style="writing-mode: vertical-rl;margin: 10px; font-size: small; letter-spacing: -1px; transform:">
                おしゃれな店内で<br>快適にお過ごしください！！</p>
        </div><br><br><br>
        <!-- 画像セクション -->
        <div class="center-img">
            <img src="img/美容師　外観　外.jpg" style="width: 700px;">
        </div>

        <!-- 住所・電話・営業時間 -->
        <p>　　　　　住所　　　　　〒848-4535<br>　　　　　　　　　　　　京都府京都市1F</p>
        <hr class="bo">
        <p>　　　　　TEL　　　　　090-7547-5554</p>
        <hr class="bo">
        <p>　　　　　営業時間　　　9:00～19:00</p>
        <hr class="bo">
        <p>　　　　　定休日　　　　火曜日</p>

        <!-- Google Map -->
        <div style="text-align: center; margin-top: 20px;">
            <iframe
                src="https://www.google.com/maps/embed?pb=!1m14!1m12!1m3!1d98297.39557069725!2d136.25333844009566!3d35.34443936673647!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!5e0!3m2!1sja!2sjp!4v1759578254710!5m2!1sja!2sjp"
                width="100%" height="450" style="border:0; max-width: 700px;" allowfullscreen="" loading="lazy"
                referrerpolicy="no-referrer-when-downgrade">
            </iframe>
        </div>

        <!-- ADDRESS -->
        <h3>03 <span class="senn"></span>MENU</h3>
        <div style="text-align: center;">
            <img src="img/名称未設定のデザイン.png" style="width: 900px; height: 300px;">
        </div>
        <p>　　　　　　　カット　　　　　　　¥4.100～　　　　　　　カラー　　　　　　¥5.100～</p>
        <hr class="bo">

        <p>　　　　　　　デザインカラー　　　¥10.100～　　　　　　 パーマ　　　　　　¥6.100～</p>
        <hr class="bo">

        <p>　　　　　　　トリートメント　　　¥3.10～</p>
        <hr class="bo">

        <!-- STAFF -->
        <h3>04 <span class="senn"></span>STAFF</h3>


        <div class="staff-section">
            <img src="https://1.bp.blogspot.com/-q3wHeD3V-Vs/VGLMcL-qStI/AAAAAAAApAs/Fql70guQhE0/s800/job_biyoushi.png"
                style="width: 250px;">
            <p>stylist</p>
        </div>

        <p>
            <span
                style="font-family: Cambria, Georgia, 'Times New Roman', serif; color: #5f585885; font-size: x-large;">
                kawano
            </span>
            　　　河野　翔也<br>
            <span
                style="font-family: Cambria, Georgia, 'Times New Roman', serif; color: #5f585885; font-size: x-large;">
                shoya
            </span>
        </p>
        <h3>06 <span class="senn"></span>RECRUIT</h3>
        <div style="display: flex; align-items: flex-start; gap: 20px;">
            <img src="img/i.png" style="width: 400px; height: 300px;">
            <p style="font-size: x-large; font-family: 'Courier New', Courier, monospace;">
                一緒に働ける方、募集中です!! <br><br><br><br><br><br>Tel.　　090-7547-5554<br>Mail. <a href="">jfaaf@gmail.com</a>
            </p>



        </div>
    </div>
    </div>
</body>

</html>
