# webpageHTML-css

<html>

<head>
    <title> Welcom to my Web Development page </title>

    <style>
        * {
            margin: 0;
            padding: 0;
        }

        .navbar {
            display: flex;
            align-items: center;
            justify-content: center;
            position: sticky;
            top: 0;
            cursor: pointer;
        }

        .background {
            background: black;
            background-blend-mode: darken;
            background-size: cover;
        }

        .nav-list {
            width: 70%;
            display: flex;
            align-items: center;
        }

        .logo {
            display: flex;
            justify-content: center;
            align-items: center;
        }

        .logo img {
            width: 180px;
            border-radius: 50px;
        }

        .nav-list li {
            list-style: none;
            padding: 26px 30px;
        }

        .nav-list li a {
            text-decoration: none;
            color: white;
        }

        .nav-list li a:hover {
            color: grey;
        }

        .rightnav {
            width: 30%;
            text-align: right;
        }

        #search {
            padding: 5px;
            font-size: 17px;
            border: 2px solid grey;
            border-radius: 9px;
        }

        .firstsection {
            background-color: rgb(154, 158, 148);
            height: 350px;
        }

        .secondsection {
            background-color: rgb(128, 128, 137);
            height: 350px;
        }

        .box-main {
            display: flex;
            justify-content: center;
            align-items: center;
            color: black;
            max-width: 80%;
            margin: auto;
            height: 80%;
        }

        .firsthalf {
            width: 100%;
            display: flex;
            flex-direction: column;
            justify-content: center;
        }

        .secondhalf {
            width: 30%;
        }

        .secondhalf img {
            width: 70%;
            border: 4px solid white;
            border-radius: 150px;
            display: block;
            margin: auto;
        }

        .text-big {
            font-family: 'Piazzolla', serif;
            font-weight: bold;
            font-size: 35px;
        }

        .text-small {
            font-size: 18px;
        }

        .btn {
            padding: 8px 20px;
            margin: 7px 0;
            border: 2px solid white;
            border-radius: 8px;
            background: none;
            color: white;
            cursor: pointer;
        }

        .btn-sm {
            padding: 6px 10px;
            vertical-align: middle;
        }

        .section {
            height: 400px;
            display: flex;
            align-items: center;
            justify-content: center;
            max-width: 90%;
            margin: auto;
        }

        .section-Left {
            flex-direction: row-reverse;
        }

        .paras {
            padding: 0px 65px;
        }

        .thumbnail img {
            width: 250px;
            border: 2px solid black;
            border-radius: 26px;
            margin-top: 19px;
        }

        .center {
            text-align: center;
        }

        .text-footer {
            text-align: center;
            padding: 20px 0;
            font-family: 'Ubuntu', sans-serif;
            display: flex;
            justify-content: center;
            color: white;
        }
    </style>
</head>

<body>
    <nav class="navbar background">
        <ul class="nav-list">
            <div class="logo">
                <img src="https://images.unsplash.com/photo-1581091226825-a6a2a5aee158?q=80&w=1770&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D">
            </div>
            <li><a href="#c">
                    <h2>C </h2>

                    <p><a href="https://en.wikipedia.org/wiki/C_(programming_language)">Visit Wikipdia!</a></p>
                </a></li>
            <li><a href="#c++">
                    <h2>C++</h2><p><a href="https://www.w3schools.com/cpp/cpp_intro.asp">Visit W3!</a></p>
                </a></li>
            <li><a href="#Java">
                <h2>Java</h2><p><a href="https://www.w3schools.com/java/">Visit W3!</a></p>
            </a></li>
            <li><a>Courses</a></li>
        </ul>

        <div>
            <input type="text" name="search" id="search">
            <button>Search</button>

        </div>
    </nav>

    <section class="firstsection">
        <div class="box-main">
            <div class="firstHalf">
                <h1><u>C</u></h1>
                <p class="text-small">
                    C is a versatile, procedural programming language developed in the early 1970s. Known for its efficiency and portability, C has influenced many other languages. It is widely used in system programming, embedded systems and software development.
                </p>


            </div>
        </div>
    </section>
    <h1>The Video Element</h1>

    <video width="400" height="300" controls>
        <source src="https://www.videvo.net/video/teacher-helping-male-high-school-student-working-in-computer-class/944988/#rs=video-box.mp4" type="video/mp4">
        <source src="https://www.videvo.net/video/teacher-helping-male-high-school-student-working-in-computer-class/944988/#rs=video-box.ogg" type="video/ogg">
    </video>
    <audio controls>
        <source src="https://www.videvo.net/royalty-free-music-track/plain-folks/230799/#rs=audio-download.ogg" type="audio/ogg">
        <source src="https://www.videvo.net/royalty-free-music-track/plain-folks/230799/#rs=audio-download.mp3" type="audio/mpeg">

    </audio>

    <section class="secondsection">
        <div class="box-main">
            <div class="firstHalf">
                <h1><u>
                        C++</u>
                </h1>
                <p class="text-small">
                    C++ is a versatile, high-performance programming language that combines procedural, object-oriented, and generic programming features. It is widely used for developing software, including system and application software, game development, and embedded systems, offering a balance between low-level hardware access and high-level abstractions.
                </p>


            </div>
        </div>
    </section>

    <section class="section">
        <div class="paras">
            <h1><u>Java</u></h1>

            <p class="sectionSubTag text-small">
                Java is a versatile, object-oriented programming language known for its platform independence. It is widely used in web development, mobile applications (Android)and enterprise systems. Java's "write once, run anywhere" principle enables code portability across various devices.
            </p>


        </div>

        <div class="thumbnail">
            <img src="https://images.unsplash.com/photo-1581091226825-a6a2a5aee158?q=80&w=1770&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D" alt="laptop image">
        </div>
    </section>

    <footer class="background">
        <p class="text-footer">
        <h3>***************Thank you****************</h3>
        </p>


    </footer>
</body>

</html>

</title>
</head>

</html>
