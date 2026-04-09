<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Swaraj Kumar Behera | Portfolio</title>
    <style>
        :root { 
            --primary: #2d3436; 
            --accent: #0984e3; 
            --text: #636e72; 
            --bg: #f5f6fa; 
            --transition: all 0.3s ease-in-out;
        }

        /* Smooth Scroll & Fade-in Animation */
        html { scroll-behavior: smooth; }
        @keyframes fadeInUp {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }

        body { 
            font-family: 'Segoe UI', sans-serif; 
            line-height: 1.6; 
            color: var(--text); 
            background: var(--bg); 
            margin: 0; 
            animation: fadeInUp 0.8s ease-out;
        }

        header { 
            background: white; 
            padding: 3rem 10%; 
            text-align: center; 
            border-bottom: 3px solid var(--accent);
            transition: var(--transition);
        }

        /* Profile Picture Styling */
        .profile-img {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            object-fit: cover;
            border: 4px solid var(--accent);
            margin-bottom: 20px;
            transition: transform 0.5s ease;
            box-shadow: 0 10px 20px rgba(0,0,0,0.1);
        }
        .profile-img:hover {
            transform: scale(1.05) rotate(2deg);
        }

        .container { width: 80%; margin: auto; padding: 20px; }
        
        .section-title { 
            color: var(--primary); 
            border-left: 5px solid var(--accent); 
            padding-left: 15px; 
            margin: 40px 0 20px; 
        }

        .grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 20px; }

        /* Card Hover Transitions */
        .card { 
            background: white; 
            padding: 25px; 
            border-radius: 12px; 
            box-shadow: 0 4px 6px rgba(0,0,0,0.05);
            transition: var(--transition);
            border: 1px solid transparent;
        }
        .card:hover {
            transform: translateY(-10px);
            box-shadow: 0 15px 30px rgba(0,0,0,0.1);
            border-color: var(--accent);
        }

        .card h3 { color: var(--accent); margin-top: 0; }
        .tag { 
            background: #dfe6e9; 
            padding: 4px 10px; 
            border-radius: 20px; 
            font-size: 0.75rem; 
            margin-right: 5px;
            transition: background 0.3s;
        }
        .card:hover .tag { background: var(--accent); color: white; }

        footer { text-align: center; padding: 40px; background: var(--primary); color: white; margin-top: 50px; }
        a { color: var(--accent); text-decoration: none; font-weight: bold; transition: var(--transition); }
        a:hover { color: var(--primary); }
    </style>
</head>
<body>

<header>
    <img src="profile.jpg" alt="Swaraj Kumar Behera" class="profile-img">
    <h1>Swaraj Kumar Behera [cite: 2]</h1>
    <p>Data Analyst | Business Analyst | PGDM Marketing & Business Analytics [cite: 22]</p>
    <p>
        <a href="mailto:swarajkumarbehe8@gmail.com">Email [cite: 3]</a> | 
        <a href="https://linkedin.com/in/swarajkumarbehera/">LinkedIn [cite: 5]</a> | 
        +91 8847825552 [cite: 4]
    </p>
</header>

<div class="container">
    <h2 class="section-title">About Me</h2>
    <p>
        Results-driven professional with a PGDM in Marketing & Business Analytics from ISB&M Pune [cite: 20, 22] and a B.Tech in Computer Science from CUTM Bhubaneswar[cite: 23, 24]. I specialize in bridging the gap between raw data and strategic business decisions using SQL, Python, and Power BI[cite: 6, 7].
    </p>

    <h2 class="section-title">Featured Projects</h2>
    <div class="grid">
        <div class="card">
            <h3>Retail Sales Performance Dashboard</h3>
            <p>End-to-end Power BI solution tracking regional KPIs and YoY growth for a multi-chain retailer.</p>
            <div><span class="tag">Power BI</span><span class="tag">DAX</span><span class="tag">Power Query</span></div>
        </div>
        <div class="card">
            <h3>E-commerce Customer Segmentation</h3>
            <p>RFM analysis using SQL and Python to identify high-value customer clusters and retention strategies.</p>
            <div><span class="tag">SQL</span><span class="tag">Python</span><span class="tag">Pandas</span></div>
        </div>
        <div class="card">
            <h3>Real Estate Market Predictor</h3>
            <p>Predictive modeling using linear regression to estimate property values in the Bangalore market.</p>
            <div><span class="tag">Machine Learning</span><span class="tag">EDA</span><span class="tag">Python</span></div>
        </div>
        <div class="card">
            <h3>Logistics Efficiency Analysis</h3>
            <p>Advanced Excel modeling that identified bottlenecks, reducing processing delays by over 2 hours daily.</p>
            <div><span class="tag">Advanced Excel</span><span class="tag">Business Analysis</span></div>
        </div>
    </div>

    <h2 class="section-title">Technical Expertise</h2>
    <div class="grid">
        <div class="card">
            <h3>Data Analysis & Programming</h3>
            <ul>
                <li>SQL (Joins, Subqueries, CTES) [cite: 6]</li>
                <li>Python (Pandas, NumPy) [cite: 6]</li>
                <li>Advanced Microsoft Excel [cite: 6]</li>
            </ul>
        </div>
        <div class="card">
            <h3>Visualization & BI Tools</h3>
            <ul>
                <li>Power BI (DAX, Interactive Dashboards) [cite: 7]</li>
                <li>Tableau & Excel Charts [cite: 7]</li>
                <li>KPI Tracking & Reporting [cite: 9]</li>
            </ul>
        </div>
    </div>
</div>

<footer>
    <p>&copy; 2026 Swaraj Kumar Behera. Built with Precision.</p>
</footer>

</body>
</html>
