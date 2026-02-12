<!DOCTYPE html>
<html lang="pt">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>VIP003 Streaming</title>

<style>
body {
    margin: 0;
    font-family: Arial, sans-serif;
    background-color: #141414;
    color: white;
}

header {
    background: rgba(0,0,0,0.9);
    padding: 15px 50px;
    position: fixed;
    width: 100%;
    z-index: 10;
}

.logo {
    font-size: 26px;
    font-weight: bold;
    color: red;
}

.hero {
    height: 100vh;
    background: linear-gradient(to top, #141414 10%, transparent 60%);
    display: flex;
    align-items: center;
    justify-content: center;
    text-align: center;
    padding: 20px;
}

.hero-content h1 {
    font-size: 50px;
    margin-bottom: 20px;
}

.button {
    background: red;
    padding: 15px 30px;
    border-radius: 5px;
    color: white;
    text-decoration: none;
    font-weight: bold;
    cursor: pointer;
}

.video-container {
    display: none;
    padding: 40px;
    text-align: center;
}

video {
    width: 80%;
    max-width: 900px;
    border-radius: 10px;
}
</style>
</head>

<body>

<header>
    <div class="logo">VIP003</div>
</header>

<section class="hero">
    <div class="hero-content">
        <h1>Conteúdo Exclusivo</h1>
        <div class="button" onclick="mostrarVideo()">Assistir Agora</div>
    </div>
</section>

<section class="video-container" id="videoSection">
    <h2>🎬 Reprodução</h2>
    <video controls>
        <source src="Lizzy1.mp4" type="video/mp4">
        Seu navegador não suporta vídeo.
    </video>
</section>

<script>
function mostrarVideo() {
    document.getElementById("videoSection").style.display = "block";
    window.scrollTo({
        top: document.getElementById("videoSection").offsetTop,
        behavior: "smooth"
    });
}
</script>

</body>
</html>
