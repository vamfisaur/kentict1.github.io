<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>INFORMATION COMMUNICATION TECHNOLOGY</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }

        header {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 1em;
        }

        nav {
            background-color: #eee;
            padding: 1em;
            text-align: center;
        }

        nav ul {
            list-style: none;
            margin: 0;
            padding: 0;
        }

        nav li {
            display: inline;
            margin-right: 10px;
        }

        nav a {
            color: #333;
            text-decoration: none;
            padding: 8px 16px;
            border: 1px solid #333;
            background-color: #eee;
            border-radius: 4px;
            transition: background-color 0.3s ease;
        }

        nav a:hover {
            background-color: #333;
            color: white;
        }

        main {
            padding: 1em;
        }

        article {
            border-bottom: 1px solid #ccc;
            margin-bottom: 1em;
            padding-bottom: 1em;
        }

        .details {
            display: none;
            margin-top: 10px;
            padding: 10px;
            background-color: #fff;
            border: 1px solid #ccc;
            border-radius: 4px;
            transition: max-height 0.3s ease;
            overflow: hidden;
        }

        .show-details {
            cursor: pointer;
            color: #007bff;
            text-decoration: underline;
            display: inline-block;
            margin-top: 10px;
            transition: color 0.3s ease;
        }

        .show-details:hover {
            color: #0056b3;
        }
    </style>
</head>

<body>

    <header>
        <h1>INFORMATION COMMUNICATION TECHNOLOGY</h1>
    </header>

    <nav>
        <ul>
            <li><a href="index.html">Home</a></li>
            <li><a href="Subjects.html">ICT</a></li>
            <li><a href="About.html">About</a></li>
            <li><a href="#">Contact</a></li>
        </ul>
    </nav>

    <main>
        <article>
            <h2>What is ICT?</h2>
            <p>ICT, or information and communications technology (or technologies), is the infrastructure and components that enable modern computing. Among the goals of IC technologies, tools and systems is to improve the way humans create, process and share data or information with each other.</p>
            <div class="details" id="details1">
                <p>Information and Communication Technology can contribute to universal access to education, equity in education, the delivery of quality learning and teaching, teachers' professional development and more efficient education management, governance, and administration.</p>
            </div>
            <span class="show-details" onclick="toggleDetails('details1')">Read more</span>
        </article>

        <article>
            <h2>Why you should consider choosing ICT?</h2>
            <p>You should consider choosing ict if you have interest on technologies or on coding buiding softwares , websites and even games and many more.</p>
            <div class="details" id="details2">
                <p>Theres many available opportunities online , they're accepting everyone who has knowledge on coding or on some technical stuff hardware or software.</p>
            </div>
            <span class="show-details" onclick="toggleDetails('details2')">Read more</span>
        </article>
    </main>

    <footer>
        <p>&copy; KENT RV A. CRISOSTOMO 11-ICT 1 EMTECH </p>
    </footer>

    <script>
        function toggleDetails(detailsId) {
            var details = document.getElementById(detailsId);
            if (details.style.display === "block") {
                details.style.display = "none";
            } else {
                details.style.display = "block";
            }
        }
    </script>

</body>

</html>


