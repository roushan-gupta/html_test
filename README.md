<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <h1>first</h1>
    <p id="about">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Error adipisci saepe eligendi nostrum totam, odit dignissimos quia tempore explicabo optio, quasi tempora cupiditate deleniti. Dolorum ullam autem libero doloribus soluta!</p> <hr>
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Sunt, tempore quis explicabo aut sit mollitia repellat suscipit veritatis, nobis vero repudiandae! Blanditiis iste,<br>quis quos est ipsa quae dolore dolor ab itaque consectetur tempore voluptatum amet dicta veniam officiis rerum iusto consequuntur maxime fugiat ex perferendis odio! Numquam, temporibus cupiditate.</p>
    <hr>
    <a href="www.google.com" target="_blank"> google page </a><br>
    <hr>
    <img src="images/r1.jpg" alt="this is a pic" width="150"> <hr>
    <!-- <video src="assets/video.mp4" height="300" controls autoplay muted/> -->
     <hr>
    <b>roushan</b><br>
    <i>kumar</i><br>
    <u>gupta</u><br>
    <s>rk</s>
    <hr>
    <pre>                  roushan
        kumar                 gupta
                    rkg
    </pre>
    <hr>
    <big>this is big text</big><br>
    <small>this is small text</small>
    <hr>
    <big>(a+b)<sup>2</sup>=a<sup>2</sup>+b<sup>2</sup>+2ab
    <br>
    Formula of water is: H<sub>2</sub>O
    </big>
    <hr>
    &delta;<hr>
    <a href="www.instagram.com" target="_blank"><img src="images/r2.jpg" alt="alternate pic" height="150"></a>
    <hr>
    <header>This is Header</header>
    <main>This is Main</main>
    <hr>
    <main> 
        <section>
            <h2>admission</h2>
            admission will start soon
        </section>
        <section>
            <h2>Placements</h2>
            After completion...
        </section>
        <br>
        <section>
            <article>
                Lorem ipsum dolor sit, amet consectetur adipisicing elit. Error quidem quis in fugiat officiis repudiandae cumque voluptas incidunt assumenda voluptate minima, porro corporis consequatur ipsum, repellat doloribus qui aut esse! Suscipit perferendis debitis incidunt deserunt mollitia similique eius, tenetur molestiae velit, provident deleniti ratione voluptatibus explicabo odio. Ullam tempore provident perferendis ab officia illum fuga ut tempora, error enim dicta consectetur exercitationem, quo et, repellendus suscipit sunt porro? Totam, dolores ratione assumenda ipsum eveniet et possimus harum libero blanditiis! Itaque dicta amet eaque iure fugiat. Facilis assumenda odit quos nemo rem a asperiores, quas impedit possimus ex quod quaerat unde atque voluptatibus excepturi ipsum veniam magnam ab molestias odio cumque veritatis. Ullam expedita, dolores cupiditate, beatae earum asperiores nemo velit corrupti, blanditiis ipsa porro. Ipsa alias harum cum illo a molestiae earum reiciendis saepe natus similique nobis nam ab repudiandae, temporibus tempora dignissimos at. Dolorem ea exercitationem commodi quia ducimus fuga aut iste doloribus nam! Vitae dignissimos, accusamus ratione sed molestiae, numquam magnam repellat delectus fuga consequuntur voluptatem quisquam dolore modi aspernatur. Neque voluptate nulla reiciendis qui incidunt, consequuntur expedita maxime natus ratione fuga quo impedit dolore, sunt recusandae amet nisi veniam cumque consequatur magni? Dicta cum voluptates illo non?
            </article>
        </section>
        <aside>
            <h3>Recommended Books</h3>
            <ul>
                <li>Internet of things</li>
                <li>Introduction to algorithm</li>
            </ul>
        </aside>
    </main>
    <div>
        <a href="#div">div</a>
        <p id="div">this is under div</p>
    </div>
    <p>Lorem ipsum <span id="dolor" style="color: red;">dolor</span> sit amet consectetur</p>
    <hr>
    <h4>Lists</h4>
    <ol>
        <li>HTML</li>
            <ol type="i">
                <li>level 0</li>
                <li>level 1</li>
            </ol>
        <li>C</li>
            <ol type="A">
                <li>Basic</li>
                <li>Medium</li>
                <li>Advanced</li>
            </ol>
        <li>java</li>
            <ol type="a">
                <li>Array</li>
                <li>String</li>
            </ol>
    </ol>
    <ul>
        <li>Apple</li>
        <li>Banana</li>
        <li>Cherry</li>
    </ul>
    <hr>
    <table border="1">
        <caption>Students Data</caption>
        <tr>
            <th>Name</th>
            <th>City</th>
            <th>Marks</th>
        </tr>
        <tr>
            <td>Roushan</td>
            <td>Mohania</td>
            <td>80</td>
        </tr>
        <tr>
            <td>Kumar</td>
            <td>Kaimur</td>
            <td>89</td>
        </tr>
        <tr>
            <td colspan="3">this cell spans three column</td>
        </tr>
    </table>
    <hr>
    <h3>Forms</h3>
    <form action="/contact-me" method="post">

        <label for="email">username: </label>
        <input type="text" placeholder="enter email" name="username" id="email" value="" required>
        <br>
        <label for="user_password">password: </label>
        <input type="password" name="password" id="user_password" placeholder="enter password">
        <input type="submit" name="submit">
        <br>
        <label for="date">Date: </label>
        <input type="date" name="date" id="date">
        <br>
        <label for="file">File: </label>
        <input type="file" id="file">
        <br>
        <label for="color">color: </label>
        <input type="color">
        <br>
        <label for="range">Range: </label>
        <input type="range">
        <br>
        <label for="click">button: </label>
        <input type="button" name="button" value="click">
        <br>

        <label for="male">male: </label>
        <input type="radio" name="gender" value="male" id="male">
        <label for="female">female: </label>
        <input type="radio" name="gender" value="female" id="female">
        <br>
        Select:-
        <label for="c">c: </label>
        <input type="checkbox" name="lang" id="c" value="c">
        <label for="java">java</label>
        <input type="checkbox" name="lang" id="java" value="java">
        <label for="python">python: </label>
        <input type="checkbox" name="lang" id="python" value="python">
        <br>
        <label for="country">Select your county: </label>
        <select name="country" id="country">
            <option value="india">india</option>
            <option value="uk">uk</option>
            <option value="us">us</option>
            <option value="others">others</option>
        </select>
        <br>
        <textarea name="story" id="story" cols="30" rows="5">enter your story here</textarea>
    </form>
    <hr>
    <iframe src="www.youtube.com" height="150" width="200"></iframe>
    <footer>
            <nav>
                <a href="#home">Home</a><br>
                <a href="#about">About</a><br>
                <a href="#services">Services</a><br>
                <a href="#contact">Contact</a>
            </nav>
    </footer>
</body>
</html>
