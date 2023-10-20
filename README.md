# digital-clock
make your own clock

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

