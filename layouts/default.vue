<template>
    <div id="mainLayout">
        <Html lang="en-GB">
            <Head>
                <Title>JamesWebStudio</Title>
            </Head>
            <Meta name="description" content="JamesWebStudio - Functionality and Simplicity by Design" />
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