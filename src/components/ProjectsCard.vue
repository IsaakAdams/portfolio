<template>
    <div class="main-container">
        <div class="project-card" v-for="item in items" :key="item">
            <h2>{{ item.Title }}</h2>
            <img :src="item.Image" alt="">
            <p>{{ item.About }}</p>
            <div class="links">
                <a :href="item.Link1" target="_blank">
                    <i class="fa-brands fa-github"></i>
                </a>
                <a :href=item.Link2 target="_blank">
                    <i class="fa-solid fa-arrow-up-right-from-square"></i>
                </a>
            </div>
        </div>
    </div>
    
</template>

<script>
    import jsonData from "../projects.json"
    const projectsArray = jsonData.projectsArray
    export default {
        data() {
            return {
                items: projectsArray
            }
        }
    }
    console.log(jsonData.projectsArray)
</script>

<style scoped>
    .main-container {
        margin-top: 5%;
        display: flex;
        justify-content: center;
        align-items: center;
        flex-wrap: wrap;
    }

    .project-card {
        text-align: center;
        margin: 20px 10px;
        padding: 15px;
        flex-basis: 40%;
        background-color: white;
        box-shadow: rgba(0, 0, 0, 0.24) 0px 3px 8px;
        border-radius: 25px;
    }

    .project-card img {
        height: 20rem;
    }

    .links {
        display: flex;
        flex-direction: row;
        align-items: center;
        justify-content: flex-end;
    }


    .links i {
        font-size: 2.5rem;
        margin: 5px;
        color: black;
    }

    .links i:hover {
        font-size: 2.6rem;
        color: #1292EE;
    }
</style>