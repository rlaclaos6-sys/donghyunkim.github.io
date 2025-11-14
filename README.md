
<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>나만의 식물 스토어</title>
    <style>
        body { font-family: Arial, sans-serif; margin: 0; padding: 0; background: #f4f7f4; }
        header { background: #4CAF50; color: white; padding: 20px; text-align: center; font-size: 24px; }
        .container { padding: 20px; }
        .grid { display: flex; flex-wrap: wrap; gap: 20px; justify-content: center; }
        .card { background: white; width: 250px; border-radius: 10px; box-shadow: 0 2px 6px rgba(0,0,0,0.15); padding: 15px; text-align: center; }
        .card img { width: 100%; height: auto; border-radius: 10px; }
        .btn { display: inline-block; margin-top: 10px; padding: 10px 15px; background: #4CAF50; color: white; text-decoration: none; border-radius: 6px; }
    </style>
</head>
<body>
    <header>🌱 나만의 식물 스토어</header>

    <div class="container">
        <h2>판매 중인 식물</h2>
        <div class="grid">
            <!-- 금전수 -->
            <div class="card">
                <img src="plant1.jpg" alt="금전수">
                <h3>금전수</h3>
                <p>15,000원</p>
                <a class="btn" href="mailto:example@mail.com?subject=금전수 구매문의">구매 문의</a>
            </div>

            <!-- 떡갈고무나무 -->
            <div class="card">
                <img src="plant2.jpg" alt="떡갈고무나무">
                <h3>떡갈고무나무</h3>
                <p>20,000원</p>
                <a class="btn" href="mailto:example@mail.com?subject=떡갈고무나무 구매문의">구매 문의</a>
            </div>

            <!-- 몬스테라 -->
            <div class="card">
                <img src="plant3.jpg" alt="몬스테라">
                <h3>몬스테라 대형</h3>
                <p>25,000원</p>
                <a class="btn" href="mailto:example@mail.com?subject=몬스테라 구매문의">구매 문의</a>
            </div>
        </div>
    </div>
</body>
</html>
