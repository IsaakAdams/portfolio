<template>
    <div id="gallery-root" class="ui container">
        <h2>Projects</h2>
        <div class="card-gallery">
            <!-- First Card Start -->
            <div class="ui card">
                <div class="image">
                    <img src="../assets/tailwind-landing-page.png" alt="Tailwind Landing Page Image">
                </div>
                <div class="content">
                    <p class="header">Tailwind Landing Page</p>
                    <div class="description">
                        <p>Project uses low-level tailwind css framework to create a landing page for the 'manage' company.</p>
                    </div>
                </div>
                <div class="extra content">
                    <a target="_blank" href="https://isaak-tailwind-landing-page.netlify.app/">
                        <button class="ui inverted brown button">Visit</button>
                    </a>
                </div>
            </div>
            <!-- First Card End -->

            <!-- Second Card Start -->
            <div class="ui card">
                <div class="image">
                    <img src="../assets/facebook-clone.png" alt="Image of Facebook Login Page">
                </div>
                <div class="content">
                    <p class="header">Facebook Login Clone</p>
                    <div class="description">
                        <p>Project uses Vue.js components and the bulma css framework to create a clone of the Facebook login page.</p>
                    </div>
                </div>
                <div class="extra content">
                    <a target="_blank" href="#">
                        <button class="ui inverted brown button">Visit</button>
                    </a>
                </div>
            </div>
            <!-- Second Card End -->

            <!-- Third Card Start -->
        </div>
    </div>
</template>


<style scoped>
    h2 {
        text-align: center;
        margin-bottom: 30px;
    }
    .container {
        margin-top: 30px;
        padding-bottom: 30px;
    }

    .card-gallery {
        display: flex;
        justify-content: space-around;
        align-items: center;
    }

    div.extra {
        display: flex;
        justify-content: flex-end;
    }
    
</style>