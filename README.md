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
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Carrear Details</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.2.1/css/all.min.css">
     <link rel="stylesheet" href="style.css">
  
</head>
<body>
  
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
  <section class="Carrear">
    
    
    <!--------------------- HSC details ------------------------------------------>   

                <h1 align="center"> HSC Details</h1><br>
                
               <table cellpadding="20px">
                      
                       
                       
                      <td style="padding-left: 0px;" >HSC Board :  
                        <select style="font-size: 15px" >
                        
                            <option>CBSE</option>
                            <option>ICSC</option>
                            <option>State board</option>
                        
                        </select>
                        </td>
                       
                          
                    </table>
                    <tr>
                      <tr>
                      <br>  <td>HSC Institued Name*</td>
                        <br><input type="text" name="HSC Institued Name* " maxlength="50" placeholder="Institued name" />
                        </tr>
                      
                    <tr>
                     <br><br> <td>HSC Percentage</td>
                      <br><input type="text" name="HSC Percentage " maxlength="50" placeholder="OBTAINED MARK" />
                      </tr>
                      <tr>
                        
                        <input type="text" name="HSC Percentage" maxlength="50" placeholder="MAXIMUM MARK" />
                        </tr>
                    
  <!--------------------- SSC details------------------------------------------>
                   <br><br> <h1 align="center">SSC Details</h1><br>
               <table cellpadding="20px">
                      <tr>
                          
                         
                        
                    
                    
                        <td style="padding-left: 0px;" >SSC Board :  
                        <select style="font-size: 15px" >
                            <option>CBSC</option>
                            <option>ICSC</option>
                            <option>State board</option>
                            
                        </select>
                        </td>
                      
                    </table>
                    <tr>
                     <br> <td>HSC Institued Name*</td>
                      <br><input type="text" name="HSC Institued Name* " maxlength="50" placeholder="Institued name" />
                      </tr>

                    <tr>
                    <br>  <td>SSC Percentage</td>
                      <br><input type="text" name="SSC Percentage " maxlength="50" placeholder="OBTAINED MARK" />
                      </tr>
                      <tr>
                        
                        <input type="text" name="SSC Percentage" maxlength="50" placeholder="MAXIMUM MARK" />
                        </tr>
                   
                    
               <!--------------------- pursuning details ------------------------------------------>
              <br><br> <h1 align="center">Pursuing Details</h1><br>
               <tr>
                <td>Currently Pursuning</td>
                <br><input type="text" name="Currently Pursuing " maxlength="50" placeholder="" />
                </tr>
                <tr>
                <br> <br> <td>Current Institued Name</td>
                  <br><input type="text" name="Current Institued Name " maxlength="50" placeholder="Institued name" />
                  </tr>
                  <tr>
                   <br><br> <td>Overall Percentage</td>
                    <br><input type="text" name="overall Percentage " maxlength="50" placeholder="OBTAINED MARK" />
                    </tr>
                    <tr>
                     <br> <br><td>Current backlogs if any*</td>
                      <br><input type="text" name="Current backlog of any* " maxlength="50" placeholder=" " />
                      </tr>



  




                      </section>

  <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.6.3/jquery.min.js"></script>

  <script src="script.js"></script>
    
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Upload Document</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.2.1/css/all.min.css">
     <link rel="stylesheet" href="style.css">
  
</head>
<body>
 
  
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
  <section class="docoument">
    <!--------------------- upload photo ------------------------------------------>
    <h1>Recent Passport Size Photograph
    <span>(image size less than 4MB)*</span>
    </h1>
    <br><input type="file" id="myFile" /> <br /><br />
    <!--------------------- upload hsc marksheet ------------------------------------------>
    <h1>HSC Mark Sheet 
      <span>(image, PDF or docs size less than 4MB)*</span>
      </h1>
      <input type="file" id="myFile" /> <br /><br />
      <!--------------------- upload ssc marksheet------------------------------------------>
      <h1>SSC Mark Sheet 
        <span>(image,PDF or docs size less than 4MB)*</span>
        </h1>
        <input type="file" id="myFile" /> <br /><br />
        <!--------------------- all semester mark sheet ------------------------------------------>
        <h1>ALL Semester Mark sheet In Single PDF or docs
          <span>(File size less than 10MB)*</span>
          </h1>
          <input type="file" id="myFile" /> <br /><br />

     
          <form name="myForm" action="/action_page.php" onsubmit="return validateForm()" method="post">
            
            <input type="submit" value="Submit">
            </form>
          
        

  
  </section>





  <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.6.3/jquery.min.js"></script>

  <script src="script.js"></script>
    
</body>
</html>

