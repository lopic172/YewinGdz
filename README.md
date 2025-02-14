<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>YewinGdz</title>
    <link rel="icon" href="yewin.png" type="image/x-icon">
    <style>
        body {
          background-color: yellow;
        }
    <style>
        body {
            font-family: Arial, sans-serif;
        }
        .tabs {
            display: flex;
            cursor: pointer;
            margin-bottom: 10px;
        }
        .tab {
            padding: 10px 20px;
            background: #15bfdd;
            border: 1px solid #ccc;
            border-bottom: none;
            margin-right: 5px;
        }
        .tab.active {
            background: white;
            border-top: 2px solid #007bff;
            font-weight: bold;
        }
        .content {
            border: 1px solid #ccc;
            padding: 20px;
            display: none;
        }
        .content.active {
            display: block;
        }
    </style>
</head>
<body>

<div class="tabs">
    <div class="tab active" data-target="tab1">Главная</div>
    <div class="tab" data-target="tab2">Класс</div>
    <div class="tab" data-target="tab3">Поддержка</div>
</div>

<div class="content active" id="tab1">
    <h2>Главная</h2>
    <p>Это содержимое первой вкладки.</p>
    <iframe src="https://yoomoney.ru/quickpay/fundraise/button?billNumber=18DAUVMGSLT.250214&" width="330" height="50" frameborder="0" allowtransparency="true" scrolling="no"></iframe>
       <iframe src="https://yoomoney.ru/quickpay/fundraise/button?billNumber=18DAV5HI6N9.250214&" width="330" height="50" frameborder="0" allowtransparency="true" scrolling="no"></iframe>
       <iframe src="https://yoomoney.ru/quickpay/fundraise/button?billNumber=18DAVBN8FVJ.250214&" width="330" height="50" frameborder="0" allowtransparency="true" scrolling="no"></iframe>
</div>
<div class="content" id="tab2">
    <h2>Выберите класс:</h2>
    <div class="tab active" data-target="1class">1 класс</div>
    <div class="tab" data-target="2class">2 класс</div>
    <div class="tab" data-target="3class">3 класс</div>
    <div class="tab active" data-target="4class"> 4 класс</div>
    <div class="tab" data-target="5class">5 класс</div>
    <div class="tab" data-target="6class">6 класс</div>
    <div class="tab active" data-target="7class">7 класс</div>
    <div class="tab" data-target="8class">8 класс</div>
    <div class="tab" data-target="9class">9 класс</div>
    <div class="tab active" data-target="10class">10 класс</div>
    <div class="tab" data-target="11class">11 класс</div>
    <br>
    <iframe src="https://yoomoney.ru/quickpay/fundraise/button?billNumber=18DAUVMGSLT.250214&" width="330" height="50" frameborder="0" allowtransparency="true" scrolling="no"></iframe>
       <iframe src="https://yoomoney.ru/quickpay/fundraise/button?billNumber=18DAV5HI6N9.250214&" width="330" height="50" frameborder="0" allowtransparency="true" scrolling="no"></iframe>
       <iframe src="https://yoomoney.ru/quickpay/fundraise/button?billNumber=18DAVBN8FVJ.250214&" width="330" height="50" frameborder="0" allowtransparency="true" scrolling="no"></iframe>
    <p>
    
    </p>
</div>
<div class="content" id="1class">
    <h2>1 класс:</h2>
</div>
<div class="content" id="2class">
    <h2>2 класс:</h2>
</div>
<div class="content" id="3class">
    <h2>3 класс:</h2>
</div>
<div class="content" id="4class">
    <h2>4 класс:</h2>
</div>
<div class="content" id="5class">
    <h2>5 класс:</h2>
</div>
<div class="content" id="6class">
    <h2>6 класс:</h2>
</div>
<div class="content" id="7class">
    <h2>7 класс:</h2>
</div>
<div class="content" id="8class">
    <h2>8 класс:</h2>
</div>
<div class="content" id="9class">
    <h2>9 класс:</h2>
</div>
<div class="content" id="10class">
    <h2>10 класс:</h2>
</div>
<div class="content" id="11class">
    <h2>11 класс:</h2>
</div>



<div class="content" id="tab3">
    <h2>Поддержка:</h2>

    <a href="https://forms.yandex.ru/u/67aefd88f47e739bf2a520d2/"><b>поддержка</b> </a> &thinsp;
    <a href="https://forms.yandex.ru/u/67aefcfceb6146896609f294/"><b>предложить идею</b></a>
    <br>
<br>
       <iframe src="https://yoomoney.ru/quickpay/fundraise/button?billNumber=18DAUVMGSLT.250214&" width="330" height="50" frameborder="0" allowtransparency="true" scrolling="no"></iframe>
       <iframe src="https://yoomoney.ru/quickpay/fundraise/button?billNumber=18DAV5HI6N9.250214&" width="330" height="50" frameborder="0" allowtransparency="true" scrolling="no"></iframe>
       <iframe src="https://yoomoney.ru/quickpay/fundraise/button?billNumber=18DAVBN8FVJ.250214&" width="330" height="50" frameborder="0" allowtransparency="true" scrolling="no"></iframe>
    </p>
</div>

<script>
    const tabs = document.querySelectorAll('.tab');
    const contents = document.querySelectorAll('.content');

    tabs.forEach(tab => {
        tab.addEventListener('click', () => {
            tabs.forEach(t => t.classList.remove('active'));
            contents.forEach(c => c.classList.remove('active'));

            tab.classList.add('active');
            document.getElementById(tab.dataset.target).classList.add('active');
        });
    });
</script>

</body>
</html>
