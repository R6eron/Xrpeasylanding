# UVDM Demo Script: 8-Step Projection
initial_xlm = 115735
targets = [1, 2, 3, 4, 5, 6, 7, 8]
retention = 50000  # Optimized retention
for i, target in enumerate(targets):
    harvest = (initial_xlm - retention) * 0.1 if i == 0 else initial_xlm * 0.1
    print(f"At ${target}: Harvest {harvest:.0f} XLM = ${harvest * target:,.0f}")
    initial_xlm = retention + (harvest * target * 0.5 / 0.31665)  # 50% reinvest at $0.31665
print(f"Final XLM: {initial_xlm:.0f}, Value at $8: ${initial_xlm * 8:,.2f}")
# Xrpeasylanding
Xrpeasy-landing page

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>XRPeasy | UVDM: 8 Steps to 1 Million $ – It's Just Math</title>
    <style>
        body { font-family: 'Arial', sans-serif; margin: 0; padding: 0; background-color: #f4f7fa; color: #333; line-height: 1.6; }
        .container { max-width: 1200px; margin: 0 auto; padding: 0 20px; }
        header { background: linear-gradient(135deg, #0f4c75, #2c7a7b); color: white; text-align: center; padding: 60px 20px; }
        header h1 { font-size: 2.5em; margin: 0; }
        header p { font-size: 1.2em; margin: 10px 0 30px; }
        .btn { display: inline-block; background: #ff6b35; color: white; padding: 15px 30px; text-decoration: none; border-radius: 5px; font-weight: bold; transition: background 0.3s, transform 0.3s; }
        .btn:hover { background: #e55a2b; transform: translateY(-2px); }
        .btn-secondary { background: #28a745; }
        .btn-secondary:hover { background: #218838; }
        section { padding: 60px 0; }
        .book-cover { max-width: 300px; height: auto; border-radius: 10px; box-shadow: 0 10px 30px rgba(0,0,0,0.2); filter: drop-shadow(0 0 10px rgba(0, 255, 255, 0.3)); /* Neon glow to match cover */ }
        .books-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 40px; }
        .book-card { background: white; padding: 30px; border-radius: 10px; box-shadow: 0 5px 20px rgba(0,0,0,0.1); text-align: center; }
        .academy-cta { background: #f8f9fa; text-align: center; }
        .excerpt { background: rgba(15, 76, 117, 0.1); padding: 20px; border-left: 4px solid #0f4c75; margin: 20px 0; font-style: italic; }
        footer { background: #0f4c75; color: white; text-align: center; padding: 30px; }
        footer a { color: #ff6b35; text-decoration: none; }
        @media (max-width: 768px) { header h1 { font-size: 2em; } .container { padding: 0 10px; } .book-cover { max-width: 250px; } }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <h1>8 Steps to 1 Million $: Unlock the UVDM Power</h1>
            <p>It's Just Math... Turn $3,540 into a compounding $60K annuity with the Ultrasafe Virtual Digital Machine. Featuring XRP, XLM, FLR, and SGB – investing made easy by XRPeasy.</p>
            <img src="https://i.imgur.com/5z5q3zq.png" alt="UVDM? It’s Just Math... Book Cover by Ron Lewis – 8 Steps to 1 Million $ with XRP, XLM, FLR, SGB" class="book-cover">
            <br><br>
            <a href="#books" class="btn">Explore the Book</a>
            <a href="https://your-academy-sales-link.com/join" class="btn btn-secondary" target="_blank">Join Nexpert Academy Now</a>
        </div>
    </header>

    <section id="about">
        <div class="container">
            <h2>About UVDM? It’s Just Math...</h2>
            <p>From ex-Royal Engineer Commando Sergeant Ron Lewis: After surviving scams and regulatory crashes that cost him $43K, this is your mission-tested guide to financial freedom. The UVDM is an 8-step framework using assets like XLM (target: $8) for compounding yields, Nexo debt optimization, and diversification into FLR, SGB, and PAXG. It's not get-rich-quick – it's sustainable math for parents, pensioners, and anyone building a legacy.</p>
            <div class="excerpt">
                <blockquote>"What if you could avoid all of that? The UVDM is my response—a million-dollar formula anyone can trust. It's a lifelong partner, a piggy bank with a virtual card on Google Pay. Become a Nexpert today and never look back."</blockquote>
                <cite>– Ron Lewis, Author</cite>
            </div>
            <p>Join the XRPeasy community: Become a Nexpert today.</p>
        </div>
    </section>

    <section id="books">
        <div class="container">
            <h2>Featured Books</h2>
            <div class="books-grid">
                <div class="book-card">
                    <img src="https://i.imgur.com/5z5q3zq.png" alt="UVDM? It’s Just Math... Book Cover by Ron Lewis" class="book-cover">
                    <h3>UVDM? It’s Just Math...</h3>
                    <p>The 8 steps to 1 million $ and a 60K annuity. Case studies, XLM strategies, and safety protocols for the digital age – featuring XRP, XLM, FLR, and SGB.</p>
                    <a href="https://www.amazon.com/UVDM-Just-Math-Ron-Lewis/dp/YOUR-ASIN-HERE" class="btn" target="_blank">Buy on Amazon</a>
                </div>
                <!-- Add more books here -->
                <!-- 
                <div class="book-card">
                    <img src="https://via.placeholder.com/300x400/2c7a7b/white?text=Book+2+Cover" alt="Book 2 Cover" class="book-cover">
                    <h3>Your Second Book Title</h3>
                    <p>Brief description...</p>
                    <a href="#" class="btn" target="_blank">Buy Now</a>
                </div>
                -->
            </div>
        </div>
    </section>

    <section class="academy-cta" id="academy">
        <div class="container">
            <h2>Ready to Master UVDM? Join the Nexpert Academy</h2>
            <p>Exclusive training on the 8 steps, live Q&A, community access, and tools to implement the strategy. Limited spots – start your journey to $60K+ annual yields and 1 million $ legacy.</p>
            <a href="https://your-academy-sales-link.com/join" class="btn btn-secondary" style="font-size: 1.5em; padding: 20px 40px;" target="_blank">Enroll Today – $97/Month</a>
            <p style="margin-top: 20px; font-size: 0.9em; color: #666;">(Includes book access, templates, and XRPeasy support)</p>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>&copy; 2025 Ron Lewis | XRPeasy. All rights reserved. | <a href="https://x.com/XRPeasy" target="_blank">Follow on X</a> | <a href="mailto:contact@xrpeasy.com">Contact Us</a></p>
        </div>
    </footer>

    <script>
        // Simple smooth scroll for internal links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                document.querySelector(this.getAttribute('href')).scrollIntoView({ behavior: 'smooth' });
            });
        });
    </script>
</body> <section id="automation">
    <div class="container">
        <h2>UVDM Automation: Scripts for the 8 Steps</h2>
        <p>Reduce error with open-source code for Nexo trades, XLM alerts, and simulations. From the NexpertUVDM-Automation repo—customize for your $1M path.</p>
        <ul>
            <li><strong>xrpl_script.py</strong>: XRPL/Flare staking and minting.</li>
            <li><strong>uvdm_steps.py</strong>: 8-step harvesting simulation (e.g., $60K/year projection).</li>
            <li><strong>xlm_monitor.py</strong>: $1 triggers and dip alerts.</li>
        </ul>
        <a href="https://github.com/R6eron/NexpertUVDM-Automation" class="btn btn-secondary" target="_blank">Download Repo & Scripts</a>
        <p>Start with `python xlm_monitor.py`. Join Nexpert Academy for API setup and grants.</p>
    </div>
</section>
</html>initial landing page deploy 
