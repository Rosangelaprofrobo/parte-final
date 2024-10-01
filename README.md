# parte-final
<html lang="pt-BR">

<head>
    <link rel="stylesheet" href="styles.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link
        href="https://fonts.googleapis.com/css2?family=Chakra+Petch:ital,wght@0,300;0,400;0,500;0,600;0,700;1,300;1,400;1,500;1,600;1,700&display=swap"
        rel="stylesheet">
    <title>Aluraflix</title>
    <title>Guiminamflix</title>
</head>

<body>
    <header>ALURAFLIX</header>
    <header>GUIMINAMFLIX</header>

    <section class="chamada">
        <div class="chamada-texto">
            <h1>ATRAVÉS DO ARANHAVERSO</h1>
            <p>#homem-aranha</p>
        </div>

        <div>
            <iframe width="560" height="315" src="https://www.youtube.com/embed/gt_fAE1Eg2Q?si=EEv-tsY_b1B2OwKE"
                title="YouTube video player" frameborder="0"
                allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
                referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
        </div>
    </section>

    <section class="categoria">
        <h2>Filmes e séries</h2>
        <div class="categoria-videos">
            <a href="https://www.youtube.com/watch?v=cs15QqG6Gjc">
                <img src="https://img.youtube.com/vi/cs15QqG6Gjc/maxresdefault.jpg" />
            </a>
            <a href="https://www.youtube.com/watch?v=nCmIwcycUJ8">
                <img src="https://img.youtube.com/vi/nCmIwcycUJ8/maxresdefault.jpg" />
            </a>
.css
+16
-4
Original file line number	Diff line number	Diff line change
    background: black;
    margin: 0px;
    font-family: "Chakra Petch", sans-serif;
    margin-bottom: 100px;
}

header {
    font-size: 20px;
}

img {
    height: 200px;
}
.categoria-videos {
    display: flex;
    overflow-x: auto;
.categoria {
    padding-left: 20px;
    padding-right: 20px;
    margin-top: 50px;
}
.categoria-videos img {
    opacity: 0.5;
    height: 200px;
}
.categoria-videos img:hover {
    opacity: 1.0;
    border: 3px solid green;
}
.categoria h2 {
    color: rgb(42, 122, 228);
}
