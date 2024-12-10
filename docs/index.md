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


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ETL Project Overview</title>

    <style>
        /* General Styling */
        body {
            font-family: 'Arial', sans-serif;
            background-color: #E6E6FA; /* Lavender background */
            margin: 0;
            padding: 0;
            color: #333;
            line-height: 1.6;
        }

        /* Header Section */
        header {
            background: linear-gradient(45deg, #8A2BE2, #9370DB, #E6E6FA); /* Rich lavender gradient */
            color: white;
            text-align: center;
            padding: 60px 20px;
            box-shadow: 0 8px 16px rgba(0, 0, 0, 0.2);
        }

        header h1 {
            font-size: 3.5em;
            margin: 0;
            text-shadow: 2px 2px 6px rgba(0, 0, 0, 0.3);
        }

        header p {
            font-size: 1.5em;
            margin-top: 10px;
            color: rgba(255, 255, 255, 0.9);
        }

        nav {
            background-color: #9370DB; /* Medium lavender */
            padding: 10px;
            text-align: center;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-size: 1.2em;
            font-weight: bold;
            transition: color 0.3s ease;
        }

        nav a:hover {
            color: #FFD700; /* Gold on hover */
        }

        /* Highlight Section */
        .highlight-section {
            background: linear-gradient(45deg, #9370DB, #E6E6FA); /* Subtle lavender gradient */
            color: #333;
            padding: 50px 20px;
            text-align: center;
            margin: 50px auto;
            border-radius: 20px;
            width: 90%;
            max-width: 1200px;
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.2);
        }

        .highlight-section h2 {
            font-size: 2.5em;
            margin-bottom: 10px;
            color: #4B0082; /* Deep lavender */
        }

        .highlight-section p {
            font-size: 1.3em;
            color: #555;
        }

        /* Team Section */
        .team-container {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 30px;
            padding: 40px;
        }

        .team-member {
            background: white;
            border-radius: 15px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.15);
            overflow: hidden;
            text-align: center;
            padding: 20px;
            width: 280px;
        }

        .team-member img {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            object-fit: cover;
            margin: 20px 0;
            border: 4px solid #8A2BE2; /* Lavender border */
        }

        .team-member h3 {
            color: #4B0082;
            font-size: 1.5em;
            margin: 10px 0;
        }

        .team-member p {
            font-size: 1.1em;
            color: #666;
        }

        /* Footer Section */
        footer {
            background: #4B0082;
            color: white;
            text-align: center;
            padding: 20px;
            font-size: 1.2em;
            margin-top: 50px;
        }

        footer p {
            margin: 0;
        }
    </style>
</head>
<body>

    <!-- Header Section -->
    <header>
        <h1>ETL Project Overview</h1>
        <p>Welcome to the ETL Project Website - Demonstrating ETL pipelines using Python and FHIR APIs</p>
    </header>

    <!-- Navigation Bar -->
    <nav>
        <a href="index.md">Home</a> | 
        <a href="bpmn.md">BPMN Model</a> | 
        <a href="use_case.md">Use Case Model</a> | 
        <a href="etl_pipeline.md">ETL Pipeline</a> | 
        <a href="insights.md">Insights</a> | 
        <a href="team.md">Team Contributions</a> | 
        <a href="about.md">About</a>
    </nav>

    <!-- Footer Section -->
    <footer>
        <p>&copy; 2024 ETL Project. All Rights Reserved.</p>
    </footer>

</body>
</html>
