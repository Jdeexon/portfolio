
<template>
    <nav class="navbar">
        <div class="navbar-container">
            <a href="#home" class="logo" aria-label="Jdeexon home">
                <span class="logo-mark">J</span>
                <span class="logo-name">DEEXON</span>
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
    position: relative;
    z-index: 10;
    width: 100%;

    background: rgba(7, 17, 28, 0.96);
    border-bottom: 1px solid rgba(100, 181, 246, 0.16);
}

/* Match the Hero section's container width and side padding */
.navbar-container {
    display: flex;
    align-items: center;
    justify-content: space-between;
    gap: 2rem;

    width: 100%;
    max-width: 1400px;
    min-height: 76px;
    margin: 0 auto;
    padding: 0 2rem;
}

/* LOGO */

.logo {
    display: inline-flex;
    align-items: center;
    gap: 0.1rem;
    flex-shrink: 0;

    color: #f4f7fb;
    text-decoration: none;
    font-size: 1.25rem;
    font-weight: 800;
    letter-spacing: -0.045em;

    transition: opacity 0.25s ease;
}

.logo:hover {
    opacity: 0.85;
}

.logo-mark {
    color: #2196f3;
    font-size: 1.65rem;
    line-height: 1;
    text-shadow: 0 0 18px rgba(33, 150, 243, 0.3);
}

.logo-name {
    color: #f4f7fb;
}

/* NAVIGATION LINKS */

.nav-links {
    display: flex;
    align-items: center;
    justify-content: flex-end;
    gap: clamp(1rem, 1.8vw, 1.75rem);
}

.nav-links a {
    position: relative;
    display: inline-flex;
    align-items: center;

    min-height: 76px;

    color: #b8c6d4;
    text-decoration: none;
    font-size: 0.9rem;
    font-weight: 500;
    white-space: nowrap;

    transition: color 0.25s ease;
}

.nav-links a::after {
    content: "";
    position: absolute;
    right: 0;
    bottom: 20px;
    left: 0;

    height: 2px;
    border-radius: 2px;
    background: #2196f3;

    transform: scaleX(0);
    transform-origin: left;
    transition: transform 0.25s ease;
}

.nav-links a:hover {
    color: #ffffff;
}

.nav-links a:hover::after {
    transform: scaleX(1);
}

/* TABLET */

@media (max-width: 1000px) {
    .navbar-container {
        gap: 1.5rem;
    }

    .nav-links {
        gap: 1rem;
    }

    .nav-links a {
        font-size: 0.82rem;
    }
}

/* MOBILE */

@media (max-width: 760px) {
    .navbar-container {
        min-height: auto;
        flex-direction: column;
        align-items: flex-start;
        gap: 0.75rem;
        padding: 1rem 1.25rem 0;
    }

    .logo {
        font-size: 1.15rem;
    }

    .logo-mark {
        font-size: 1.5rem;
    }

    .nav-links {
        width: 100%;
        justify-content: flex-start;
        gap: 1.4rem;

        overflow-x: auto;
        overscroll-behavior-x: contain;
        scrollbar-width: none;
    }

    .nav-links::-webkit-scrollbar {
        display: none;
    }

    .nav-links a {
        min-height: 42px;
        font-size: 0.82rem;
    }

    .nav-links a::after {
        bottom: 0;
    }
}

@media (max-width: 420px) {
    .navbar-container {
        padding-right: 1rem;
        padding-left: 1rem;
    }

    .nav-links {
        gap: 1.2rem;
    }
}
</style>