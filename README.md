<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>personal information form</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
 <div class="container">
     <h1 class="brand"> Web Design </h1>
     <div class="wrapper">
         <div class="company-info">
             <h3>Web Design</h3>
             <ul>
                 <li> komal jagadale</li>
                 <li>RIT Islampur</li>
                 <li>Web Development</li>
             </ul>


         </div>
         <div class="contact">
             <h3>Feedback form:</h3>
             <form>
                 <p>
                     <label>Name:</label>
                     <input type="text" name="name" placeholder="komal vikas jagadale." required>
                 </p>

                 <p>
                    <label>Class :</label>
                    <input type="text" name="class" required>
                </p>

                <p>
                    <label>Email Id:</label>
                    <input type="email" name="email" placeholder="komaljagadele2017@gmail.com" required>
                </p>

                <p>
                    <label>Mob. Number:</label>
                    <input type="text" name="number" required>
                </p>

                <p>
                    <label>Address:</label>
                    <input type="text" Address="Address" required>
                </p>

                <p>
                <br>
                <input type ="radio" name="gender" id="male">

                    <label>for="male">male</label><br>
                    <input type="radio" name="gender" id="female">
                    <label for="female">female</label>
                    
                </p>

                <p>
                    <button>Submit now</button>
                </p>
             </form>

         </div>
     </div>
 </div>
    
</body>
</html>
