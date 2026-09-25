
<template>
    <section id="home" class="hero">
        <div class="hero-container">
            <!-- LEFT: HERO CONTENT -->
            <div class="hero-content">
                <p class="hero-label">
                    <span class="label-dot"></span>
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
                        View My Projects
                        <span aria-hidden="true">→</span>
                    </a>

                    <a href="/resume.pdf" class="btn btn-secondary">
                        Download CV
                    </a>
                </div>

                <div class="hero-socials">
                    <a
                        href="https://github.com/Jdeexon"
                        target="_blank"
                        rel="noopener noreferrer"
                        aria-label="GitHub profile"
                    >
                        <svg viewBox="0 0 24 24" fill="currentColor">
                            <path
                                d="M12 .9a11.1 11.1 0 0 0-3.51 21.63c.56.1.76-.24.76-.54v-2.1c-3.1.67-3.76-1.32-3.76-1.32-.5-1.28-1.23-1.62-1.23-1.62-1.01-.69.08-.68.08-.68 1.12.08 1.71 1.15 1.71 1.15.99 1.7 2.6 1.21 3.23.92.1-.72.39-1.21.7-1.49-2.48-.28-5.09-1.24-5.09-5.52 0-1.22.44-2.22 1.15-3-.12-.28-.5-1.42.11-2.96 0 0 .94-.3 3.06 1.15a10.65 10.65 0 0 1 5.57 0c2.12-1.45 3.06-1.15 3.06-1.15.61 1.54.23 2.68.11 2.96.72.78 1.15 1.78 1.15 3 0 4.29-2.61 5.23-5.1 5.51.4.35.75 1.02.75 2.06v3.05c0 .3.2.65.77.54A11.1 11.1 0 0 0 12 .9Z"
                            />
                        </svg>
                    </a>

                    <a
                        href="https://www.linkedin.com/in/johnedisonbaccay30/"
                        target="_blank"
                        rel="noopener noreferrer"
                        aria-label="LinkedIn profile"
                    >
                        <svg viewBox="0 0 24 24" fill="currentColor">
                            <path
                                d="M20.45 2H3.55C2.69 2 2 2.68 2 3.52v16.96c0 .84.69 1.52 1.55 1.52h16.9c.86 0 1.55-.68 1.55-1.52V3.52c0-.84-.69-1.52-1.55-1.52ZM7.93 18.45H4.96V9h2.97v9.45ZM6.45 7.71a1.72 1.72 0 1 1 0-3.44 1.72 1.72 0 0 1 0 3.44Zm12 10.74h-2.97v-4.6c0-1.1-.02-2.52-1.54-2.52-1.54 0-1.78 1.2-1.78 2.44v4.68H9.2V9h2.85v1.29h.04c.4-.75 1.37-1.54 2.82-1.54 3.01 0 3.56 1.98 3.56 4.56v5.14Z"
                            />
                        </svg>
                    </a>

                    <a
                        href="mailto:edisonbaccaymoy1230@gmail.com"
                        aria-label="Send email"
                    >
                        <svg
                            viewBox="0 0 24 24"
                            fill="none"
                            stroke="currentColor"
                            stroke-width="1.8"
                            stroke-linecap="round"
                            stroke-linejoin="round"
                        >
                            <rect
                                x="3"
                                y="5"
                                width="18"
                                height="14"
                                rx="2"
                            />
                            <path d="m3 7 9 6 9-6" />
                        </svg>
                    </a>
                </div>
            </div>

            <!-- RIGHT: PHOTO AREA -->
            <div class="hero-visual" aria-hidden="true">
                <div class="hero-photo"></div>
                <div class="photo-overlay"></div>

                <div class="hero-quote">
                    <span>Learn.</span>
                    <span>Build.</span>
                    <span>Improve.</span>
                    <span>Repeat.</span>
                </div>
            </div>
        </div>
    </section>
</template>

<style scoped>
.hero {
    position: relative;
    min-height: 620px;
    overflow: hidden;
    background: #07111c;
}

/* MAIN LAYOUT */

.hero-container {
    position: relative;
    display: grid;
    grid-template-columns: minmax(0, 1fr) minmax(0, 0.95fr);
    align-items: center;

    max-width: 1400px;
    min-height: 620px;
    margin: 0 auto;
    padding: 3rem 2rem;
}

/* LEFT CONTENT */

.hero-content {
    position: relative;
    z-index: 2;
    max-width: 650px;
    padding: 2rem 0;
}

.hero-label {
    display: flex;
    align-items: center;
    gap: 0.6rem;

    margin: 0 0 1.25rem;

    color: #64b5f6;
    font-size: 0.75rem;
    font-weight: 700;
    letter-spacing: 0.15rem;
}

.label-dot {
    width: 7px;
    height: 7px;
    flex-shrink: 0;
    border-radius: 50%;
    background: #2196f3;
    box-shadow: 0 0 12px rgba(33, 150, 243, 0.7);
}

.hero h1 {
    margin: 1rem 0;

    color: #f4f7fb;
    font-size: clamp(3rem, 5vw, 4.5rem);
    font-weight: 800;
    line-height: 1.02;
    letter-spacing: -0.04em;
}

.hero h1 span {
    display: block;
    color: #2196f3;
}

.hero h2 {
    max-width: 600px;
    margin: 1.5rem 0 1rem;

    color: #d6e1eb;
    font-size: 1.4rem;
    line-height: 1.4;
    font-weight: 500;
}

.hero-description {
    max-width: 560px;
    margin: 0;

    color: #aebdca;
    font-size: 1rem;
    line-height: 1.7;
}

/* BUTTONS */

.hero-actions {
    display: flex;
    flex-wrap: wrap;
    gap: 1rem;
    margin-top: 2rem;
}

.btn {
    display: inline-flex;
    align-items: center;
    justify-content: center;
    gap: 0.6rem;

    min-height: 48px;
    padding: 0.85rem 1.4rem;

    border: 1px solid transparent;
    border-radius: 0.5rem;

    text-decoration: none;
    font-size: 0.9rem;
    font-weight: 600;

    transition:
        transform 0.25s ease,
        background-color 0.25s ease,
        border-color 0.25s ease;
}

.btn:hover {
    transform: translateY(-2px);
}

.btn-primary {
    background-color: #2196f3;
    color: #ffffff;
    box-shadow: 0 8px 24px rgba(33, 150, 243, 0.2);
}

.btn-primary:hover {
    background: #1976d2;
}

.btn-secondary {
    border-color: #2196f3;
    background: rgba(7, 17, 28, 0.65);
    color: #64b5f6;
}

.btn-secondary:hover {
    background: #2196f3;
    color: #ffffff;
}

/* SOCIAL LINKS */

.hero-socials {
    display: flex;
    align-items: center;
    gap: 1.1rem;
    margin-top: 1.75rem;
}

.hero-socials a {
    display: flex;
    align-items: center;
    justify-content: center;

    width: 25px;
    height: 25px;

    color: #c1d0df;
    transition:
        color 0.2s ease,
        transform 0.2s ease;
}

.hero-socials a:hover {
    color: #64b5f6;
    transform: translateY(-2px);
}

.hero-socials svg {
    width: 18px;
    height: 18px;
}

/* RIGHT PHOTO */

.hero-visual {
    position: absolute;
    inset: 0 0 0 28%;
    overflow: hidden;
    pointer-events: none;
}

.hero-photo {
    position: absolute;
    inset: 0;

    background-image: url("/images/hero-study.png");
    background-repeat: no-repeat;
    background-size: cover;
    background-position: center 35%;
}

/* Blends photo into the dark website background */

.photo-overlay {
    position: absolute;
    inset: 0;

    background:
        linear-gradient(
            90deg,
            #07111c 0%,
            rgba(7, 17, 28, 0.9) 12%,
            rgba(7, 17, 28, 0.45) 42%,
            rgba(7, 17, 28, 0.08) 100%
        ),
        linear-gradient(
            0deg,
            #07111c 0%,
            rgba(7, 17, 28, 0.15) 30%,
            rgba(7, 17, 28, 0.08) 75%,
            #07111c 100%
        );
}

/* Small quote over the image */

.hero-quote {
    position: absolute;
    right: 3rem;
    bottom: 2rem;

    display: flex;
    flex-direction: column;
    align-items: flex-end;
    gap: 0.25rem;

    color: rgba(160, 205, 240, 0.8);
    font-size: 0.8rem;
    font-style: italic;
    letter-spacing: 0.04rem;
}

/* TABLET */

@media (max-width: 900px) {
    .hero-container {
        grid-template-columns: 1fr;
        min-height: 620px;
        padding: 3rem 2rem;
    }

    .hero-content {
        max-width: 590px;
    }

    .hero-visual {
        left: 25%;
    }

    .hero-photo {
        background-position: 58% center;
    }

    .photo-overlay {
        background:
            linear-gradient(
                90deg,
                #07111c 0%,
                rgba(7, 17, 28, 0.9) 35%,
                rgba(7, 17, 28, 0.35) 100%
            ),
            linear-gradient(
                0deg,
                #07111c 0%,
                transparent 45%,
                #07111c 100%
            );
    }
}

/* MOBILE */

@media (max-width: 600px) {
    .hero,
    .hero-container {
        min-height: 650px;
    }

    .hero-container {
        padding: 4rem 1.25rem 5rem;
    }

    .hero-content {
        padding: 1rem 0;
    }

    .hero-visual {
        inset: 0;
    }

    .hero-photo {
        background-position: 60% center;
    }

    .photo-overlay {
        background:
            linear-gradient(
                90deg,
                rgba(7, 17, 28, 0.96) 0%,
                rgba(7, 17, 28, 0.82) 58%,
                rgba(7, 17, 28, 0.5) 100%
            ),
            linear-gradient(
                0deg,
                #07111c 0%,
                transparent 55%,
                #07111c 100%
            );
    }

    .hero-label {
        font-size: 0.65rem;
        letter-spacing: 0.1rem;
    }

    .hero h1 {
        font-size: clamp(2.8rem, 11vw, 3.8rem);
    }

    .hero h2 {
        font-size: 1.15rem;
    }

    .hero-description {
        font-size: 0.9rem;
        line-height: 1.7;
    }

    .hero-actions {
        gap: 0.75rem;
    }

    .btn {
        min-height: 45px;
        padding: 0.75rem 1rem;
        font-size: 0.82rem;
    }

    .hero-quote {
        right: 1.25rem;
        bottom: 1.5rem;
        font-size: 0.7rem;
    }
}
</style>