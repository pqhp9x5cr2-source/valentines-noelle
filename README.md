# valentines-noelle
For noelle
<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Happy Valentine's Day</title>

<style>
body {
    margin: 0;
    padding: 0;
    font-family: Arial, sans-serif;
    background: linear-gradient(135deg, #b11313, #1c1c1c);
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    overflow: hidden;
}

/* Spider web background effect */
body::before {
    content: "";
    position: absolute;
    width: 200%;
    height: 200%;
    background-image: radial-gradient(white 1px, transparent 1px);
    background-size: 40px 40px;
    opacity: 0.05;
}

/* Main Card */
.card {
    background: #ffffff;
    color: #b11313;
    padding: 40px 25px;
    border-radius: 20px;
    text-align: center;
    box-shadow: 0 0 30px rgba(0,0,0,0.6);
    max-width: 350px;
    animation: float 3s ease-in-out infinite;
}

/* Floating animation */
@keyframes float {
    0% { transform: translateY(0px); }
    50% { transform: translateY(-10px); }
    100% { transform: translateY(0px); }
}

h1 {
    font-size: 24px;
    margin: 0;
}

/* Cute swinging heart */
.heart {
    font-size: 40px;
    margin-top: 20px;
    animation: swing 2s infinite ease-in-out;
}

@keyframes swing {
    0% { transform: rotate(-10deg); }
    50% { transform: rotate(10deg); }
    100% { transform: rotate(-10deg); }
}
</style>
</head>

<body>

<div class="card">
    <h1>Happy Valentine’s Day, Noelle! 🤟🏻</h1>
    <div class="heart">🕷️❤️</div>
</div>

</body>
</html>
