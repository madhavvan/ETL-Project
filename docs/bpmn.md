# ETL Project Overview

Welcome to the ETL project website. This project demonstrates the ETL pipeline using Python and FHIR APIs.




[Home](index.md) | [BPMN Model](bpmn.md) | [Use Case Model](use_case.md) | [ETL Pipeline](etl_pipeline.md) | [Insights](insights.md) | [Team Contributions](team.md) | [About](about.md)
=======


<img alt="img.png" height="500" src="img.png" width="600"/>

The diagram illustrates the ETL process from extraction to loading, with decision points and key tasks highlighted.
[Back to Home](index.md)


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
            background: url('https://via.placeholder.com/1000x500') center/cover no-repeat;
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
            width: 100%;
            max-width: 900px;
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
