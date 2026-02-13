
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Amir Hamza Premium Casino - Ultra Ads</title>
    
    <!-- FontAwesome & Google Fonts -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <link href="https://fonts.googleapis.com/css2?family=Oswald:wght@400;700&family=Inter:wght@400;900&display=swap" rel="stylesheet">
    
    <!-- Adsterra Social Bar & Popunder -->
    <script src="https://pl28710343.effectivegatecpm.com/e1/71/5d/e1715d3cbc848ab99e8b5ceff41d01b8.js"></script>

    <style>
        :root { --gold: #ffd700; --dark: #0b0d17; --card: #161b22; --p: #0ea5e9; --s: #ec4899; --wa: #25D366; --tg: #0088cc; --yt: #FF0000; --fb: #1877F2; }
        * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Inter', sans-serif; }
        body { background: var(--dark); color: white; overflow-x: hidden; cursor: pointer; }

        /* 1. Auto Refresh Timer Bar */
        .refresh-timer { position: fixed; top: 0; left: 0; height: 5px; background: linear-gradient(to right, var(--gold), var(--s)); width: 100%; z-index: 2000; animation: timer-progress 15s linear infinite; }
        @keyframes timer-progress { from { width: 100%; } to { width: 0%; } }

        header { background: rgba(0,0,0,0.9); padding: 15px 5%; display: flex; justify-content: space-between; align-items: center; border-bottom: 2px solid var(--gold); position: sticky; top: 5px; z-index: 100; backdrop-filter: blur(10px); }
        .logo { font-family: 'Oswald', sans-serif; font-size: 24px; font-weight: 900; color: var(--gold); text-shadow: 0 0 10px var(--gold); }
        .balance-chip { background: var(--gold); color: black; padding: 5px 15px; border-radius: 5px; font-weight: 900; font-size: 18px; box-shadow: 0 0 15px var(--gold); }

        .container { max-width: 1200px; margin: 20px auto; padding: 0 15px; display: grid; grid-template-columns: 1fr; gap: 20px; }
        @media (min-width: 1024px) { .container { grid-template-columns: 300px 1fr 300px; } }

        .card { background: var(--card); border: 1px solid #30363d; border-radius: 20px; padding: 25px; text-align: center; box-shadow: 0 10px 30px rgba(0,0,0,0.5); }

        /* 2. Tabs System */
        .tabs { display: flex; justify-content: space-around; background: #000; padding: 10px; border-radius: 50px; margin-bottom: 20px; border: 1px solid var(--gold); }
        .tab-item { cursor: pointer; opacity: 0.6; padding: 8px 15px; font-weight: bold; font-size: 14px; transition: 0.3s; }
        .tab-active { opacity: 1; color: var(--gold); border-bottom: 2px solid var(--gold); }

        /* 3. Slot Machine UI (3 Task System) */
        .slot-machine { background: #000; padding: 20px; border: 4px solid var(--gold); border-radius: 15px; margin: 20px 0; position: relative; }
        .slots { display: flex; justify-content: center; gap: 10px; font-size: 50px; margin: 20px 0; background: #111; padding: 15px; border-radius: 10px; }
        .slot { width: 75px; height: 100px; background: white; color: black; display: flex; align-items: center; justify-content: center; border-radius: 8px; border-bottom: 5px solid #bbb; font-family: 'Oswald', sans-serif; }
        
        .task-steps { display: flex; justify-content: center; gap: 10px; margin-bottom: 15px; }
        .step-dot { width: 12px; height: 12px; border-radius: 50%; background: #334155; border: 1px solid var(--gold); }
        .step-dot.active { background: var(--gold); box-shadow: 0 0 10px var(--gold); }

        .spin-btn { background: linear-gradient(180deg, #ff4d4d, #b30000); color: white; border: none; width: 100%; padding: 20px; border-radius: 12px; font-size: 24px; font-weight: 900; cursor: pointer; text-transform: uppercase; box-shadow: 0 6px #660000; transition: 0.2s; }
        .spin-btn:active { transform: translateY(4px); box-shadow: 0 2px #660000; }
        .spin-btn:disabled { background: #555; box-shadow: none; cursor: not-allowed; }

        /* 4. Fake Notification */
        #notify { position: fixed; bottom: 20px; left: 20px; background: white; color: black; padding: 12px 20px; border-radius: 10px; font-size: 13px; transform: translateY(200%); transition: 0.5s; z-index: 1000; box-shadow: 0 10px 40px rgba(0,0,0,0.8); border-left: 5px solid var(--gold); }

        /* 5. Floating Social Menu */
        .float-menu { position: fixed; bottom: 30px; right: 20px; display: flex; flex-direction: column; gap: 12px; z-index: 1000; }
        .float-icon { width: 55px; height: 55px; border-radius: 50%; display: flex; align-items: center; justify-content: center; color: white; font-size: 24px; text-decoration: none; box-shadow: 0 5px 15px rgba(0,0,0,0.5); transition: 0.3s; animation: float-pulse 2s infinite; }
        @keyframes float-pulse { 0% { transform: scale(1); } 50% { transform: scale(1.1); } 100% { transform: scale(1); } }

        /* Support Links */
        .support-link { display: flex; align-items: center; gap: 15px; background: #000; padding: 15px; border-radius: 12px; margin-top: 15px; text-decoration: none; color: white; font-weight: bold; border: 1px solid #334155; }

        .ad-status { font-size: 11px; color: #22c55e; margin-top: 10px; font-weight: bold; text-transform: uppercase; letter-spacing: 1px; }
    </style>
</head>
<body onclick="handleGlobalPop()">

<!-- 15s Auto Refresh Timer -->
<div class="refresh-timer"></div>

<!-- Fake Notification -->
<div id="notify">User <b>Amir Hamza</b> just withdrew $10.00</div>

<header>
    <div class="logo">HAMZA CASINO</div>
    <div class="balance-chip">$ <span id="balance">0.00</span></div>
</header>

<div class="container">
    <!-- Sidebar Left: Ads & Info -->
    <div class="card">
        <p style="color: var(--gold); font-size: 12px; margin-bottom: 15px;">VIP SPONSOR ADS</p>
        <center>
            <script>atOptions = {'key' : '25dea51816ccf1440371367ae3710e86','format' : 'iframe','height' : 250,'width' : 300,'params' : {}};</script>
