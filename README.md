<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Kyle's Tips on Restoring Jeeps</title>

    <meta name="description"
          content="Kyle's tips on restoring Willys Jeeps, including parts, wiring, and painting.">

    <link rel="stylesheet" href="styles.css">
</head>

<body>

<main>

    <div class="hero">

        <img src="Kyle's Tips on Restoring Jeeps.png"
             alt="Kyle's Tips on Restoring Jeeps"
             class="main-image">

        <nav class="hero-links" aria-label="Jeep restoration topics">

            <a href="Where to buy parts.png">
                Where to Buy Parts
            </a>

            <a href="Wiring Harness.png">
                Wiring Harness
            </a>

            <a href="Painting.png">
                Painting
            </a>

        </nav>

    </div>

</main>
</body>
</html>
body {
    margin: 0;
    background-color: black;
    font-family: Arial, Helvetica, sans-serif;
}

.hero {
    position: relative;
    width: 100%;
    max-width: 1800px;
    margin: auto;
}

.main-image {
    width: 100%;
    height: auto;
    display: block;
}

/* This places the links in the center of your main image */
.hero-links {
    position: absolute;
    top: 50%;
    left: 50%;

    transform: translate(-50%, -50%);

    display: flex;
    flex-direction: column;
    align-items: center;

    gap: 20px;
}

.hero-links a {
    color: white;
    background-color: rgba(0, 0, 0, 0.75);

    font-size: 24px;
    font-weight: bold;

    padding: 12px 20px;

    text-decoration: none;

    border-radius: 5px;
}

.hero-links a:hover,
.hero-links a:focus {
    background-color: white;
    color: black;

    outline: 3px solid yellow;
}

@media screen and (max-width: 768px) {

    .hero-links {
        gap: 10px;
    }

    .hero-links a {
        font-size: 16px;
        padding: 8px 12px;
    }
}

</body>
</html>
