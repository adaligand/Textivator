<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Textivator Menu</title>
    <style>
        body {
            font-family: Arial, sans-serif;
        }

        .menu {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-between;
            padding: 20px;
        }

        .menu a {
            padding: 15px 25px;
            margin: 10px;
            font-weight: bold;
            border-radius: 8px;
            transition: background-color 0.3s;
            display: inline-block;
            text-decoration: none;
            color: #000000;
            background-color: #f9f9f9;
            border: 2px solid #ccc;
            cursor: pointer;
            text-align: center;
            box-sizing: border-box;
            font-size: 16px;
        }

        .menu a:hover {
            background-color: #A9A9A9;
            transform: translateY(-4px);
        }

        .menu a:active {
            background-color: #A9A9A9;
        }

        .subtitle {
            display: block;
            font-weight: normal;
            font-size: 14px;
            color: #666;
        }

        /* Media Query for screens up to 600px */
        @media (max-width: 320px) {
            .menu a {
                width: 45%; /* 2 buttons per row */
                font-size: 15px;
                padding: 12px;
                box-sizing: border-box;
            }
        }

        /* Media Query for screens larger than 600px */
        @media (min-width: 601px) {
            .menu a {
                width: 20%; /* 4 buttons per row on larger screens */
            }
        }
    </style>
</head>
<body>

    <div class="menu">
        <a href="https://adaligand.github.io/Textivator/Dragator.html">
            Dragator
            <span class="subtitle">Screen + print</span>
        </a>
        <a href="https://adaligand.github.io/Textivator/Gapfillator.html">
            Gapfillator
            <span class="subtitle">Screen + print</span>
        </a>
        <a href="https://adaligand.github.io/Textivator/Pyramidor.html">
            Pyramidor
            <span class="subtitle">Screen only</span>
        </a>
        <a href="https://adaligand.github.io/Textivator/Chunkator.html">
            Chunkator
            <span class="subtitle">Screen + print</span>
        </a>
        <a href="https://adaligand.github.io/Textivator/Spacator.html">
            Spacator
            <span class="subtitle">Screen + print</span>
        </a>
        <a href="https://adaligand.github.io/Textivator/Vowelator.html">
            Vowelator
            <span class="subtitle">Screen + print</span>
        </a>
        <a href="https://adaligand.github.io/Textivator/Consonator.html">
            Consonator
            <span class="subtitle">Screen + print</span>
        </a>
        <a href="https://adaligand.github.io/Textivator/Lettrator.html">
            Lettrator
            <span class="subtitle">Screen + print</span>
        </a>
        <a href="https://adaligand.github.io/Textivator/Tanglator.html">
            Tanglator
            <span class="subtitle">Print only</span>
        </a>
        <a href="https://adaligand.github.io/Textivator/Punctuator.html">
            Punctuator
            <span class="subtitle">Print only</span>
        </a>
        <a href="https://adaligand.github.io/Textivator/Typator.html">
            Typator
            <span class="subtitle">Screen only</span>
        </a>
    </div>

</body>
</html>
