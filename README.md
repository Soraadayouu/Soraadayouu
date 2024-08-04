<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Profil Web</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="profile-container">
        <img src="profile.jpg" alt="Foto Profil" class="profile-img">
        <h1 class="name">Nama Anda</h1>
        <p class="bio">Deskripsi singkat tentang diri Anda. Misalnya, pekerjaan, hobi, atau minat Anda.</p>
        <ul class="social-links">
            <li><a href="https://facebook.com" target="_blank">Facebook</a></li>
            <li><a href="https://twitter.com" target="_blank">Twitter</a></li>
            <li><a href="https://linkedin.com" target="_blank">LinkedIn</a></li>
        </ul>
    </div>
    <script src="scripts.js"></script>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f4;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    margin: 0;
}

.profile-container {
    background-color: #fff;
    padding: 20px;
    border-radius: 10px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    text-align: center;
}

.profile-img {
    width: 150px;
    height: 150px;
    border-radius: 50%;
    object-fit: cover;
}

.name {
    font-size: 24px;
    margin: 10px 0;
}

.bio {
    font-size: 16px;
    color: #666;
}

.social-links {
    list-style: none;
    padding: 0;
}

.social-links li {
    display: inline;
    margin: 0 10px;
}

.social-links a {
    text-decoration: none;
    color: #3498db;
}
// Jika ada fitur interaktif, tambahkan di sini.
console.log("Profil Web berhasil dimuat.");
