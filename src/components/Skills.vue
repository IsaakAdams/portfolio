<template>
    <div id="skills-root" class="skills-root">
        <h2>Skills!</h2>

        <!-- Skills list -->
        <div class="skills-list">
            <div class="skill-item">
                HTML5
                <img src="../assets/html.png" alt="HTML logo">
            </div>
            <div class="skill-item">
                CSS3
                <img src="../assets/css.png" alt="CSS logo">
            </div>
            <div class="skill-item">
                Javascript
                <img src="../assets/javascript.png" alt="Javascript logo">
            </div>
            <div class="skill-item">
                Vue
                <img src="../assets/vue.png" alt="VUE logo">
            </div>
            <div class="skill-item">
                React
                <img src="../assets/react.png" alt="REACT logo">
            </div>
            <div class="skill-item">
                Python
                <img src="../assets/python.png" alt="PYTHON logo">
            </div>
            <div class="skill-item">
                Sql
                <img src="../assets/sql.png" alt="SQL logo">
            </div>
            <div class="skill-item">
                Git
                <img src="../assets/git.png" alt="GIT logo">
            </div>
        </div>
    </div>
</template>

<style scoped>
    /* Root div */
    .skills-root {
        background-color: #E3D5CA;
        padding: 30px 10px;
    }

    /* h2 inside root div */
    h2 {
        text-align: center;
    }

    /* Skill list styling */
    .skills-list {
        display: flex;
        justify-content: space-evenly;
    }

    .skill-item img {
        width: 50px;
        margin-top: 5px;
    }

    .skill-item:hover {
        border: 1px solid white;
        border-radius: 3px;
        transform: scale(1.1);
        padding: 10px;
    }

    .skill-item {
        display: flex;
        flex-direction: column;
        align-items: center;
        transition: all 0.2s ease-in-out;
    }
</style>