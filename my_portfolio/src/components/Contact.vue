
<template>
    <section id="contact" class="contact">
        <div class="contact-container">
            <div class="contact-card">
                <p class="section-label">▌ GET IN TOUCH</p>

                <h2>Let's Connect</h2>

                <p class="contact-description">
                    I'm always open to connecting with people, exploring
                    opportunities, and discussing technology. Feel free
                    to reach out!
                </p>

                <div class="contact-actions">
                    <!-- EMAIL -->
                    <a
                        class="contact-button primary"
                        href="mailto:edisonbaccaymoy1230@gmail.com"
                    >
                        <svg
                            viewBox="0 0 24 24"
                            fill="none"
                            stroke="currentColor"
                            stroke-width="1.8"
                            stroke-linecap="round"
                            stroke-linejoin="round"
                        >
                            <rect x="3" y="5" width="18" height="14" rx="2" />
                            <path d="m3 7 9 6 9-6" />
                        </svg>

                        Email Me
                    </a>

                    <!-- GITHUB -->
                    <a
                        class="contact-button"
                        href="https://github.com/Jdeexon"
                        target="_blank"
                        rel="noopener noreferrer"
                    >
                        <svg
                            viewBox="0 0 24 24"
                            fill="currentColor"
                            aria-hidden="true"
                        >
                            <path
                                d="M12 .9a11.1 11.1 0 0 0-3.51 21.63c.56.1.76-.24.76-.54v-2.1c-3.1.67-3.76-1.32-3.76-1.32-.5-1.28-1.23-1.62-1.23-1.62-1.01-.69.08-.68.08-.68 1.12.08 1.71 1.15 1.71 1.15.99 1.7 2.6 1.21 3.23.92.1-.72.39-1.21.7-1.49-2.48-.28-5.09-1.24-5.09-5.52 0-1.22.44-2.22 1.15-3-.12-.28-.5-1.42.11-2.96 0 0 .94-.3 3.06 1.15a10.65 10.65 0 0 1 5.57 0c2.12-1.45 3.06-1.15 3.06-1.15.61 1.54.23 2.68.11 2.96.72.78 1.15 1.78 1.15 3 0 4.29-2.61 5.23-5.1 5.51.4.35.75 1.02.75 2.06v3.05c0 .3.2.65.77.54A11.1 11.1 0 0 0 12 .9Z"
                            />
                        </svg>

                        GitHub
                    </a>

                    <!-- LINKEDIN -->
                    <a
                        class="contact-button"
                        href="https://www.linkedin.com/in/johnedisonbaccay30/"
                        target="_blank"
                        rel="noopener noreferrer"
                    >
                        <svg
                            viewBox="0 0 24 24"
                            fill="currentColor"
                            aria-hidden="true"
                        >
                            <path
                                d="M20.45 2H3.55C2.69 2 2 2.68 2 3.52v16.96c0 .84.69 1.52 1.55 1.52h16.9c.86 0 1.55-.68 1.55-1.52V3.52c0-.84-.69-1.52-1.55-1.52ZM7.93 18.45H4.96V9h2.97v9.45ZM6.45 7.71a1.72 1.72 0 1 1 0-3.44 1.72 1.72 0 0 1 0 3.44Zm12 10.74h-2.97v-4.6c0-1.1-.02-2.52-1.54-2.52-1.54 0-1.78 1.2-1.78 2.44v4.68H9.2V9h2.85v1.29h.04c.4-.75 1.37-1.54 2.82-1.54 3.01 0 3.56 1.98 3.56 4.56v5.14Z"
                            />
                        </svg>

                        LinkedIn
                    </a>
                </div>

                <div class="contact-email">
                    <span class="email-label">Or send me an email at</span>

                    <a href="mailto:edisonbaccaymoy1230@gmail.com">
                        edisonbaccaymoy1230@gmail.com
                    </a>
                </div>
            </div>
        </div>
    </section>
</template>

<style scoped>
.contact {
    padding: 4rem 0;
    border-top: 1px solid #172536;
}

.contact-container {
    max-width: 1000px;
    margin: 0 auto;
    padding: 0 2rem;
}

.contact-card {
    position: relative;
    overflow: hidden;
    padding: 3.5rem 2rem;
    text-align: center;

    border: 1px solid #1c344a;
    border-radius: 1rem;

    background:
        radial-gradient(
            circle at top,
            rgba(33, 150, 243, 0.1),
            transparent 55%
        ),
        linear-gradient(
            145deg,
            #0b1b2a,
            #07111c
        );
}

.section-label {
    margin: 0 0 0.75rem;
    color: #64b5f6;
    font-size: 0.7rem;
    font-weight: 700;
    letter-spacing: 0.15rem;
}

.contact-card h2 {
    margin: 0;
    color: #ffffff;
    font-size: 2.5rem;
    line-height: 1.2;
    letter-spacing: -0.03em;
}

.contact-description {
    max-width: 600px;
    margin: 1rem auto 0;
    color: #91a4b5;
    font-size: 0.95rem;
    line-height: 1.8;
}

.contact-actions {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    gap: 0.85rem;
    margin-top: 2rem;
}

.contact-button {
    display: inline-flex;
    align-items: center;
    justify-content: center;
    gap: 0.6rem;

    min-width: 135px;
    padding: 0.85rem 1.2rem;

    border: 1px solid #29445c;
    border-radius: 0.5rem;

    background: rgba(12, 31, 47, 0.8);
    color: #dce8f3;

    font-size: 0.85rem;
    font-weight: 600;
    text-decoration: none;

    transition:
        transform 0.25s ease,
        border-color 0.25s ease,
        background 0.25s ease;
}

.contact-button svg {
    width: 18px;
    height: 18px;
    flex-shrink: 0;
}

.contact-button:hover {
    transform: translateY(-3px);
    border-color: #2196f3;
    background: #102b42;
}

.contact-button.primary {
    border-color: #2587ef;
    background: #2587ef;
    color: #ffffff;
}

.contact-button.primary:hover {
    border-color: #64b5f6;
    background: #1475d1;
}

.contact-email {
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 0.5rem;
    margin-top: 2rem;
}

.email-label {
    color: #71869a;
    font-size: 0.8rem;
}

.contact-email a {
    color: #b6cde0;
    font-size: 0.9rem;
    text-decoration: none;
    overflow-wrap: anywhere;
    transition: color 0.2s ease;
}

.contact-email a:hover {
    color: #64b5f6;
}

/* TABLET AND MOBILE */

@media (max-width: 600px) {
    .contact {
        padding: 3rem 0;
    }

    .contact-container {
        padding: 0 1.25rem;
    }

    .contact-card {
        padding: 2.5rem 1.25rem;
    }

    .contact-card h2 {
        font-size: 2rem;
    }

    .contact-description {
        font-size: 0.88rem;
    }

    .contact-actions {
        flex-direction: column;
    }

    .contact-button {
        width: 100%;
    }

    .contact-email a {
        font-size: 0.82rem;
    }
}
</style>