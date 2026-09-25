
<template>
    <footer class="footer">
        <div class="footer-container">
            <a href="#home" class="footer-brand" aria-label="Back to top">
                <span class="brand-mark">J</span>DEEXON
            </a>

            <p class="footer-tagline">
                Learn. Build. Improve. Repeat.
            </p>

            <div class="footer-links">
                <a href="#home">Home</a>
                <a href="#about">About</a>
                <a href="#projects">Projects</a>
                <a href="#contact">Contact</a>
            </div>

            <div class="footer-bottom">
                <p>
                    © {{ currentYear }} JDEEXON. All rights reserved.
                </p>

                <a href="#home" class="back-to-top">
                    Back to top ↑
                </a>
            </div>
        </div>
    </footer>
</template>

<script setup lang="ts">
const currentYear = new Date().getFullYear()
</script>

<style scoped>
.footer {
    padding: 2.5rem 0 1.5rem;
    border-top: 1px solid #1c344a;
    background: #050d15;
}

.footer-container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 2rem;
    text-align: center;
}

.footer-brand {
    display: inline-flex;
    align-items: center;
    gap: 0.1rem;

    color: #f4f7fb;
    font-size: 1.35rem;
    font-weight: 800;
    letter-spacing: 0.04rem;
    text-decoration: none;
}

.brand-mark {
    color: #2196f3;
}

.footer-tagline {
    margin: 0.75rem 0 1.5rem;
    color: #8296a9;
    font-size: 0.85rem;
}

.footer-links {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    gap: 1.5rem;
    margin-bottom: 2rem;
}

.footer-links a,
.back-to-top {
    color: #a8bacb;
    font-size: 0.8rem;
    text-decoration: none;
    transition: color 0.2s ease;
}

.footer-links a:hover,
.back-to-top:hover {
    color: #64b5f6;
}

.footer-bottom {
    display: flex;
    justify-content: space-between;
    align-items: center;
    gap: 1rem;

    padding-top: 1.25rem;
    border-top: 1px solid #172536;
}

.footer-bottom p {
    margin: 0;
    color: #63788c;
    font-size: 0.75rem;
}

.back-to-top {
    white-space: nowrap;
}

@media (max-width: 600px) {
    .footer-container {
        padding: 0 1.25rem;
    }

    .footer-links {
        gap: 1rem;
    }

    .footer-bottom {
        flex-direction: column;
        gap: 0.75rem;
    }
}
</style>