
<template>
    <footer class="footer">
        <div class="footer-container">

            <!-- MAIN FOOTER -->
            <div class="footer-main">

                <!-- BRAND -->
                <a
                    href="#home"
                    class="footer-brand"
                    aria-label="Jdeexon - Back to top"
                >
                    <span class="brand-mark">J</span>
                    <span class="brand-name">DEEXON</span>
                    <span class="brand-period">.</span>
                </a>

                <!-- TAGLINE -->
                <p class="footer-tagline">
                    Learn. Build. Improve. Repeat.
                </p>

            </div>


            <!-- FOOTER DIVIDER -->
            <div class="footer-divider"></div>


            <!-- FOOTER BOTTOM -->
            <div class="footer-bottom">

                <p class="copyright">
                    © {{ currentYear }}
                    <span>JDEEXON</span>.
                    All rights reserved.
                </p>

                <p class="footer-note">
                    Designed & developed with purpose.
                </p>

            </div>

        </div>
    </footer>
</template>


<script setup lang="ts">
const currentYear = new Date().getFullYear()
</script>


<style scoped>
/* ========================================
   FOOTER
======================================== */

.footer {
    --footer-border: #172b3d;
    --footer-text: #8296a9;
    --footer-muted: #647b90;
    --footer-accent: #2196f3;

    padding: 2rem 0 1.25rem;

    border-top: 1px solid var(--footer-border);
    background: #050d15;
}


/* ========================================
   CONTAINER
======================================== */

.footer-container {
    width: min(100% - 4rem, 1200px);
    margin-inline: auto;
}


/* ========================================
   MAIN FOOTER
======================================== */

.footer-main {
    display: flex;
    align-items: center;
    justify-content: space-between;
    gap: 1rem;
}


/* ========================================
   BRAND
======================================== */

.footer-brand {
    display: inline-flex;
    align-items: center;

    color: #f1f5f9;
    font-size: 1.1rem;
    font-weight: 800;
    letter-spacing: 0.04em;

    text-decoration: none;
}

.brand-mark {
    color: var(--footer-accent);
}

.brand-name {
    color: #f1f5f9;
}

.brand-period {
    color: var(--footer-accent);
}


/* ========================================
   TAGLINE
======================================== */

.footer-tagline {
    margin: 0;

    color: var(--footer-text);
    font-size: 0.8rem;
    font-weight: 400;
    letter-spacing: 0.01em;
    line-height: 1.6;
}


/* ========================================
   DIVIDER
======================================== */

.footer-divider {
    height: 1px;
    margin: 1.5rem 0 1rem;

    background: var(--footer-border);
}


/* ========================================
   BOTTOM COPYRIGHT
======================================== */

.footer-bottom {
    display: flex;
    align-items: center;
    justify-content: space-between;
    gap: 1rem;
}

.copyright,
.footer-note {
    margin: 0;

    color: var(--footer-muted);
    font-size: 0.7rem;
    line-height: 1.6;
}

.copyright span {
    color: #a8bacb;
    font-weight: 600;
}

.footer-note {
    text-align: right;
}


/* ========================================
   ACCESSIBILITY
======================================== */

.footer-brand:focus-visible {
    outline: 2px solid #64b5f6;
    outline-offset: 5px;
    border-radius: 2px;
}


/* ========================================
   RESPONSIVE
======================================== */

@media (max-width: 600px) {
    .footer {
        padding: 1.5rem 0 1rem;
    }

    .footer-container {
        width: calc(100% - 2.5rem);
    }

    .footer-main {
        align-items: flex-start;
        flex-direction: column;
        gap: 0.4rem;
    }

    .footer-tagline {
        font-size: 0.75rem;
    }

    .footer-divider {
        margin: 1.25rem 0 0.85rem;
    }

    .footer-bottom {
        align-items: flex-start;
        flex-direction: column;
        gap: 0.35rem;
    }

    .copyright,
    .footer-note {
        font-size: 0.68rem;
        text-align: left;
    }
}
</style>