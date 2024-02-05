<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HR Portal</title>
    <link rel="shortcut icon" href="/download.png" type="image/x-icon">
    <style>
        body{
         margin: 0px;
         padding: 0px;
            font-family: Arial, sans-serif;
            background-color:aliceblue;
        }
            header ,footer{
                background-color: rgb(161, 86, 161);
                color:blanchedalmond;
                text-align: center;
                padding: 2px;
            }
            .navitem{

                display: inline;
                padding: 15px;
            }
            .navitem a {
                text-decoration: none;
                color: blanchedalmond;
            }
            .registerform{
                width: max-content;
                margin-left: auto;
                margin-right: auto;

            }
            .employeetable{
                text-align: center;
            }
            table{
                margin-left: auto;
                margin-right: auto;
                width: 100%;
                border-collapse: collapse;
            }
             th,td{
                border: 1px solid blanchedalmond;
                padding: 5px;
             }
             .contactus{
                text-align: center
             }
        
    </style>
</head>
<body>
    <header>
        <h1>Welcome to Company HR Portal</h1>
        <nav>
        <ul>
            <li class="navitem"><a href="#employee-registration">Employee Registration</a></li>
            <li class="navitem"><a href="#employee-directory">Employee Directory</a></li>
            <li class="navitem"><a href="#contact-us">Contact Us</a></li>
        </ul>
    </nav><br>    
    </header>
    <image src="./image11.png" style=" width: 100%;"></image>
      <section id="employee-registration" class="registerform">
        <h2>Employee Registration</h2>
        <p>Fill the below form to register as <em>employee.</em></p>
        <form>
        <label for="name">Name:</label>
        <input type="text" placeholder="Enter Name" id="name"><br>
        <label for="email">Email id:</label>
        <input type="email" placeholder="Enter Email" id="email"><br>
        <label for="password">Password</label>
        <input type="password" placeholder="Enter Password" id="password"><br>
        <label for="age">Age:</label>
        <input type="number" placeholder="Enter Age" id="age"><br>
        <label for="role">Select role</label>
        <select> 
            <option>Software Engineer</option>
            <option>Product Manager</option>
            <option>Designer</option>
            <option>HR representative</option>
        </select><br>
        <label for="joiningdate">Select Joining Date:</label>
        <input type="date" id="joiningdate"><br>
        <input type="submit">  <input type="reset"> 
        </form>
    </section><br>
    <section id="employee-directory" class="employeetable">
        <h2>Employee Directory</h2>
        <p>List of all register employees.</p>
        <table>
            <tr>
                <th><h3>Employee ID</h3></th>
                <th><h3>Employee Name</h3></th>
                <th><h3>Employee Role</h3></th>
            </tr>
            <tr>
                <th>1001</th>
                <th>Kausambi</th>
                <th>Software Engineer</th>
            </tr>
            <tr>
                <th>1002</th>
                <th>Anish</th>
                <th>Designer</th>
            </tr>
            <tr>
                <th>1003</th>
                <th>Aditya</th>
                <th>Designer</th>
            </tr>
            <tr>
                <th>1004</th>
                <th>Ronak</th>
                <th>Software Engineer</th>
            </tr>
            <tr>
                <th>1005</th>
                <th>Karan</th>
                <th>HR Representative</th>
            </tr>
            <tr>
                <th>1006</th>
                <th>Deepesh</th>
                <th>Product Manager</th>
            </tr>
        </table>
    </section><br>
    <section id="contact-us" class="contactus">
        <h2>Contact Us</h2>
        <p>You can contact us at company@official.com or visit us between 9AM-6PM.</p>
        <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d456177.9540046825!2d78.7158300823079!3d26.715952429999533!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x3975dfd884cf6219%3A0xb538c7e9e5e6e2d9!2z4KSH4KSf4KS-4KS14KS-LCDgpIngpKTgpY3gpKTgpLAg4KSq4KWN4KSw4KSm4KWH4KS2!5e0!3m2!1shi!2sin!4v1706752455476!5m2!1shi!2sin" width="500" height="250 style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
    </section><br>
    <footer>
        <p>&copy; 2024-2025 Company Name</p>
    </footer>
</body>
</html># HR-Portal
