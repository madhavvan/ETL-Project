# ETL Project Overview

Welcome to the ETL project website. This project demonstrates the ETL pipeline using Python and FHIR APIs.




[Home](index.md) | [BPMN Model](bpmn.md) | [Use Case Model](use_case.md) | [ETL Pipeline](etl_pipeline.md) | [Insights](insights.md) | [Team Contributions](team.md) | [About](about.md)
=======

![img_2.png](img_2.png)

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

    <!-- Inline CSS for Lavender Theme with Card Design -->
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #E6E6FA;  /* Lavender background */
            color: #4B0082;  /* Indigo text */
            margin: 0;
            padding: 0;
            line-height: 1.6;
        }

        h1 {
            color: #8A2BE2;  /* Purple */
            text-align: center;
            margin-top: 50px;
        }

        nav a {
            text-decoration: none;
            color: #4B0082;
            margin: 0 15px;
            font-weight: bold;
        }

        nav a:hover {
            color: #8A2BE2;
        }

        /* Card Design */
        .card {
            background-color: white;
            border-radius: 10px;
            padding: 20px;
            margin: 20px auto;
            width: 80%;
            max-width: 600px;
            box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.1);
        }

        .card img {
            width: 100%;
            border-radius: 10px;
        }

        .card h3 {
            color: #8A2BE2;
            text-align: center;
        }

        .card p {
            font-size: 1.2em;
            color: #333;
        }

        .button {
            background-color: #8A2BE2;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            text-align: center;
            cursor: pointer;
            display: block;
            margin: 20px auto;
        }

        .button:hover {
            background-color: #4B0082;  /* Darker purple on hover */
        }
    </style>
</head>
<body>
    <h1>ETL Project Overview</h1>

    <nav>
        <a href="#">Home</a> | 
        <a href="#">BPMN Model</a> | 
        <a href="#">Use Case Model</a> | 
        <a href="#">ETL Pipeline</a> | 
        <a href="#">Insights</a> | 
        <a href="#">Team Contributions</a> | 
        <a href="#">About</a>
    </nav>

    <!-- Card with Content -->
    <div class="card">
        <img src="{{ url_for('static', filename='img.png') }}" alt="ETL Process Diagram">
        <h3>ETL Process Overview</h3>
        <p>This diagram illustrates the ETL process from extraction to loading, with decision points and key tasks highlighted.</p>
        <button class="button">Learn More</button>
    </div>

    <!-- Another Card Example -->
    <div class="card">
        <h3>Team Contributions</h3>
        <p>Explore the contributions of each team member in making this ETL project successful.</p>
        <button class="button">View Team</button>
    </div>

</body>
</html>
