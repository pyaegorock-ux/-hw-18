# -hw-18
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Heading Assignment Final</title>
    <style>
        body {
            font-family: "Times New Roman", Times, serif;
            padding: 50px;
        }

        /* Heading 1: Black top line, Yellow bottom line, Red shadow */
        h1 {
            display: inline-block;
            font-size: 44px;
            margin: 0 0 40px 0;
            padding: 5px 0;
            /* Top black border and Bottom yellow border */
            border-top: 3px solid black;
            border-bottom: 3px solid #E6E600; 
            /* Red ghosting reflection */
            text-shadow: 2px 2px 2px rgba(255, 0, 0, 0.4);
        }

        /* Heading 2: Yellow outer box with Black inner frame */
        h2 {
            font-style: italic;
            font-weight: normal;
            font-size: 32px;
            padding: 5px 15px;
            /* Yellow thick border */
            border: 4px solid #E6E600;
            /* Black thin inner line using negative offset */
            outline: 1px solid black;
            outline-offset: -5px;
        }

        /* Heading 3: Bottom Right aligned and underlined */
        h3 {
            text-align: right;
            text-decoration: underline;
            font-size: 26px;
            margin-top: 60px;
        }
    </style>
</head>
<body>

    <h1>This is heading 1</h1>

    <h2>This is heading 2</h2>

    <h3>This is heading 3</h3>

</body>
</html>
