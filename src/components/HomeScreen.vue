<template>
    <main>
        <div class="opening-text">
            <h1>Jeff Herz</h1>
            <h3>An avid problem-solver and software developer</h3>
            <AboutMe/>

        </div>
        
    </main>
</template>

<script>
import AboutMe from './AboutMe'

export default {
    name: AboutMe,
    components: {
        'AboutMe': AboutMe
    }
}
</script>

<style>
    body {
        background-color: #464649;
    }
</style>