<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Samyak Jain | Data Scientist</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Lato:wght@400;700&family=Montserrat:wght@600;700&display=swap" rel="stylesheet">
    <style>
        :root {
            --primary-color: #2c3e50;
            --secondary-color: #34495e;
            --accent-color: #0072b1;
            --background-color: #f8f9fa;
            --text-color: #333;
            --card-background: #ffffff;
            --border-color: #e9ecef;
        }

        body {
            font-family: 'Lato', sans-serif;
            background-color: var(--background-color);
            color: var(--text-color);
            margin: 0;
            padding: 20px;
            line-height: 1.6;
        }

        .container {
            max-width: 900px;
            margin: 40px auto;
            padding: 40px;
            background-color: var(--card-background);
            border-radius: 10px;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.05);
        }

        header {
            text-align: center;
            margin-bottom: 40px;
            border-bottom: 2px solid var(--border-color);
            padding-bottom: 30px;
        }

        h1 {
            font-family: 'Montserrat', sans-serif;
            color: var(--primary-color);
            font-size: 2.8em;
            margin-bottom: 10px;
        }

        .tagline {
            font-size: 1.2em;
            color: var(--secondary-color);
            font-style: italic;
            margin-top: 10px;
            margin-bottom: 25px;
        }
        
        .social-links a {
            margin: 0 5px;
        }
        
        .social-links img {
            transition: transform 0.2s ease-in-out;
        }

        .social-links img:hover {
            transform: scale(1.05);
        }

        h2 {
            font-family: 'Montserrat', sans-serif;
            color: var(--primary-color);
            font-size: 2em;
            border-bottom: 2px solid var(--accent-color);
            padding-bottom: 10px;
            margin-top: 40px;
            margin-bottom: 20px;
        }

        p {
            margin-bottom: 1.5em;
        }

        b, strong {
            color: var(--secondary-color);
        }

        i, em {
            color: var(--accent-color);
        }

        a {
            color: var(--accent-color);
            text-decoration: none;
            font-weight: bold;
        }

        a:hover {
            text-decoration: underline;
        }

        section {
            margin-bottom: 40px;
        }
        
        /* Portfolio Table Styling */
        .portfolio-table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 20px;
        }

        .portfolio-table th, .portfolio-table td {
            padding: 15px;
            text-align: left;
            border-bottom: 1px solid var(--border-color);
        }

        .portfolio-table th {
            background-color: var(--background-color);
            font-family: 'Montserrat', sans-serif;
            font-weight: 600;
        }
        
        .portfolio-table tr:hover {
            background-color: #f1f3f5;
        }

        .portfolio-table code {
            background-color: #e9ecef;
            padding: 3px 6px;
            border-radius: 4px;
            font-family: 'Courier New', Courier, monospace;
            font-size: 0.9em;
        }

        /* Certifications Grid Styling */
        .certifications-grid {
            display: flex;
            flex-wrap: wrap;
            gap: 15px;
            margin-top: 20px;
        }
        
        .certifications-grid a img {
            transition: transform 0.2s ease-in-out, box-shadow 0.2s ease-in-out;
            border-radius: 5px;
        }
        
        .certifications-grid a img:hover {
            transform: translateY(-3px);
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
        }

        /* Responsive Design */
        @media (max-width: 768px) {
            .container {
                padding: 20px;
                margin: 20px auto;
            }
            h1 {
                font-size: 2.2em;
            }
            h2 {
                font-size: 1.8em;
            }
        }
        
        @media (max-width: 480px) {
            .social-links {
                display: flex;
                flex-direction: column;
                gap: 10px;
            }
            .portfolio-table, .portfolio-table tbody, .portfolio-table tr, .portfolio-table td {
                display: block;
                width: 100%;
            }
            .portfolio-table thead {
                display: none;
            }
            .portfolio-table tr {
                margin-bottom: 20px;
                border: 1px solid var(--border-color);
                border-radius: 5px;
            }
            .portfolio-table td {
                border: none;
                border-bottom: 1px solid var(--border-color);
                position: relative;
                padding-left: 50%;
            }
            .portfolio-table td:before {
                position: absolute;
                left: 15px;
                width: 45%;
                padding-right: 10px;
                white-space: nowrap;
                font-weight: bold;
                font-family: 'Montserrat', sans-serif;
            }
            .portfolio-table td:nth-of-type(1):before { content: "S. No."; }
            .portfolio-table td:nth-of-type(2):before { content: "Skills"; }
            .portfolio-table td:nth-of-type(3):before { content: "Project"; }
        }
    </style>
</head>
<body>

    <div class="container">
        <header>
            <h1>Hello, I'm SAMYAK JAIN</h1>
            <p class="tagline">Attention is all you need.</p>
            <div class="social-links">
                <a href="https://www.linkedin.com/in/samyakjain-ds"><img src="https://img.shields.io/badge/-LinkedIn-0072b1?&style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
                <a href="https://drive.google.com/file/d/1poExsi7iUS9BDXEW-pql98mhcx2D1w2K/view?usp=sharing"><img src="https://img.shields.io/badge/-Resume-4285F4?style=for-the-badge&logo=resume&logoColor=white" alt="Resume"/></a>
                <a href="https://public.tableau.com/app/profile/samyak.jain8329/vizzes"><img src="https://img.shields.io/badge/-Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white" alt="Tableau"/></a>
            </div>
        </header>

        <main>
            <section id="introduction">
                <h2>A Short Introduction!</h2>
                <p>
                    Hey there! I’m <b>Samyak Jain</b>, a guy who loves playing around with data and making sense of it. My journey into the world of <b>data science</b> started during the last year of my college, and I’ve been hooked ever since.
                </p>
                <p>
                    I graduated from the <b>University of Delhi</b> with a degree in <i>Computer Applications and Economics</i>. Right now, I’m diving deeper into the field by pursuing a <b>Diploma in Data Science</b> from <b>IIT Madras</b>, where I’m learning all about <i>machine learning</i> and <i>advanced analytics</i>—areas I’m <i>super passionate about</i>.
                </p>
                <p>
                    During college, I discovered my knack for <b>programming</b> and <b>logic building</b> while creating a <i>2D platformer game</i> using only Python. That experience, combined with my love for <i>maths and stats</i> from my school days, made me realize that <b>data science</b> is where I belong.
                </p>
                <p>
                    With a strong foundation in <b>Python</b> and its powerful libraries like <i>Pandas</i>, <i>scikit-learn</i>, and <i>BeautifulSoup</i>, I specialize in <b>data manipulation</b>, <b>machine learning</b>, and <b>web scraping</b>. My skill set also includes <b>advanced statistical analysis</b>, <b>SQL</b> for data querying, and visualization tools like <b>Power BI</b> and <b>Excel</b>, making me proficient in delivering <b>comprehensive data-driven solutions</b>.
                </p>
                <p>
                    In my journey as a data professional, I’ve worked on projects ranging from <i>predictive modeling</i> and <i>sentiment analysis</i> to <b>interactive dashboard creation</b> and <b>business intelligence reporting</b>. These experiences have equipped me with the <i>analytical mindset</i> and <i>technical skills</i> needed to excel in both <b>Data Analyst</b> and <b>Data Scientist</b> roles.
                </p>
                <p>
                    I strongly believe in <i>learning a little every day</i> and staying consistent—<i>small steps lead to big changes over time</i>.
                </p>
                <p>
                    When I’m not crunching numbers or analyzing data, you’ll probably find me <i>watching well-documented YouTube videos</i>, <i>gaming with my friends</i>, or <i>strength training</i> to stay healthy and energized. Feel free to explore my portfolio as I continue to learn and grow in this exciting field of <b>data science</b>!
                </p>
            </section>

            <section id="portfolio">
                <h2>Portfolio</h2>
                <p>Here is a list of my <b>projects</b>!</p>
                <table class="portfolio-table">
                    <thead>
                        <tr>
                            <th>S. No.</th>
                            <th>Skills</th>
                            <th>Associated Project</th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr>
                            <td>1</td>
                            <td><code>Git and Conda Env Development</code>, <code>Data Cleaning</code>, <code>Data Preprocessing</code>, <code>Hyperparameter Tuning</code>, <code>Streamlit Website Development and Deployment</code>, <code>Machine Learning</code>, <code>Python</code></td>
                            <td><a href="https://github.com/SamyakJain-DS/end-to-end-machine-learning">End to End Machine Learning</a></td>
                        </tr>
                        <tr>
                            <td>2</td>
                            <td><code>Git and Conda Env Development</code>, <code>Complex Web Scraping</code>, <code>Data Cleaning</code>, <code>Database Management - OLTP & OLAP</code>, <code>API Development and Deployment</code>, <code>Streamlit Website Development and Deployment</code>, <code>Data Analysis</code>, <code>Python</code></td>
                            <td><a href="https://github.com/SamyakJain-DS/end-to-end-data-analysis">End to End Data Analysis</a></td>
                        </tr>
                        <tr>
                            <td>3</td>
                            <td><code>Excel</code>, <code>Power BI</code>, <code>Dashboard</code></td>
                            <td><a href="https://github.com/SamyakJain-DS/B2B_Pharma_Sales_Analysis">B2B Pharma Company's Sales Data Analysis</a></td>
                        </tr>
                        <tr>
                            <td>4</td>
                            <td><code>Python</code>, <code>NLP</code>, <code>Text Analysis</code>, <code>Sentiment Analysis</code></td>
                            <td><a href="https://github.com/SamyakJain-DS/Text_Analysis_Using_Python">Data Preparation for Text Analysis of Online Articles</a></td>
                        </tr>
                        <tr>
                            <td>5</td>
                            <td><code>Python</code>, <code>Debugging</code>, <code>Problem Solving</code></td>
                            <td><a href="https://github.com/SamyakJain-DS/PokeMario">PokeMario</a></td>
                        </tr>
                        <tr>
                            <td>6</td>
                            <td><code>Excel</code>, <code>Statistics and Visualisation</code>, <code>Inference Regression Modelling</code></td>
                            <td><a href="https://github.com/SamyakJain-DS/Life-Expectancy">Life Expectancy & its Determinants</a></td>
                        </tr>
                        <tr>
                            <td>7</td>
                            <td><code>Excel</code>, <code>Tableau</code></td>
                            <td><a href="https://github.com/SamyakJain-DS/naruto-directors-analysis">Naruto Study</a></td>
                        </tr>
                        <tr>
                            <td>8</td>
                            <td><code>Excel</code>, <code>Tableau</code>, <code>SQL</code>, <code>Powerpoint</code></td>
                            <td><a href="https://github.com/SamyakJain-DS/bellabeat">Case Study Bellabeat</a></td>
                        </tr>
                         <tr>
                            <td>9</td>
                            <td><code>Excel</code>, <code>Tableau</code>, <code>SQL</code>, <code>Powerpoint</code></td>
                            <td><a href="https://github.com/SamyakJain-DS/cyclistics">Case Study Cyclistics</a></td>
                        </tr>
                    </tbody>
                </table>
            </section>

            <section id="certifications">
                <h2>Certifications</h2>
                <div class="certifications-grid">
                    <a href="https://coursera.org/share/08771d9d6845ed219bd47182c2c4694f"><img src="https://img.shields.io/badge/Professional_Data_Analysis_Certification-Google-rgb(66, 133, 244)" alt="Google Certification"></a>
                    <a href="https://www.udemy.com/certificate/UC-xxxxxxxx/"><img src="https://img.shields.io/badge/Data_Science_Bootcamp_by_365_Careers-Udemy-purple" alt="Udemy Certification"></a>
                    <a href="https://www.pragmaticworks.com/boot-camps/power-bi-boot-camp/"><img src="https://img.shields.io/badge/PowerBI_Beginner_to_Pro_Workshop-Pragmatic_Works-rgb(0, 30, 55)" alt="Pragmatic Works Certification"></a>
                    <a href="https://ineuron.ai/"><img src="https://img.shields.io/badge/Machine_Learning_Foundations-iNeuron-rgb(234, 170, 46)" alt="iNeuron Certification"></a>
                    <a href="https://ineuron.ai/"><img src="https://img.shields.io/badge/Hypothesis_Testing-iNeuron-rgb(234, 170, 46)" alt="iNeuron Certification"></a>
                    <a href="https://ineuron.ai/"><img src="https://img.shields.io/badge/Time_Series_Forecasting-iNeuron-rgb(234, 170, 46)" alt="iNeuron Certification"></a>
                    <a href="https://drive.google.com/file/d/1HiF2sMnBOb9v69OpGgHzb68rnBvs3ntJ/view?usp=sharing"><img src="https://img.shields.io/badge/TATA_Data_Viz._Simulation-Forage-rgb(0, 30, 55)" alt="Forage TATA"></a>
                    <a href="https://drive.google.com/file/d/1sFSUuOVJk0wOCTzoPA790-Tgg56ktOYE/view?usp=sharing"><img src="https://img.shields.io/badge/Deloitte_Data_Analysis_Simulation-Forage-rgb(0, 30, 55)" alt="Forage Deloitte"></a>
                </div>
            </section>
        </main>
    </div>

</body>
</html>
