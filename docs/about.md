# ETL Project Overview


[Home](index.md) | [BPMN Model](bpmn.md) | [Use Case Model](use_case.md) | [ETL Pipeline](etl_pipeline.md) | [Insights](insights.md) | [Team Contributions](team.md) | [About](about.md)
=======




<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About - ETL Project</title>

    <style>
        /* General Styling */
        body {
            font-family: 'Arial', sans-serif;
            background: linear-gradient(120deg, #ffe6e6, #ffcccc); /* Light red gradient */
            margin: 0;
            padding: 0;
            color: #333;
            overflow-x: hidden;
        }

        h1 {
            color: #ff4500; /* Fiery orange-red */
            margin: 20px 0;
            font-size: 3.5rem;
            text-shadow: 4px 4px 6px rgba(255, 69, 0, 0.7); /* Fiery effect */
            font-family: 'Impact', sans-serif;
            text-transform: uppercase;
            position: relative;
        }

        h1::after {
            content: "🔥";
            font-size: 4rem;
            position: absolute;
            right: -50px;
            top: 10px;
            animation: bounce 2s infinite;
        }

        @keyframes bounce {
            0%, 100% {
                transform: translateY(0);
            }
            50% {
                transform: translateY(-10px);
            }
        }

        .background-graphic {
            position: absolute;
            top: 10%;
            left: -50px;
            width: 150px;
            height: 150px;
            background: rgba(255, 69, 0, 0.1);
            border-radius: 50%;
            filter: blur(50px);
        }

        .background-graphic.secondary {
            top: 70%;
            left: 70%;
            width: 200px;
            height: 200px;
        }

        .team-container {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 30px;
            padding: 60px 20px;
            position: relative;
            z-index: 10;
        }

        .team-member {
            background: #fff;
            border-radius: 15px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            overflow: hidden;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
            width: 260px;
            text-align: center;
            position: relative;
        }

        .team-member:hover {
            transform: translateY(-10px);
            box-shadow: 0 8px 16px rgba(0, 0, 0, 0.3);
        }

        .team-member img {
            width: 150px;
            height: 150px;
            border-radius: 50%; /* Circular images */
            object-fit: cover;
            margin-top: 20px;
            border: 4px solid #ff9999; /* Light red border around images */
        }

        .team-member h3 {
            font-size: 18px;
            margin: 15px 0 5px;
            color: #ff4500; /* Fiery red-orange for names */
        }

        .team-member p {
            font-size: 14px;
            margin: 0 0 15px;
            color: #666;
        }

        .team-member .icon {
            font-size: 2rem;
            color: #ff4500;
            margin-top: 10px;
        }

        /* Footer Styling */
        footer {
            margin-top: 20px;
            padding: 10px 0;
            background: #ff9999;
            color: #fff;
            text-align: center;
            font-size: 14px;
        }
    </style>
</head>
<body>

    <div class="background-graphic"></div>
    <div class="background-graphic secondary"></div>

    <h1>Meet Our Team</h1>
    <div class="team-container">
        <div class="team-member">
            <img src="img_2.png" alt="Dr Yashitha Raga">
            <h3>Dr Yashitha Raga</h3>
            <p>ETL Developer</p>
            <div class="icon">💻</div>
        </div>

        <div class="team-member">
            <img src="img_3.png" alt="Dr Aishwarya">
            <h3>Dr Aishwarya</h3>
            <p>ETL Developer</p>
            <div class="icon">📊</div>
        </div>

        <div class="team-member">
            <img src="img_4.png" alt="Venu Madhav Pentala">
            <h3>Venu Madhav Pentala</h3>
            <p>ETL Developer</p>
            <div class="icon">🔍</div>
        </div>

        <div class="team-member">
            <img src="img_5.png" alt="Dr Pallavi Vandanapu">
            <h3>Dr Pallavi Vandanapu</h3>
            <p>ETL Developer</p>
            <div class="icon">🚀</div>
        </div>
    </div>

    <footer>
        © 2024 ETL Project Team. All Rights Reserved.
    </footer>

</body>
</html>




 