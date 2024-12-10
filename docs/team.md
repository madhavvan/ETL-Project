# ETL Project Overview

Welcome to the ETL project website. This project demonstrates the ETL pipeline using Python and FHIR APIs.




[Home](index.md) | [BPMN Model](bpmn.md) | [Use Case Model](use_case.md) | [ETL Pipeline](etl_pipeline.md) | [Insights](insights.md) | [Team Contributions](team.md) | [About](about.md)
=======

---

## Team Contributions

<div style="background: linear-gradient(135deg, #FFA500, #FF6347); color: #000000; border-radius: 20px; padding: 30px; margin: 20px auto; width: 90%; max-width: 1200px; box-shadow: 0 15px 25px rgba(0, 0, 0, 0.4), inset 0 -5px 10px rgba(255, 255, 255, 0.2); font-family: 'Georgia', serif; text-align: center; font-size: 1.2rem;">
    <h3 style="color: #000000; text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.5);">Project Team and Roles</h3>
    <table style="width: 100%; border-collapse: collapse; margin: 20px 0; color: #000000; box-shadow: 0 8px 16px rgba(0, 0, 0, 0.4);">
        <thead>
            <tr style="background-color: #FFD700; color: #000000; box-shadow: 0 4px 6px rgba(0, 0, 0, 0.2);">
                <th style="border: 2px solid #000000; padding: 15px; font-size: 1.1rem; text-shadow: 1px 1px 3px rgba(255, 255, 255, 0.5);">Team Member</th>
                <th style="border: 2px solid #000000; padding: 15px; font-size: 1.1rem; text-shadow: 1px 1px 3px rgba(255, 255, 255, 0.5);">Role</th>
                <th style="border: 2px solid #000000; padding: 15px; font-size: 1.1rem; text-shadow: 1px 1px 3px rgba(255, 255, 255, 0.5);">Contributions</th>
                <th style="border: 2px solid #000000; padding: 15px; font-size: 1.1rem; text-shadow: 1px 1px 3px rgba(255, 255, 255, 0.5);">Reflections</th>
            </tr>
        </thead>
        <tbody>
            <tr class="scroll-effect">
                <td style="border: 1px solid #000000; padding: 15px;">Pallavi Vandanapu</td>
                <td style="border: 1px solid #000000; padding: 15px;">Coding Specialist</td>
                <td style="border: 1px solid #000000; padding: 15px;">Completed coding tasks 1 and 2 involving API integration and data processing.</td>
                <td style="border: 1px solid #000000; padding: 15px;">Gained insights into FHIR APIs and real-world data transformation challenges.</td>
            </tr>
            <tr class="scroll-effect">
                <td style="border: 1px solid #000000; padding: 15px;">Venu Madhav Pentala</td>
                <td style="border: 1px solid #000000; padding: 15px;">Website Designer</td>
                <td style="border: 1px solid #000000; padding: 15px;">Designed and implemented the project website with intuitive navigation.</td>
                <td style="border: 1px solid #000000; padding: 15px;">Enhanced web development skills while ensuring project accessibility.</td>
            </tr>
            <tr class="scroll-effect">
                <td style="border: 1px solid #000000; padding: 15px;">Yashita Raga Saranam</td>
                <td style="border: 1px solid #000000; padding: 15px;">BPMN and Coding Specialist</td>
                <td style="border: 1px solid #000000; padding: 15px;">Completed coding tasks 3 and 4, built BPMN model reflecting processes.</td>
                <td style="border: 1px solid #000000; padding: 15px;">Learned about process visualization and multi-tool integration.</td>
            </tr>
            <tr class="scroll-effect">
                <td style="border: 1px solid #000000; padding: 15px;">Haneesha Donepudi</td>
                <td style="border: 1px solid #000000; padding: 15px;">Use Case Model Designer</td>
                <td style="border: 1px solid #000000; padding: 15px;">Created use case models defining system interactions and roles.</td>
                <td style="border: 1px solid #000000; padding: 15px;">Developed clear communication skills for technical concepts.</td>
            </tr>
            <tr class="scroll-effect">
                <td style="border: 1px solid #000000; padding: 15px;">Aishwarya Voraganti</td>
                <td style="border: 1px solid #000000; padding: 15px;">Documentation Specialist</td>
                <td style="border: 1px solid #000000; padding: 15px;">Developed and structured project documentation.</td>
                <td style="border: 1px solid #000000; padding: 15px;">Improved technical writing and organization skills.</td>
            </tr>
        </tbody>
    </table>
</div>

<style>
    /* Scroll Effect */
    .scroll-effect {
        opacity: 0;
        transform: translateY(50px);
        transition: all 0.6s ease-out;
    }

    .scroll-effect.visible {
        opacity: 1;
        transform: translateY(0);
    }
</style>

<script>
    // JavaScript for Scroll Animation
    const scrollElements = document.querySelectorAll(".scroll-effect");

    const elementInView = (el, offset = 100) => {
        const elementTop = el.getBoundingClientRect().top;
        return elementTop <= (window.innerHeight - offset);
    };

    const displayScrollElement = (element) => {
        element.classList.add("visible");
    };

    const hideScrollElement = (element) => {
        element.classList.remove("visible");
    };

    const handleScrollAnimation = () => {
        scrollElements.forEach((el) => {
            if (elementInView(el, 100)) {
                displayScrollElement(el);
            } else {
                hideScrollElement(el);
            }
        });
    };

    window.addEventListener("scroll", () => {
        handleScrollAnimation();
    });

    // Initial check to display elements in view
    handleScrollAnimation();
</script>



<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ETL Project Overview</title>

    <style>
        /* General Styling */
        body {
            font-family: 'Arial', sans-serif;
            background-color: #FFE5B4;  /* Lavender background */
            margin: 0;
            padding: 0;
            line-height: 1.6;
        }
</head>
<body>