<template>
    <div id="mainLayout">
        <Html lang="en-GB">
            <title>JamesWebStudio</title>
        </Html>
        <Nav />
        <slot />
        <Footer />
    </div>
</template>

<style scoped>
#mainLayout {
    display:flex; 
    flex-direction: column;
}
</style>