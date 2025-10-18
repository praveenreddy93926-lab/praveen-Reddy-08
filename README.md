
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title></title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <Style>
        body{
            font-size: 50px;
              width: 95%;
    height: auto;
        }
        section{
            height: 100vh;
           border: 2px solid yellow;
           margin: 5pc;
           padding: 5pc;
           border-radius: 30px;
           background-clip: border-box;
           justify-content: center;
           align-items: center;
           place-items: center;
        }
        body{
            text-align: center;
            margin: 100px;
    width: 95%;
    height: auto;
        }
        h1{
            font-size: 2em;
              width: 95%;
    height: auto;
        }
        ol{
           color :white;
            text-align: center;
        }
        .male{
            color : palevioletred;
        }
       .p{
            text-align: center;
        }
        .lable{
            color: white;
        }
          *{
            font-family: 'Franklin Gothic Medium';
          }
            #praveen{
                text-align: center;
            }
            h1{
                font-weight: lighter;
            }h1{
                text-decoration: underline;
            }
            button{
                color:rgb(255, 3, 3);
            }
            body{
                background-image: url("Screenshot 2025-10-01 195640.png");
                background-size:cover;
                background-repeat: no-repeat;
                background-attachment: fixed;
            }
            button{
                height:40px;
                width: 140px;
                border-radius: 20px;
                cursor: pointer;
            }
            .reddy{
                size-adjust: 30px;
            }
           button:hover{
            color:rgb(255, 255, 255);
            background-color:rgb(0, 0, 0);
           }
           .image{
            background-image: url("praveen reddy....jpg");
            background-size: cover;
            height: 1000px;
            border-radius: 30px;
           }
        .praveen-img{
            width: 100px;
            height: auto;
        }
        h5{
            color: rgb(0, 0, 0);
            text-align: left;
        }
        .student{
            text-align: top;
        }
        *{
                 fontsize:80px
            }
        .input{
            border: 4px;
            padding: 8px;
            border-radius: 10px;
        }
    </Style>
</head>
<body>
    <section>
    <header>
      <center>
          <h1 style="color:greenyellow" class = "pr">- I am Praveen Reddy -</h1>
        </center>
    </header>
    <main>
        <center>
        <a href = "sub.html" >
                <button>Course</button>
            <a href="details.html">
            <button > Student Details </button>
            </a>
            <br>
            <br>
            <a href = "https://chatgpt.com/c/68dbd180-f660-8323-970d-6113fbe1d239">go to chatgpt </a>
            <h3 style="color :darkturquoise">........ </h3>
        </center>
    </main>
    </section>
            <section>
            <h3 style="color: chartreuse;">languages.</h3>
            <ol>
                <li>
                    java
                </li>
                <li>c++</li>
                <li>c-programing</li>
                <li>HTML</li>
                <li>Css</li>
            </ol>
        </section>
    <section  class="image" >
    <form action =" ">
        <h3 style="color:rgb(199, 29, 29) " class="student">- Student Details -</h3>
        <br>
        <br>
        <br><br><br>
        <h5>NAME: Praveen Reddy.</h5>
        <h5>ROLL: 248R1A6664. </h5>
        <h5>Class: CSE(AIML). </h5>
    </form>
        </section>
            <section>
            <h4 style="color:rgb(0, 88, 252)">- Contact me -</h4><br>
                  <lable  class ="lable" for = "Name">Name: </lable>
                  <input type = "Text"  class="input" placeholder="enter name "><br><br>
                 <label class="lable" for="phone" >Phone number</label>
                  <input type="password" class="input" name ="password" ><br><br>
                  <label for="password" class="lable" >Date</label>    
                  <input type="date" class="input" id = "dateofbirth">
                  <br><br>
                  <b class="lable" >enter ur Gender: </b>
                  <input type="radio" class="input" id = "male" name="k" value = "male" >
                  <lable for = "k"  class="lable" >Male</lable>
                  <input type="radio"  id ="ma" class ="input" name = "k" value = "female"> 
                  <lable for="k" class="lable" >Female</lable>
                  <br><br>
                  <b class="lable"> checkbox</b>
                  <input type = "checkbox" class ="input" id = "box" value = "value">
                  <b class="lable">box1</b>
                  <input type = "checkbox" id = "box" class="input" value = "value">
                  <b class="lable"> box2 </b>
                  <br>
                  <h1>
                </h1>
                <center>
                    <button type ="submit" style="size: 20px;" class="reddy">Submit</button>
                </center>
    </section>    
</body>
</html>
