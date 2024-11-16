<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fatemeh Asgarinejad</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            display: flex;
            height: 100vh;
            background-color: #ffffff;
        }
        .container {
            display: flex;
            width: 100%;
        }
        .column {
            padding: 20px;
            box-sizing: border-box;
        }
        .left-column {
            flex: 1;
            text-align: center;
        }
        .left-column img {
            max-width: 100%;
            height: auto;
        }
        .right-column {
            flex: 2;
            padding-left: 40px;
        }
        .right-column p {
            margin: 0;
            font-size: 16px;
            line-height: 1.5;
        }
        /* Smaller font size for section headings */
        h3, h4 {
            font-size: 18px;  /* Set font size for smaller headings */
            margin-top: 10px;
            font-weight: bold;
        }

        /* Smaller font size for university headings */
        .university-heading {
            font-size: 18px;  /* Same size for university headings */
            margin-top: 10px;
            font-weight: bold;
            border-bottom: none; /* Remove border under university names */
        }

        /* Add border under "Teaching", "Publications", "Students", "Talks", and "Awards" */
        .section-heading {
            font-size: 18px;
            font-weight: bold;
            border-bottom: 2px solid #0073e6; /* Blue line below the headings */
            padding-bottom: 5px;
            margin-bottom: 10px;
        }

        /* Inline styling for "Halıcıoğlu Data Science Institute" and "Teaching Assistant" */
        .inline-list {
            display: flex;
            align-items: center; /* Align the items vertically centered */
        }
        .inline-list li {
            display: inline-block;
            margin-right: 10px; /* Add space between list items */
        }

        /* Custom bullet points for unordered lists */
        ul {
            list-style-type: none; /* Remove default bullets */
            padding-left: 0;
        }
        li::before {
            content: "•";  /* Default bullet */
            color: #0073e6; /* Blue bullet color */
            font-size: 20px;
            margin-right: 10px;
        }

        .links {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            margin-top: 20px;
        }
        .links a {
            color: #0073e6;
            text-decoration: none;
            margin: 0 10px;
            font-size: 24px; /* Size of the icons */
        }
        .links a:hover {
            color: #0056b3; /* Darker shade on hover */
        }
        .anchor {
            display: none !important;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="column left-column">
            <img src="IMG_0739.JPG" alt="Fatemeh Asgarinejad">
            <div class="links">
                <a href="https://www.linkedin.com/in/fatemeh-asgarinejad/" title="LinkedIn"><i class="fab fa-linkedin"></i></a>
                <a href="https://github.com/Fasgarinejad" target="_blank" title="Stack Overflow"><i class="fab fa-stack-overflow"></i></a>
                <a href="mailto:fasgarinejad@ucsd.edu" title="Email"><i class="fas fa-envelope"></i></a>
                <a href="https://www.youtube.com/@fatemehasgarinejad" target="_blank" title="YouTube"><i class="fab fa-youtube"></i></a>
                <a href="https://scholar.google.com/citations?user=UjbstjkAAAAJ&hl=en" target="_blank" title="Google Scholar"><i class="fas fa-book"></i></a>
            </div>
        </div>
        <div class="column right-column">
            <p>Hi! 👋 I'm Fatemeh ("Faa-teh-meh"), a fifth-year Ph.D. candidate at the Electrical and Computer Engineering department at the University of California, San Diego (joint with San Diego State University). I work on Hyperdimensional Computing Security and synergy of Hyperdimensional Computing and Machine Learning under supervision of <a href="https://cseweb.ucsd.edu/~trosing/" title="Prof_Rosing">Prof. Tajana Rosing</a> and <a href="https://aksanli.sdsu.edu/" title="Prof_Rosing">Prof. Baris Aksanli</a>. <br>       
                
               I am actively seeking academic positions with a strong focus on <strong>teaching</strong> in the job market.</p>

            <h3 class="section-heading">Teaching</h3>
            
            <!-- University of California, San Diego -->
            <h4 class="university-heading">University of California, San Diego</h4>
            <ul>
                <li><strong>Instructor, CSE 20 (Summer 2024)</strong> (Discrete Mathematics)</li>
                <li><strong>Teaching Assistant, Computer Science and Engineering</strong>
                    <ul>
                        <li><strong>CSE 101:</strong> Design and Analysis of Algorithms (Summer 2023)</li>
                        <li><strong>CSE 20:</strong> Discrete Mathematics (Spring 2021, Spring 2022, Summer 2022, Spring 2023, Winter 2023)</li>
                        <li><strong>CSE 21:</strong> Mathematics for Algorithms and Systems Analysis (Winter, Spring, and Fall 2024)</li>
                    </ul>
                </li>
            </ul>
            
            <!-- Teaching Assistant, Halıcıoğlu Data Science Institute and Teaching Assistant (inline) -->
            <ul class="inline-list">
                <li><strong>Teaching Assistant, Halıcıoğlu Data Science Institute</strong></li>
                <li><strong>DSC 200:</strong> Data Science Programming (Fall 2023)</li>
                <li><strong>DSC 40A:</strong> Theoretical Foundations of Data Science (Summer 2023)</li>
            </ul>

            <!-- San Diego State University -->
            <h4 class="university-heading">San Diego State University</h4>
            <ul>
                <li><strong>Instructor:</strong> First Year Seminars (Four Classes)</li>
            </ul>

            <!-- UC San Diego Extension -->
            <h4 class="university-heading">UC San Diego Extension</h4>
            <ul>
                <li><strong>Teaching Assistant:</strong> DSE 220x - Machine Learning Fundamentals (Prof. Sanjoy Dasgupta, Three Semesters)</li>
            </ul>

            <!-- Publications -->
            <h3 class="section-heading">Publications</h3>
            
            <!-- Students -->
            <h3 class="section-heading">Students</h3>
            
            <!-- Awards -->
            <h3 class="section-heading">Awards</h3>
            <ul>
                <li>DAC’61 Young Fellow Best Video Presentation Award, 2024</li>
                <li>DAC Young Fellow at the 61st Design Automation Conference in San Francisco, 2024</li>
                <li>SRC Research Scholar and awarded funding for conference participation, 2024</li>
                <li>UCSD travel grant, 2024</li>
                <li>Member of HKN (Eta Kappa Nu) Honor Society of UC San Diego since May 2022</li>
            </ul>
                
            <!-- Talks -->
            <h3 class="section-heading">Talks</h3>
            <ul>
                <li>PRISM Center Annual Review, UC San Diego, “PRISM Center Summer Virtual High School Program”, Nov 2024</li>
                <li>TECHCON, “Harnessing Hyperdimensional Computing’s Explainability for Adversarial Attacks”, Sep 2024</li>
                <li>Colegio San Agustin-Bacolod University’s 60th Founding Anniversary Research Conference, “Applying Machine Learning and Brain-Inspired Computing for Innovative Problem Solving”, July 2023</li>
            </ul>
        </div>
    </div>
</body>
</html>
