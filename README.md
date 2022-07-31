# responsive
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" media="screen and (max-width:376px )" href="mobile.css">
    <link rel="stylesheet" media="screen and (min-width:376px )" href="desktops.css">
    <link rel="stylesheet" media="screen and (max-width:1440px)" href="tests.css">
    <link rel="preconnect" href="https://fonts.gstatic.com">
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300&display=swap" rel="stylesheet">
    <style>
        
        .form {
            display: block;
            margin: 20px;
            background-color: #dddddd;
            padding: 12px;
            border: 3px;
            border-radius: 4px;
            max-width: 330px;
            flex-wrap: wrap;





        }

        button {
            border: 0cm;

        }

        .container {
            margin-bottom: 15px;
            max-width: 300px;
            text-align: center;
        }

        .input {
            display: block;
            width: 100%;
            padding: 12px;
            border: 3px solid #dddddd;
            border-radius: 4px;
            color: black;


        }

        .header {
            display: block;
            margin-bottom: 15px;
            max-width: 300px;
            text-align: center;
            font-optical-sizing: 300px;
            background-color: blueviolet;
            padding: 5px;
            column-width: 0250px;
            margin-left: 12px;

        }
    </style>
</head>

<body>
    <main>

        <div class="left">
            <h1><b>Learn to code by<br>watching other </b></h1>
            <p>See how experienced developer solve problems in real-time.<br>
                Watching scripted tutorials is great, but understanding how <br>developers think is invaluable</p>
        </div>
        <div class="right">
            <div class="header">
                <table>
                    <p> <b>Try it free 7 days</b> then $20/mo. thereafter</p>
                </table>
            </div>




            <div class="form">
                <div class="container">
                    <input type="text" class="input" placeholder="First Name">
                </div>
                <div class="container">
                    <input type="text" class="input" placeholder="Last Name">
                </div>
                <div class="container">
                    <input type="email" class="input" placeholder="email adress">
                </div>
                <div class="container">
                    <input type="password" class="input" placeholder="password">
                </div>
                <div class="container" style="background-color:hsl(154, 59%, 51%);">

                    <a style="color: WHITE;" href="INITIATE">CLAIM YOURS TODAY </a>
                </div>
                <footer>
                    <p>by clicking the button, you are agreeing to our <button style="color:red ; " type="submit">Terms
                            and services</button></P>
                </footer>
            </div>



        </div>

    </main>
</body>

</html>
