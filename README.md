<!DOCTYPE html>
<html lang="kk">
<head>
    <style>
        .image-container {
           display: flex;
            justify-content: center;
            align-items: center
        }

        .image-container img {
            width: 450px;
            height: 330px;
            margin: 15px;
            transition: transform 0.3s; 
        }

        .image-container:hover img { 
            transform: scale(1.05); 
        }
       

    </style>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>FC Barcelona</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #e1ed08;
        }
        header {
            background-color: #200696;
            color: white;
            padding: 20px;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #9c0404;
            padding: 20px;
        }
        nav a {
            transition: color 0.3s,transform 0.3s;
            color: white;
            margin: 0 15px;
            text-decoration: none;
            font-weight: bold;
            font-size: 20px;
        }
        nav a:hover {
            color: yellow;
            transform: scale(1.1);
            text-decoration: underline;
        }
       
.fade-in {
    opacity: 0;
    transform: translateY(30px);
    animation: fadeIn 1.5s ease-out forwards;
}

@keyframes fadeIn {
    to {
        opacity: 1;
        transform: translateY(0);
    }
}

        main {
            padding: 20px;
        }
        section {
            margin: 20px 0;
        }
        h2 {
            color: #200696;
        }
        h3 {
            color: #200696;
        }
        footer {
            background-color: #200696;
            color: white;
            text-align: center;
            padding: 20px;
        }
        table {
            width: 100%;
            border-collapse: collapse;
            margin: 20px 0;
        }
        table, th, td {
            border: 1px solid #080000;
        }
        th, td {
            padding: 12px;
            text-align: center;
        }
        th {
            background-color: #9e190a;
            color: white;
        }

        #login-form {
            display: none;
            text-align: center;
            margin-top: 50px;
        }
        #login-form input {
            margin: 10px;
            padding: 10px;
            width: 200px;
        }
        #login-form button {
            padding: 10px 20px;
            background-color: #200696;
            color: white;
            border: none;
            cursor: pointer;
        }
        #login-form button:hover {
            background-color: #9c0404;
        }
    </style>
</head>
<body>
   

<header>
    <h1>FC Barcelona</h1>
    <p>Барселона футбол клубының ресми сайты</p>
</header>

<div id="login-form">
    <h2>Сайтқа кіру</h2>
    <input type="text" id="username" placeholder="Логин">
    <input type="password" id="password" placeholder="Пароль">
    <button onclick="login()">Кіру</button>
    <p id="error-message" style="color: red;"></p>
</div>

<main id="main-content" style="display:none;">

    <nav>
        <a href="barcelona.html">Басты бет</a>
        
        <a href="legends.html">Легендалары</a>
        <a href="trophies.html">Трофейлері</a>
        <a href="players.html">Ойыншылары</a>
        <a href="strukture.html">Құрылымы</a>
    </nav>

    <section id="home" class="fade-in">
        <h2>Басты бет</h2>
        <p>Футбол Клубы Барселона (қысқартылған түрде FC Barcelona) 1899 жылы Каталонияның Барселона қаласында Жоан Гампер мен оның достарының бастамасымен құрылды. Бұл клуб тек футбол ғана емес, Каталонияның мәдени және саяси символы болып табылады. Барселона клубының негізгі түсі — көк және қызыл, оның "Blaugrana" деген лақап аты осы түстерге байланысты. Клубтың ұраны – "Més que un club" (аудармасы: "Клубтан да артық"), бұл ұран клубтың әлеуметтік және саяси маңыздылығын көрсетеді.

            Барселона клубының стадионы Камп Ноу (Camp Nou) деп аталады, ол әлемдегі ең үлкен стадиондардың бірі және 99,354 адамға дейін сыйымдылығы бар. Бұл стадион 1957 жылы ашылған және клубтың негізгі үй алаңы болып табылады.</p>
        
    </section>
    

    <section id="about" class="fade-in" >
        <h2>Клуб туралы</h2>
        <p>Барселона клубының қазіргі президенті – Жоан Лапорта, ал бас бапкері – Хави Эрнандес. Клубтың тарихында көптеген атақты футболшылар болған, олардың ішінде Лионель Месси, Роналдиньо, Хави, Андрес Иньеста, Карлес Пуйоль және Неймар сынды әлемге танымал ойыншыларды атап өтуге болады.</p>
    </section>
 

    <section id="achievements" class="fade-in">
        <h2>Жетістіктері</h2>
        <p>Барселона көптеген ішкі және халықаралық турнирлерде үздік ойын көрсетіп, әлемдегі ең үздік клубтардың бірі болып табылады.</p>
        <table > 
            <tr>
                <th>Турнир</th>
                <th>Жеңіс саны</th>
            </tr>
            <tr>
                <td>Ла Лига</td>
                <td>27</td>
            </tr>
            <tr>
                <td>Кубок дел Рей</td>
                <td>31</td>
            </tr>
            <tr>
                <td>УЕФА Чемпиондар Лигасы</td>
                <td>5</td>
            </tr>
            <tr>
                <td>УЕФА Суперкубогы</td>
                <td>5</td>
            </tr>
            <tr>
                <td>ФИФА Клубтық Әлем Чемпионаты</td>
                <td>3</td>
            </tr>
        </table>
    </section>

    
        <h2>Трофейлері</h2>
        <p>Барселона клубы өзінің тарихында 90-нан астам түрлі ұлттық және халықаралық трофейлерді жеңіп алды. Соның ішінде Ла Лига, Кубок дел Рей, Чемпиондар Лигасы және ФИФА Клубтық Әлем Чемпионаты бар.</p>
    </section>

    
        <h2>Ойыншылары</h2>
        <p>Қазіргі таңда Барселонаның жұлдызды ойыншылары:</p>
        <ul>
            <li>Роберт Левандовски</li>
            <li>Марк-Андре тер Штеген</li>
            <li>Френки де Йонг</li>
            <li>Педри</li>
            <li>Гави</li>
            <li>Рафинья</li>
            <li>Ямаль</li>
        </ul>
    </section>
    <p><div class="image-container" class="fade-in">
        <img src="images/Barcelona logo.jpg" width="450" height="300" alt="Barcelona logo">
           <div class="image-container">
       <img src="images/Barcelona team.jpg" width="450" height="300" alt="Barcelona team">
         <div class="image-container" >
        <img src="images/Barcelona stadium.jpg" width="450" height="300" alt="Barcelona stadium"></p>
    </div>
    
   

</main>

<footer>
    <p>© 2024 FC Barcelona. Барлық құқықтар қорғалған.</p>
    <p>
        <a href="https://twitter.com/FCBarcelona" target="_blank" style="color: white;">Twitter</a> |
        <a href="https://www.facebook.com/fcbarcelona" target="_blank" style="color: white;">Facebook</a> |
        <a href="https://www.instagram.com/fcbarcelona/" target="_blank" style="color: white;">Instagram</a>
    </p>
</footer>

<script>
    function login() {
        var username = document.getElementById("username").value;
        var password = document.getElementById("password").value;
        
        if (username === "a" && password === "123") {
            document.getElementById("login-form").style.display = "none";
            document.getElementById("main-content").style.display = "block";
        } else {
            document.getElementById("error-message").innerText = "Қате логин немесе пароль!";
        }
    }

    document.getElementById("login-form").style.display = "block";
    document.addEventListener('DOMContentLoaded', () => {
    const fadeInElements = document.querySelectorAll('.fade-in');
    fadeInElements.forEach((element) => {
        element.classList.add('fade-in');
    });
});

</script>

</body>
</html>




