```html
<!-- table and form tags -->

<html>
    <head>
        <title>TableTag</title>
    </head>

    <body>
         <!--
           tr = row
           td= column
           th = table heading 
        -->
        
        <table>
            <tr>
                <th>Name</th>
                <th>Status</th>
                <th>Email</th>
            </tr>
            <tr>
                <td> Noor Nafis </td>
                <td> ****</td>
                <td> test@gmail.com</td>
            </tr>

            <tr>
                <td>Robin Hood</td>
                <td>Mingle</td>
                <td> robin@gmail.com </td>
            </tr>
        </table> <br><br>

        <!-- this is a contact us section -->
        <!-- cltr+/ for comments -->
        <section>
            <!-- <form action = ""></form> --> 
            <!-- we will use action when we will learn JavaScript -->
             <input type="text"> <br> <br>
             <input type = "text" placeholder="Your name">
             <input type = "submit"><br> <br>
             <input type = "text" placeholder="Your Mom's name"
             required>
             <!-- the required will create a "Please fill out this form" 
              if u put ur cursor in the box -->
    
             <input type = "email" placeholder="Your Email"
             required>
            <br><br>
             <input type="password" placeholder="Your password"">
             <input type = "submit"> <br><br>
             <input type = "date">
             <input type = "url">

             <!-- there is more input types just look at the w3school docs -->
             <form>

             </form>
        </section>
    </body>
</html>```
