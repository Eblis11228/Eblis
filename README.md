<!DOCTYPE html>
<html lang="fa">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ربات ابلیس</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            color: #333;
            text-align: center;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #333;
            color: #fff;
            padding: 20px 0;
        }

        main {
            padding: 20px;
        }

        .command-section {
            margin-top: 20px;
        }

        button {
            background-color: #333;
            color: #fff;
            padding: 10px 20px;
            border: none;
            cursor: pointer;
            margin-top: 10px;
        }

        button:hover {
            background-color: #555;
        }

        .hidden {
            display: none;
        }

        label {
            display: block;
            margin-top: 10px;
        }

        input {
            padding: 5px;
            margin-top: 5px;
            width: 200px;
        }

        footer {
            background-color: #333;
            color: #fff;
            padding: 10px 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
    <script>
        document.addEventListener("DOMContentLoaded", function() {
            const tagButton = document.getElementById('tagButton');
            const responseDiv = document.getElementById('response');
            const identityForm = document.getElementById('identityForm');
            const submitIdentity = document.getElementById('submitIdentity');

            tagButton.addEventListener('click', function() {
                responseDiv.innerHTML = 'هویتت رو بگو و اسم میخای یا مقام؟';
                identityForm.classList.remove('hidden');
            });

            submitIdentity.addEventListener('click', function() {
                const name = document.getElementById('name').value;
                const rank = document.getElementById('rank').value;
                responseDiv.innerHTML = `اینجانب ربات پرهام ابلیس بزرگ تایید میکنم که ${name} حق تگ ابلیس رو با مقام ${rank} داره و فیک نیست`;
                identityForm.classList.add('hidden');
            });
        });
    </script>
</head>
<body>
    <header>
        <h1>ربات ابلیس</h1>
    </header>
    <main>
        <section class="command-section">
            <button id="tagButton">حق تگ ابلیس میخام</button>
            <div id="response"></div>
            <div id="identityForm" class="hidden">
                <label for="name">نام:</label>
                <input type="text" id="name" placeholder="مثال: پرهام تومار">
                <label for="rank">مقام:</label>
                <input type="text" id="rank" placeholder="مثال: شاه">
                <button id="submitIdentity">ارسال</button>
            </div>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 ربات ابلیس</p>
    </footer>
</body>
</html><!DOCTYPE html>
<html lang="fa">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ربات ابلیس</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            color: #333;
            text-align: center;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #333;
            color: #fff;
            padding: 20px 0;
        }

        main {
            padding: 20px;
        }

        .command-section {
            margin-top: 20px;
        }

        button {
            background-color: #333;
            color: #fff;
            padding: 10px 20px;
            border: none;
            cursor: pointer;
            margin-top: 10px;
        }

        button:hover {
            background-color: #555;
        }

        .hidden {
            display: none;
        }

        label {
            display: block;
            margin-top: 10px;
        }

        input {
            padding: 5px;
            margin-top: 5px;
            width: 200px;
        }

        footer {
            background-color: #333;
            color: #fff;
            padding: 10px 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
    <script>
        document.addEventListener("DOMContentLoaded", function() {
            const tagButton = document.getElementById('tagButton');
            const responseDiv = document.getElementById('response');
            const identityForm = document.getElementById('identityForm');
            const submitIdentity = document.getElementById('submitIdentity');

            tagButton.addEventListener('click', function() {
                responseDiv.innerHTML = 'هویتت رو بگو و اسم میخای یا مقام؟';
                identityForm.classList.remove('hidden');
            });

            submitIdentity.addEventListener('click', function() {
                const name = document.getElementById('name').value;
                const rank = document.getElementById('rank').value;
                responseDiv.innerHTML = `اینجانب ربات پرهام ابلیس بزرگ تایید میکنم که ${name} حق تگ ابلیس رو با مقام ${rank} داره و فیک نیست`;
                identityForm.classList.add('hidden');
            });
        });
    </script>
</head>
<body>
    <header>
        <h1>ربات ابلیس</h1>
    </header>
    <main>
        <section class="command-section">
            <button id="tagButton">حق تگ ابلیس میخام</button>
            <div id="response"></div>
            <div id="identityForm" class="hidden">
                <label for="name">نام:</label>
                <input type="text" id="name" placeholder="مثال: پرهام تومار">
                <label for="rank">مقام:</label>
                <input type="text" id="rank" placeholder="مثال: شاه">
                <button id="submitIdentity">ارسال</button>
            </div>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 ربات ابلیس</p>
    </footer>
</body>
</html>
