<!DOCTYPE html>
<html>
<head>
    <title>Number Order Guessing Game</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/materialize/1.0.0/css/materialize.min.css">
    <script src="https://cdnjs.cloudflare.com/ajax/libs/materialize/1.0.0/js/materialize.min.js"></script>
    <style>
        .container {
            max-width: 500px;
        }
    </style>
    <script>
        var numTries = 0;
        var selectedNumbers = [];
        var guessedNumbers = [];

        function randomizeNumbers() {
            // Define the available numbers
            var numbers = [1, 2, 3, 4, 5, 6];

            // Reset the selected numbers array
            selectedNumbers = [];

            // Randomly select 4 numbers
            for (var i = 0; i < 4; i++) {
                var randomIndex = Math.floor(Math.random() * numbers.length);
                var selectedNumber = numbers.splice(randomIndex, 1)[0];
                selectedNumbers.push(selectedNumber);
            }

            // Enable the input fields and Guess button
            var inputFields = document.getElementsByClassName("number-input");
            for (var j = 0; j < inputFields.length; j++) {
                inputFields[j].disabled = false;
                inputFields[j].value = "";
            }
            document.getElementById("guessButton").disabled = false;

            // Reset the number of tries
            numTries = 0;

            // Clear guessed numbers
            guessedNumbers = [];
            
            // Clear the guess list
            document.getElementById("guessedNumbers").innerHTML = "";

            // Display a message to start guessing
            document.getElementById("message").innerHTML = "Guess the order of the selected numbers!";
        }

        function guessOrder() {
            // Get the user's guessed order
            var guess1 = parseInt(document.getElementById("1").value);
            var guess2 = parseInt(document.getElementById("2").value);
            var guess3 = parseInt(document.getElementById("3").value);
            var guess4 = parseInt(document.getElementById("4").value);

            // Validate the guessed numbers
            if (guess1 < 1 || guess1 > 6 || guess2 < 1 || guess2 > 6 || guess3 < 1 || guess3 > 6 || guess4 < 1 || guess4 > 6) {
                M.toast({html: 'Please enter numbers between 1 and 6.', classes: 'red'});
                return;
            }

            // Store the guessed numbers
            var currentGuess = [guess1, guess2, guess3, guess4];
            guessedNumbers.push(currentGuess);

            // Compare the user's guesses with the selected numbers
            var correctPositions = 0;
            var correctNumbers = 0;
            if (guess1 === selectedNumbers[0]) {
                correctPositions++;
                correctNumbers++;
            } else if (guess1 === selectedNumbers[1] || guess1 === selectedNumbers[2] || guess1 === selectedNumbers[3]) {
                correctNumbers++;
            }

            if (guess2 === selectedNumbers[1]) {
                correctPositions++;
                correctNumbers++;
            } else if (guess2 === selectedNumbers[0] || guess2 === selectedNumbers[2] || guess2 === selectedNumbers[3]) {
                correctNumbers++;
            }

            if (guess3 === selectedNumbers[2]) {
                correctPositions++;
                correctNumbers++;
            } else if (guess3 === selectedNumbers[0] || guess3 === selectedNumbers[1] || guess3 === selectedNumbers[3]) {
                correctNumbers++;
            }

            if (guess4 === selectedNumbers[3]) {
                correctPositions++;
                correctNumbers++;
            } else if (guess4 === selectedNumbers[0] || guess4 === selectedNumbers[1] || guess4 === selectedNumbers[2]) {
                correctNumbers++;
            }

            // Increment the number of tries
            numTries++;

            // Display the result
            var result = "Correct Positions: " + correctPositions + "<br>Correct Numbers: " + correctNumbers + "<br>Tries: " + numTries;
            document.getElementById("result").innerHTML = result;

            // Check if the user wins
            if (correctPositions === 4) {
                document.getElementById("message").innerHTML = "You Win!";
                document.getElementById("guessButton").disabled = true;
            }

            // Display guessed numbers
            document.getElementById("guessedNumbers").innerHTML += currentGuess.join(", ") + "<br>";
        }
    </script>
</head>
<body>
    <div class="container">
        <h1 class="center-align">Number Order Guessing Game</h1>
        <div class="row">
            <div class="col s12 center-align">
                <button class="btn waves-effect waves-light" onclick="randomizeNumbers()">Start Game</button>
            </div>
        </div>
        <div class="row">
            <div class="col s12 center-align">
                <p id="message"></p>
            </div>
        </div>
        <div class="row">
            <div class="col s12">
                <ol>
                    <li><input type="number" id="1" class="number-input" disabled></li>
                    <li><input type="number" id="2" class="number-input" disabled></li>
                    <li><input type="number" id="3" class="number-input" disabled></li>
                    <li><input type="number" id="4" class="number-input" disabled></li>
                </ol>
            </div>
        </div>
        <div class="row">
            <div class="col s12 center-align">
                <button class="btn waves-effect waves-light" id="guessButton" onclick="guessOrder()" disabled>Guess</button>
            </div>
        </div>
        <div class="row">
            <div class="col s12 center-align">
                <p id="result"></p>
            </div>
        </div>
        <div class="row">
            <div class="col s12">
                <p id="guessedNumbers"></p>
            </div>
        </div>
    </div>
</body>
</html>
