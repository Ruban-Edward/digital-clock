# digital-clock
make your own clock

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="preconnect" href="https://fonts.gstatic.com">
    <link href="https://fonts.googleapis.com/css2?family=Orbitron&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="style.css">
    <title>Clock</title>
</head>
<body>
    <section class="container">
        <div id="clock"></div>
        <input onchange="setAlarmTime(this.value)" name="alarmTime" type="datetime-local">
        <div class="controls">
            <button onclick="setAlarm()" class="button set-alarm">Set alarm</button>
            <button onclick="clearAlarm()" class="button clear-alarm">Clear alarm</button>
        </div>
    </section>
    <script src="index.js"></script>
</body>
</html>
