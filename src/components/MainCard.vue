<template>
    <!-- Wrapper Container -->
    <div class="wrapper">
        <!-- Main Container -->
        <div class="main-container">
            <!-- Container One -->
            <div class="container-one">
                <div class="profile">
                    <img src="../assets/tux.jpg" alt="">
                    <h3>Isaak Adams</h3>
                    <p>Full Stack Developer Student</p>
                </div>
                <div class="social-links">
                        <div class="link" id="gHubLink">
                            <a href="https://github.com/IsaakAdams?tab=repositories" target="_blank">
                                <h2>GitHub</h2>
                                <i class="fa-brands fa-square-github"></i>
                            </a>
                        </div>
                        
                </div>
            </div>

            <!-- Container Two -->
            <div class="container-two">
                <div class="about-me">
                    <h1>About Me</h1>
                    <p>
                        I am currently a student at Central Piedmont Community College studying to obtain a degree in IT - Full Stack Programming.
                    </p>
                    <p>
                        I am currently looking for an intern/co-op job position as a Front-End, Back-End, or Full-Stack Developer.
                    </p>
                    <p>
                        I am eager to learn as much as possible about both web and software development, and I am a fast and flexible learner.
                    </p>
                    <p>
                        I create websites and applications using the web languages of HTML, CSS, and JavaScript that will assist users in accessing and interacting with a site or app. I also have some experience with the React front-end javascript library.
                    </p>

                </div>
                <div class="technology-section">
                    <h1>Technologies Studied</h1>
                    <div class="logos">
                        <i class="fa-brands fa-js"></i>
                        <i class="fa-brands fa-css3"></i>
                        <i class="fa-brands fa-html5"></i>
                    </div>
                </div>

                <div class="button-container">
                    <div class="projects-button">
                        <a href="https://github.com/IsaakAdams?tab=repositories">My Projects</a>
                    </div>
                    <div class="projects-button">
                        <a href="/resume.pdf" download>My Resume</a>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script setup>
   
</script>

<style scoped>
    /* Wrapper Container */
    .wrapper {
        display: flex;
        justify-content: center;
    }

    /* Main Container Start */
    .main-container {
        display: flex;
        flex-direction: row;
        background-color: #bcbcbc;
        border-radius: 25px;
        margin: 1.5%;
        width: 60%;
        background-color: #A0D4FF;
        box-shadow: rgba(0, 0, 0, 0.24) 0px 3px 8px;
    }
    /* Main Container End */

    /* Container One Start */
    .container-one {
        background-color: #1292EE;
        text-align: center;
        width: 30%;
        padding: 2.5%;
        border-radius: 25px;
    }

    .profile img {
        height: 5rem;
        border-radius: 50%;
    }

    .link a {
        text-decoration: none;
        color: #000;
        font-size: 16px;
    }

    .link a:hover {
        color: #fff;
    }

    .link i {
        font-size: 2.5rem;
        color: #000;
    }

    #gHubLink {
        margin-top: 50px;
    }
    /* Container One End */


    /* Container Two Start */
    .container-two {
        text-align: center;
        width: 70%;
        margin: 2.5%;
    }

    .container-two h1 {
        font-size: 2.5rem;
    }

    .about-me {
        text-align: left;
    }

    .logos i {
        font-size: 2.5rem;
        border-radius: 25px;
        margin: 0 10px;
    }

    .button-container {
        display: flex;
        flex-direction: row;
        justify-content: center;
        align-items: center;
        margin-top: 5%;
    }

    .projects-button {
        background-color: #005CA4;
        margin: 5px;
        padding: 5px;
        border-radius: 15px;
    }

    .projects-button:hover {
        background-color: #fff;
    }

    .projects-button a {
        text-decoration: none;
        color: #fff;
        font-size: 1.2rem;

    }

    .projects-button a:hover {
        color: #005CA4;
    }

    /* Container Two End */


    /* Media Queries */
    @media only screen and (max-width: 950px) {
        .main-container {
            width: 95%;
        }
    }
</style>