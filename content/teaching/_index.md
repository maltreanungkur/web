---
title: "My Page with LaTeX"
math: true
---

<html>
<head>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #1e1e1e;
            color: #ffffff;
            margin: 0;
            padding: 0;
        }
        a {
            color: #00d4ff;
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
        }
        h1, h2, h3 {
            color: #ffcc00;
        }
        .section-header {
            text-align: center;
            font-size: 24px;
            margin: 20px 0;
            font-variant: small-caps;
        }
        .timeline {
            margin: 20px auto;
            padding: 10px;
            max-width: 800px;
            background-color: #2e2e2e;
            border-radius: 8px;
        }
        .timeline-item {
            margin-bottom: 20px;
            padding: 10px;
            background-color: #333;
            border-left: 5px solid #ffcc00;
            border-radius: 5px;
        }
        .timeline-item-header {
            font-weight: bold;
            font-size: 18px;
        }
        .timeline-item-subheader {
            font-style: italic;
            font-size: 14px;
            color: #cccccc;
        }
        .reference {
            margin: 20px;
            padding: 10px;
            border: 1px solid #555;
            background-color: #2e2e2e;
            border-radius: 5px;
        }
    </style>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/KaTeX/0.7.1/katex.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/KaTeX/0.7.1/contrib/auto-render.min.js"></script>
    <script>
        document.addEventListener("DOMContentLoaded", function () {
            renderMathInElement(document.body, {
                delimiters: [
                    {left: "$$", right: "$$", display: true},
                    {left: "\\[", right: "\\]", display: true},
                    {left: "$", right: "$", display: false},
                    {left: "\\(", right: "\\)", display: false}
                ]
            });
        });
    </script>
</head>
<body>
    <div>
        <h1 class="section-header">My Custom Seminar Page</h1>
        <p>Welcome to the seminar on <b>Intersection Homology</b> and <b>Perverse Sheaves</b>. This seminar is based on the book by Kirwan and Wolf.</p>

        <div class="timeline">
            <div class="timeline-item">
                <div class="timeline-item-header">1. Overview Talk</div>
                <div class="timeline-item-subheader">12/01 - Prof. Suresh Nayak</div>
                Notes taken by me (LaTeXed): <a href="./notes/overview.pdf">Overview Talk</a>.
            </div>
            <div class="timeline-item">
                <div class="timeline-item-header">2. Review Talk</div>
                <div class="timeline-item-subheader">19/01 - Prognadipto Majumdar and Eeshan Pandey</div>
                Notes by me (LaTeXed): <a href="./notes/prereq.pdf">Prerequisites</a>.<br>
                <p>In this lecture, we cover prerequisites including a review of singular, simplicial, Borel-Moore (co)homology, and more.</p>
            </div>
            <!-- Add more timeline items as needed -->
        </div>

        <div class="section-header">References</div>
        <div class="reference">
            <ul>
                <li><b>Main Text:</b> <a href="./documents/Frances%20Kirwan,%20Jonathan%20Woolf.pdf">F. Kirwan, J. Woolf, *An Introduction to Intersection Homology Theory*</a></li>
                <li><b>Further Reading:</b>
                    <ul>
                        <li><a href="./documents/Laurenţiu%20G.%20Maxim.pdf">L. G. Maxim, *Intersection Homology & Perverse Sheaves*</a></li>
                        <li><a href="./documents/Stratified%20Morse%20Theory.pdf">M. Goresky, R. MacPherson, *Stratified Morse Theory*</a></li>
                        <!-- Add more references as needed -->
                    </ul>
                </li>
            </ul>
        </div>
    </div>
</body>
</html>
