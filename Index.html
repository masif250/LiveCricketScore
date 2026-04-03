<!DOCTYPE html>
<html>
<head>
    <style>
        body { background: transparent; font-family: 'Segoe UI', sans-serif; color: white; }
        .scoreboard {
            width: 450px;
            background: linear-gradient(90deg, #1e3c72 0%, #2a5298 100%);
            border-bottom: 5px solid #f1c40f;
            padding: 10px;
            border-radius: 10px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        .team-name { font-weight: bold; font-size: 24px; padding-left: 10px; }
        .score { font-size: 32px; font-weight: 900; color: #f1c40f; }
        .overs { font-size: 16px; opacity: 0.8; margin-left: 5px; }
    </style>
</head>
<body>

<div class="scoreboard">
    <div class="team-name" id="team">PAK</div>
    <div>
        <span class="score" id="score">0-0</span>
        <span class="overs" id="overs">(0.0)</span>
    </div>
</div>

<script>
    async function updateScore() {
        const options = {
            method: 'GET',
            headers: {
                'X-RapidAPI-Key': 'YOUR_API_KEY_HERE', // Apni key yahan lagayein
                'X-RapidAPI-Host': 'cricket-live-score.p.rapidapi.com'
            }
        };

        try {
            const response = await fetch('https://cricket-live-score.p.rapidapi.com/match/live', options);
            const data = await response.json();
            // Yahan data match kar ke UI update karein
            // Note: API response ke mutabiq keys change ho sakti hain
            document.getElementById('score').innerText = data.score; 
            document.getElementById('overs').innerText = "(" + data.overs + ")";
        } catch (error) {
            console.error(error);
        }
    }

    setInterval(updateScore, 30000); // Har 30 second baad update hoga
    updateScore();
</script>

</body>
</html>
