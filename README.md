<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Моя личная страница</title>
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            background-color: #f8f9fa;
            color: #343a40;
            margin: 0;
            padding: 0;
        }
        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
            background-color: #ffffff;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            border-radius: 8px;
        }
        header, footer {
            text-align: center;
            background-color: #007BFF;
            color: white;
            padding: 15px 0;
            border-radius: 8px 8px 0 0;
        }
        footer {
            border-radius: 0 0 8px 8px;
        }
        h1, h2, h3 {
            color: #007BFF;
        }
        .content {
            margin-top: 20px;
        }
        .section {
            margin-bottom: 20px;
        }
        .section img {
            max-width: 100%;
            border-radius: 8px;
        }
        a {
            color: #007BFF;
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
        }
        .button {
            display: inline-block;
            padding: 10px 20px;
            font-size: 16px;
            cursor: pointer;
            text-align: center;
            text-decoration: none;
            outline: none;
            color: #fff;
            background-color: #007BFF;
            border: none;
            border-radius: 8px;
            box-shadow: 0 5px #999;
        }
        .button:hover {background-color: #0056b3}
        .button:active {
            background-color: #0056b3;
            box-shadow: 0 3px #666;
            transform: translateY(4px);
        }
        form {
            display: flex;
            flex-direction: column;
        }
        input, textarea {
            margin-bottom: 10px;
            padding: 10px;
            border: 1px solid #ddd;
            border-radius: 8px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Добро пожаловать на мою личную страницу!</h1>
    </header>
    <div class="container">
        <div class="content">
            <div class="section">
                <h2>Обо мне</h2>
                <p>Здравствуйте! Меня зовут [Ваше имя], и я [ваша профессия или хобби]. Я увлекаюсь [ваши интересы и увлечения].</p>
                <img src="profile.jpg" alt="Моя фотография">
            </div>
            <div class="section">
                <h2>Мои интересы</h2>
                <p>Я люблю [ваши интересы]. В свободное время я занимаюсь [ваши увлечения].</p>
                <button class="button" onclick="displayAlert()">Узнать больше</button>
            </div>
            <div class="section">
                <h2>Мои достижения</h2>
                <p>Я горжусь своими достижениями, такими как [ваши достижения].</p>
            </div>
            <div class="section">
                <h2>Контакты</h2>
                <p>Вы можете связаться со мной по электронной почте: <a href="mailto:[ваш email]">[ваш email]</a>.</p>
            </div>
            <div class="section">
                <h2>Обратная связь</h2>
                <form>
                    <label for="name">Имя:</label>
                    <input type="text" id="name" name="name">
                    <label for="email">Email:</label>
                    <input type="email" id="email" name="email">
                    <label for="message">Сообщение:</label>
                    <textarea id="message" name="message" rows="4"></textarea>
                    <button class="button" type="submit">Отправить</button>
                </form>
            </div>
        </div>
    </div>
    <footer>
        <p>&copy; 2024 [Ваше имя]. Все права защищены.</p>
    </footer>
    <script>
        function displayAlert() {
            alert("Спасибо за интерес! Больше информации скоро будет добавлено.");
        }
    </script>
</body>
</html>
