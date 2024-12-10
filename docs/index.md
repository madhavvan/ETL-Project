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
            font-family: 'Georgia', serif;
            background-color: #E6E6FA; /* Lavender background */
            margin: 0;
            padding: 0;
            line-height: 1.6;
            color: #333;
            overflow-x: hidden; /* Prevent horizontal scrolling */
        }

        /* Wavy Border Effect */
        .wavy-border {
            position: relative;
            padding: 40px 20px;
            margin: 20px auto;
            background: #FFFFFF; /* White background for content */
            border-radius: 15px;
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.1); /* Subtle shadow */
            max-width: 1200px;
            z-index: 1;
        }

        .wavy-border::before,
        .wavy-border::after {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            z-index: -1;
            background: linear-gradient(90deg, #4B0082, #8A2BE2);
            mask-image: repeating-radial-gradient(circle, transparent, transparent 10px, white 10px, white 20px);
            -webkit-mask-image: repeating-radial-gradient(circle, transparent, transparent 10px, white 10px, white 20px);
            border-radius: 15px;
        }

        .wavy-border::before {
            top: -10px;
            left: -10px;
            right: -10px;
            bottom: -10px;
        }

        .wavy-border::after {
            top: -15px;
            left: -15px;
            right: -15px;
            bottom: -15px;
            opacity: 0.7;
        }

        /* Navigation Bar */
        nav {
            background: #4B0082; /* Deep violet */
            padding: 15px;
            text-align: center;
            position: sticky;
            top: 0;
            z-index: 10;
            box-shadow: 0 5px 10px rgba(0, 0, 0, 0.1); /* Subtle shadow */
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
            color: #FFD700; /* Gold hover effect */
        }

        /* Header Styles */
        h1 {
            font-size: 2.8rem;
            color: #4B0082;
            text-align: center;
            margin-bottom: 20px;
            text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.2);
        }

        h2 {
            font-size: 2rem;
            color: #8A2BE2;
            text-align: center;
            margin-bottom: 20px;
        }

        p {
            font-size: 1.2rem;
            color: #333;
            text-align: justify;
            line-height: 1.8;
        }

        /* Footer */
        footer {
            text-align: center;
            padding: 20px;
            background: #4B0082; /* Deep violet */
            color: #FFFFFF;
            margin-top: 40px;
            font-size: 1rem;
            border-radius: 0 0 10px 10px;
        }
    </style>
</head>
<body>


    <footer>
        <p>&copy; 2024 ETL Project. All Rights Reserved.</p>
    </footer>

</body>
</html>

