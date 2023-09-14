# Surveys
Survey project
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="x-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
 <title>Document</title>
 <style>
    #candy {
        width: 250px;
        border: 5px solid blueviolet
     }
     #candy2 {
        width:250px;
        border: 5px solid pink
     }
 </style>
 </head>

<body>
    <!-- <h1> Welcome to Lexi's Project </h1> -->
    <form action="result.html" method="get">
 <div> 
    <lable for="name">Name:</lable>
    <input type="text" name="name" id="name" placeholder="Enter you name..."/>
    <br />
    <lable for="Username">User Name:</lable>
    <input type="text" name="Username" id="User Name" Placeholder="Enter your User Name.."/>
    </div>
   
    <div>
    <lable for="password">Password:</lable>
    <input type="password" name="Password" id="Password" placeholder="Enter your password...">
</div>

<div>
    <lable>Gender:</lable> <br />

    <lable for="male">Male</lable>
    <input type="radio" name="gender" id="male" value="Male">
    
    <lable for="female"> Female</lable>
 <input type="radio" name="gender" id="female" value="Female" checked>
</div>

 <div>
    <lable> Select Your Favorite Animal:</lable>
    
    <input type="checkbox" name="animal_1"id="Lion" Value="Lion" checked>
    <lable for="Lion">Lion</lable>
   
    <input type="checkbox" name="animal_2" id="dog" value="Dog">
    <lable for="Fish">Fish</lable>

    <input type="checkbox" name="animal_3" id="Dragon"value="Dragon" checked>
<lable for="Dragon">Dragon</lable>
</div>

<div>
    <lable for="color">Color:</lable>
    <input type="color" name="selected_color" id="color">
  </div>

    
     <div>
        <lable for="age">Age:</lable>
        <input type="number" name="age" id="age"
    </div>

    <div>
        <label for="search">Search</label>
        <input
        type="search"
        name="search"
        id="search"
        placeholder="search..." />
    </div>

        <div>
        <lable for="date">Enter Date:</lable>
        <input type="date" name="enter_date" id="date" min="2020-09-01"
        max="2021-11-30"/>
    </div>
   
     <div>
     <lable for="email">Email:</lable>
     <input type="email" name="entered_email" id="email" placeholder="example@exanple.com"/>
     </div>

    <div>
     <lable for="file"> Chose File:</lable>
     <input type="file" name="selected_file" id="file" multiple/>
    </div>
    
     <div>
     <lable for="phone"> Phone Number:</lable>
     <input type="tel" name="phone_number" id="phone" pattern="[0-9]{3}"-[0-9]{3}-[0-9]{4}" placeholder="xxx-xxx-xxx"/>
     </div>
     <hr />
     <div>
     <lable for="candy">Which candy do you like?</lable>
     <br />
     <select name="sweet" id="candy" multipe size="6">
      <option value="Sour patch kids">Sour Patch Kids</option>
      <option value="Sour Gum Drop">Sour Gum Drop</option>
      <option value="Sour Punch">Sour Punch</option>
      <option value="AIR HEAD XTREMES"> AIR HEAD XTREMES</option>
      <option value="Slime Licker"> Slime Licker</option>
      <option value="Haribo sour candy"> Haribo sour candy</option>
       </select>
     </div>
        
        <div>
        <lable for="candy2">Which sweets do you like?</lable>
        <br /> 
     <select name="sweet" id="candy2" multiple size="8">
      <optgroup label="Chocolate desserts">
      <option value="Chocolate Cake"> Chocolate Cake</option>
      <option value="Milk Duds"> Milk Duds</option>
      <option value="Chocolate Pudding"> Chocolate Pudding</option>
      <option value="Chololate brownie">Chocolate Brownie</option>
      <option value="Chololate Almonds"> Chocolate Almonds</option>
   </optgroup>

   <optgroup label="Vanilla Desserts"> 
        <option value="Vanilla Pudding">Vanilla Pudding</options>
        <option value="Vanilla cake">Vanilla Cake</option>
        <option value="Vanilla icecream">Vanilla Icecream</option>
        <optin value="Vanilla truffle">Vanilla Truffle</optin>
        </optgroup>
</select>
</div>
<br /><br /><br />

<div>
    <label for="comment"> Please leave a comment:</lable>
    <br />
    <textarea
    name="comment"
    id="comment"
    style="resize: none; width: 75%"
    placeholder="Write your comment here...">
</textarea>
</div>    

 <br /><br /><br /><br />
 <input type="reset" />
 <input type="Submit"/>
 </form>
 </body>
 </html>
        
