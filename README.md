<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title> javascript task 2</title>
    </head>
    <body>
        <h1>This is my javascript Task 2</h1>
        <script>
            var Para = [{principal:"a",time: "b"},{principal:"a",time: "b"},{principal:"a",time: "b"},{principal:"a",time: "b"}];
                
            var data =[{principal: 2500,time: 1.8},{principal: 1000,time: 5},{principal: 3000,time: 1},{principal: 2000,time: 3}];
            
    function interestCalculator(Para) {

        for (i = 0; i<Para.length; i++){
        if (Para[i].principal>=2500 && Para[i].time > 1 && Para[i].time < 3) {Para[i].rate = 3;} 
        else if (Para[i].principal>=2500 && Para[i].time>=3) {Para[i].rate = 4;} 
        else if (Para[i].principal<2500 || Para[i].time<=1 ) {Para[i].rate = 2;} 
        else {para[i].rate = 1;}
        
        console.log(data[i].rate);
        }

        for (i = 0; i<data.length; i++){
            data[i].interest = [];
            data[i].interest = (data[i].principal  * data[i].time * data[i].rate)/100
            console.log(data[i].interest) }
        
         var interestData = [];
         var interestData = data;
         console.log(interestData);
         return interestData;
       }  
 
        interestCalculator(data); 

                                      
    </script>
    </body>
</html>
