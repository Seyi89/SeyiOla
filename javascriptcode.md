<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>
    <h1>My Javascript Task</h1>
    <p id="demo"></p>
    <script >
    	// my first javascript task. Here goes nothing.
let firstName = 'Oluwaseyi'; 
let lastName = 'Olawuwo';
let regCourses = ['html,css,javascript', 'design']
console.log(firstName , '', lastName,'', regCourses);
   console.log('Number of Registered Courses:', '',regCourses.length);

   for (let i=1; i <= 200; i++) {
        if (i % 2 ==0)
        console.log(i)
   }
   document.getElementById("demo").innerHTML = firstName + ' ' + lastName + '<br>' + regCourses;
    </script>
</body>
</html>
