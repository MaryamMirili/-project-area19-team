@import url('https://fonts.googleapis.com/css2?family=Yusei+Magic&display=swap');
* {
	padding: 0;
	margin: 0;
	box-sizing: border-box;
}
html {
	font-size: 13px;
	font-family: 'Yusei+Magic', sans-serif;
	scroll-behavior: smooth;
}
a {
	text-decoration: none;
}
.container {
	min-height: 100vh;
	width: 100%;
	display: flex;
	align-items: center;
	justify-content: center;
}
img {
	height: 10%;
	width: 80%;
	object-fit: cover;
}
p {
	color: black;
	font-size: 1.9rem;
	margin-top: 5px;
	line-height: 2.5rem;
	font-weight: 500px;
	letter-spacing: .05rem;
}
.section-title {
	font-size: 4rem;
	font-weight: 300;
	color: black;
	margin-bottom: 10px;
	text-transform: uppercase;
	letter-spacing: .2rem;
	text-align: center;
}


.cta {
	display: inline-block;
	padding: 10px 30px;
	color: white;
	background-color: transparent;
	border: 2px solid rgb(20, 130, 220);
	font-size: 2rem;
	text-transform: uppercase;
	letter-spacing: .1rem;
	margin-top: 30px;
	transition: .3s ease;
	transition-property: background-color, color;
}
.cta:hover {
	color: white;
	background-color: rgb(20, 130, 220);
}
.brand h1 {
	font-size: 3rem;
	text-transform: uppercase;
	color: white;
}
.brand h1 span {
	color: rgb(20, 130, 220);
}

/* Header section */
#header {
	position: fixed;
	z-index: 1000;
	left: 0;
	top: 0;
	width: 100vw;
	height: auto;
}
#header .header {
	min-height: 8vh;
	background-color: rgba(236, 3, 3, 0.24);
	transition: .3s ease background-color;
}
#header .nav-bar {
	display: flex;
	align-items: center;
	justify-content: space-between;
	width: 100%;
	height: 100%;
	max-width: 1300px;
	padding: 0 10px;
}


/* End Header section */

/* start Section */
#start {
    background-image: url();
	background-color:coral
	background-size: cover;
	background-position: top center;
	position: relative;
	z-index: 1;
}
#start::after {
	content: '';
	position: absolute;
	left: 0;
	top: 0;
	height: 100%;
	width: 100%;
	background-color:black;
	opacity: .8;
	z-index: -1;
}

#start h1 {
	display: block;
	width: fit-content;
	font-size: 4rem;
	position: relative;
	color: white;
	
}

/* End start Section */

/* Services Section */
#services .services {
	flex-direction: column;
	text-align: center;
	max-width: 1500px;
	margin: 0 auto;
	padding: 100px 0;
}
#services .service-top {
	max-width: 500px;
    margin: 0 auto;
    color:darkgoldenrod;
}
#services .section-title span {
    color:blue;
}

/* End Services Section */

/* Projects section */
#projects .projects {
	flex-direction: column;
	max-width: 1200px;
	margin: 0 auto;
	padding: 50px 0;
}
#projects .projects-header h1 {
	margin-bottom: 60px;
}
#projects .all-projects {
	display: flex;
	align-items: center;
	justify-content: center;
	flex-direction: column;
}
#projects .project-item {
	display: flex;
	align-items: center;
	justify-content: center;
	flex-direction: column;
	width: 80%;
	margin: 20px auto;
	overflow: hidden;
	border-radius: 10px;
}
#projects .project-info h1 {
	font-size: 4rem;
	font-weight: 500;
}
#projects .project-info h2 {
	font-size: 1.8rem;
	font-weight: 500;
    margin-top: 5px;
    color:blueviolet;
}
#projects .project-info p {
	color:black;
}
.img {
    border: 1px solid rgba(2, 0, 0, 0.719);
    border-radius: 45px;
    padding: 100px;
    width: 50px;
  }

/* End Projects section */

/* End Section */
#end .end {
	flex-direction: column-reverse;
	text-align: center;
	max-width: 1200px;
	margin: 0 auto;
	padding: 100px 20px;
}

#end .col-right {
	width: 100%;
}
#end .col-right h2 {
	font-size: 2.4rem;
	font-weight: 500;
	letter-spacing: .2rem;
    margin-bottom: 10px;
    text-align:center;
    color:blue;
}
#end .col-right p {
    margin-bottom: 20px;
    text-align: center;
}
#end .col-right .cta {
	color: black;
	margin-bottom: 50px;
	padding: 10px 20px;
    font-size: 2rem;
    text-align:center;
}
/* End  Section */


/* son */
#son {
	background-image: linear-gradient(60deg, #b90b9c 0%, #e40dc0 100%);
}
#son .son {
	min-height: 200px;
	flex-direction: column;
	padding-top: 50px;
	padding-bottom: 10px;
}
#son h2 {
	color: white;
	font-weight: 500;
	font-size: 1.8rem;
	letter-spacing: .1rem;
	margin-top: 10px;
	margin-bottom: 10px;
}

#son p {
	color: white;
	font-size: 1.3rem;
}
/* End son */
