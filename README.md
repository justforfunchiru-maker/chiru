<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Points Table</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="container">
        <h1>Points Table</h1>
        <div id="status-message"></div>
        <table id="points-table">
            <thead>
                <tr>
                    <th>Team</th>
                    <th>Played</th>
                    <th>Won</th>
                    <th>Lost</th>
                    <th>Points</th>
                    <th>NRR</th>
                </tr>
            </thead>
            <tbody>
                </tbody>
        </table>
        
        <div id="edit-form-container" class="hidden">
            <h2>Edit Table</h2>
            <form id="edit-form">
                <div class="form-group">
                    <label for="team-select">Select Team:</label>
                    <select id="team-select" name="team"></select>
                </div>
                <div class="form-group">
                    <label for="played-input">Played:</label>
                    <input type="number" id="played-input" name="played">
                </div>
                <div class="form-group">
                    <label for="won-input">Won:</label>
                    <input type="number" id="won-input" name="won">
                </div>
                <div class="form-group">
                    <label for="lost-input">Lost:</label>
                    <input type="number" id="lost-input" name="lost">
                </div>
                <div class="form-group">
                    <label for="points-input">Points:</label>
                    <input type="number" id="points-input" name="points">
                </div>
                <div class="form-group">
                    <label for="nrr-input">NRR:</label>
                    <input type="text" id="nrr-input" name="nrr">
                </div>
                <button type="submit">Update</button>
            </form>
        </div>
        
        <button id="toggle-edit-button">Toggle Edit Mode</button>
    </div>

    <script src="script.js"></script>
</body>
</html>
