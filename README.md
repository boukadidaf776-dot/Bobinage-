<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <title>Société Rebobinage Samir ben Salah</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            background: #f4f4f4;
            color: #333;
        }
        header {
            background: #0b5ed7;
            color: white;
            padding: 30px;
            text-align: center;
        }
        section {
            padding: 30px;
            max-width: 1000px;
            margin: auto;
            background: white;
            margin-top: 20px;
        }
        h2 {
            color: #0b5ed7;
        }
        .lang {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 30px;
        }
        .ar {
            direction: rtl;
            text-align: right;
            font-family: "Tahoma", Arial, sans-serif;
        }
        footer {
            text-align: center;
            padding: 15px;
            background: #ddd;
            margin-top: 20px;
        }
        @media (max-width: 768px) {
            .lang {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>

<header>
    <h1>Société Rebobinage Samir ben Salah</h1>
    <p>Société de réparation des moteurs électriques</p>
</header>

<section class="lang">
    <!-- Français -->
    <div>
        <h2>À propos</h2>
        <p>
            La Société Rebobinage Samir ben Salah est spécialisée dans la
            réparation, le rebobinage et l’entretien des moteurs électriques.
        </p>

        <h2>Nos services</h2>
        <ul>
            <li>Réparation de moteurs électriques</li>
            <li>Rebobinage professionnel</li>
            <li>Maintenance et diagnostic</li>
        </ul>

        <h2>Contact</h2>
        <p>
            📍 Adresse : Borj Louzir, rue Mostapha Mohsen, Tunis<br>
            📞 Téléphone : 00216 22 56 70 38
        </p>
    </div>

    <!-- العربية -->
    <div class="ar">
        <h2>من نحن</h2>
        <p>
            شركة لف المحركات سمير بن صالح مختصة في إصلاح
            ولف وصيانة المحركات الكهربائية.
        </p>

        <h2>خدماتنا</h2>
        <ul>
            <li>إصلاح المحركات الكهربائية</li>
            <li>لف المحركات باحتراف</li>
            <li>الصيانة والكشف الفني</li>
        </ul>

        <h2>الاتصال</h2>
        <p>
            📍 العنوان : برج اللوزير، شارع مصطفى محسن، تونس<br>
            📞 الهاتف : 00216 22 56 70 38
        </p>
    </div>
</section>

<footer>
    © 2026 - Société Rebobinage Samir ben Salah
</footer>

</body>
</html>
