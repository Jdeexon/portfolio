
<template>
    <section id="experience" class="journey">
        <div class="journey-container">
            <div class="section-heading">
                <p class="section-label">▌ EXPERIENCE & EDUCATION</p>
                <h2>My Journey</h2>
            </div>

            <div class="timeline">
                <!-- ELEMENTARY -->
                <article class="timeline-item">
                    <span class="timeline-dot"></span>

                    <p class="timeline-date">Graduated 2017</p>

                    <div class="timeline-content">
                        <h3>Elementary Education</h3>
                        <p class="timeline-place">
                            Magalalag East Elementary School
                        </p>
                        <p class="timeline-location">
                            Elementary Graduate
                        </p>
                    </div>
                </article>

                <!-- HIGH SCHOOL -->
                <article class="timeline-item">
                    <span class="timeline-dot"></span>

                    <p class="timeline-date">Graduated 2023</p>

                    <div class="timeline-content">
                        <h3>High School Education</h3>
                        <p class="timeline-place">
                            Magalalag West National High School
                        </p>
                        <p class="timeline-location">
                            High School Graduate
                        </p>
                    </div>
                </article>

                <!-- COLLEGE -->
                <article class="timeline-item">
                    <span class="timeline-dot"></span>

                    <p class="timeline-date">2023 – Present</p>

                    <div class="timeline-content">
                        <h3>BS Computer Engineering</h3>
                        <p class="timeline-place">
                            Cagayan State University
                        </p>
                        <p class="timeline-location">
                            Tuguegarao City
                        </p>
                    </div>
                </article>

                <!-- OJT -->
                <article class="timeline-item">
                    <span class="timeline-dot"></span>

                    <p class="timeline-date">2024 – 2025</p>

                    <div class="timeline-content">
                        <h3>OJT – Help Desk Support</h3>
                        <p class="timeline-place">
                            RDC Technology Solutions, Inc.
                        </p>
                        <p class="timeline-location">
                            On-the-Job Training
                        </p>
                    </div>
                </article>

                <!-- CONTINUOUS LEARNING -->
                <article class="timeline-item">
                    <span class="timeline-dot current"></span>

                    <p class="timeline-date">Present</p>

                    <div class="timeline-content">
                        <h3>Continuous Learning</h3>
                        <p class="timeline-place">
                            Web Development, AI, Networking
                        </p>
                        <p class="timeline-location">
                            Building new skills
                        </p>
                    </div>
                </article>
            </div>
        </div>
    </section>
</template>

<style scoped>
.journey {
    padding: 1.5rem 0 2rem;
    border-top: 1px solid #172536;
}

.journey-container {
    width: 100%;
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 2rem;
}

.section-heading {
    margin-bottom: 1.5rem;
}

.section-label {
    margin: 0 0 0.35rem;
    color: #64b5f6;
    font-size: 0.65rem;
    font-weight: 700;
    letter-spacing: 0.12rem;
}

.section-heading h2 {
    margin: 0;
    color: #f4f7fb;
    font-size: 1.65rem;
    line-height: 1.2;
}

/* TIMELINE */

.timeline {
    position: relative;
    display: grid;
    grid-template-columns: repeat(5, minmax(0, 1fr));
    gap: 1rem;
    padding-top: 1.25rem;
}

.timeline::before {
    content: "";
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    height: 1px;
    background: #284158;
}

.timeline-item {
    position: relative;
    min-width: 0;
}

.timeline-dot {
    position: absolute;
    top: -1.5rem;
    left: 0;

    width: 11px;
    height: 11px;

    border: 2px solid #07111c;
    border-radius: 50%;

    background: #2587ef;
    box-shadow: 0 0 0 1px #2587ef;
}

.timeline-dot.current {
    background: #43c59e;
    box-shadow: 0 0 0 1px #43c59e;
}

.timeline-date {
    margin: 0 0 0.5rem;
    color: #d4deea;
    font-size: 0.72rem;
    font-weight: 600;
}

.timeline-content h3 {
    margin: 0 0 0.35rem;
    color: #f2f6fb;
    font-size: 0.82rem;
    font-weight: 600;
    line-height: 1.4;
}

.timeline-place {
    margin: 0;
    color: #b6c4d2;
    font-size: 0.72rem;
    line-height: 1.5;
    overflow-wrap: anywhere;
}

.timeline-location {
    margin: 0.2rem 0 0;
    color: #788da2;
    font-size: 0.68rem;
    line-height: 1.5;
}

/* TABLET */

@media (max-width: 950px) {
    .timeline {
        grid-template-columns: repeat(3, minmax(0, 1fr));
        row-gap: 2.5rem;
    }

    .timeline::before {
        display: none;
    }

    .timeline-item {
        padding-top: 0.9rem;
        border-top: 1px solid #284158;
    }

    .timeline-dot {
        top: -6px;
    }
}

/* MOBILE */

@media (max-width: 600px) {
    .journey {
        padding: 1.5rem 0;
    }

    .journey-container {
        padding: 0 1.25rem;
    }

    .timeline {
        grid-template-columns: 1fr;
        gap: 1.75rem;
    }

    .timeline-item {
        padding: 0 0 0 1rem;
        border-top: none;
        border-left: 1px solid #284158;
    }

    .timeline-dot {
        top: 0;
        left: -6px;
    }

    .timeline-date {
        margin-bottom: 0.35rem;
    }
}
</style>