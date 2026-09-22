<template>
    <section id="home" class="hero">

        <div class="hero-content">

            <p class="hero-label">
                COMPUTER ENGINEERING STUDENT
            </p>

            <h1>
                Hi, I'm
                <span>Jdeexon</span>
            </h1>

            <h2>
                Building software, hardware, and technology solutions.
            </h2>

            <p class="hero-description">
                I'm a Computer Engineering student exploring software
                development, embedded systems, networking, and systems
                engineering. I'm always open to learning new technologies
                and building practical solutions.
            </p>

            <div class="hero-actions">
                <a href="#projects" class="btn btn-primary">
                    View My Projects →
                </a>

                <a href="#" class="btn btn-secondary">
                    Download CV
                </a>
            </div>

        </div>

    </section>
</template>

<style scoped>

.hero {
    max-width: 1200px;
    margin: 0 auto;
    padding: 6rem 2rem;
}

.hero-content {
    max-width: 650px;
}

.hero-label {
    color: #2196f3;
    font-size: 0.8rem;
    font-weight: 700;
    letter-spacing: 0.15rem;
}

.hero h1 {
    margin: 1rem 0;
    font-size: clamp(3rem, 8vw, 4.5rem);
    line-height: 1;
}

.hero h1 span {
    display: block;
    color: #2196f3;
}

.hero h2 {
    max-width: 650px;
    font-size: 1.5rem;
    line-height: 1.4;
    font-weight: 500;
    color: #d6e1eb;
}

.hero-description {
    max-width: 600px;
    color: #aebdca;
    line-height: 1.7;
}

.hero-actions {
    display: flex;
    gap: 1rem;
    margin-top: 2rem;
}

.btn {
    padding: 0.9rem 1.5rem;
    border-radius: 0.5rem;
    text-decoration: none;
    font-weight: 600;
    transition: all 0.3s ease;
}

.btn-primary {
    background-color: #2196f3;
    color: #ffffff;
}

.btn-secondary {
    border: 1px solid #2196f3;
    color: #2196f3;

}

.btn-primary:hover {
    background: #1976d2;
}

.btn-secondary:hover {
    background: #2196f3;
    color: #ffffff;
}

@media (max-width: 768px) {
    .hero {
        padding: 4rem 1.5rem;
    }

    .hero h1 {
        font-size: 3.5rem;
    }

    .hero h2 {
        font-size: 1.25rem;
    }

    .hero-actions {
        flex-direction: column;
        align-items: flex-start;
    }
}

</style>