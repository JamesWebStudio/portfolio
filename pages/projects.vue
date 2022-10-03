<template>
    <section id="projects">
        <div id="projects-head-info">
            <h2>Projects</h2>
            <h5>A small sample of our previous work</h5>
        </div>
        <section id="cards-container">
            <section class="card">
                <div class="card-title">
                    <h4>Space Odyssey</h4>
                </div>
                <div class="card-sub-title">A space exploration & info site with NASA live news feed and 3 level quiz</div>
                <div class="card-body">
                    <img src="@/assets/spaceodyssey.webp" alt="No Image">
                </div>
                <div class="card-tech">
                    <p>Nuxt 2 & NASA API</p>
                </div>
                <div class="card-link">
                    <a href="http://www.space-odyssey.surge.sh" target="_blank">Link</a>
                </div>
            </section>
            <section class="card">
                <div class="card-title">
                    <h4>Pocket Office</h4>
                </div>
                <div class="card-sub-title">Simple mobile appointments, meetings and diary app</div>
                <div class="card-body">
                    <img src="@/assets/pocketoffice.webp" alt="No Image">
                </div>
                <div class="card-tech">
                    <p>Vue 2.6 & Firebase</p>
                </div>
                <div class="card-link">
                    <a href="http://pocket-office.surge.sh/" target="_blank">Link</a>
                </div>
            </section>
            <section class="card">
                <div class="card-title">
                    <h4>Workout Buddy</h4>
                </div>
                <div class="card-sub-title">A training app for training and diet advice and recording of stats & progress</div>
                <div class="card-body">
                    <img src="@/assets/workoutbuddy.webp" alt="No Image" loading="lazy">
                </div>
                <div class="card-tech">
                    <p>Nuxt, Firebase & Charts</p>
                </div>
                <div class="card-link">
                    <a href="https://workoutbuddy.surge.sh/" target="_blank">Link</a>
                </div>
            </section>
            <section class="card">
                <div class="card-title">
                    <h4>TBD</h4>
                </div>
                <div class="card-sub-title">TBW</div>
                <div class="card-body">
                    <img src="@/assets/spaceodyssey.jpg" alt="No Image" loading="lazy">
                </div>
                <div class="card-tech">
                    <p>Vue 2.6 & Firebase</p>
                </div>
                <div class="card-link">
                    <a href="http://www.space-odyssey.surge.sh" target="_blank">Link</a>
                </div>
            </section>
            <section class="card">
                <div class="card-title">
                    <h4>TDB</h4>
                </div>
                <div class="card-sub-title">TBW</div>
                <div class="card-body">
                    <img src="@/assets/spaceodyssey.jpg" alt="No Image" loading="lazy">
                </div>
                <div class="card-tech">
                    <p>Vue 2.6 & Firebase</p>
                </div>
                <div class="card-link">
                    <a href="http://www.space-odyssey.surge.sh" target="_blank">Link</a>
                </div>
            </section>
            <section class="card">
                <div class="card-title">
                    <h4>TBD</h4>
                </div>
                <div class="card-sub-title">TBW</div>
                <div class="card-body">
                    <img src="@/assets/spaceodyssey.jpg" alt="No Image" loading="lazy">
                </div>
                <div class="card-tech">
                    <p>Vue 2.6 & Firebase</p>
                </div>
                <div class="card-link">
                    <a href="http://www.space-odyssey.surge.sh" target="_blank">Link</a>
                </div>
            </section>
        </section>
    </section>
    
</template>

<script setup>


</script>

<style scoped>
    #projects {
        color: white;
        margin-top:30px;
    }

    #projects-head-info {
        padding-left:15px;
    }

    #cards-container {
        display:flex;
        flex-wrap: wrap;
    }

    h1, h4 {
        margin:0;
    }
    .card {
        margin-top:25px;
    }
    

    .card-sub-title {
        background-color: rgb(10, 10 ,10);
        min-height: 60px;
        padding:5px;
        text-align:center;
    }

    .card-tech {
        background-color: black;
        text-align: center;
        padding:5px;
    }

    .card-link {
        color: orangered;
    }

    @media (min-width:800px) {
        #cards-container {
            margin: 30px 15px;
        }
    }
</style>