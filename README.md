<head>
    <style>
        .container{
            display: flex;
            flex-flow: column wrap;
            align-items: center;
        }
        .links{
            display: inline;
            text-decoration: none;
            color: blue;
        }
        .links:hover{
            color: red;
            border: 1px solid red;
        }
        #abt-desc{
            display: flex;
            flex-wrap: wrap;
            align-items: center;
            width: 20%;
        }
        #langs+div img{
            display: block;
            width: 3em;
            height: 3em;
        }
        #contact+div{
            display: flex;
            align-content:center;
        }
        #contact+div a img{
            height: 100px;
            padding-top: 25px;
        }
        #contact+div a img:first-of-type{
            padding-top: 0px;
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <nav>
                <a href="#abt" class="links">About me</a>
                <span> | </span>
                <a href="#langs" class="links">Languages and Tools</a>
                <span> | </span>
                <a href="#contact" class="links">Contacts</a>
            </nav>
        </header>
        <h1 id="abt">About me:</h1>
        <div id="abt-desc">
            <ul>
                <li>Currently studying at Maths and Science High School "Akad. Sergey P. Koroliov", Blagoevgrad.</li>
                <li>Studying to become a Software Engineer.</li>
                <li>I'm currently learning Python at <a href="https://softuni.bg/">SoftUni</a>, as well as many other things on my own.</li>
            </ul>
        </div>
        <h1 id="langs">Languages and Tools:</h1>
        <div>
            <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/csharp/csharp-original.svg" title="C#" alt="C#" />
            <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original-wordmark.svg" title="Python" alt="Python" />
            <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/unity/unity-original.svg" title="Unity" alt="Unity" />
            <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original-wordmark.svg" title="HTML5" alt="HTML5" />
            <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original-wordmark.svg" title="CSS3" alt="CSS3" />
            <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mongodb/mongodb-original-wordmark.svg" title="MongoDB" alt="MongoDB" />
        </div>
        <h1 id="contact">How to contact me:</h1>
        <div>
            <a href="mailto::marcello_k@abv.bg"><img src="https://blog.abv.bg/wp-content/uploads/2009/2011/01/abv-logo.png" title="ABV" alt="ABV" style="height:70px;" /></a>
            <a href="mailto::marcello30032005@gmail.com"><img src="https://th.bing.com/th?id=ODLS.5e7ae0d8-1132-4a2a-8aa8-cb76156d41b8&w=32&h=32&qlt=90&pcl=fffffa&o=6&pid=1.2" title="Gmail" alt="Gmail" /></a>
        </div>
    </div>
</body>
