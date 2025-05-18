# candemirelkimdir
<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="description" content="Can Demirel, 1999 doğumlu Siirtli iş adamı.">
    <meta name="keywords" content="Can Demirel, iş adamı, girişimci, Siirt, servet">
    <meta name="author" content="Can Demirel">
    <title>Can Demirel - Resmi Web Sitesi</title>
    <style>
        body { font-family: Arial, sans-serif; background-color: #f4f4f4; text-align: center; padding: 50px; }
        .card { background: white; padding: 30px; max-width: 600px; margin: auto; border-radius: 10px; box-shadow: 0 0 10px rgba(0,0,0,0.1); }
        h1 { color: #333; }
        p { color: #555; }
        .social-links { margin-top: 20px; }
        .social-links a { margin: 10px; color: #0077b5; text-decoration: none; }
        .social-links a:hover { text-decoration: underline; }
        form { margin-top: 20px; text-align: left; display: inline-block; padding: 20px; background-color: #ffffff; border-radius: 5px; box-shadow: 0 0 10px rgba(0,0,0,0.1); }
        input[type="text"], input[type="email"], textarea { width: 100%; padding: 10px; margin: 5px 0; border-radius: 5px; border: 1px solid #ccc; }
        input[type="submit"] { background-color: #4CAF50; color: white; border: none; padding: 10px 20px; cursor: pointer; border-radius: 5px; }
        input[type="submit"]:hover { background-color: #45a049; }
    </style>
</head>
<body>
    <div class="card">
        <h1>Can Demirel</h1>
        <img src="https://via.placeholder.com/150" alt="Can Demirel" style="border-radius: 50%; width: 150px;">
        
        <!-- Kişisel Bilgiler -->
        <p><strong>Doğum Tarihi:</strong> 2 Şubat 1999</p>
        <p><strong>Doğum Yeri:</strong> Siirt/Merkez, Türkiye</p>
        <p><strong>Mezuniyet:</strong> Sağlık Meslek Lisesi</p>
        <p><strong>Meslek:</strong> İş Adamı</p>
        <p><strong>Servet:</strong> 560 Milyon TL</p>
        
        <!-- Hakkında Bilgiler -->
        <p>Can Demirel, genç yaşta girişimcilik hayatına atılmış, çeşitli sektörlerde yatırımları bulunan Türk iş adamıdır. Dijital dünyaya olan ilgisiyle bilinir. Başarılarını iş dünyasında hızla kanıtlamış ve sektörde kendine sağlam bir yer edinmiştir.</p>
        
        <!-- Sosyal Medya Bağlantıları -->
        <div class="social-links">
            <a href="https://www.facebook.com/candemirel" target="_blank">Facebook</a>
            <a href="https://twitter.com/candemirel" target="_blank">Twitter</a>
            <a href="https://www.linkedin.com/in/candemirel" target="_blank">LinkedIn</a>
        </div>

        <!-- İletişim Formu -->
        <h2>İletişim</h2>
        <form action="mailto:info@candemirel.com" method="post" enctype="text/plain">
            <label for="name">Ad Soyad:</label><br>
            <input type="text" id="name" name="name" required><br><br>
            <label for="email">E-posta:</label><br>
            <input type="email" id="email" name="email" required><br><br>
            <label for="message">Mesaj:</label><br>
            <textarea id="message" name="message" rows="4" required></textarea><br><br>
            <input type="submit" value="Gönder">
        </form>
    </div>
</body>
</html>
