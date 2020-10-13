<html>
 <head> 
  <title> Form with table </title> 
 </head> 
 <body> 
  <form> 
   <h1><u>Application form</u></h1> Name: 
   <input type="text" name="your name" maxlength="15"> 
   <br> Address: 
   <input type="text" name="Addr"> 
   <br> Gender: 
   <input type="radio" name="Gndr" value="M">Male 
   <input type="radio" name="Gndr" valur="F">Female 
   <br> Contact#: 
   <input type="text" name="Cnum"> 
   <p> E-mail ID:<input type="text" name="email"><br> Password:<input type="PASSWORD" mame="pwd"></p> 
   <br> 
   <table border="2" bordercolor="black" cellpadding="5"> 
    <tbody> 
     <tr> 
      <th>Combination opted</th> 
      <th>Facilities required </th> 
     </tr> 
     <tr> 
      <td><input type="radio" name="course" value="pcmc"> PCMC <br> <input type="radio" name="course" value="ceba"> CEBA <br> <input type="radio" name="course" value="pcmb"> PCMB </td> 
      <td> <input type="checkbox" name="hstl" value="yes"> Hostel <br> <input type="checkbox" name="tr" value="yes"> Transportation <br> <input type="checkbox" name="coaching" valut="yes"> Extra coaching <br> </td> 
     </tr> 
    </tbody> 
   </table> 
   <p> Remarks/Comments if any: <br> <textarea name="comment" rows="2" cols="50">
     </textarea> </p> 
   <input type="submit" value="Submit the form"> 
   <input type="Reset"> 
  </form> 
 </body>
</html>
