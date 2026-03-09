<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AceQE1 - The Smart IMG Bank</title>
    <style>
        :root { --med-blue: #0056b3; --soft-bg: #f4f7f9; --white: #ffffff; --text: #2c3e50; }
        body { font-family: 'Segoe UI', Arial, sans-serif; background: var(--soft-bg); color: var(--text); margin: 0; line-height: 1.6; -webkit-user-select: none; user-select: none; }
        header { background: var(--med-blue); color: white; padding: 40px 20px; text-align: center; box-shadow: 0 4px 10px rgba(0,0,0,0.1); }
        .logo { font-size: 2.2rem; font-weight: bold; letter-spacing: 1px; margin-bottom: 5px; }
        .tagline { opacity: 0.9; font-size: 1rem; }
        .container { max-width: 800px; margin: -30px auto 40px; padding: 0 20px; }
        .card { background: var(--white); border-radius: 15px; padding: 25px; margin-bottom: 25px; box-shadow: 0 10px 30px rgba(0,0,0,0.05); border-top: 5px solid var(--med-blue); transition: 0.3s; }
        .card:hover { transform: translateY(-5px); }
        .question { font-weight: 700; font-size: 1.2rem; margin-bottom: 20px; color: #1a2a3a; }
        .options-list { list-style: none; padding: 0; }
        .option { background: #f9f9f9; border: 1px solid #eee; padding: 15px; margin-bottom: 10px; border-radius: 10px; cursor: pointer; transition: 0.2s; font-size: 1rem; }
        .option:hover { background: #eef5ff; border-color: var(--med-blue); }
        .btn-reveal { background: var(--med-blue); color: white; border: none; padding: 15px; width: 100%; border-radius: 10px; font-weight: bold; cursor: pointer; margin-top: 10px; font-size: 1rem; }
        .rationale { display: none; margin-top: 20px; padding: 20px; background: #e7f3ff; border-left: 6px solid var(--med-blue); border-radius: 8px; font-size: 0.95rem; }
        footer { text-align: center; padding: 40px; color: #95a5a6; font-size: 0.85rem; }
        @media (max-width: 600px) { header { padding: 30px 15px; } .logo { font-size: 1.8rem; } }
    </style>
</head>
<body oncontextmenu="return false;">

<header>
    <div class="logo">AceQE1</div>
    <div class="tagline">The Ultimate MCCQE1 Bank for IMGs</div>
</header>

<div class="container">
    <div class="card">
        <div class="question">Q1: A 45-year-old female presents with acute right upper quadrant pain radiating to the shoulder. Ultrasound shows gallstones and thickened gallbladder wall. What is the most likely diagnosis?</div>
        <div class="options-list">
            <div class="option">A) Biliary Colic</div>
            <div class="option">B) Acute Cholecystitis</div>
            <div class="option">C) Ascending Cholangitis</div>
            <div class="option">D) Acute Pancreatitis</div>
        </div>
        <button class="btn-reveal" onclick="toggleRationale('r1')">Show Answer & Rationale</button>
        <div id="r1" class="rationale">
            <strong>Correct Answer: B (Acute Cholecystitis)</strong><br><br>
            The presence of thickened gallbladder wall and persistent pain (unlike biliary colic) strongly points towards cholecystitis. Murphy's sign would likely be positive.
        </div>
    </div>
    
    </div>

<footer>
    &copy; 2026 MCCQE1 Mastery Hub | Exclusive IMG Resource
</footer>

<script>
    function toggleRationale(id) {
        const element = document.getElementById(id);
        element.style.display = (element.style.display === "block") ? "none" : "block";
    }
</script>

</body>
</html>
