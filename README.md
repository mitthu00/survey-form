
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Survey Form</title>
    <style>
        .wrap{

color: white;
border: hidden;
min-width: 10px;
background-attachment:fixed;
height: auto;
background-image: linear-gradient(rgba(0, 0, 0, 0.8),rgba(0, 0, 0, 0.8)),url(pro.jpeg) ;
background-repeat: no-repeat;
background-position: center;
background-size: cover;

margin-right: 500px;
overflow-x: hidden;
margin-left: 500px;
float: right;

float: auto;
font-size: 25px;
text-shadow: 3px 3px 3px black;

}
.heading{
display: block;
text-shadow: 3px 3px 3px black;
}
.width{
width: 400px;
border-radius: 50px;
}
.wrap2{
 color: white;

}
table,tr,td,th {
border:hidden;
border-collapse: collapse;
text-align: center;
caption-side: top;
min-width: 50px;
min-height: 70px;
}
body{
background-color: rgba(0, 0, 0, 0.8);

display: block;
block-size: 220px;
}

.wrap3{

display: flex;
justify-content: center ;
display: block;
align-items: center;

color: white;
border: hidden;
min-width: 100px;



height: auto;
background-image: linear-gradient(rgba(0, 0, 0, 0.8),rgba(0, 0, 0, 0.8)),url(bgcrop.jpg) ;
background-attachment: fixed;
background-repeat: no-repeat;
background-position: center;
background-size: cover;


margin-right: 500px;
margin-left: 500px;
float: auto;
font-size: 25px;
text-shadow: 3px 3px 3px black;
}

textarea{
background-color: rgb(52, 49, 49);

color: white;
border: hidden;
font-size: medium;
margin-bottom: 2px;
}



    </style>
    <script>
        function check()
        {
            var uname=document.getElementById("uname");
            if(uname.value==0){
                alert("Name can't be empty");
                return false;
            }
            var pass=document.getElementById("pass");

            if(pass.value==0){
                alert("Email can't be empty");
                return false;
            }


            else {
                return true;
            }
        }
    </script>
</head>
<body>
 
    <div class="wrap">
        
        
        <form action="greentick.html" onsubmit="return check();" name="google-sheet">
           
            <h1 class="heading" align="center">Survey Form</h1>
            <hr>
            <label  for="Name">Name:</label>
            <br>
            <input id="uname" type="text" class="width" placeholder="Enter your name" name="Name">
            <br>
            <label  for="Email">Email:</label>
            <br>
            <input id="pass" class="width" type="email" placeholder="Enter your Email" name="Email">
            <br>
            <label  for="Ph no.">Contact Number:</label>
            <br>
            <input id="cpass" class="width"type="number" name="Ph. no">
            <br>
            <label for="gen">Gender:</label>
            <br>
          
        
            <select>
                <option value="I">Male</option>
                <option value="I">Female</option>
            </select>
            <br>
         
            <br>
            <hr>
            <br>
            

            <label for="optn3">1. Are you fully satisfied with the cleanliness and condition of bedding of our rooms?</label>
            <br>
            <br>
            <input type="radio"  name="optn3">Yes
            <br>
            <input type="radio" name="optn3">No
            <br><br>
            <br>
            <label for="optn4">2. Please rate your experience on the following</label>
            <br>
            <br>
       
            <table>
                <thead>
                   <td colspan="1"></td>
                    <td>Excellent</td>
                    <span>  </span>
                   <td>Great</td>
                   <td>Good</td>
                   <td>Fair</td>
                   <td>Poor</td>


</thead>
                <tbody>
                    <tr>
                        <td>Bathroom cleanliness</td>
                        <td > <input type="radio" name="optn30"></td>
                        <td > <input type="radio" name="optn30"></td>
                        <td > <input type="radio" name="optn30"></td>
                        <td > <input type="radio" name="optn30"></td>
                        <td > <input type="radio" name="optn30"></td>
                    </tr>
                  
                    <tr>
                        <td>Physical condition </td>
                        <td > <input type="radio" name="optn31"></td>
                        <td > <input type="radio" name="optn31"></td>
                        <td > <input type="radio" name="optn31"></td>
                        <td > <input type="radio" name="optn31"></td>
                        <td > <input type="radio" name="optn31"></td>
                    </tr>
                     <tr>
                        <td>Quality of bath amenities</td>
                        <td > <input type="radio" name="optn32"></td>
                        <td > <input type="radio" name="optn32"></td>
                        <td > <input type="radio" name="optn32"></td>
                        <td > <input type="radio" name="optn32"></td>
                        <td > <input type="radio" name="optn32"></td>
                    </tr>
                    <tr>
                        <td>Lighting in bathroom</td>
                        <td > <input type="radio" name="optn33"></td>
                        <td > <input type="radio" name="optn33"></td>
                        <td > <input type="radio" name="optn33"></td>
                        <td > <input type="radio" name="optn33"></td>
                        <td > <input type="radio" name="optn33"></td>
                    </tr>
                    <tr>
                        <td>Towels and bath robe material</td>
                        <td > <input type="radio" name="optn34"></td>
                        <td > <input type="radio" name="optn34"></td>
                        <td > <input type="radio" name="optn34"></td>
                        <td > <input type="radio" name="optn34"></td>
                        <td > <input type="radio" name="optn34"></td>
                    </tr>

                </tbody>
                <br>
            </table>
  
        
       
        
        <br>
    </div>
   
   
    <div class="wrap3">
        <br>
        
        <label  for="g1"> 3. Which room type did you choose for your stay?</label>
        <br>
        <br>
         <input type="radio" name="g1"  />Standard
         <br>
         <input type="radio" name="g1" />Deluxue
         <br>
         <input type="radio" name="g1"  />Executive
         <br>
         <input type="radio" name="g1" />Suite
       
         <br>
         <br>
         <br>
       
        <label for="optn2">4. Was the condition of the room & furnishings satisfactory?</label>
        <br>
        <br>
        <input type="radio" name="optn2" >Yes
        <br>
        <input type="radio" name="optn2" >No
        <br><br>
        <br>
        <label for="yn">5. Did you face any problems while accessing our Internet service in room ?</label>
        <br>
        <br>
      
        <input type="radio" name="yn">Yes 
     <br>
        <input type="radio" name="yn">No
        <br>
        <br>
        <br>
        <label for="yn">6. Did you find the workspace in the room comfortable to work?</label>
      <br>
      <br>
        <input type="radio" name="yn">Yes 
     <br>
        <input type="radio" name="yn">No
        <br>
        <br><br>
        <label for="add">7. General comments</label>
        <br>
        <br>
        <textarea  name="add"rows="7"cols="72"></textarea>

<br><br>
          <form action="greentick.html">
            <input type="submit" name="sname" value="submit"/>
          </form>
           
     </div>
    </form>
    
<script>
    const scriptURL = 'https://script.google.com/macros/s/AKfycbzIvARZZbpQ6VR7IntS9FiHCCo-r58Fa-FcnCc691m5fb5qYZaIEQvs8bj8aTrY3WHB/exec'
    const form = document.forms['google-sheet']
  
    form.addEventListener('submit', e => {
      e.preventDefault()
      fetch(scriptURL, { method: 'POST', body: new FormData(form)})
        .then(response => alert("Thanks for Contacting us..! Your Response has been submitted"))
        .catch(error => console.error('Error!', error.message))
    })
  </script>

</body>
</html>
