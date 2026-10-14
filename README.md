<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ergonomic Enhanced Spoon | Documentation</title>
    <style>
        :root {
            --bg-color: #0f1115;
            --card-bg: #1a1d24;
            --text-main: #f0f2f5;
            --text-muted: #9ca3af;
            --accent: #d4a373;
        }
        
        body {
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
            background-color: var(--bg-color);
            color: var(--text-main);
            margin: 0;
            padding: 0;
            line-height: 1.6;
        }

        header {
            background: linear-gradient(135deg, #1a1d24 0%, #111318 100%);
            border-bottom: 1px solid #2a2e39;
            padding: 4rem 2rem;
            text-align: center;
        }

        h1 {
            font-size: 2.5rem;
            margin: 0 0 0.5rem 0;
            color: #ffffff;
        }

        .subtitle {
            font-size: 1.2rem;
            color: var(--accent);
            margin-bottom: 1.5rem;
        }

        .founders {
            font-size: 1rem;
            color: var(--text-muted);
            background: rgba(255, 255, 255, 0.05);
            display: inline-block;
            padding: 0.5rem 1.5rem;
            border-radius: 50px;
            border: 1px solid rgba(255, 255, 255, 0.1);
        }

        .container {
            max-width: 900px;
            margin: 3rem auto;
            padding: 0 1.5rem;
        }

        section {
            background: var(--card-bg);
            border: 1px solid #2a2e39;
            border-radius: 12px;
            padding: 2.5rem;
            margin-bottom: 2rem;
            box-shadow: 0 10px 30px rgba(0,0,0,0.5);
        }

        h2 {
            font-size: 1.5rem;
            margin-top: 0;
            border-bottom: 2px solid var(--accent);
            padding-bottom: 0.5rem;
            display: inline-block;
        }

        p, li {
            color: var(--text-muted);
        }

        ul {
            padding-left: 1.2rem;
        }

        li {
            margin-bottom: 0.5rem;
        }

        .gallery-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
            gap: 1.5rem;
            margin-top: 1.5rem;
        }

        .media-card {
            background: #111318;
            border: 1px solid #2a2e39;
            border-radius: 8px;
            overflow: hidden;
            text-align: center;
        }

        .media-card img, .media-card video {
            width: 100%;
            height: auto;
            display: block;
        }

        .media-caption {
            padding: 0.75rem;
            font-size: 0.9rem;
            color: var(--text-muted);
        }

        footer {
            text-align: center;
            padding: 2rem;
            color: var(--text-muted);
            font-size: 0.9rem;
            border-top: 1px solid #2a2e39;
        }
    </style>
</head>
<body>

    <header>
        <h1>🥄 Ergonomic Enhanced Spoon (EES)</h1>
        <div class="subtitle">Next-Generation 3D-Modelled Adaptive Cutlery</div>
        <div class="founders">Created by <strong>E</strong> &amp; <strong>Z</strong></div>
    </header>

    <div class="container">
        <section>
            <h2>Overview</h2>
            <p>The Ergonomic Enhanced Spoon (EES) is an advanced adaptive utensil designed for ultimate grip stability, comfort, and precise balance. Built using precision CAD workflows and multi-layered grip mechanics, the product integrates a custom-contoured handle optimized for users requiring enhanced support.</p>
        </section>

        <section>
            <h2>Key Product Features</h2>
            <ul>
                <li><strong>Ergonomic Contour Handle:</strong> Features a specialized molded grip body for a secure, anti-slip hold.</li>
                <li><strong>Balanced Weight Distribution:</strong> Engineered to reduce wrist fatigue and maximize control during usage.</li>
                <li><strong>Precision 3D Model:</strong> Fully optimized for 3D printing and manufacturing workflows.</li>
            </ul>
        </section>

        <section>
            <h2>Product &amp; 3D Gallery</h2>
            <p>Visual documentation showcasing the physical assembly, studio isolation, and 3D design iterations:</p>
            
            <div class="gallery-grid">
                <!-- Image 1 -->
                <div class="media-card">
                    <img src="spoon-isolated.jpg" alt="Ergonomic Spoon Studio Render">
                    <div class="media-caption">Studio Isolated Render</div>
                </div>

                <!-- Image 2 -->
                <div class="media-card">
                    <img src="spoon-hand.jpg" alt="Ergonomic Spoon Hand Grip">
                    <div class="media-caption">Hand Grip Ergonomics</div>
                </div>

                <!-- Video Showcase -->
                <div class="media-card">
                    <video autoplay loop muted playsinline>
                        <source src="tripo-showcase.mp4" type="video/mp4">
                        Your browser does not support the video tag.
                    </video>
                    <div class="media-caption">3D Model Turntable Showcase</div>
                </div>
            </div>
        </section>
    </div>

    <footer>
        <p>&copy; 2026 E &amp; Z. Hosted on GitHub Pages.</p>
    </footer>

</body>
</html>
