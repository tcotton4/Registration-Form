# Registration-Form
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Registration Form</title>
</head>
<body>
    <h1> Registration Form</h1>
    <form action="/process" method="post">
    <div>
        <label>First Name: * </label>
        <input type="text" name= "name">
    </div>
    <div>
        <label> Last Name: *</label>
        <input type="text" name= "name">
    </div>
    <div>
        <label>Email Adress: *</label>
        <input type= "text" name= "email">
    </div>
    <div> 
        <label> Password: *</label>
        <input type="password" name= "password">
    </div>
    <div> 
        <label> Confirm Password: *</label>
        <input type="password" name="password">
    </div>
    <div>
        <label> Birthday:</label>
        <input type="date" name="dob">
    </div>
    <div> 
        <label>Gender Identity:</label>
    </div>
    <div>
        <input type="radio" id="male" name="gender" value="male">
        <label for= "male">Male</label>
        <input type="radio" id="female" name="gender" value="female">
        <label for= "female">Female</label>
        <input type="radio" id="non" name="gender" value="non">
        <label for= "non">Non-binary</label>
        <input type="radio" id="prefer" name="gender" value="prefer">
        <label for= "prefer">I prefer not to answer</label>
    </div>
    <div> 
        <textarea name="comment" cols="25" rows="5">
        </textarea>
    </div> 
    <div>
    <select name="codelang">
        <option>JavaScript</option>
        <option>HTML</option>
        <option>Python</option>
        <option>CSS</option>
        <option>MERN</option>
    </select>
    </div>
    <div>
        <input type="checkbox" name="yes" id="yes">
        <label for="yes">Yes, I would like to receive periodic email updates</label>
    </div>
    <div>
        <input type="submit" value="Create Account">
    </div>
    </form>

    <p> * Indicates a required field</p>
</body>
</html>
