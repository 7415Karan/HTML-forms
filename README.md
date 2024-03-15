# HTML-forms
<!DOCTYPE html>
<html lang="en">
  <head>
    <link rel="stylesheet" href="./Form.css" />
    <title>From</title>
  </head>
  <body>
    <center>
      <h1>HTML Form</h1>
    </center>

      <form action="">
        <div class="formGroup">
          <label for="name">Name: </label>
          <input type="text" placeholder="Enter you name" id="name" />
        </div>

        <div class="formGroup">
          <label for="email">Email: </label>
          <input type="email" placeholder="Enter your email" id="email" />
        </div>

        <div class="formGroup">
          <label for="phone">Mob. No.: </label>
          <input type="tel" placeholder="Enter your mob. no." id="phone" />
        </div>

        <div class="formGroup">
          <label for="gender">Gender: </label>
          <input type="radio" id="male" name="gender">
          <label for="male">Male</label>
          
          <input type="radio" id="female" name="gender">
          <label for="female">Female</label>
          
          <input type="radio" id="other" name="gender">
          <label for="other">Other</label>
        </div>

        <div class="formGroup">
          <label for="fruits">Fav. Fruits: </label>

          <input type="checkbox" name="fruits" id="Apple">
          <label for="Apple">Apple</label>

          <input type="checkbox" name="fruits" id="Grapes">
          <label for="Grapes">Grapes</label>

          <input type="checkbox" name="fruits" id="Banana">
          <label for="Banana">Banana</label>
        </div>

        <div class="formGroup">

          <label for="cars">Cars: </label>

          <select name="" id="cars">
            <option value="in">select</option>
            <option value="in">India</option>
            <option value="BMW">BMW</option>
            <option value="Volvo">Volvo</option>
          </select>

        </div>
        
        <div class="formGroup">
          <input type="submit" value="Submit" />
          <input type="reset" value="Reset" />
        </div>
      </form>
  </body>
</html>

*************CSS**********
.formGroup{
  margin: 1rem;

  margin-left: 5rem;
}
