<template>
    <nav class="navbar">
        <div class="navbar-container">

            <a href="#home" class="logo">
                <span>J</span>DEEXON
            </a>

            <div class="nav-links">
                <a href="#home">Home</a>
                <a href="#about">About</a>
                <a href="#skills">Skills</a>
                <a href="#projects">Projects</a>
                <a href="#experience">Experience</a>
                <a href="#certifications">Certifications</a>
                <a href="#contact">Contact</a>
            </div>

        </div>
    </nav>
</template>

<style scoped>

.navbar {
    border-bottom: 1px solid #1c344a;
}

.navbar-container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 1rem 2rem;

    display: flex;
    justify-content: space-between;
    align-items: center;
}

.logo {
    text-decoration: none;
    color: #ffffff;

    font-size: 1.3rem;
    font-weight: 800;
    letter-spacing: -0.03em;
}

.logo span {
    color: #2196f3;
}

.nav-links {
    display: flex;
    gap: 1.5rem;
}

.nav-links a {
    text-decoration: none;
    color: #aebdca;

    transition: color 0.3s ease;
}

.nav-links a:hover {
    color: #2196f3;
}

</style>