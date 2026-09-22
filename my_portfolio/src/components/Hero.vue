<template>
    <section id="home" class="hero">

        <div class="hero-container">

            <div class="hero-content">

                <p class="hero-label">
                    COMPUTER ENGINEERING STUDENT
                </p>

                <h1>
                    Hi, I'm
                    <span>John Edison Baccay</span>
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

        </div>

    </section>
</template>

<style scoped>

.hero {
    min-height: 620px;
    padding: 5rem 0;
}

.hero-container {
    max-width: 1200px;
    min-height: 520px;

    margin: 0 auto;
    padding: 0 2rem;

    display: flex;
    align-items: center;
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

    font-size: clamp(3.5rem, 6vw, 4.5rem);
    line-height: 0.95;
    letter-spacing: -0.03em;
}

.hero h1 span {
    display: block;

    color: #2196f3;

    white-space: nowrap;
}

.hero h2 {
    max-width: 600px;

    margin: 1.5rem 0 1rem;

    font-size: 1.4rem;
    line-height: 1.4;
    font-weight: 500;

    color: #d6e1eb;
}

.hero-description {
    max-width: 560px;

    margin: 0;

    color: #aebdca;
    line-height: 1.7;
}

.hero-actions {
    display: flex;
    gap: 1rem;

    margin-top: 2rem;
}

.btn {
    display: inline-flex;
    align-items: center;

    padding: 0.85rem 1.4rem;

    border-radius: 0.5rem;

    text-decoration: none;
    font-weight: 600;

    transition: all 0.3s ease;
}

.btn-primary {
    background-color: #2196f3;
    color: #ffffff;

    box-shadow: 0 8px 24px rgba(33, 150, 243, 0.2);
}

.btn-secondary {
    border: 1px solid #2196f3;

    background: transparent;
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
        padding: 4rem 0;
    }

    .hero-container {
        padding: 0 1.5rem;
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