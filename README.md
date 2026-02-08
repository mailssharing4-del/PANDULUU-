<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>My Proposal to You</title>

<style>
    body {
        margin: 0;
        height: 100vh;
        background: radial-gradient(circle at top, #2b1055, #000);
        overflow: hidden;
        font-family: 'Segoe UI', sans-serif;
        color: white;
        display: flex;
        justify-content: center;
        align-items: center;
        text-align: center;
    }

    .stars {
        position: absolute;
        width: 100%;
        height: 100%;
        background: url('https://i.imgur.com/9QZ7Q4F.png');
        animation: moveStars 60s linear infinite;
        opacity: 0.6;
    }

    @keyframes moveStars {
        from { background-position: 0 0; }
        to { background-position: 10000px 5000px; }
    }

    .card {
        background: rgba(255, 255, 255, 0.08);
        backdrop-filter: blur(10px);
        padding: 40px;
        border-radius: 25px;
        max-width: 350px;
        box-shadow: 0 0 30px rgba(255, 0, 150, 0.4);
        z-index: 2;
        animation: fadeIn 3s ease;
    }

    @keyframes fadeIn {
        from { opacity: 0; transform: scale(0.8); }
        to { opacity: 1; transform: scale(1); }
    }

    h1 {
        color: #ffb6f3;
        margin-bottom: 10px;
    }

    .name {
        font-size: 28px;
        color: #ff5fd2;
        font-weight: bold;
        margin: 10px 0;
    }

    p {
        font-size: 16px;
        line-height: 1.6;
        color: #f1eaff;
    }

    .heart {
        font-size: 40px;
        animation: heartbeat 1.5s infinite;
        margin-top: 20px;
    }

    @keyframes heartbeat {
        0%, 100% { transform: scale(1); }
        50% { transform: scale(1.3); }
    }

    .btn {
        margin-top: 25px;
        padding: 12px 30px;
        border: none;
        border-radius: 30px;
        background: linear-gradient(45deg, #ff5fd2, #ff9de2);
        color: white;
        font-size: 16px;
        cursor: pointer;
        box-shadow: 0 0 15px rgba(255, 95, 210, 0.7);
    }

    .btn:hover {
        transform: scale(1.05);
    }
</style>
</head>

<body>

<div class="stars"></div>

<div class="card">
    <h1>Happy Propose Day 💫</h1>

    <div class="name">PANDULUU 💖</div>

    <p>
        In this endless universe full of stars,<br>
        my heart chose only <strong>you</strong>.<br><br>

        With every heartbeat, every dream,<br>
        every silent prayer…<br>
        I see my forever in your eyes.<br><br>

        Will you walk with me,<br>
        not just today,<br>
        but for all the magical tomorrows? ✨
    </p>

    <div class="heart">💗</div>

    <button class="btn" onclick="alert('You are my forever 🌙💞')">
        Will You Be Mine?
    </button>
</div>

</body>
</html>
