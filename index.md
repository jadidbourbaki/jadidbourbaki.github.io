<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hayder Tirmazi - Mathematician & Cryptographer</title>
    <style>
        :root {
            --primary-color: #2c3e50;
            --accent-color: #3498db;
            --background-color: #f9fafb;
            --text-color: #2c3e50;
            --paper-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.1), 0 2px 4px -1px rgba(0, 0, 0, 0.06);
        }

        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, sans-serif;
            line-height: 1.6;
            color: var(--text-color);
            background-color: var(--background-color);
            margin: 0;
            padding: 0;
        }

        .container {
            max-width: 800px;
            margin: 2rem auto;
            padding: 2rem;
            background: white;
            border-radius: 8px;
            box-shadow: var(--paper-shadow);
        }

        .header {
            margin-bottom: 2rem;
            padding-bottom: 1rem;
            border-bottom: 2px solid #eee;
        }

        h1 {
            font-size: 2.5rem;
            color: var(--primary-color);
            margin: 0;
            font-weight: 700;
        }

        h3 {
            color: var(--primary-color);
            font-size: 1.5rem;
            margin: 2rem 0 1rem;
            padding-bottom: 0.5rem;
            border-bottom: 2px solid #eee;
        }

        .role {
            font-size: 1.25rem;
            color: #666;
            margin: 0.5rem 0;
        }

        a {
            color: var(--accent-color);
            text-decoration: none;
            transition: color 0.2s ease;
        }

        a:hover {
            color: #2980b9;
            text-decoration: underline;
        }

        .publications {
            list-style: none;
            padding: 0;
        }

        .publications li {
            margin-bottom: 1.5rem;
            padding: 1rem;
            background: #f8f9fa;
            border-radius: 6px;
            transition: transform 0.2s ease;
        }

        .publications li:hover {
            transform: translateX(5px);
        }

        .bibtex-button {
            display: inline-block;
            padding: 0.25rem 0.5rem;
            font-size: 0.875rem;
            color: #666;
            background: #fff;
            border: 1px solid #ddd;
            border-radius: 4px;
            cursor: pointer;
            margin-left: 0.5rem;
        }

        .bibtex-button:hover {
            background: #f0f0f0;
            text-decoration: none;
        }

        .projects {
            list-style: none;
            padding: 0;
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 1rem;
        }

        .projects li {
            padding: 1rem;
            background: #f8f9fa;
            border-radius: 6px;
            transition: transform 0.2s ease;
        }

        .projects li:hover {
            transform: translateY(-2px);
        }

        .contact {
            margin-top: 2rem;
            padding-top: 1rem;
            border-top: 2px solid #eee;
        }

        .social-links {
            display: flex;
            gap: 1rem;
            margin-top: 1rem;
        }

        @media (max-width: 768px) {
            .container {
                margin: 1rem;
                padding: 1rem;
            }
            
            h1 {
                font-size: 2rem;
            }
            
            .projects {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <header class="header">
            <h1>Hayder Tirmazi</h1>
            <p class="role">Mathematician, Cryptographer</p>
            <p>Currently a student at <a href="https://www.ccny.cuny.edu/?srsltid=AfmBOorqHdVvcZ__0rvLc3XSP4U3-edoeLiyci5odU9sA8vytoF2hlI3">City College of New York</a></p>
        </header>

        <section>
            <h3>Publications</h3>
            <ul class="publications">
                <li>
                    <a href="https://arxiv.org/abs/2501.15751">A Privacy Model for Classical & Learned Bloom Filters</a> — Hayder Tirmazi
                    <a href="#" class="bibtex-button" onclick="navigator.clipboard.writeText('@misc{tirmazi2025privacymodelclassical, title={A Privacy Model for Classical & Learned Bloom Filters}, author={Hayder Tirmazi}, year={2025}, eprint={2501.15751}, archivePrefix={arXiv}, primaryClass={cs.CR}, url={https://arxiv.org/abs/2501.15751}}'); alert('BibTex copied!');">Copy BibTex</a>
                </li>
                <li>
                    <a href="https://eprint.iacr.org/2025/089">An Introduction to Protein Cryptography</a> — Hayder Tirmazi, Tien Phuoc Tran
                    <a href="#" class="bibtex-button" onclick="navigator.clipboard.writeText('@misc{cryptoeprint:2025/089, author = {Hayder Tirmazi and Tien Phuoc Tran}, title = {An Introduction to Protein Cryptography}, howpublished = {Cryptology {ePrint} Archive, Paper 2025/089}, year = {2025}, url = {https://eprint.iacr.org/2025/089}}'); alert('BibTex copied!');">Copy BibTex</a>
                </li>
                <li>
                    <a href="https://arxiv.org/abs/2412.15469">Computational Complexity of Game Boy Games</a> — Hayder Tirmazi, Ali Tirmazi, Tien Phuoc Tran
                    <a href="#" class="bibtex-button" onclick="navigator.clipboard.writeText('@misc{tirmazi2024computationalcomplexitygameboy, title={Computational Complexity of Game Boy Games}, author={Hayder Tirmazi and Ali Tirmazi and Tien Phuoc Tran}, year={2024}, eprint={2412.15469}, archivePrefix={arXiv}, primaryClass={cs.CC}, url={https://arxiv.org/abs/2412.15469}}'); alert('BibTex copied!');">Copy BibTex</a>
                </li>
                <li>
                    <a href="https://arxiv.org/abs/2409.06556">Adversary Resilient Learned Bloom Filters</a> — Allison Bishop, Hayder Tirmazi
                    <a href="#" class="bibtex-button" onclick="navigator.clipboard.writeText('@misc{bishop2025adversaryresilientlearnedbloom, title={Adversary Resilient Learned Bloom Filters}, author={Allison Bishop and Hayder Tirmazi}, year={2025}, eprint={2409.06556}, archivePrefix={arXiv}, primaryClass={cs.CR}, url={https://arxiv.org/abs/2409.06556}}'); alert('BibTex copied!');">Copy BibTex</a>
                </li>
            </ul>
        </section>

        <section>
            <h3>Open Source</h3>
            <ul class="projects">
                <li>
                    <a href="https://lilyfarm.org/getLocation">lilyfarmd</a>
                    <p>Access affordable healthy food in your community.</p>
                </li>
                <li>
                    <a href="https://lilyfarm.org/developerResources/baldwin.html">Baldwin project</a>
                    <p>Resources for unlearning toxic masculinity.</p>
                </li>
                <li>
                    <a href="https://lilyfarm.org/static/lily.html">lilypond</a>
                    <p>A free game for refugee children.</p>
                </li>
            </ul>
        </section>

        <section class="contact">
            <h3>Contact</h3>
            <div class="social-links">
                <a href="mailto:hayder.research@gmail.com">hayder.research@gmail.com</a>
                <a href="https://scholar.google.com/citations?user=qgOBcYMAAAAJ&hl=en">Google Scholar</a>
            </div>
            <div style="transform: scale(0.75); transform-origin: left; margin-top: 1rem;">
                <script type="text/javascript" src="https://cdnjs.buymeacoffee.com/1.0.0/button.prod.min.js" 
                    data-name="bmc-button" 
                    data-slug="lilyfarm" 
                    data-color="#FFDD00" 
                    data-emoji="🌈"  
                    data-font="Lato" 
                    data-text="buy me a coffee" 
                    data-outline-color="#000000" 
                    data-font-color="#000000" 
                    data-coffee-color="#ffffff">
                </script>
            </div>
        </section>
    </div>

    <!-- Google tag (gtag.js) -->
    <script async src="https://www.googletagmanager.com/gtag/js?id=G-K4F6FRWCSL"></script>
    <script>
        window.dataLayer = window.dataLayer || [];
        function gtag(){dataLayer.push(arguments);}
        gtag('js', new Date());
        gtag('config', 'G-K4F6FRWCSL');
    </script>
</body>
</html>
