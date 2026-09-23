<template>
    <section id="about" class="about">

        <div class="about-container">

            <!-- Personal Photo -->
            <div class="about-photo">

                <div class="photo-placeholder">
                    YOUR PHOTO
                </div>

                <div class="about-quote">
                    <p>
                        "Technology is a tool.
                        People are the purpose."
                    </p>
                </div>

            </div>


            <!-- About Content -->
            <div class="about-content">

                <p class="section-label">
                    ABOUT ME
                </p>

                <h2>
                    More Than Just Code
                </h2>

                <p class="about-description">
                    I'm a Computer Engineering student who enjoys
                    understanding how technology works—from software
                    and databases to embedded systems and networks.
                </p>

                <p class="about-description">
                    My interests span web development, embedded systems,
                    databases, and emerging technologies. I enjoy learning
                    by building, experimenting, solving problems, and
                    turning ideas into practical systems.
                </p>

                <div class="about-info">

                    <span>📍 Alibago, Enrile, Cagayan</span>

                    <span>🎓 BS Computer Engineering</span>

                </div>

                <div class="about-info">

                    <span>💙 Christian</span>

                    <span>🌱 Lifelong Learner</span>

                    <span>🤝 Servant Leader</span>

                </div>

            </div>


            <!-- Build / Learn / Serve -->
            <div class="about-values">

                <article class="value-card">

                    <div class="value-icon">
                        &lt;/&gt;
                    </div>

                    <div>
                        <h3>Build</h3>

                        <p>
                            Practical and purposeful
                            technology solutions.
                        </p>
                    </div>

                </article>


                <article class="value-card">

                    <div class="value-icon">
                        📖
                    </div>

                    <div>
                        <h3>Learn</h3>

                        <p>
                            Explore, adapt, and grow
                            continuously.
                        </p>
                    </div>

                </article>


                <article class="value-card">

                    <div class="value-icon">
                        👥
                    </div>

                    <div>
                        <h3>Serve</h3>

                        <p>
                            Use my skills to help people
                            and contribute to society.
                        </p>
                    </div>

                </article>

            </div>

        </div>

    </section>
</template>


<style scoped>

.about {
    padding: 5rem 0;
    border-top: 1px solid #1c344a;
}

.about-container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 2rem;

    display: grid;
    grid-template-columns: 220px 1fr 220px;
    gap: 2.5rem;

    align-items: center;
}


/* PHOTO */

.about-photo {
    position: relative;
}

.photo-placeholder {
    height: 280px;

    border: 1px solid #1c344a;
    border-radius: 0.75rem;

    background: #0b1825;

    display: flex;
    align-items: center;
    justify-content: center;

    color: #aebdca;
    font-size: 0.8rem;
    letter-spacing: 0.1rem;
}

.about-quote {
    position: absolute;

    left: -0.75rem;
    bottom: -0.75rem;

    width: 190px;

    padding: 1rem;

    border: 1px solid #2196f3;
    border-radius: 0.6rem;

    background: #07111c;
}

.about-quote p {
    margin: 0;

    color: #2196f3;

    font-size: 0.85rem;
    font-style: italic;
    line-height: 1.5;
}


/* ABOUT CONTENT */

.section-label {
    color: #2196f3;

    font-size: 0.8rem;
    font-weight: 700;
    letter-spacing: 0.15rem;
}

.about h2 {
    margin: 0.75rem 0 1rem;

    font-size: 2.4rem;
}

.about-description {
    max-width: 650px;

    color: #aebdca;
    line-height: 1.7;
}

.about-info {
    display: flex;
    flex-wrap: wrap;

    gap: 1rem;

    margin-top: 1rem;

    color: #aebdca;
    font-size: 0.9rem;
}


/* VALUES */

.about-values {
    display: flex;
    flex-direction: column;

    gap: 1.5rem;
}

.value-card {
    display: flex;
    align-items: center;

    gap: 1rem;
}

.value-icon {
    width: 46px;
    height: 46px;

    flex-shrink: 0;

    border: 1px solid #2196f3;
    border-radius: 50%;

    display: flex;
    align-items: center;
    justify-content: center;

    color: #2196f3;

    font-weight: 700;
}

.value-card h3 {
    margin: 0 0 0.25rem;

    font-size: 1rem;
}

.value-card p {
    margin: 0;

    color: #aebdca;

    font-size: 0.85rem;
    line-height: 1.5;
}


/* RESPONSIVE */

@media (max-width: 900px) {

    .about-container {
        grid-template-columns: 180px 1fr;
    }

    .about-values {
        grid-column: 1 / -1;

        display: grid;
        grid-template-columns: repeat(3, 1fr);
    }

}

@media (max-width: 768px) {

    .about-container {
        grid-template-columns: 1fr;

        gap: 2rem;
    }

    .about-photo {
        max-width: 280px;
    }

    .about-values {
        grid-template-columns: 1fr;
    }

}

</style>