# My-resume
<!DOCTYPE html>
<html>
<head>
	<title>MY RESUME</title>
	<link rel="stylesheet" type="text/css" href="sample.css">
</head>
<body>
    <div class="mainContainer">
        <div class="myDetailsContainer">
            <div class="flexOne flexCenter">
                <img alt="profile" class="profilePic" src="GK.jpg">
            </div>
            <div class="flexTwo">
                <h1 class="highlight">KALEESWARAN G</h1>
                <h3 class="highlight">Student</h3>
                <p>
                	Age : 18<br>
                	1st Year B.Tech-Artificial Intelligence and Data Science.<br>
                	Batch : 2022-2026<br>
                	RAMCO INSTITUTE OF TECHNOLOGY Rajapalayam.
                </p>

                <p><span class="highlight">Mobile: </span>xxx-xxx-8706 <span class="highlight"><br>Email: </span>kaleeswaran22v@gmail.com
                    <span class="highlight">Adress:</span>Vadakku Chathiram<br>
                    <span class="highlight">Country:</span>India</p>
            </div>
        </div>
        <div class="experienceContainer">
            <h2>Summary</h2>
            <p>I am a Engineering student and ambitious and driven.
            I thrive on challenge and constantly set goals for myself, so I have something to strive towards. I am not comfortable with setting and I am always looking for an opportunity to do better and achieve greatness.</p>
        </div>

        <div class="divider"></div>
        
        <div class="descriptionContainer">
            <div class="flexOne leftContainer">
            	<div>
                    <h2>Academic History</h2>
                        <p class="highlight">12th </p>
                        <h5>Batch : 2022</h5>
                        <p>Percentage : 79.17%</p>
                        <p>Viveka Matric Hr Sec School Sivagiri - 627757.</p>
                        <p class="highlight">10th</p>
                        <h5>Batch : 2020</h5>
                        <p>Percentage : 74.4%</p>
                        <p>Viveka Matric Hr Sec School Sivagiri - 627757.</p>
                </div>
                <div>
                    <h2>Skills</h2>
                    <ul>
                    	<li>Programming Languages : Python</li>
                        <li>Web Development: HTML, CSS</li>
                    </ul>
                </div>
            </div>
            <div class="flexTwo">
                <h2>Activities</h2>
                <div>

                    <h5> <span class="highlight">Sports</span></h5>
                    <ul>
                    	<li>Volleyball</li>
                    	<li>Carrom</li>
                    </ul>
                </div>
                <div>

                    <h5> <span class="highlight">Others</span></h5>
                    <ul>
                    	<li>Member in ECO club RIT</li>
                    	<li>Member in Tamilan Siragugal club</li>
                    </ul>
                </div>
            </div>
        </div>
    </div>
</body>
</html>

#CSS
body{
    padding:0px;
    margin:0px;
    background-color: black;
    font-family: 'Poppins',sans-serif;
}

.flexOne{
    flex:1;
}

.flexTwo{
    flex:1;
}

.flexCenter{
    display: flex;
    justify-content: center;
    align-items: center;
}

.mainContainer{
    max-width: 45vw;
    display: flex;
    margin:0 auto;
    padding:2rem;
    background-color: rgb(255, 255, 255);
    flex-direction: column;
}

.myDetailsContainer{
    display: flex;
}

.profilePic{
    width: 150px;
    height: 150px;
    border-radius: 60%;
}

.experienceContainer{
    margin-left: 2rem;
}

.descriptionContainer{
    display: flex;
    margin-bottom: 2rem;
}

.leftContainer{
    margin-left: 2rem;
}

.divider{
    border:1px solid black;
    width:100%
}

h1,
h3,
h5,
h4 {
    line-height: 0.8;
    line-break: 2 ;
}


li,
p {
    font-size: 14px;
    font-family: 'Poppins', sans-serif;
}

.highlight {
    color: #05a794;
    font-weight: 900;
}

