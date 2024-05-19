# mohahtml
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Smartsheet Embed</title>
    <style>
        /* Set iframe size and style */
        iframe {
            width: 1000px;
            height: 700px;
            border: none;
        }
        /* Style for the overlay to hide the bar */
        .overlay {
            position: absolute;
            top: 0; /* Adjust this value to match the height of the bar */
            left: 0;
            width: 1000px; /* Match the iframe width */
            height: 50px; /* Adjust this value to match the height of the bar */
            background: white; /* Or the background color of the iframe */
            z-index: 10;
        }
        /* Positioning for the iframe and overlay container */
        .container {
            position: relative;
            width: 1000px;
            height: 700px;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="overlay"></div>
        <iframe id="smartsheet-embed" src="https://app.smartsheet.com/b/publish?EQBCT=0a48f3ce31ba41bca322de6a2fb9524e"></iframe>
    </div>
</body>
</html>
