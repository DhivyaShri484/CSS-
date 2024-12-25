<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Responsive Layout</title>
    <link rel="stylesheet" href="css/style.css">
</head>
<body>

    <header>
        <h1>Responsive Design Example</h1>
    </header>

    <div class="section-container">
        <section class="section">
            <div class="title">Chicken</div>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
        </section>
        <section class="section">
            <div class="title">Beef</div>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
        </section>
        <section class="section">
            <div class="title">Sushi</div>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
        </section>
    </div>

</body>
</html>

/* Section container (Desktop) */
.section-container {
    display: flex;
    justify-content: space-between;
    margin: 20px;
}

/* Each section */
.section {
    width: 32%;
    padding: 10px;
    margin-bottom: 20px;
    background-color: #f1f1f1;
    border: 1px solid #000;
    position: relative;
}

/* Title inside each section */
.title {
    position: absolute;
    top: 10px;
    right: 10px;
    background-color: #333;
    color: #fff;
    padding: 5px;
    font-size: 1.25em;
}
