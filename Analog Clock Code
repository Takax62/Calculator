<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Static Analog Clock</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body class="light-mode">
    <div class="mode-switch">
        <button onclick="toggleMode()">Toggle Mode</button>
    </div>
    <div class="clock">
        <div class="hand hour"></div>
        <div class="hand minute"></div>
        <div class="hand second"></div>
        <label style="--i: 1"><span>1</span></label>
        <label style="--i: 2"><span>2</span></label>
        <label style="--i: 3"><span>3</span></label>
        <label style="--i: 4"><span>4</span></label>
        <label style="--i: 5"><span>5</span></label>
        <label style="--i: 6"><span>6</span></label>
        <label style="--i: 7"><span>7</span></label>
        <label style="--i: 8"><span>8</span></label>
        <label style="--i: 9"><span>9</span></label>
        <label style="--i: 10"><span>10</span></label>
        <label style="--i: 11"><span>11</span></label>
        <label style="--i: 12"><span>12</span></label>
    </div>
</body>
</html>

body {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    height: 100vh;
    margin: 0;
    transition: background-color 0.3s, color 0.3s;
}

body.light-mode {
    background-color: #f3f4f6;
    color: #333;
}

body.dark-mode {
    background-color: #333;
    color: #f3f4f6;
}

.mode-switch {
    margin-bottom: 20px;
}

.clock {
    width: 200px;
    height: 200px;
    border: 10px solid currentColor;
    border-radius: 50%;
    position: relative;
    background-color: currentColor;
}

.hand {
    width: 50%;
    height: 6px;
    background-color: currentColor;
    position: absolute;
    top: 50%;
    transform-origin: 100%;
    transform: rotate(90deg);
}

.hour {
    height: 8px;
}

.minute {
    height: 6px;
}

.second {
    height: 4px;
    background-color: red;
}

label {
    position: absolute;
    width: 20px;
    height: 20px;
    text-align: center;
    font-size: 12px;
    transform: rotate(calc(var(--i) * 30deg)) translate(90px) rotate(calc(var(--i) * -30deg));
}

label span {
    display: block;
    transform: rotate(calc(var(--i) * 30deg));
}
