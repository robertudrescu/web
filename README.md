creative commons license 

trebuie sa pui for la label input

# <!DOCTYPE html>
<html lang="en">

<head>

    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>rockPaperScissors</title>

    <link rel="stylesheet" href="style.css">

    <style>
        body {
            background-color: rgb(0, 0, 0);
        }
    </style>

    <script>


        function kps(userOption) {

            let randomNumber = Math.random()
            let option = Math.floor(randomNumber * 3 + 1)

            let optionText
            let result


            if (userOption == 1 && option == 1) {

                result = "It's a draw."

            } else if (userOption == 1 && option == 2) {

                result = "Computer wins."

            } else if (userOption == 1 && option == 3) {

                result = "You win."

            }


            if (userOption == 2 && option == 1) {

                result = "You win."

            } else if (userOption == 2 && option == 2) {

                result = "It's a draw."

            } else if (userOption == 2 && option == 3) {

                result = "Computer wins."

            }


            if (userOption == 3 && option == 1) {

                result = "Computer wins."

            } else if (userOption == 3 && option == 2) {

                result = "You win."

            } else if (userOption == 3 && option == 3) {

                result = "It's a draw."

            }


            function getOptionText(option) {

                if (option == 1) {

                    return "rock."

                } else if (option == 2) {

                    return "paper."

                } else if (option == 3) {

                    return "scissors."

                }

            }


            function play(userOption) {

                let message = "You chose " + getOptionText(userOption) + ". Computer chose" + getOptionText(computerOption) + getKp(result)

                let randomNumber = Math.random()
                let computerOption = Math.floor(randomNumber * 3 + 1)

                let messageElement = document.getElementById("message")
                messageElement.innerHTML = message
                console.log(message)

            }

        }

    </script>

</head>

<body>

    <div class="center vertical-box align-center h-full font text-white">

        <div class="center horizontal-box align-center">

            <div class="vertical-box align-center">

                <button onclick="kps(1)"><img class="img-width2" src="images/image copy 11.png" alt="image"></button>
                <h2>Rock</h2>

            </div>

            <div class="vertical-box align-center">

                <button onclick="kps(2)"><img class="img-width2" src="images/image copy 12.png" alt="image"></button>
                <h2>Paper</h2>

            </div>

            <div class="vertical-box align-center">

                <button onclick="kps(3)"><img class="img-width2" src="images/image copy 13.png" alt="image"></button>
                <h2>Scissors</h2>

            </div>

        </div>

        <div id="message"></div>

    </div>

</body>

</html>


# terminal-github  

    git add .
    git commit -m ""
    git push
    
# check contrast

    https://webaim.org/resources/contrastchecker/


# complementary colors

    https://www.canva.com/colors/color-wheel/


# operator
    
    count = count + 1
    count += 1
    count++    

# parameter

    variable of function

    ex: function hello(name) {}

    name is a parameter in example


# variables

    coming soon

# Grow taller

    - don't be fat
    - eat enough
    - fast 20h+ –> sprint 6x20s –> natural sugars (ex: smoothie)
    - drink raw milk
    - taurine (ex: dark meat), glycine (meat, fish, dairy), magnesium (seeds, nuts,fish, dark chocolate), zinc (meat, dairy, nuts)
    - eat raw carrots
    - consume bone broth
    - fix anterior pelvic tilt (ex: back extensions, lunge stretch)
    - dead hang (better with hook grip attachments)



# ll
            if (option == 1 && userOption == 1) {

                message = "You chose rock, computer chose rock"

            } else if (option == 2 && userOption == 1) {

                message = "You chose rock, computer chose paper"

            } else if (option == 3 && userOption == 1) {

                message = "You chose rock, computer chose scissors"
            }
                else if (option == 1 && userOption == 2) {

                message = "You chose paper, computer chose rock"

            } else if (option == 2 && userOption == 2) {

                message = "You chose paper, computer cose paper"

            } else if (option == 3 && userOption == 2) {

                message = "You chose paper, computer chose scissors"
            }


            if (option == 1 && userOption == 3) {

                console.log("You chose scissors, computer chose rock. " + result)

            } else if (option == 2 && userOption == 3) {

                console.log("You chose scissors, computer chose paper. " + result)

            } else if (option == 3 && userOption == 3) {

                console.log("You chose scissors, computer chose scissors. " + result)
            }

            message += ". " + result;

            let messageElement = document.getElementById("message")
            messageElement.innerHTML = message;
            console.log(message)


            if (userOption == 1) {


            } else if (userOption == 2) {

                let messageElement = document.getElementById("message")
                messageElement.innerHTML = "You chose paper, computer chose " + optionText + result


            } else {

                let messageElement = document.getElementById("message")
                messageElement.innerHTML = "You chose scissors, computer chose " + optionText + result


            }


