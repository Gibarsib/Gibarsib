echo '<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>Catálogo de Vídeos</title>
</head>
<body>
    <header>
        <h1>Catálogo de Vídeos</h1>
    </header>
    <main>
        <section class="video-catalog">
            <article class="video-item">
                <img src="path/to/video-thumbnail1.jpg" alt="Vídeo 1">
                <h2>Título do Vídeo 1</h2>
                <p>Descrição do vídeo 1.</p>
            </article>
            <article class="video-item">
                <img src="path/to/video-thumbnail2.jpg" alt="Vídeo 2">
                <h2>Título do Vídeo 2</h2>
                <p>Descrição do vídeo 2.</p>
            </article>
            <article class="video-item">
                <img src="path/to/video-thumbnail3.jpg" alt="Vídeo 3">
                <h2>Título do Vídeo 3</h2>
                <p>Descrição do vídeo 3.</p>
            </article>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 Catálogo de Vídeos</p>
    </footer>
</body>
</html>' > index.html && echo 'body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
}

header {
    background: #333;
    color: #fff;
    padding: 10px 0;
    text-align: center;
}

h1 {
    margin: 0;
}

main {
    padding: 20px;
}

.video-catalog {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
    gap: 20px;
}

.video-item {
    background: #fff;
    border: 1px solid #ddd;
    border-radius: 8px;
    padding: 10px;
    text-align: center;
}

.video-item img {
    max-width: 100%;
    border-radius: 4px;
}

footer {
    text-align: center;
    padding: 20px 0;
    background: #333;
    color: #fff;
    position: relative;
    bottom: 0;
    width: 100%;
}' > styles.css
