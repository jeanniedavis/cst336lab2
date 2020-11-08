<!DOCTYPE html>
<html>
    <head>
        <meta charset ="utf-8">
        <title> US Quiz</title>
        <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" integrity="sha384-JcKb8q3iqJ61gNV9KGb8thSsNjpSL0n8PARn9HuZOnIxN0hoP+VmmDGMN5t9UJ0Z" crossorigin="anonymous">
        <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
        <script src = "https://cdnjs.cloudflare.com/ajax/libs/underscore.js/1.9.1/underscore-min.js" ></script> 
        <script>
            $(document).ready(function() {
                // $("button").on("click", function(){
                //     console.log($("#q1").val());
            //    }); //click
            //Global Variables
            var score = 0;
            var attempts=localStorage.getItem("total_attempts");
            //event Listeners
            $("button").on("click", gradeQuiz);
            //question 5 images
            $(".q5Choice").on("click", function() {
                $(".q5Choice").css("background","");
                $(this).css("background","rgb(255, 255, 0)");
            });
            displayQ4Choices();
            //functions
            
          function displayQ4Choices() {
            let q4ChoicesArray =["Maine", "Rhode Island", "Maryland", "Delaware"];
            q4ChoicesArray = _.shuffle(q4ChoicesArray);
            for (let i=0; i<q4ChoicesArray.length; i++) {
                $("#q4Choices").append(`<input type="radio" name="q4" id="${q4ChoicesArray[i]}" value="${q4ChoicesArray[i]}"> <label for ="${q4ChoicesArray[i]}"> ${q4ChoicesArray[i]}</label>`);
            }
            }
            function isFormValid(){
                let isValid=true;
                if($("#q1").val() =="") {
                    isValid=false;
                    $("#validationFdbk").html("Question 1 was not answered");
                }
                return isValid;
            }
            
            function rightAnswer(index){
                $(`#q${index}Feedback`).html ("Correct!");
                $(`#q${index}Feedback`).attr("class", "bg-success text-white");
                $(`#markImg${index}`).html("<img src ='img/checkmark.png' alt='checkmark'>");
                score+=10;
               

            }
            function wrongAnswer(index){
                $(`#q${index}Feedback`).html("Incorrect!");
                $(`#q${index}Feedback`).attr("class", "bg-warning text-white");
                $(`#markImg${index}`).html("<img src = 'img/xmark.png' alt='xmark'>");
            }
            function gradeQuiz(){
                
                $("#validationFdbk").html(""); //resets validation feedback
                
                if(!isFormValid()){
                    return;
                }
                
                //variables
                score = 0;
                let q1Response = $("#q1").val().toLowerCase();
                let q2Response = $("#q2").val();
                //let q3Response =$("q3").val();
                let q4Response = $("input[name=q4]:checked").val();
                let q6Response=$("#q6").val().toLowerCase();
                let q7Response = $("input[name=q7]:checked").val();
                let q8Response=$("#q8").val().toLowerCase();
                let q9Response=$("#q9").val().toLowerCase();
                let q10Response = $("#q10").val();

                //question 1
                if(q1Response=="sacramento") {
                  rightAnswer(1);
                } else{
                    wrongAnswer(1);
                }
                //question2
                 if(q2Response=="mo") {
                    rightAnswer(2);
                } else{
                    wrongAnswer(2);
                }
                //question3
               if ($("#Jefferson").is(":checked") && $("#Roosevelt").is(":checked") && !$("#Jackson").is(":checked") && !$("Franklin").is(":checked")) {
                   rightAnswer(3);
               } else{
                   wrongAnswer(3);
               }
               //question4
               if(q4Response =="Rhode Island"){
                   rightAnswer(4);
               }else{
                   wrongAnswer(4);
               }
               //question5
               if ($("#seal2").css("background-color") =="rgb(255, 255, 0)") {
                   rightAnswer(5);
               } else {
                   wrongAnswer(5);
               } 
               //question6
               if(q6Response =="washingtondc" || q6Response =="washington dc"){
                   rightAnswer(6);
               }
               else {
                   wrongAnswer(6);
               }
              
              //question 7
                if ($("#Washington").is(":checked") && !$("#California").is(":checked") && !$("#Seattle").is(":checked") && !$("Miami").is(":checked")) {
                   rightAnswer(7);
               } else{
                   wrongAnswer(7);
               }
               //question 8
              if(q8Response =="pacific ocean" || q8Response =="pacificocean" || q8Response=="pacific"){
                   rightAnswer(8);
               }
               else {
                   wrongAnswer(8);
               }
               //question 9
                if(q9Response =="mexico"){
                   rightAnswer(9);
               }
               else {
                   wrongAnswer(9);
               }
                if(q10Response=="sf") {
                    rightAnswer(10);
                } else{
                    wrongAnswer(10);
                }
                if (score >=80){
                $("#totalScore").attr("class", "text-success").html(`Nice! Your total score is  ${score}`);
                  }
                  else {
                     $("#totalScore").attr("class", "text-danger").html(`Good job! Your total score is  ${score}`);
                   // $("#totalScore").html(`Good job! Your total score is  ${score}`);
                    }}
                $("#totalAttempts").html(`Total Attempts: ${++attempts}`);
                    localStorage.setItem("total_attempts", attempts);
                }) //ready
        </script>
    </head>
    <body class="text-center">
        <h1 class="jumbotron">US Geography Quiz</h1>
        <h3><span id="markImg1"></span> What is the capital of California?</h3>
        <input type ="text" id="q1">
        <br><br>
        <div id="q1Feedback"></div>
        <br><br>
        <h3><span id="markImg2"></span> What is the longest river?</h3>
        <select id="q2">
            <option value =""> Select One</option>
            <option value ="ms"> Mississippi</option>
            <option value="mo"> Missouri</option>
            <option value ="co">Colorado</option>
            <option value"de">Delaware</option>
        </select>
        <br><br>
        <div id="q2Feedback"></div>
        <br>
        <h3><span id="markImg3"></span>What presidents are carved into Mount Rushmore?</h3>
        <input type="checkbox" id="Jackson"> <label for="Jackson"> A.Jackson</label>
        <input type="checkbox" id="Franklin"> <label for="Franklin"> B.Franklin</label>
        <input type="checkbox" id="Jefferson"> <label for="Jefferson"> T.Jefferson</label>
        <input type="checkbox" id="Roosevelt"> <label for="Roosevelt"> T. Roosevelt</label>
        <br><br>
        <div id="q3Feedback"></div>
        <br><br>
        <h3><span id="markImg4"></span> What is the smallest US State?</h3>
        <div id="q4Choices"></div>
        <div id="q4Feedback"></div>
        <br><br>
        <h3><span id="markImg5"> What image is in the Great Seal of the State of California?</span></h3>
        <img src="img/seal1.png" alt="Seal 1" class="q5Choice" id="seal1"></img>
        <img src="img/seal2.png" alt="Seal 2" class="q5Choice" id="seal2"></img>
        <img src="img/seal3.png" alt="Seal 3" class="q5Choice" id="seal3"></img>
        <div id="q5Feedback"></div>
        <br><br>
        <h3><span id="markImg6"></span> What is the capital of the United States of America?</h3>
        <input type ="text" id="q6">
        <br><br>
        <div id="q6Feedback"></div>
        <br>
        <h3><span id="markImg7"></span> Where is the White House located?</h3>
        <input type="checkbox" id="Washington"> <label for="Washington"> Washington DC</label>
        <input type="checkbox" id="California"> <label for="California"> California</label>
        <input type="checkbox" id="Seattle"> <label for="Seattle"> Seattle</label>
        <input type="checkbox" id="Miami"> <label for="Miami"> Miami</label>
        <br><br>
        <div id="q7Feedback"></div>
        <br>
        <h3><span id="markImg8"></span> What ocean is immediately West of California?</h3>
        <input type ="text" id="q8">
        <br><br>
        <div id="q8Feedback"></div>
        <br>
         <h3><span id="markImg9"></span> What country is immediately South of the United States</h3>
        <input type ="text" id="q9">
        <br><br>
        <div id="q9Feedback"></div>
        <br>
        <h3><span id="markImg10"></span> Where is the Golden Gate Bridge Located?</h3>
        <select id="q10">
            <option value =""> Select One</option>
            <option value ="sf"> San Francisco</option>
            <option value="sd"> San Diego</option>
            <option value ="sa">Santa Ana</option>
            <option value"sl">Saint Louis</option>
        </select>
        <br><br>
        <div id="q10Feedback"></div>
        <h3 id="validationFdbk" class="bg-danger text-white"></h3>
        <button class= "btn btn-info"> Submit Quiz</button>
        <br>
        <h2 id="totalScore" class="text-info"></h2>
        <h3 id="totalAttempts"></h3>
    </body>
</html>