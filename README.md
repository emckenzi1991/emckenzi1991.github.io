<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title><CV class="html"></CV></title>
    <link rel="stylesheet" href="mobile-first.css" />
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Patrick+Hand&display=swap"
      rel="stylesheet"
    />
  </head>
  <a id="top"></a>
  <nav>
    <ul class="main-nav">
      <li><a href="CV.html">Home</a></li>
      <li><a href="cakes.html">Cakes</a></li>
      <li><a href="contact.html">Contact</a></li>
    </ul>
  </nav>
  <header>
    <h1>Elizabeth McKenzie</h1>
    <img
      id="profile-pic"
      src="https://media.licdn.com/dms/image/v2/D4D03AQF04gpPBCzpzw/profile-displayphoto-crop_800_800/B4DZfgQRtaGgAI-/0/1751814054582?e=1757548800&v=beta&t=1U7wYrI-bdlCER-PS_30wobJy1suRmFMsmx-bsj1h28"
      alt="Profile Picture"
    />

    <div class="contact-info">
      <p>Email: emckenzi1991@gmail.com</p>
      <p>Phone: (716) 940-2966</p>
      <a href="https://www.linkedin.com/in/elizabeth-mckenzie-1b0a4b1a2/">
        <button>Find Me On Linkedin</button>
      </a>
      <a href="https://github.com/emckenzi1991">
        <button>Find Me On GitHub</button>
      </a>
    </div>
  </header>
  <hr />

  <body>
    <h2>Summary</h2>
    <p>
      Re-entering the engineering field with renewed focus and updated skills.
      While working in other fields I focused on personal development and am now
      motivated and ready to bring renewed dedication and talent back to
      software engineering.
    </p>

    <h2>Education</h2>
    <ul>
      <li>Newfane High School, Newfane, NY. Class of 2017</li>
      <li>
        Niagara County Community College, Sanborn, NY. 2017-2018 Mechanical
        Engineering, No Degree
      </li>
      <li>SpringBoard, Software Development Bootcamp, 2025-present</li>
    </ul>
    <h2>Skills</h2>
    <ul>
      <li>Retail Merchandising</li>
      <li>Customer Service</li>
      <li>Problem Solving</li>
      <li>Loss Prevention</li>
      <li>Team Leadership</li>
      <li>Cake Decorating</li>
    </ul>

    <div class="Experience">
      <h2>Experience</h2>
      <h3>Walmart, Team Lead. 2019-present</h3>

      <ul>
        <li>Lead and manage a team of 20 employees</li>
        <li>Analyze sales figures to track customer buying behaviors</li>
        <li>Facilitating Vendor Relations</li>
      </ul>

      <h3>Walmart, Cake Decorator. 2018-2019</h3>

      <ul>
        <li>
          Assisted customers with planning cake vision, including color, theme,
          and size
        </li>
        <li>
          Monitored inventory levels of baking supplies and alerted management
          when restocking was necessary
        </li>
        <li>Maintained a clean and organized work area</li>
      </ul>
      <a href="cakes.html">
        <button>Check out my cakes!</button>
      </a>
      <!--protflio of custom cakes-->

      <h3>Walamrt, Bakery\Deli Associate. 2017-2019</h3>
      <ul>
        <li>
          Operated ovens and other equipment to bake products according to
          established recipes
        </li>
        <li>Followed food safety guidelines while preparing all food items</li>
        <li>
          Attended training sessions related to food safety procedures and
          technique
        </li>
      </ul>
    </div>
    <h2>Certification</h2>
    <ol>
      <li>
        Food Safety Manager- National Registry of Food Safety Professionals
      </li>
      <li>CPR and AED certified</li>
      <li>Forklift certified</li>
    </ol>
    <h2>Volunteer Work</h2>
    <ul>
      <li>Making Strides Against Breast Cancer</li>
      <li>Walk Out Of The Darkness</li>
      <li>Children's Miracle Network</li>
      <li>Niagara Honor Flights</li>
    </ul>
    <hr />
    <footer>
      <h3>Send Me a Message!</h3>
      <!-- Contact Form -->
      <form action="#">
        <label for="name">Name:</label>
        <input
          type="text"
          id="name"
          name="name"
          required
          placeholder="Jane Doe"
        /><br /><br />

        <label for="email">Email:</label>
        <input
          type="email"
          id="email"
          name="email"
          required
          placeholder="JDoe@email.com"
        /><br /><br />

        <label for="organization">Organization:</label>
        <input
          type="text"
          id="organization"
          name="organization"
          placeholder="Walmart"
        /><br /><br />

        <label for="reason">Reason for Contact:</label>
        <select id="reason" name="reason" required>
          <option value="inquiry">General Inquiry</option>
          <option value="collaboration">Collaboration</option>
          <option value="feedback">Job Offer</option>
          <option value="other">Other</option></select
        ><br /><br />

        <label for="message">Message:</label><br />
        <textarea
          id="message"
          name="message"
          required
          rows="4"
          cols="50"
          placeholder="Enter Message Here &lt;3"
        ></textarea
        ><br /><br />

        <button type="submit">Send Message!</button>
      </form>
      <p>Thank you for viewing my CV. I look forward to connecting with you!</p>
    </footer>
    <!--https://stackoverflow.com/questions/32102747/how-to-make-a-back-to-top-button-using-css-and-html-only-->
    <a href="#top"> <button>back to top</button></a>
  </body>
</html>
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Cakes</title>
    <link rel="stylesheet" href="mobile-first.css" />
    <link
      href="https://fonts.googleapis.com/css2?family=Patrick+Hand&display=swap"
      rel="stylesheet"
    />
    <a id="top"></a>
  </head>
  <nav>
    <ul class="main-nav">
      <li><a href="CV.html">Home</a></li>
      <li><a href="cakes.html">Cakes</a></li>
      <li><a href="contact.html">Contact</a></li>
    </ul>
  </nav>
  <body>
    <div class="cakeUL">
      <h1>My Cake Portfolio</h1>
      <p>
        Here are some examples of cakes I have decorated during my time at
        Walmart.
      </p>
      <ul>
        <li><span>Teir Cakes</span></li>
        <li>Sheet Cakes</li>
        <li>Cookie Cakes</li>
        <li>Cupcakes</li>
        <li>Fruit Top Cakes</li>
        <li>Edible Images</li>
      </ul>
    </div>
    <div class="cake-pics">
      <img src="cake1.JPG" alt="Wedding Cake1 tall" />
      <img src="cake3.JPG" alt="Buffalo Bills Tier3 tall" />
      <img src="cake6.JPG" alt="Summer Tier6 tall" />
      <img src="cake4.JPG" alt="USA Cake4 tall" />
      <img src="cake7.jpg" alt="Princess Cake7 tall" />
      <img src="cake5.JPG" alt="Halloween Cookie5 tall" />
      <img src="cake9.jpeg" alt="baby shower tall" />
      <img src="cake10.jpg" alt="fox tall" />
      <img src="cake8.JPG" alt="Pie Slice8 wide" />
      <img src="cake2.JPG" alt="Taco Cake2 wide" />
    </div>
  </body>
  <a href="#top"> <button>back to top</button></a>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>contact</title>
     <link rel="stylesheet" href="mobile-first.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Patrick+Hand&display=swap" rel="stylesheet">
</head>
  <nav>
    <ul class="main-nav">
      <li><a href="CV.html">Home</a></li>
      <li><a href="cakes.html">Cakes</a></li>
      <li><a href="contact.html">Contact</a></li>
    </ul>
  </nav>
<body>
    <h2>Send Me a Message!</h2>
            <!-- Contact Form -->
                <form action="#">
                    <label for="name">Name:</label>
                    <input type="text" id="name" name="name" required placeholder="Jane Doe"><br><br>

                    <label for="email">Email:</label>
                    <input type="email" id="email" name="email" required placeholder="JDoe@email.com"><br><br>

                    <label for="organization">Organization:</label>
                    <input type="text" id="organization" name="organization" placeholder="Walmart"><br><br>

                    <label for="reason">Reason for Contact:</label>
                    <select id="reason" name="reason" required>
                        <option value="inquiry">General Inquiry</option>
                        <option value="collaboration">Collaboration</option>
                        <option value="feedback">Job Offer</option>
                        <option value="other">Other</option>
                    </select><br><br>

                    <label for="message">Message:</label><br>
                    <textarea id="message" name="message" required rows="4" cols="50" placeholder="Enter Message Here &lt;3"></textarea><br><br>

                    <button type="submit">Send Message!</button>
                </form>
                <br>
                 <a href="https://www.linkedin.com/in/elizabeth-mckenzie-1b0a4b1a2/">
      <button>Find Me On Linkedin</button>
      <a href="https://github.com/emckenzi1991">
      <button>Find Me On GitHub</button>
</body>
</html>

html {
  font-family: "Patrick Hand";
}
html {
  background: linear-gradient(135deg, #f0e7fb 5%, #fbc2eb 100%);
  color: black;
}
hr {
  border: 1px solid rgb(147, 8, 217);
  margin: auto;
}

/* Navigation styles */
nav {
  background-color: rgb(239, 183, 222);
  padding: 10px;
}
a {
  color: rgb(147, 8, 217);
  text-decoration: none;
}
nav a:hover {
  color: rgb(18, 0, 26);
}
.main-nav {
  display: flex;
  justify-content: space-between;
  list-style-type: none;
  padding: 0;
  margin: 0;
}
/*form styles */
textarea {
  width: 55%;
  height: 275px;
  padding: 10px;
  border-radius: 5px;
  border: 1px solid;
}

/* mobile screen code for home page */
@media (max-width: 700px) {
  /* Button styles */
  button {
    background-color: rgb(147, 8, 217);
    color: rgb(255, 251, 251);
    border: none;
    padding: 0.25em 0.25em;
    cursor: pointer;
    border-radius: 0.5em;
  }
  button:hover {
    background-color: rgb(199, 19, 115);
    color: white;
    box-shadow: inset 0 0 1rem rgba(147, 8, 217, 0.5),
      0 0 10px rgba(147, 8, 217, 0.5);
  }
  button {
    padding: 0.5em 0.5em;
    font-size: 0.9rem;
  }

  /* Header styles */
  header #profile-pic {
    width: 5rem;
    height: 5rem;
    border-radius: 15%;
    border: rgba(147, 8, 217) solid 2px;
    display: inline-block;
    transition: width 0.3s ease-in-out, height 0.3s ease-in-out;
  }
  header h1 {
    color: rgb(18, 0, 26);
    font-size: 2em;
    text-align: center;
    transition-duration: 0.3s;
  }
  header .contact-info {
    text-align: end;
    float: inline-end;
    font-size: 1rem;
    transition-property: font-size;
    transition-duration: 0.3s;
  }
  header p {
    margin: 0.4rem;
  }
}

/* Desktop screen code for home page */
@media (min-width: 701px) {
  header #profile-pic {
    width: 9em;
    height: 9em;
    border-radius: 15%;
    border: rgba(147, 8, 217) solid 2px;
    display: inline-block;
    transition: width 0.3s ease-in-out, height 0.3s ease-in-out;
  }

  header h1 {
    color: rgb(18, 0, 26);
    font-size: 3rem;
    text-align: center;
    transition-duration: 0.3s;
  }

  header .contact-info {
    text-align: end;
    float: inline-end;
    font-size: 1.2rem;
    transition-property: font-size;
    transition-duration: 0.4s;
  }

  /* Button styles */
  button {
    background-color: rgb(147, 8, 217);
    color: rgb(255, 251, 251);
    border: none;
    padding: 10px 20px;
    font-size: 16px;
    cursor: pointer;
    border-radius: 5px;
  }

  button:hover {
    background-color: rgb(199, 19, 115);
    color: white;
    box-shadow: inset 0 0 5px rgba(147, 8, 217, 0.5),
      0 0 10px rgba(147, 8, 217, 0.5);
  }
}

/* moblie screen code cake portfolie */
@media (max-width: 1140px) {
  /* Cake Image styles */
  img[alt*="tall"] {
    max-width: auto;
    height: 10rem;
  }
  img[alt*="wide"] {
    width: 13rem;
  }
  img {
    border-radius: 1rem;
    margin: 0.25rem;
    box-shadow: rgba(147, 8, 217, 0.5) 0px 0px 1rem;
    transition: width 0.9s ease-in-out, height 0.9s ease-in-out;
  }
}
/* desktop screen code cake portfolie */
@media (min-width: 1141px) {
  /* cake portfolio styles */
  .cake-portfolio {
    text-align: center;
    margin: 20px;
    padding: 20px;
    box-sizing: border-box;
    width: 70%;
    display: inline-block;
    vertical-align: top;
  }
  .cake-pics {
    display: inline-block;
    width: 70%;
    border-left: 2px solid rgb(147, 8, 217);
    padding-left: 10px;
  }

  .cakeUL {
    text-align: center;
    margin: 20px;
    padding: 20px;
    box-sizing: border-box;
    width: 25%;
    display: inline-block;
    vertical-align: top;
  }
  /* Cake Image styles */
  img[alt*="tall"] {
    max-width: auto;
    height: 400px;
  }
  img[alt*="wide"] {
    width: 520px;
  }
  img {
    border-radius: 10px;
    margin: 10px;
    box-shadow: rgba(147, 8, 217, 0.5) 0px 0px 10px;
    transition: width 0.9s ease-in-out, height 0.9s ease-in-out;
  }
}


