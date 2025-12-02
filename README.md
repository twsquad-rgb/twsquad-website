# twsquad-website
TW Squad official website
<!DOCTYPE html>
<html lang="bn">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TW SQUAD - AI Trading Signals</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header class="main-header">
        <div class="logo">
            <img src="logo.jpg" alt="TW SQUAD Logo">
        </div>
        <nav class="nav-links">
            <a href="#">হোম</a>
            <a href="#">পরিষেবা</a>
            <a href="#">যোগাযোগ</a>
        </nav>
    </header>

    <section class="hero-section">
        <h1>TW SQUAD</h1>
        <h2>পেশাদার বাইনারি ট্রেডিং সিগন্যাল এবং এআই বট</h2>
        
        <div class="access-box">
            <p>আপনার অ্যাকাউন্ট দিয়ে বিনামূল্যে ব্যবহারের জন্য পাসওয়ার্ড লিখুন</p>
            <input type="password" placeholder="পাসওয়ার্ড লিখুন">
            <button onclick="alert('প্রবেশ করতে হলে আপনাকে এই অংশটিকে প্রোগ্রামিং করে কার্যকরী করতে হবে।')">প্রবেশ করুন</button>
        </div>
        
        <div class="cta-section">
            <p>আমাদের উন্নত ট্রেডিং বটটি সম্পূর্ণ ফ্রিতে ব্যবহার করার জন্য নিচের লিংক থেকে আপনার অ্যাকাউন্ট খুলুন।</p>
            <a href="আপনার ব্রোকার/অ্যাকাউন্ট খোলার লিংক" target="_blank" class="cta-button">
                এখনই একাউন্ট খুলুন
            </a>
            </div>
    </section>

    <footer class="main-footer">
        <p>© 2025 TW SQUAD | সকল অধিকার সংরক্ষিত</p>
    </footer>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    background-color: #1e1e1e; /* 5S TRADER-এর মতো গাঢ় ব্যাকগ্রাউন্ড */
    color: #ffffff;
    margin: 0;
    padding: 0;
    text-align: center;
}

.main-header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 20px 40px;
    background-color: #000000;
}

.logo img {
    height: 50px; /* লোগোর সাইজ */
    border-radius: 50%; /* লোগোটিকে গোলাকার করতে পারেন */
}

.nav-links a {
    color: #ffffff;
    text-decoration: none;
    margin-left: 20px;
    font-weight: bold;
}

.hero-section {
    padding: 80px 20px;
}

.hero-section h1 {
    font-size: 3em;
    color: #007bff; /* নীল রঙের হাইলাইট */
    margin-bottom: 5px;
}

.hero-section h2 {
    font-size: 1.5em;
    font-weight: normal;
    margin-bottom: 40px;
}

.access-box {
    background-color: #2c2c2c;
    padding: 30px;
    border-radius: 10px;
    max-width: 400px;
    margin: 0 auto 30px;
}

.access-box input[type="password"] {
    padding: 10px;
    width: 80%;
    margin-bottom: 15px;
    border: 1px solid #444;
    background-color: #1e1e1e;
    color: #fff;
    border-radius: 5px;
}

.access-box button {
    background-color: #28a745; /* সবুজ বাটন */
    color: white;
    padding: 10px 20px;
    border: none;
    cursor: pointer;
    border-radius: 5px;
    font-weight: bold;
}

.cta-button {
    display: inline-block;
    background-color: #ffc107; /* হলুদ বাটন */
    color: #000000;
    padding: 15px 30px;
    text-decoration: none;
    font-size: 1.2em;
    font-weight: bold;
    border-radius: 5px;
    margin-top: 20px;
}

.main-footer {
    padding: 20px;
    background-color: #000000;
    font-size: 0.8em;
}
