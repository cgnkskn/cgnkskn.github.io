<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cagin Keskin | Ph.D. Candidate in Economics</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            background-color: #f8f9fa;
            color: #333;
            line-height: 1.6;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }
        
        header {
            background: linear-gradient(135deg, #2c3e50 0%, #4a6491 100%);
            color: white;
            padding: 40px 0;
            margin-bottom: 30px;
        }
        
        .header-content {
            display: flex;
            justify-content: space-between;
            align-items: center;
            flex-wrap: wrap;
        }
        
        .profile-info {
            flex: 2;
            min-width: 300px;
        }
        
        .profile-image {
            flex: 1;
            text-align: center;
            min-width: 200px;
        }
        
        .profile-img {
            width: 180px;
            height: 180px;
            border-radius: 50%;
            object-fit: cover;
            border: 5px solid rgba(255, 255, 255, 0.3);
            background-color: #b3cde0;
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            font-size: 80px;
        }
        
        h1 {
            font-size: 2.5rem;
            margin-bottom: 10px;
        }
        
        .subtitle {
            font-size: 1.2rem;
            font-weight: 400;
            margin-bottom: 15px;
            color: #e0e0e0;
        }
        
        .contact-info {
            margin: 20px 0;
        }
        
        .contact-info a {
            color: #b3cde0;
            text-decoration: none;
            transition: color 0.3s;
        }
        
        .contact-info a:hover {
            color: white;
            text-decoration: underline;
        }
        
        .social-links {
            margin-top: 20px;
        }
        
        .social-links a {
            color: white;
            font-size: 1.5rem;
            margin-right: 15px;
            transition: transform 0.3s;
        }
        
        .social-links a:hover {
            transform: translateY(-3px);
        }
        
        section {
            background: white;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            padding: 30px;
            margin-bottom: 30px;
        }
        
        h2 {
            color: #2c3e50;
            margin-bottom: 20px;
            padding-bottom: 10px;
            border-bottom: 2px solid #e8e8e8;
        }
        
        h3 {
            color: #4a6491;
            margin: 25px 0 15px;
        }
        
        p {
            margin-bottom: 15px;
        }
        
        .abstract {
            background-color: #f5f7fa;
            padding: 20px;
            border-left: 4px solid #4a6491;
            margin: 20px 0;
            border-radius: 0 4px 4px 0;
        }
        
        .keywords {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
            margin-top: 20px;
        }
        
        .keyword {
            background-color: #e8edf5;
            color: #4a6491;
            padding: 5px 12px;
            border-radius: 20px;
            font-size: 0.9rem;
        }
        
        .btn {
            display: inline-block;
            background-color: #4a6491;
            color: white;
            padding: 10px 20px;
            border-radius: 4px;
            text-decoration: none;
            margin-top: 10px;
            transition: background-color 0.3s;
        }
        
        .btn:hover {
            background-color: #2c3e50;
        }
        
        footer {
            text-align: center;
            padding: 20px;
            margin-top: 40px;
            color: #6c757d;
            font-size: 0.9rem;
        }
        
        @media (max-width: 768px) {
            .header-content {
                flex-direction: column;
                text-align: center;
            }
            
            .profile-info {
                margin-bottom: 30px;
            }
            
            h1 {
                font-size: 2rem;
            }
        }
    </style>
</head>
<body>
    <header>
        <div class="container header-content">
            <div class="profile-info">
                <h1>Cagin Keskin</h1>
                <p class="subtitle">Ph.D. Candidate in Economics</p>
                <p class="subtitle">CERGE-EI (Center for Economic Research and Graduate Education—Economics Institute)</p>
                <div class="contact-info">
                    <p><i class="fas fa-envelope"></i> Email: <a href="mailto:Cagin.Keskin@cerge-ei.cz">Cagin.Keskin@cerge-ei.cz</a></p>
                </div>
                <div class="social-links">
                    <a href="#" title="Google Scholar"><i class="fab fa-google"></i></a>
                    <a href="#" title="LinkedIn"><i class="fab fa-linkedin"></i></a>
                    <a href="#" title="ResearchGate"><i class="fab fa-researchgate"></i></a>
                    <a href="#" title="Twitter"><i class="fab fa-twitter"></i></a>
                </div>
            </div>
            <div class="profile-image">
                <div class="profile-img">
                    <i class="fas fa-user-graduate"></i>
                </div>
            </div>
        </div>
    </header>

    <div class="container">
        <section id="about">
            <h2>About Me</h2>
            <p>I am a Ph.D. candidate at CERGE-EI (Center for Economic Research and Graduate Education—Economics Institute), a joint workplace of Charles University and the Czech Academy of Sciences.</p>
            <p>My research interests lie in firm dynamics, production networks, and more generally topics at the intersection between macroeconomics and international trade.</p>
        </section>

        <section id="cv">
            <h2>Curriculum Vitae</h2>
            <p>My complete academic CV is available for download.</p>
            <a href="#" class="btn"><i class="fas fa-download"></i> Download CV (PDF)</a>
        </section>

        <section id="research">
            <h2>Research</h2>
            
            <h3>Step-by-Step Intangibles</h3>
            <div class="abstract">
                <p><strong>Abstract.</strong> In this paper, I distinguish intangibles into transferable (patent, software) and embedded (brand value, organizational capital), which provide firms with a competitive advantage. I document that as firms increase their degree of segmentation, the ratio of transferable to embedded intangible investment, markup, productivity, and market fluidity declines, indicating that segmentation is systematically associated with a shifting intangible composition and frictions that reduce market fluidity. Motivated by this novel evidence, I extend the canonical endogenous growth framework to endogenize firms' investment decisions, while allowing firms to expand both vertically and horizontally. A key prediction of the model is that embedded intangibles are the primary driver of a firm's ability to expand across segments, which raises entry barriers for competitors and wastes resources rather than promoting long-run growth. This mechanism ultimately shapes aggregate misallocation, firm dynamics, and welfare, highlighting the trade-off between firm-level advantages and economy-wide outcomes.</p>
            </div>
            
            <div class="keywords">
                <span class="keyword">Schumpeterian Growth</span>
                <span class="keyword">Step-by-Step Innovation</span>
                <span class="keyword">Intangible Assets</span>
                <span class="keyword">Firm Dynamics</span>
            </div>
            
            <a href="#" class="btn"><i class="fas fa-file-pdf"></i> Download Paper</a>
        </section>
    </div>

    <footer>
        <div class="container">
            <p>&copy; 2023 Cagin Keskin | Ph.D. Candidate in Economics</p>
            <p>CERGE-EI, Charles University and the Czech Academy of Sciences</p>
        </div>
    </footer>
</body>
</html>


