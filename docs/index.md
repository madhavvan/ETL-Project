# ETL Project Overview

Welcome to the ETL project website. This project demonstrates the ETL pipeline using Python and FHIR APIs.




[Home](index.md) | [BPMN Model](bpmn.md) | [Use Case Model](use_case.md) | [ETL Pipeline](etl_pipeline.md) | [Insights](insights.md) | [Team Contributions](team.md) | [About](about.md)
=======




## ETL Project Documentation
My ETL Project aims to get data from the OpenEMR FHIR API, does some transformation and then load the data to another FHIR API

## The purpose of the ETL pipeline
"Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo. Nemo enim ipsam voluptatem quia voluptas sit aspernatur aut odit aut fugit, sed quia consequuntur magni dolores eos qui ratione voluptatem sequi nesciunt. Neque porro quisquam est, qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit, sed quia non numquam eius modi tempora incidunt ut labore et dolore magnam aliquam quaerat voluptatem. Ut enim ad minima veniam, quis nostrum exercitationem ullam corporis suscipit laboriosam, nisi ut aliquid ex ea commodi consequatur? Quis autem vel eum iure reprehenderit qui in ea voluptate velit esse quam nihil molestiae consequatur, vel illum qui dolorem eum fugiat quo voluptas nulla pariatur?"

## The key tools and technologies used
At vero eos et accusamus et iusto odio dignissimos ducimus qui blanditiis praesentium voluptatum deleniti atque corrupti quos dolores et quas molestias excepturi sint occaecati cupiditate non provident, similique sunt in culpa qui officia deserunt mollitia animi, id est laborum et dolorum fuga. Et harum quidem rerum facilis est et expedita distinctio. Nam libero tempore, cum soluta nobis est eligendi optio cumque nihil impedit quo minus id quod maxime placeat facere possimus, omnis voluptas assumenda est, omnis dolor repellendus. Temporibus autem quibusdam et aut officiis debitis aut rerum necessitatibus saepe eveniet ut et voluptates repudiandae sint et molestiae non recusandae. Itaque earum rerum hic tenetur a sapiente delectus, ut aut reiciendis voluptatibus maiores alias consequatur aut perferendis doloribus asperiores repellat."

## Summary of the deliverables
On the other hand, we denounce with righteous indignation and dislike men who are so beguiled and demoralized by the charms of pleasure of the moment, so blinded by desire, that they cannot foresee the pain and trouble that are bound to ensue; and equal blame belongs to those who fail in their duty through weakness of will, which is the same as saying through shrinking from toil and pain.
These cases are perfectly simple and easy to distinguish.
In a free hour, when our power of choice is untrammelled and when nothing prevents our being able to do what we like best, every pleasure is to be welcomed and every pain avoided. But in certain circumstances and owing to the claims of duty or the obligations of business it will frequently occur that pleasures have to be repudiated and annoyances accepted. The wise man therefore always holds in these matters to this principle of selection: he rejects pleasures to secure other greater pleasures, or else he endures pains to avoid worse pains.



<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ETL Project Overview</title>

    <style>
        /* General Styling */
        body {
            font-family: 'Georgia', serif; /* Stylish font */
            background-color: #E6E6FA; /* Light Lavender background */
            margin: 0;
            padding: 0;
            line-height: 1.6;
            color: #000000;
            position: relative;
            overflow-x: hidden; /* Prevent horizontal scrolling */
        }

        /* Violet Borders */
        body::before,
        body::after {
            content: '';
            position: absolute;
            width: 100%;
            height: 20px;
            background: linear-gradient(90deg, #4B0082, #8A2BE2); /* Violet Gradient */
            z-index: 1;
        }

        body::before {
            top: 0;
        }

        body::after {
            bottom: 0;
        }

        /* Content Styling */
        h1 {
            font-size: 3rem;
            color: #4B0082; /* Deep Violet */
            text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.3); /* Subtle shadow for headers */
            text-align: center;
            margin-top: 40px;
        }

        h2, h3 {
            color: #4B0082;
            font-size: 2rem;
            text-align: center;
            margin: 20px 0;
        }

        p {
            font-size: 1.2rem;
            color: #333333; /* Darker text for readability */
            margin: 20px auto;
            text-align: center;
            max-width: 900px;
        }

        /* Decorative Border for Content Sections */
        .content {
            max-width: 1100px;
            margin: 40px auto;
            padding: 30px;
            background: rgba(255, 255, 255, 0.9); /* Slightly transparent white */
            border-radius: 15px;
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.3);
            border: 5px solid #4B0082; /* Violet border */
        }

        /* Navigation Bar */
        nav {
            background: #4B0082; /* Deep Violet */
            padding: 10px 0;
            text-align: center;
            position: sticky;
            top: 0;
            z-index: 10;
            box-shadow: 0 5px 10px rgba(0, 0, 0, 0.2);
        }

        nav a {
            color: #FFFFFF;
            text-decoration: none;
            margin: 0 15px;
            font-size: 1.2rem;
            font-weight: bold;
            transition: color 0.3s ease;
        }

        nav a:hover {
            color: #FFD700; /* Gold on hover */
        }

        /* Additional Styling for Footer */
        footer {
            text-align: center;
            padding: 20px;
            background: #4B0082; /* Deep Violet */
            color: #FFFFFF;
            position: relative;
            margin-top: 40px;
        }

        footer p {
            margin: 0;
            font-size: 1rem;
        }
    </style>
</head>
<body>

    <nav>
        <a href="#">Home</a>
        <a href="#">BPMN Model</a>
        <a href="#">Use Case Model</a>
        <a href="#">ETL Pipeline</a>
        <a href="#">Insights</a>
        <a href="#">Team Contributions</a>
        <a href="#">About</a>
    </nav>

    <div class="content">
        <h1>ETL Project Overview</h1>
        <p>Welcome to the ETL project website. This project demonstrates the ETL pipeline using Python and FHIR APIs.</p>
    </div>

    <div class="content">
        <h2>ETL Project Documentation</h2>
        <p>My ETL Project aims to get data from the OpenEMR FHIR API, does some transformation, and then loads the data to another FHIR API.</p>
    </div>

    <footer>
        <p>&copy; 2024 ETL Project. All Rights Reserved.</p>
    </footer>
</body>
</html>


