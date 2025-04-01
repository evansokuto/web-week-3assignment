# web-week-3assignment

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>osiepe united</title>
    <!-- 3. external css -->
  <link rel="stylesheet" href="cssstyle.css">

    <h1>osiepe LISTS</h1>
    <ol type="i">

        <li>Emmanuel Ochieng'</li>
        <li>Evans Okuto</li>
        <li>Okuto Violet</li>
        <li>Okuto Kliens</li>
        <li>Mercy Okuto</li>

        <h1>IMAGE</h1>
        <a href="https://www.pexels.com/photo/iconic-eiffel-tower-replica-at-paris-las-vegas-31325144/">
            <img src="image.jpg" alt="click to visit" width="350" height="350">
        </a>
     <br><br>

     <table border="2">
        <caption>OSIEPE DETAILS</caption>
        <head>
            <tr>
                <th>name</th>
                <th>address</th>
                <th>mobile</th>
                <th>email</th>
            </tr>
        </head>
        <tbody>
            <tr>
                <td>Evans Okuto</td>
                <td>Nairobi</td>
                <td>0768950554</td>
                <td>evansokuto2019@gmail.com</td>
            </tr>
            <tr>
                <td>Emmanuel ochieng</td>
                <td>Kisumu</td>
                <td>0795134979</td>
                <td>emmanuelochieng@gmail.com</td>
            </tr>
            <tr>
                <td>Violet Okuto</td>
                <td>Homabay</td>
                <td>0792796978</td>
                <td>violetokuto@gmail.com</td>
            </tr>
            <tr>
                <td>Okuto Kleins</td>
                <td>Siaya</td>
                <td>0712134979</td>
                <td>okutokleins@gmail.com</td>
            </tr>
            <tr>
                <td>Mercy Okuto</td>
                <td>Kisii</td>
                <td>0712345678</td>
                <td>mercyokuto@gmail.com</td>
            </tr>
        </tbody>
     </table border ="2">
        <br><br>

        <h1>REGISTRATION FORM</h1>
        <form action="" method="">
            <label for="name"></label>.
            <input type="text" id="student name" name="student name" placeholder="Enter your full name" required>
            <br><br>
            <label for="email">Email</label>
            <input type="email" id="email" name="email" placeholder="Your Email" placeholder="user@example.com" required>
            <br><br>
            <label for="password">password</label>
            <input type="password" id="password" name="password" placeholder="Minimum 8 characters"  required>
            <br><br>
            <label for="dob">Date of Birth:</label>
            <input type="date" id="dob" name="dob" required>
            <br><br>
            <label for="gender"></label>
            <input type="radio" id="gender" name="gender" value="female"> female
            <input type="radio" id="gender" name="gender" value="male"> male
            <br><br>
            <label for="county">county</label>
            <select name="county" id="county"> 
                <option> -- select county --</option>
                <option value="Kisumu">Kisumu</option>
                <option value="Siaya">Siaya</option>
                <option value="Nigeria">Homabay</option>
                <option value="Kisii">Kisii</option>
                <option value="Nairobi">Nairobi</option>
            </select>
            <br><br>
            <label>Job tittle:</label>
            <input type="checkbox" id="teacher" name="job tittle" value="teacher">
            <label for="teacher">teacher</label>
            <input type="checkbox" id="farmer" name="job tittle" value="farmer">
            <label for="farmer">farmer</label>
            <input type="checkbox" id="others" name="job tittle" value="others">
            <label for="tohers">others</label>
            <br><br>
            <button type="submit">submit</button>
  </form>
            <footer>
                <p class="highlight">&copy; 2025. All rights reserved.</p>
            </footer>
</html>


css style folder

body{
     background-color: rgba(235, 220, 85, 0.734);
 }
 
 #heading {
     text-align: center;
     text-decoration: underline;
 }
 
 input, textarea {
     width: 100%;
     border: 1px solid rgb(255, 64, 0);
     border-radius: 5px;
     font-size: 16px;
 }
 
 label {
     display: block;
     font-weight: bold;
 }
 
 button {
     background-color: rgb(66, 213, 47);
     color: white;
     border: none;
     border-radius: 5px;
     font-size: 16px;
