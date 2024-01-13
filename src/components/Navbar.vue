<template lang="">
    <div class="navb">
        <div class="nav">
            <a href="#home"><img src="https://i.postimg.cc/5tDMfVmt/Group-4-3.png" alt=""></a>
            <div class="links">
                <a href="#resume">Resume</a>
                <a href="#skills">Skills</a>
                <a href="#projects">Projects</a>
                <a href="#testimonials">Testimonials</a>
            </div>
            <div class="buttons">
                <a href="#about">
                    <div class="go"><p>About me</p><div class="bar"></div></div>
                </a>
                <a href="#contact">
                    <div class="btn light"><p>Contact</p><div class="bg"><p></p><p>Contact</p></div></div>
                </a>
            </div>
        </div>
    </div>
</template>
<script>
export default {
    
}
</script>
<style scoped>
.navb {
    width: 100%;
    min-height: 5rem;
    padding: 1rem 2rem;
    position: absolute;
    top: 0;
    z-index: +10;
}
.nav {
    display: flex;
    align-items: center;
}
.nav img {
    height: 2.1rem;
}
.nav .links {
    display: flex;
    align-items: center;
    gap: 2rem;
    margin-left: 2rem;
    margin-right: auto;
}
.nav a {
    text-decoration: none;
    color: var(--navy);
    font-weight: bold;
    font-size: 0.85rem;
    height: fit-content;
}
.buttons {
    display: flex;
    align-items: center;
    gap:2rem;
}


</style>