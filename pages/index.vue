<template>
<div id="home">
    <section id="intro" class="scale-in-center container-lg">
        <img src="src/images/logo.png" alt="">
        <h2 class="text-focus-in tracking-in-expand"><span>Welcome to JamesWebStudio</span></h2>
        <p>I'm Nigel James a full stack web developer at JamesWebStudio</p>
        <p>Availiable for front end, back end or full stack projects</p>
        <hr />
        <p>to contact us click below</p>
        <nuxt-link to="/contact"><button class="btn heartbeat custom-btn">Contact Us</button></nuxt-link>
    </section>
    <section>
        <h2>Our Services</h2>
        <div class="card">
            <div class="card-title">
                <h3>Modern Web Development</h3>
            </div>
            <div class="card-body">
                <p>Using the latest technologies we create modern and functional websites and applications</p>
                <p>All our work is fully responsize and works equally well on all screen sizes from mobile to large desktop devices and screens</p>
                <p>We use state of the art tools like Vue.js, Nuxt.js, Node,  </p>
            </div>

        </div>
        <div class="card">
            <div class="card-title">
                <h3>Wordpress Development</h3>
            </div>
            <div class="card-body">
                <p>Whether its a plain website, a personal blog or a full blown ecommerce application</p>
                <p>Wordpress is a great tool to use</p>
                <p></p>
            </div>

        </div>
        <div class="card">
            <div class="card-title">
                <h3>SEO Services</h3>
            </div>
            <div class="card-body">
                <p><span>S</span>earch <span>E</span>ngine <span>O</span>ptimization makes your site more visible to all common search engines</p>
                <p>Standard SEO is included in all our work but we provide specialized SEO services to maximise the search rankings for your site</p>
                <p></p>
            </div>

        </div>
        <div class="card">
            <div class="card-title">
                <h3></h3>
            </div>
            <div class="card-body">
                <p>Using the Latest technologies we create modern and functional websites and applications</p>
                <p>All our work is fully responsize to work equally well on all screen sizes</p>
                <p></p>
            </div>

        </div>
        
    </section>
    
</div>
</template>

<script setup>
    
</script>

<style scoped>
#home {
    position: relative;
    min-height: 100vh;
    background-color: transparent;
    
}

img {
    width:100%;
}

h2 {
    margin-bottom:30px;
    text-align: center;
    letter-spacing:2px;
}

h3 {
    margin:0;
}

#intro {
    color: white;  
    font-size: 1.2em;
    font-weight: 800;
    letter-spacing:2px;
    text-align: center;
    padding:0;
    text-align:center;
    background-size: cover;
    background-position:center;
    font-family: Roboto, Tangerine Georgia, 'Times New Roman', Times, serif;
    margin-bottom:50px;
}

#intro p, #intro h2 { 
    margin-top: 30px;
    text-shadow: 2px 0 black;
    padding: 10px;
}

#intro button:hover {
    color: bisque;
    background: radial-gradient(rgb(82, 82, 133), #012035, rgb(57, 57, 68));
    clip-path: polygon(50% 0%, 80% 10%, 100% 35%, 100% 70%, 80% 90%, 50% 100%, 20% 90%, 0% 70%, 0% 35%, 20% 10%);
}

span {
    font-weight: 900;
    color: red;
    font-size: 1.3em;
}

#about-link {
    font-size: 1.4em;
    border-top: 2px solid white;
    border-bottom: 2px solid white;
}

.card {
    margin-bottom: 3em;
    background: transparent;
}

.card-body {
    padding: 10px;
}

.card-body p span {
    color: red;
    text-decoration: italic;
    font-size: 2em;
    margin-right: 2px;
}

.card-body p {
    letter-spacing:2px;
    line-height: 25px;
}
   
   
   
/***** MEDIUM SCREEN *****/
@media screen and (min-width:800px) {
    #home {
        display: grid;
        grid-template-columns: 300px 1fr;
        column-gap: 20px;
        /* padding: 0 10%; */
    }
}


</style>