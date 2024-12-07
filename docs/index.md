
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ETL Project Overview</title>
    <style>
        /* Apply to the container section for ETL Project Overview */
        #etl-project-overview {
            background: linear-gradient(45deg, rgba(255, 0, 150, 0.8), rgba(0, 204, 255, 0.8));
            background-size: 400% 400%;
            animation: gradientAnimation 5s ease infinite;
            padding: 50px;
            border-radius: 10px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
        }

        /* Animation for background gradient */
        @keyframes gradientAnimation {
            0% {
                background-position: 0% 50%;
            }
            50% {
                background-position: 100% 50%;
            }
            100% {
                background-position: 0% 50%;
            }
        }

        /* Highlighting text */
        #etl-project-overview h1 {
            font-size: 36px;
            color: white;
            font-family: 'Arial', sans-serif;
            text-shadow: 3px 3px 5px rgba(0, 0, 0, 0.5);
            letter-spacing: 2px;
        }

        /* Navigation links styling */
        #etl-project-overview a {
            font-size: 18px;
            color: white;
            text-decoration: none;
            font-weight: bold;
            padding: 10px 20px;
            margin: 0 15px;
            transition: all 0.3s ease;
        }

        #etl-project-overview a:hover {
            background-color: rgba(255, 255, 255, 0.2);
            border-radius: 5px;
            transform: scale(1.1);
        }
    </style>
</head>
<body>

    <div id="etl-project-overview">
        <h1>ETL Project Overview</h1>
        <p>Welcome to the ETL project website. This project demonstrates the ETL pipeline using Python and FHIR APIs.</p>

        <p><a href="index.md">Home</a> | <a href="bpmn.md">![img_2.png](img_2.png)</a> | <a href="use_case.md">Use Case Model</a> | <a href="etl_pipeline.md">ETL Pipeline</a> | <a href="insights.md">Insights</a> | <a href="team.md">Team Contributions</a> | <a href="about.md">About</a></p>
    </div>

</body>
</html>


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

    <style>
        /* General Styling */
        body {
            font-family: 'Arial', sans-serif;
            background-color: #E6E6FA;  /* Lavender background */
            margin: 0;
            padding: 0;
            line-height: 1.6;
        }

        /* High-Energy Gradient Section Above the Image */
        .highlight-section {
            background: linear-gradient(45deg, #8A2BE2, #4B0082, #D8BFD8); /* Gradient background */
            color: white;
            padding: 100px 20px;
            text-align: center;
            border-radius: 20px;
            box-shadow: 0 15px 40px rgba(0, 0, 0, 0.3);
            margin: 50px 0;
            position: relative;
            overflow: hidden;
        }

        .highlight-section h1 {
            font-size: 4em;
            font-weight: bold;
            text-transform: uppercase;
            text-shadow: 0px 0px 15px rgba(138, 43, 226, 0.8); /* Neon glow effect */
            margin-bottom: 20px;
        }

        .highlight-section p {
            font-size: 1.2em;
            color: rgba(255, 255, 255, 0.8);
            line-height: 1.8;
            text-shadow: 0 0 10px rgba(0, 0, 0, 0.5);
        }

        .highlight-section .button {
            background-color: #8A2BE2;
            color: white;
            padding: 12px 30px;
            border: none;
            border-radius: 30px;
            font-size: 1.2em;
            cursor: pointer;
            text-transform: uppercase;
            margin-top: 30px;
            transition: background-color 0.3s ease, transform 0.3s ease;
        }

        .highlight-section .button:hover {
            background-color: #4B0082; /* Darker purple on hover */
            transform: scale(1.1);
        }

        /* Image Section - Full Width (Removed the image) */
        .image-section {
            background: url('https://via.placeholder.com/1500x500') center/cover no-repeat;
            width: 100%;  /* Full width of the page */
            height: 400px;
            border-radius: 10px;
            margin-top: -50px;  /* Pull image up to overlap the highlighted section */
        }

        /* Animated Floating Effect */
        .highlight-section::after {
            content: '';
            position: absolute;
            top: -20px;
            left: 50%;
            transform: translateX(-50%);
            width: 100px;
            height: 100px;
            border-radius: 50%;
            background-color: rgba(255, 255, 255, 0.1);
            animation: float 4s ease-in-out infinite;
        }

        /* Floating Animation */
        @keyframes float {
            0% {
                transform: translateY(0) translateX(-50%);
            }
            50% {
                transform: translateY(-30px) translateX(-50%);
            }
            100% {
                transform: translateY(0) translateX(-50%);
            }
        }

        /* Card Design */
        .card {
            background-color: white;
            border-radius: 15px;
            padding: 20px;
            margin: 30px auto;
            width: 80%;
            max-width: 700px;
            box-shadow: 0px 10px 20px rgba(0, 0, 0, 0.15);
            text-align: center;
        }

        .card h3 {
            font-size: 2em;
            color: #8A2BE2;
            margin-bottom: 20px;
        }

        .card p {
            font-size: 1.2em;
            color: #333;
            margin-bottom: 20px;
        }

        .card .button {
            background-color: #8A2BE2;
            color: white;
            padding: 12px 30px;
            border: none;
            border-radius: 30px;
            font-size: 1.2em;
            cursor: pointer;
            text-transform: uppercase;
            transition: background-color 0.3s ease, transform 0.3s ease;
        }

        .card .button:hover {
            background-color: #4B0082; /* Darker purple on hover */
            transform: scale(1.1);
        }

        /* Footer Section */
        footer {
            background-color: #4B0082;
            color: white;
            padding: 20px;
            text-align: center;
            font-size: 1.2em;
            margin-top: 50px;
        }

    </style>
</head>
<body>

    <!-- High-Energy Highlight Section Above the Image -->
    <div class="highlight-section">
        <h1>ETL Process Overview</h1>
        <p>This diagram illustrates the extraction, transformation, and loading (ETL) process, detailing key stages and decision points.</p>
        <button class="button">Learn More</button>
    </div>


    <!-- Card with Professional Background -->
    <div class="card">
        <h3>ETL Process Overview</h3>
        <p>This diagram illustrates the ETL process from extraction to loading, with decision points and key tasks highlighted.</p>
        <button class="button">Learn More</button>
    </div>

    <!-- Another Card -->
    <div class="card">
        <h3>Team Contributions</h3>
        <p>Explore the contributions of each team member in making this ETL project successful.</p>
        <button class="button">View Team</button>
    </div>

    <!-- Footer Section -->
    <footer>
        <p>&copy; 2024 ETL Project. All Rights Reserved.</p>
    </footer>

</body>
</html>
