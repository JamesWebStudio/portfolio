<template>
<section class="container">
    <h1 style="margin-bottom:30px;" id="contact-title">Contact Us</h1>
    <form class="mx-auto" method="POST" action="https://formsubmit.co/nigeljames14@outlook.com">
        <input type="hidden" name="_autoresponse" value="Thank you, your message as been received and we will get back to you as soon as possible" />
        <input type="hidden" name="_captcha" value="false" />
        <input type="hidden" name="_template" value="table" />
        <input type="hidden" name="_next" value="http://localhost:3000/" />
        <input type="hidden" name="_subject" value="JAMESWEBSTUDIO - new Query from website" />
        <label for="name">Your Name or Business</label>
        <input type="text" name="name" class="form-control" required id="nameInput">
        <label for="email">Contact Email</label>
        <input type="email" name="email" class="form-control" required>
        <label for="phone">Contact Phone</label>
        <input type="text" name="phone" class="form-control">
        <label for="message">Your Message</label>
        <textarea type="text" name="message" class="form-control" cols="30" rows="10" required></textarea>
        <button class="btn custom-btn" type="submit" >Send Message</button>
    </form>
</section>
</template>

<script setup>
    onMounted(() => {
        setTimeout(() => {
            document.getElementById("nameInput").focus()
        }, 500) 
    })
</script>

<style scoped>
    section {
        margin-top: 30px;
        width: 100%;
        color: white;
        padding:0 10px;
        height: 100vh;
    }

    form {
        width: 100%;
    }

    input, textarea {
        background: rgba(255, 255, 255, 0.2);
        margin-bottom:25px;
        border: none;
        border-bottom: 1px solid white;
        font-weight:600px;
        color: var(--title-background-gradient);

    }
    
    button {
        width:100%;
    }

    imput:invalid {
        border: 3px solid red;
    }

</style>