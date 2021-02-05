# HoriseonMarketing

/* Box-sizing, padding, and margin reset */

* {
  box-sizing: border-box;
  padding: 0;
  margin: 0;
}

body {
  background-color: #d9dcd6;
}

/* Header style */

.header {
  padding: 20px;
  font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
  background-color: #2a607c;
  color: #ffffff;
}

.header h1 {
  display: inline-block;
  font-size: 48px;
}

.header h1 .seo {
  color: #d9dcd6;
}

/* added '' around calibri and sand-serif so they function correctly */

.header nav {
  padding-top: 15px;
  margin-right: 20px;
  float: right;
  font-family: 'Gill Sans', 'Gill Sans MT', 'Calibri', 'Trebuchet MS', 'sans-serif';
  font-size: 20px;
}

.header nav ul {
  list-style-type: none;
}

.header nav ul li {
  display: inline-block;
  margin-left: 25px;
}

/* Text style */

a {
  color: #ffffff;
  text-decoration: none;
}

p {
  font-size: 16px;
}

/* Hero div w/img */

.hero {
  height: 800px;
  width: 100%;
  margin-bottom: 25px;
  background-image: url("../images/digital-marketing-meeting.jpg");
  background-size: cover;
  background-position: center;
}

/* floats */

.float-left {
  float: left;
  margin-right: 25px;
}

.float-right {
  float: right;
  margin-left: 25px;
}

/* Main */

.main {
  width: 75%;
  display: inline-block;
  margin-left: 20px;
}

/* Services | added '' around calibri and sans-serif*/

.services {
  margin-bottom: 20px;
  padding: 50px;
  height: 300px;
  font-family: 'Gill Sans', 'Gill Sans MT', 'Calibri', 'Trebuchet MS', 'sans-serif';
  background-color: #0072bb;
  color: #ffffff;
}

.services img {
  max-height: 200px;
}

.services h2 {
  margin-bottom: 20px;
  font-size: 36px;
}

/* Benefits aside | added '' around calibri and sans-serif */

.benefits {
  margin-right: 20px;
  padding: 20px;
  clear: both;
  float: right;
  width: 20%;
  height: 100%;
  font-family: 'Gill Sans', 'Gill Sans MT', 'Calibri', 'Trebuchet MS', 'sans-serif';
  background-color: #2589bd;
}

.benefit {
  margin-bottom: 32px;
  color: #ffffff;
}

.benefit h3 {
  margin-bottom: 10px;
  text-align: center;
}

.benefit img {
  display: block;
  margin: 10px auto;
  max-width: 150px;
}

/* Footer */

.footer {
  padding: 30px;
  clear: both;
  font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
  text-align: center;
}

.footer h4 {
  font-size: 20px;
}
