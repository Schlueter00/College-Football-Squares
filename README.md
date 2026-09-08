<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>README.txt</title>
    <style>
        body {
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
            line-height: 1.6;
            color: #333;
            max-width: 800px;
            margin: 40px auto;
            padding: 0 20px;
            background-color: #f9f9f9;
        }
        .container {
            background: #fff;
            padding: 40px;
            border-radius: 8px;
            box-shadow: 0 4px 12px rgba(0,0,0,0.05);
        }
        h1 {
            border-bottom: 2px solid #eaeaea;
            padding-bottom: 10px;
            margin-top: 0;
            color: #111;
        }
        textarea {
            width: 100%;
            height: 450px;
            padding: 16px;
            font-family: SFMono-Regular, Consolas, "Liberation Mono", Menlo, Courier, monospace;
            font-size: 0.9em;
            line-height: 1.5;
            color: #333;
            background-color: #f8f9fa;
            border: 1px solid #ced4da;
            border-radius: 6px;
            resize: vertical;
            box-sizing: border-box;
            white-space: pre;
        }
        textarea:focus {
            outline: none;
            border-color: #0d6efd;
            box-shadow: 0 0 0 3px rgba(13, 110, 253, 0.15);
        }
        .instructions {
            margin-bottom: 15px;
            font-size: 0.95em;
            color: #555;
        }
    </style>
</head>
<body>

<div class="container">
    <h1>README.txt Generator</h1>
    <p class="instructions">Here is your football board README formatted as plain text inside a text field so you can save it directly as a <code>.txt</code> file:</p>
    
    <textarea>FOOTBALL SQUARES WEB APPLICATION

A real-time, interactive Football Squares board featuring live synchronization via Firebase, automated score tracking, pool financial management, and a dedicated quarter winner scoreboard.


FEATURES

- Real-Time Collaboration: Share a live board link so participants can view real-time updates and square selections as they happen.
- Team Selection: Choose Home (Top Axis) and Away (Left Axis) teams, complete with official team colors and logos.
- Randomized Axis Numbers: Automatically shuffle and generate the 0-9 grid numbers for both axes.
- Pool Financials & Cost Tracking: 
  * Set a custom cost per square (e.g., $1, $5, $10).
  * Automatically counts claimed squares to calculate the Total Pot.
  * Dynamically splits the pot evenly across Q1 through Q4 to show the exact Payout per Quarter.
- Quarter Winner Scoreboard: A dedicated summary dashboard displaying Q1, Q2 (Half), Q3, and Q4 (Final) scores, winning square owners, and calculated cash payouts at a glance.
- Automated Winner Detection & Popups: Automatically maps final or quarter scores to the corresponding grid coordinates, highlights winning squares on the board, and triggers celebration alerts when a winner is decided.
- Print-Friendly Layout: Formats cleanly for physical printing when needed.


SETUP & CONFIGURATION

1. Make sure you have your Firebase project configured within the script tags of index.html (the app utilizes Firebase Realtime Database).
2. Open index.html in any modern web browser or host it via a static file server (such as GitHub Pages or Netlify).
3. Click "Share Live Link" to distribute the board to participants.


HOW TO PLAY

1. Claim Squares: Click on any square on the grid to assign a participant's name (Host view only).
2. Set Pricing: Input the desired dollar amount into the Cost Per Square field under Pool Financials.
3. Generate Numbers: Click "Generate Axis Numbers" once all squares are filled to randomly assign the 0-9 digits to the top and left axes.
4. Enter Scores: As the game progresses, type the quarterly scores for both teams. The scoreboard and payouts will update automatically!</textarea>
</div>

</body>
</html>
