<template>
    <div id="hello-root">
        <div id="greeting">
            <h2>Hello,<br>I'm Isaak, and I'm a web developer |</h2>
            <p>
                I am currently a student at Central Piedmont Community College studying to obtain a degree in IT - Full Stack Programming.
            </p>
            <p>
                I am currently looking for an intern/co-op job position as a Front-End, Back-End, or Full-Stack developer.
            </p>
            <p>
                I am eager to learn as much as possible about both web and software development, and I am a fast and flexible learner.
            </p>
        </div>
        <div id="photo">
            <img src="../assets/myself2.jpg" id="self">
        </div>
    </div>
</template>


<style scoped>
    #hello-root {
        display: flex;
        justify-content: space-around;
        align-items: center;
        background-color: #edede9;
        padding-top: 20px;
        padding-bottom: 20px;
    }

    #self {
        animation: fadeInRight;
        animation-duration: 1s;
    }


    #greeting {
        text-align: center;
    }

    #greeting > h2 {
        font-size: 3rem;
        margin-bottom: 50px;
    }

    #greeting > p {
        font-size: 1.2rem;
    }

    img {
        width: 400px;
    }
</style>