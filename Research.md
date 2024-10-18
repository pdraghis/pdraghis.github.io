<!-- <!DOCTYPE html>  -->
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Research</title>



    
    <!-- MathJax for LaTeX rendering -->
    <script src="https://polyfill.io/v3/polyfill.min.js?features=es6"></script>
    <script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>

    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }

         <!--.content {
            display: flex;
            max-width: none;  /* Remove the maximum width constraint */
            width: 300%;      /* Set width to full screen */
            flex-wrap: wrap;
            justify-content: space-around;
            margin: 20px auto;
            align-items: center;
        }  -->
        .content {
            display: flex;
            max-width: none;
            width: 300%;           /* Keep the wide width */
            flex-wrap: wrap;
            justify-content: center;  /* Center items within the flex container */
            margin: 0;                /* Reset margin */
            position: relative;        /* Make positioning easier */
            left: -50%;                 /* Move the content halfway across the page */
            align-items: center;
        }

        .text-block {
            width: 75%;
            margin: 20px;
            max-width: none; * Remove any existing width constraints */
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

    <h1>Research - changed</h1>

    <div class="content">
        <!-- Block 1 -->
        <div class="block-container">
            <div class="text-block">
                <h2>A Systematic View of Ten New Black Hole Spins</h2>
                <p>The launch of NuSTAR and the increasing number of binary black hole (BBH) mergers detected through gravitational wave observations have exponentially advanced our understanding of BHs. Despite the simplicity owed to being fully described by their mass and angular momentum, BHs have remained mysterious laboratories that probe the most extreme environments in the universe. While significant progress has been made in the recent decade, the distribution of spin in BHs has not yet been understood. In this work, we provide a systematic analysis of all known BHs in X-ray binary systems (XBs) that have previously been observed by NuSTAR, but have not yet had a spin measurement made using the "relativistic reflection" method obtained from those data. By looking at all the available archival NuSTAR data of these sources, we measure 10 new BH spins: IGR J17454-2919 -  \(a=0.97^{+0.03}_{−0.17}\);  GRS 1758-258 -  \(a=0.991^{+0.007}_{−0.019}\);  MAXI J1727-203 -  \(a=0.986^{+0.012}_{−0.159}\);  MAXI J0637-430 - \(a = 0.97 \pm 0.02\); Swift J1753.5-0127 -  \(a=0.997^{+0.001}_{−0.003}\);  V4641 Sgr -  \(a=0.86^{+0.04}_{−0.06}\);  4U 1543-47 -  \(a=0.98^{+0.01}_{−0.02}\);  4U 1957+11 -  \(a=0.95^{+0.02}_{−0.04}\);  H 1743-322 -  \(a=0.98^{+0.01}_{−0.02}\); and MAXI J1820+070 -  \(a=0.988^{+0.006}_{−0.028}\)  (all uncertainties are at the 1\(\sigma\) confidence level). We discuss the implications of our measurements on the entire distribution of stellar-mass BH spins in XBs, and we compare them with the spin distribution in BBHs, finding that the two distributions are clearly in disagreement. Additionally, we discuss the implications of this work on our understanding of how the "relativistic reflection" spin measurement technique works, and discuss possible sources of systematic uncertainty that can bias our measurements.</p>
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
