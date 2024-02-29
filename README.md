[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/cdqffI9o)
# WebApps-S24-Assignment-7
An assignment on java script modifying the DOM and using anonymous callback functions.
Hosted at: https://44-563-web-apps-s24.github.io/44563-webapps-s24-assignment7-S572177/money.html
Hosted at: https://44-563-web-apps-s24.github.io/44563-webapps-s24-assignment7-S572177/precision.html
Hosted at: https://44-563-web-apps-s24.github.io/44563-webapps-s24-assignment7-S572177/divlist.html





<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="utf-8" />
        <title>Webapps lab 7</title>
        <style>
            .row{
                display: flex;
                max-width: 300px;
            }
            .container{
                margin-right: 5px;
                overflow: hidden;
            }
        </style>

    </head>
    <body>
        <header><h1>Find the coins by Swetha Kamineni</h1></header>
        <div class="instructions">
            <p>Click on the locations to find coins, beware the monster</p>
            <p id="location">Number of locations checked is zero</p>
            <p id="score">Score is zero</p>
            <p onclick="help()">Click for help</p>
            <p id="help">Help report</p>
        </div>
        <!---row -1-->
        <div class="row">
            <div class="container">
                <img
              src="building.jpg"
              alt="First game field"
              id="building-0"
              height="50"
              width="50"
              onclick="check(0)"
                />
            
            </div>
            <div class="container">
                <img
              src="building.jpg"
              alt="First game field"
              height="50"
              width="50"
              id="building-1"
              onclick="check(1)"
                />

            </div>
            <div class="container">
                <img
              src="building.jpg"
              alt="First game field"
              height="50"
              width="50"
              id="building-2"
              onclick="check(2)"
                />

            </div>
            <div class="container">
                <img
              src="building.jpg"
              alt="First game field"
              height="50"
              width="50"
              id="building-3"
              onclick="check(3)"
                />

            </div>
            <div class="container">
                <img
              src="building.jpg"
              alt="First game field"
              height="50"
              width="50"
              id="building-4"
              onclick="check(4)"
                />

            </div>
        </div>
        <!--row -2-->
        <div class="row">
            <div class="container">
                <img
              src="building.jpg"
              alt="First game field"
              height="50"
              width="50"
              id="building-5"
              onclick="check(5)"
                />

            </div>
            <div class="container">
                <img
              src="building.jpg"
              alt="First game field"
              height="50"
              width="50"
              id="building-6"
              onclick="check(6)"
                />
                
            </div>
            <div class="container">
                <img
              src="building.jpg"
              alt="First game field"
              height="50"
              width="50"
              id="building-7"
              onclick="check(7)"
                />
                
            </div>
            <div class="container">
                <img
              src="building.jpg"
              alt="First game field"
              height="50"
              width="50"
              id="building-8"
              onclick="check(8)"
                />
                
            </div>
            <div class="container">
                <img
              src="building.jpg"
              alt="First game field"
              height="50"
              width="50"
              id="building-9"
              onclick="check(9)"
                />
                         
            </div>
        </div>
        <!--row -3-->
        <div class="row">
            <div class="container">
                <img
              src="building.jpg"
              alt="First game field"
              height="50"
              width="50"
              id="building-10"
              onclick="check(10)"
                />
                
            </div>
            <div class="container">
                <img
              src="building.jpg"
              alt="First game field"
              height="50"
              width="50"
              id="building-11"
              onclick="check(11)"
                />
                
            </div>
            <div class="container">
                <img
              src="building.jpg"
              alt="First game field"
              height="50"
              width="50"
              id="building-12"
              onclick="check(12)"
                />                
            </div>
            <div class="container">
                <img
              src="building.jpg"
              alt="First game field"
              height="50"
              width="50"
              id="building-13"
              onclick="check(13)"
                />                
            </div>
            <div class="container">
                <img
              src="building.jpg"
              alt="First game field"
              height="50"
              width="50"
              id="building-14"
              onclick="check(14)"
                />                
            </div>
        </div>
        <!--row -4-->
        <div class="row">
            <div class="container">
                <img
              src="building.jpg"
              alt="First game field"
              height="50"
              width="50"
              id="building-15"
              onclick="check(15)"
                />                
            </div>
            <div class="container">
                <img
              src="building.jpg"
              alt="First game field"
              height="50"
              width="50"
              id="building-16"
              onclick="check(16)"
                />                
            </div>
            <div class="container">
                <img
              src="building.jpg"
              alt="First game field"
              height="50"
              width="50"
              id="building-17"
              onclick="check(17)"
                />                
            </div>
            <div class="container">
                <img
              src="building.jpg"
              alt="First game field"
              height="50"
              width="50"
              id="building-18"
              onclick="check(18)"
                />                
            </div>
            <div class="container">
                <img
              src="building.jpg"
              alt="First game field"
              height="50"
              width="50"
              id="building-19"
              onclick="check(19)"
                />                
            </div>
        </div>
        <!--row -5-->
        <div class="row">
            <div class="container">
                <img
              src="building.jpg"
              alt="First game field"
              height="50"
              width="50"
              id="building-20"
              onclick="check(20)"
                />                
            </div>
            <div class="container">
                <img
              src="building.jpg"
              alt="First game field"
              height="50"
              width="50"
              id="building-21"
              onclick="check(21)"
                />                
            </div>
            <div class="container">
                <img
              src="building.jpg"
              alt="First game field"
              height="50"
              width="50"
              id="building-22"
              onclick="check(22)"
                />                
            </div>
            <div class="container">
                <img
              src="building.jpg"
              alt="First game field"
              height="50"
              width="50"
              id="building-23"
              onclick="check(23)"
                />                
            </div>
            <div class="container">
                <img
              src="building.jpg"
              alt="First game field"
              height="50"
              width="50"
              id="building-24"
              onclick="check(24)"
                />                
            </div>
        </div>
        <!--row -6-->
        <div class="row">
            <div class="container">
                <img
                src="building.jpg"
                alt="First game field"
                height="50"
                width="50"
                id="building-25"
                onclick="check(25)"
                  />                
            </div>
            <div class="container">
                <img
              src="building.jpg"
              alt="First game field"
              height="50"
              width="50"
              id="building-26"
              onclick="check(26)"
                />                
            </div>
            <div class="container">
                <img
              src="building.jpg"
              alt="First game field"
              height="50"
              width="50"
              id="building-27"
              onclick="check(27)"
                />                
            </div>
            <div class="container">
                <img
              src="building.jpg"
              alt="First game field"
              height="50"
              width="50"
              id="building-28"
              onclick="check(28)"
                />                
            </div>
            <div class="container">
                <img
              src="building.jpg"
              alt="First game field"
              height="50"
              width="50"
              id="building-29"
              onclick="check(29)"
                />               
            </div>
        </div>
        <!--row -7-->
        <div class="row">
            <div class="container">
                <img
              src="building.jpg"
              alt="First game field"
              height="50"
              width="50"
              id="building-30"
              onclick="check(30)"
                />                
            </div>
            <div class="container">
                <img
              src="building.jpg"
              alt="First game field"
              height="50"
              width="50"
              id="building-31"
              onclick="check(31)"
                />                
            </div>
            <div class="container">
                <img
              src="building.jpg"
              alt="First game field"
              height="50"
              width="50"
              id="building-32"
              onclick="check(32)"
                />                
            </div>
            <div class="container">
                <img
              src="building.jpg"
              alt="First game field"
              height="50"
              width="50"
              id="building-33"
              onclick="check(33)"
                />                
            </div>
            <div class="container">
                <img
              src="building.jpg"
              alt="First game field"
              height="50"
              width="50"
              id="building-34"
              onclick="check(34)"
                />                
            </div>
        </div>

    </div>

    </body>
</html>