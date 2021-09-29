<!DOCTYPE html>
<html>
<body>
<head>
<meta charset="utf-8">
<title> Med.History </title>
</head>
<h1>Medical History</h1>

<form action="survey-form.php">

  <b>Full Name<br></b>
  <label for="FIRSTname"></label>
  <input type="text" id="FIRSTname" name="First name" >
  <label for="LASTname"></label>
  <input type="text" id="LASTname" name="Last name" ><br>

  <p>Name_________________Last Name</p>

  <b>Phone number</b>
  <label for="PHnumber"></label><br>
  <input type="number" id="PHnumber" name="PHumber" >

  <br><br>

  <b>1. Check the condition that apply to you or to any members of your immediate relatives</b>
   <label for="con"></label><br>
  <input type="checkbox" id="con" name="con" >Asthma
  <label for="con"></label><br>
  <input type="checkbox" id="con" name="con" >Cancer
  <label for="con"></label><br>
  <input type="checkbox" id="con" name="con" >Cardic disease
  <label for="con"></label><br>
  <input type="checkbox" id="con" name="con" >Diabetes
  <label for="con"></label><br>
  <input type="checkbox" id="con" name="con" >Hypertension
  <label for="con"></label><br>
  <input type="checkbox" id="con" name="con" >Psygiatric disorder
  <label for="con"></label><br>
  <input type="checkbox" id="con" name="con" >Epilepcy

  <br><br>

  <b>2. Check the symptoms that you're currently experiencing</b>

   <label for="symp"></label><br>
  <input type="checkbox" id="symp" name="symp" >Chest pain
  <label for="symp"></label><br>
  <input type="checkbox" id="symp" name="symp" >Respiratory
  <label for="symp"></label><br>
  <input type="checkbox" id="symp" name="symp" >Cardic disease
  <label for="symp"></label><br>
  <input type="checkbox" id="symp" name="symp" >Cardiovascular
  <label for="symp"></label><br>
  <input type="checkbox" id="symp" name="symp" >Hematological
  <label for="symp"></label><br>
  <input type="checkbox" id="symp" name="symp" >Neurological
  <label for="symp"></label><br>
  <input type="checkbox" id="symp" name="symp" >Psychiatric
  <label for="symp"></label><br>
  <input type="checkbox" id="symp" name="con" >Gastrointestial
  <label for="symp"></label><br>
  <input type="checkbox" id="symp" name="symp" >Genitourinary
  <label for="symp"></label><br>
  <input type="checkbox" id="symp" name="symp" >Weight gain
  <label for="symp"></label><br>
  <input type="checkbox" id="symp" name="symp" >Weeight loss
  <label for="symp"></label><br>
  <input type="checkbox" id="symp" name="symp" >Muskulosceletal

  <br><br>

  <b>3. Are you currently taking any medication?</b><br>

  <label for="med"></label>
  <input type="radio" id="med" name="med" >Yes<br>
  <label for="med"></label>
  <input type="radio" id="med" name="med" >No

  <br><br>

  <b>4. Do you have any medication allergasy?</b><br>

  <label for="aller"></label>
  <input type="radio" id="aller" name="aller" >Yes<br>
  <label for="aller"></label>
  <input type="radio" id="aller" name="aller" >No<br>
  <label for="aller"></label>
  <input type="radio" id="aller" name="aller" >Not sure

  <br><br>

  <b>5. What is your gender?</b><br>

  <label for="gen"></label>
  <input type="radio" id="gen" name="gen" >Male<br>
  <label for="gen"></label>
  <input type="radio" id="gen" name="gen" >Female

  <br><br>

  <b>6. Do you use or do you have history of using tobacco?</b>

  <br><br>

  <select name="tob" required="required">
    <option value="">Yes</option>
    <option>No</option>
  </select>

  <br><br>

  <b>7. Do you use or do you have history of using illegal drugs?</b>

  <br><br>

  <select name="drug" required="required">
    <option value="">Yes</option>
    <option>No</option>
  </select>

  <br><br>

  <b>8. How often do you consume alcohol?</b><br>

  <table style="width:50%">
  <tr>
  <td><label for="alco"></label>
  <input type="radio" id="alco" name="alco" >Daily</td>
  <td><label for="alco"></label>
  <input type="radio" id="alco" name="alco" >Weekly</td>
  </tr>
  <tr>
  <td><label for="alco"></label>
  <input type="radio" id="alco" name="alco" >Monthly</td>
  <td><label for="alco"></label>
  <input type="radio" id="alco" name="alco" >Occasionally</td>
  <td><label for="alco"></label>
  </tr>
  <tr>
  <td><input type="radio" id="alco" name="alco" >Never</td>
  </tr>
  </table>

  <br><br>

  <input type="submit">

</form> 
</body>
</html>
