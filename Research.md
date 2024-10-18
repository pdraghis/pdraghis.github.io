<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Page Title</title>
    
    <!-- MathJax for LaTeX rendering -->
    <script src="https://polyfill.io/v3/polyfill.min.js?features=es6"></script>
    <script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>

    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }

        .content {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
            margin: 20px;
        }

        .text-block {
            width: 45%;
            margin: 20px;
            text-align: justify;
        }

        .figure-block {
            width: 45%;
            margin: 20px;
        }

        .figure-block img {
            max-width: 100%;
            height: auto;
            border-radius: 10px;
        }

        .block-container {
            display: flex;
            align-items: center;
            margin-bottom: 40px;
        }

        .block-container:nth-child(even) .figure-block {
            order: -1; /* Reverse order for alternating layout */
        }

        h2 {
            text-align: center;
            margin-top: 50px;
        }

        @media (max-width: 768px) {
            .block-container {
                flex-direction: column;
            }

            .text-block, .figure-block {
                width: 90%;
            }
        }
    </style>
</head>
<body>

    <h1>Page Title</h1>

    <div class="content">
        <!-- Block 1 -->
        <div class="block-container">
            <div class="text-block">
                <h2>Block 1 Title</h2>
                <p>Here is a block of text that includes some LaTeX formulas, such as inline \( E = mc^2 \), and block LaTeX equations:</p>
                <p>
                    \[
                    \int_0^\infty e^{-x^2} dx = \frac{\sqrt{\pi}}{2}
                    \]
                </p>
            </div>
            <div class="figure-block">
                <img src="path-to-image1.jpg" alt="Placeholder for Figure 1">
            </div>
        </div>

        <!-- Block 2 -->
        <div class="block-container">
            <div class="text-block">
                <h2>Block 2 Title</h2>
                <p>Another text block with LaTeX content, like the famous quadratic equation:</p>
                <p>
                    \[
                    x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}
                    \]
                </p>
            </div>
            <div class="figure-block">
                <img src="path-to-image2.jpg" alt="Placeholder for Figure 2">
            </div>
        </div>

        <!-- Add more blocks as needed -->
    </div>

</body>
</html>
