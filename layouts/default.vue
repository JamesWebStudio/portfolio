<template>
    <div id="mainLayout" class="container.lg">
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