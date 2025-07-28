# HTML-CODE-
Wt code 


1.<HTML>
<HEAD>
<TITLE>
MY NAME IS 
</TITLE>
</HEAD>
<BODY>
PRITHVIRAJ NARAVDE 
</BODY>
</HTML>

2<html>
<title>Heading</title>
<body>
<h1>PRUTHVIRAJ</h1>
<h2>SHUBHAM</h2>
<h3>AKASH</h3>
<h4>PRANJAL</h4>
<h5>BHAKTI</h5>
<h6></h6>
</body>
</html>

3.<html>
<head>
    
    <titl>text formating code</title>
</head>
<body>
    <b> global chalange  </b>
    <br>
    <em> global chalange</em>
    <br>
    <small> global chalange  </small>
    <br>
    <sup> global chalange  </sup>
    <br>
    <sub> global chalange  </sub>
    <br>
    <strong> global chalange  </strong>
    <br>
    <big> global chalange  </big>
     <br>
    <strike> global chalange  </strike>
    <br>
    <tt> global chalange</tt>

</body>
</html>



4<html>
<head>
    
    <title> font color</title>
</head>
<body>
    <br><font color ="red" size="8"face="arial"> global chalange </font>
    <br><font color ="orange" size="9"face="comic sans MS"> global chalange </font>
    <br><font color ="yellow" size="6"face="lucida sans unicode"> global chalange </font>
    <br><font color ="green" size="7"face="courier new"> global chalange </font>
    <br><font color ="blue" size="4"face="time new roman"> global chalange </font>
    <br><font color ="pink" size="10"face="arial black"> global chalange </font>
    <br><font color ="purple" size="3"face="impact"> global chalange </font>
</body>
</html>














html>
<head>
    <title>GreenWave Initiative</title>
</head>
<body>
    <!--Header-->
    <header>
        <h1>GreenWave Initiative</h1>
        <p>working towards a greener future</p>
        <hr>
    </header>

    <!--about section-->
    <section>
        <h2>About Us</h2>
        <p>GreenWave Initiative is a nonprofit organization committed to environmental conservation and promoting sustainable living globally.</p>
    </section>

    <!--services / programs-->
    <section>
        <h2>Our Programs</h2>
        <ul>
            <li>Community clean-ups</li>
            <li>Tree planting drives</li>
            <li>Environmental education workshops</li>
        </ul>
    </section>

    <!--Team section-->
    <section>
        <h2>Our Team</h2>
        <p>Driven by environmentalists, activists, and community leaders passionate about making a positive impact.</p>
    </section>

    <!--contact section-->
    <section>
        <h2>Contact Us</h2>
        <form>
            <label for="name">Your name</label><br>
            <input type="text" id="name" name="name"><br><br>
            
            <label for="email">Your email</label><br>
            <input type="email" id="email" name="email"><br><br>
            
            <label for="message">Your message</label><br>
            <textarea id="message" name="message" rows="4" cols="30"></textarea><br><br>
            
            <input type="submit" value="Send message">
        </form>
    </section>

    <!--footer-->
    <footer>
        <hr>
        <p>&copy; 2025 GreenWave Initiative. All rights reserved.</p>
    </footer>
</body>
</html>


# javascript 
<html>
<head>
    <title> javascript examle</title>
</head>
<body>
    <h2> welcome to my page </h2>
    <p> click the button to see a message : </p>
    <button onclick = "showmessage()">click me </button>
    <p id = "message"></p>
    <script>
        function showmessage(){
            document .getElementById("message").innerText="hellow javascript is working ";
        }
    </script>
</body>
</html>




<html>
<head>
    <titl> javascript assigment operator </title>
</head>
<body>
    <h2> javascript assigment operator demo</h2>
    <p id ="output"></p>
    <script> 
        let number = 10;
        number+=5;
        number-=6;
        number*=5;
        number/=5;
        number%=5;
        decoment.getElementById("output").innerhtml = "final value is "+ number;
        
    </script>
</body>
</html>




!DOCTYPE html>
<html>
<head>
    
    <title>javascript data type </title>
</head>
<body>
    <h1> javascript data type demo</h1>
        <p id = "output"></p>
        <script>
            let name ="Ajay";
            let age = 24;
            let is_student = true;
            let person = {
                firstName : "Ajay",
                lastName : "Karan"
            };
            let color = [ "red","blue"];
            let address = null;
            let phnumber ;

            let output = `
            name (string) : ${name } <br>
            age (number) :  ${age } <br>
            is_student (boolean): ${is_student }<br>
            person(object): ${JSON.stringify(person)}<br>
            color(Array) : ${color.join(",")}<br>
            address(null) : ${ address}<br>
            phnumber (undefined): ${phone}
            `;
            document.getElementById("output").innerhtml = output ;
            </script> 

</body>
</html>













<!DOCTYPE html>
<html>
<head></head>
    <title>javascript string example </title>
</head>
<body><h2>javascript string example</h2>
<p id ="demo"></p>
    <script> 
        let firstName = "jon";
        let lastName ="joy";
        let fullName = firstName +""+lastName;

        let upperCaseName = fullName .toUpperCase();
        let namelength = fullName.length;
        let containsjoy = fullName.includes ("joy");
        document.getElementById("demo").innerHTML= "full name : "+fullName+"<br>"+
        "upperCaseName : " + upperCaseName +""+"<br>"+
        "Length : "+ namelength + ""+"<br>"+
        "contain  'joy'?" + containsjoy;

    </script>
</body>
</html>
