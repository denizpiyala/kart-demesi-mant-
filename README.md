# kart-demesi-mant-
kart ödemesi basit
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>kart ödemesi</title>
</head>
<body>
    <button onclick="
        console.log(`ödenecek tutar: ${kartÖdemesi}`);
        ">sonuçu göster</button>
    <button onclick="
    kartÖdemesi = kartÖdemesi + 1;
    console.log(`ödenecek tutar: ${kartÖdemesi}`);
    ">sepete 1 ekle</button>

    <button onclick="
    kartÖdemesi = kartÖdemesi + 2;
    console.log(`ödenecek tutar: ${kartÖdemesi}`);
    ">+2</button>

    <button onclick="
    kartÖdemesi = kartÖdemesi + 3;
    console.log(`ödenecek tutar: ${kartÖdemesi}`);
    ">+3</button>

    <button onclick="
    kartÖdemesi = 0;
    console.log(`ödenecek tutar: ${kartÖdemesi}`);
    ">işlemi resetle</button>
    
    <script>
        let kartÖdemesi = 0;

    </script>
    
</body>
</html>
