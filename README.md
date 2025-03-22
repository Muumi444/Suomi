<!DOCTYPE html>
<html lang="fi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Löydä Suomi</title>
    <style>
        /* Basic Reset */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: 'Arial', sans-serif;
            background-color: #f5f5f5;
            color: #333;
            line-height: 1.6;
            padding-top: 20px;
        }
        header {
            background-color: #1e2a47;
            color: white;
            padding: 40px 20px;
            text-align: center;
            border-bottom: 5px solid #D1E1F3;
        }
        header h1 {
            font-size: 3.5em;
            margin-bottom: 10px;
        }
        header p {
            font-size: 1.2em;
            font-weight: 300;
        }
        section {
            margin: 40px auto;
            padding: 30px;
            max-width: 1100px;
            background-color: white;
            border-radius: 10px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
        }
        section h2 {
            color: #1e2a47;
            font-size: 2.5em;
            margin-bottom: 20px;
        }
        section p, section ul {
            font-size: 1.1em;
            margin-bottom: 15px;
        }
        ul {
            list-style-type: disc;
            padding-left: 20px;
        }
        footer {
            text-align: center;
            padding: 15px 0;
            background-color: #1e2a47;
            color: white;
            position: relative;
            bottom: 0;
            width: 100%;
        }
        .highlight {
            background-color: #1e2a47;
            color: white;
            padding: 5px 10px;
            border-radius: 5px;
        }
        .cta-button {
            display: inline-block;
            padding: 12px 25px;
            margin-top: 20px;
            background-color: #2a3d66;
            color: white;
            font-size: 1.2em;
            text-decoration: none;
            border-radius: 5px;
            transition: background-color 0.3s ease;
        }
        .cta-button:hover {
            background-color: #405a92;
        }
        .section-header {
            text-align: center;
            margin-bottom: 20px;
        }
        .section-header h2 {
            font-size: 2.8em;
            font-weight: bold;
        }
    </style>
</head>
<body>

    <header>
        <h1>Löydä Suomi</h1>
        <p>Tutustu Suomen luontoon, kulttuuriin ja innovaatioihin</p>
    </header>

    <div class="container">

        <!-- Geography Section -->
        <section>
            <div class="section-header">
                <h2>Geografia ja Luonto</h2>
            </div>
            <p>Suomi sijaitsee Pohjois-Euroopassa ja on rajattu Ruotsiin, Venäjään ja Norjaan. Se tunnetaan nimellä <strong>"Tuhansien järvien maa"</strong>, ja Suomessa on noin <strong>188 000 järveä</strong> sekä laajoja metsiä, jotka peittävät yli 75 % maasta.</p>
            <p>Suomen pohjoisimmassa osassa sijaitsee napapiiri, jossa voi kokea <strong>keskiyön auringon</strong> kesällä ja upean <strong>revontulet</strong> talvella. Tämä tekee Suomesta ainutlaatuisen kohteen luonnon ystäville!</p>
        </section>

        <!-- Culture Section -->
        <section>
            <div class="section-header">
                <h2>Kulttuuri ja Perinteet</h2>
            </div>
            <p>Suomalainen kulttuuri on syvästi juurtunut luontoon ja yksinkertaisuuteen. Sauna on osa jokaisen suomalaisen elämää, ja se on maassa yli 2 miljoonaa saunaa. Saunan rauhallinen ja rentouttava ympäristö on tärkeä osa suomalaista elämänmenoa.</p>
            <p>Toinen tärkeä perinne on <strong>Juhannus</strong>, jota juhlistetaan kokkojen ja perheiden yhdessäololla. Tämä juhla merkitsee kesän virallista alkua ja on täynnä ilonpitoa ja perinteitä.</p>
        </section>

        <!-- People and Language Section -->
        <section>
            <div class="section-header">
                <h2>Väestö ja Kielitaito</h2>
            </div>
            <p>Suomessa asuu noin <strong>5,5 miljoonaa asukasta</strong>, ja sen viralliset kielet ovat <strong>suomi</strong> ja <strong>ruotsi</strong>. Suomi on kieli, joka erottuu muista Euroopan kielistä, ja sillä on ainutlaatuinen rakenne.</p>
            <p>Pohjoisessa asuvat saamelaiset, joilla on oma kielensä ja kulttuurinsa. Suomi on myös tunnettu tasa-arvostaan ja se on useimmiten listattu maailman tasa-arvoisimpien maiden joukkoon.</p>
        </section>

        <!-- Economy and Innovation Section -->
        <section>
            <div class="section-header">
                <h2>Talous ja Innovaatio</h2>
            </div>
            <p>Suomi on tunnettu huippuluokan koulutuksestaan ja innovaatioistaan. Maa on koti monille tunnetuille brändeille kuten Nokia ja Rovio (Angry Birds -pelin luoja). Suomessa painotetaan myös kestäviä energiaratkaisuja, ja sen tavoitteena on olla hiilineutraali vuoteen 2035 mennessä.</p>
            <p>Suomi on myös edelläkävijä teknologian alalla ja tarjoaa jatkuvasti uusia innovatiivisia ratkaisuja eri teollisuuden aloilla.</p>
        </section>

        <!-- Famous Finns Section -->
        <section>
            <div class="section-header">
                <h2>Kuuluisat Suomalaiset</h2>
            </div>
            <p>Suomi on tuottanut monia maailmankuuluja henkilöitä eri aloilta:</p>
            <ul>
                <li><strong>Jean Sibelius</strong> – Maailmankuulu säveltäjä, jonka teos "Finlandia" on kansallinen symboli.</li>
                <li><strong>Linus Torvalds</strong> – Linux-käyttöjärjestelmän luoja, joka on mullistanut maailman ohjelmoinnin kentän.</li>
                <li><strong>Tove Jansson</strong> – Moomin-hahmojen luoja, joka on valloittanut sydämiä ympäri maailmaa.</li>
            </ul>
        </section>

        <!-- Fun Facts Section -->
        <section>
            <div class="section-header">
                <h2>Hauskoja Faktoja Suomesta</h2>
            </div>
            <ul>
                <li>Suomessa on maailman korkein kahvin kulutuksen määrä per capita.</li>
                <li>Suomessa on enemmän saunoja kuin autoja.</li>
                <li>Suomi on jatkuvasti yksi maailman onnellisimmista maista.</li>
                <li>Suomalaisille on ominaista "Sisu", joka tarkoittaa päättäväisyyttä ja sinnikkyyttä vastoinkäymisistä huolimatta.</li>
            </ul>
            <a href="#more-info" class="cta-button">Lisätietoja Suomesta</a>
        </section>

    </div>

    <footer>
        <p>&copy; 2025 Löydä Suomi | Kaikki oikeudet pidätetään</p>
    </footer>

</body>
</html>
