<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Personal Details</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.2.1/css/all.min.css">
     <link rel="stylesheet" href="style.css">
  
</head>
<body>
    <form name="contactForm" onsubmit="return validateForm()" action="confirmation.php" method="post"></form>
    <header>
    
        <h1 class="heading">Registration Form</h1>
        <nav class="navbar">
            <ul>
               
                <li><a href="personal.html">Personal Details</a></li>
                <li><a href="Carrear.html">Carrear Details</a></li>
                <li><a href="docoument.html">Upload Docoument</a></li>
                
            </ul>
        </nav>
      </header>
      <section class="personal">
        
         
         <!--------------------- First Name ------------------------------------------>
    <tr>
        <td>Name*</td>
        <br><input type="text" name="Name" maxlength="50" placeholder="First" />
        </tr>
        
        <!------------------------ Last Name --------------------------------------->
        <tr>
        <td><input type="text" name="LastName" maxlength="50" placeholder="last"/>
        </td>
        </tr>
       
        <!--------------------------Date Of Birth----------------------------------->
        <tr>
        <br><br>
        <td>Date of birth*</td>
        <td>
           <br> <input type="date">
        </td>
       
        <!-------------------------- Email ID ------------------------------------->
        <tr>
        <br><br>
        <td>Email*</td>
        <br>
        <td><input type="email" name="EmailID" maxlength="100" placeholder=""/></td>
    
         <!--------------------- Father First Name ------------------------------------------>
         <tr>
           <br> <br><td>Father Name*</td>
            <br><input type="text" name="Name" maxlength="50" placeholder="First" />
            </tr>
            
            <!------------------------ Last Name --------------------------------------->
            <tr>
            <td><input type="text" name="LastName" maxlength="50" placeholder="last"/>
            </td>
            </tr>
             <!--------------------- MOther First Name ------------------------------------------>
         <tr>
            <br><br> <td>Mother Name*</td>
             <br><input type="text" name="Name" maxlength="50" placeholder="First" />
             </tr>
    
              <!------------------------ Last Name --------------------------------------->
             <tr>
             <td><input type="text" name="LastName" maxlength="50" placeholder="last"/>
             </td>
             </tr>
    
        </tr>
              <!---------------------- Gender ------------------------------------->
    <tr>
        <br><br><td>Gender*</td>
        <td>
       <br> <input type="radio" name="Gender" value="Male" />
        M
        <br> <input type="radio" name="Gender" value="Female" />
        F
        </td>
        </tr>
        <!------------------------- Nationality ---------------------------------->
<tr>
    <br><br><td>Nationality*</td>

        <br>
        <td><input type="Nationality" name="nationality" maxlength="100" placeholder=""/></td>
    <!------------------------- Home adress ---------------------------------->
    <tr>
        <br><br> <td>Home Adress*</td>
         <br><input type="text" name="Name" maxlength="50" placeholder="Street Adress" />
         </tr>
         <tr>
             <br><br><input type="text" name="Name" maxlength="50" placeholder="city" />
             <tr>
                <input type="text" name="Name" maxlength="50" placeholder="country" />
             </tr>
             </tr>
                 <!------------------------- Telephone home ---------------------------------->
                 <tr>
                    <br><br> <td>Telephone Home*</td>
                     <br><input type="text" name="Name" maxlength="50" placeholder="#######" />
                     </tr>
                     <!------------------------- Telephone Mobile---------------------------------->
                 <tr>
                    <br> <br><td>Telephone Mobile*</td>
                     <br><input type="text" name="Name" maxlength="50" placeholder="#######" />
                     </tr>
                     
                   
                    
     
     

       
                    </section>
     

      



  <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.6.3/jquery.min.js"></script>

  <script src="script.js"></script>
    
</body>
</html>
