
<template>
  <section id="projects" class="projects">
    <div class="projects-container">
      <!-- SECTION HEADER -->
      <div class="projects-header">
        <div>
          <p class="section-label">▌ PROJECTS</p>
          <h2>Things I've Built</h2>
        </div>

        <p class="projects-tagline">
          Learning through building.<br />
          Turning ideas into practical solutions.
        </p>
      </div>

      <!-- PROJECT CARDS -->
      <div class="projects-grid">
        <!-- RDC HELP DESK -->
        <article class="project-card">
          <div class="project-image-wrapper">
            <img
              src="/images/rdc-helpdesk.png"
              alt="RDC Service Help Desk login page"
              class="project-image"
            />
          </div>

          <div class="project-top">
            <div class="project-icon">
              <svg
                viewBox="0 0 24 24"
                fill="none"
                stroke="currentColor"
                stroke-width="1.7"
                stroke-linecap="round"
                stroke-linejoin="round"
              >
                <rect x="3" y="4" width="18" height="16" rx="2" />
                <path d="M3 9h18" />
                <path d="M7 6.5h.01" />
                <path d="M10 6.5h.01" />
                <path d="M7 13h4" />
                <path d="M7 16h7" />
              </svg>
            </div>

            <span class="project-type">OJT PROJECT</span>
          </div>

          <h3>RDC Service Help Desk Management System</h3>

          <p class="project-description">
            A web-based help desk system designed to manage service
            tickets, technician assignments, schedules, and ticket
            status updates for service operations.
          </p>

          <div class="project-tags">
            <span>Node.js</span>
            <span>Express.js</span>
            <span>MySQL</span>
            <span>Sequelize</span>
            <span>Socket.io</span>
          </div>

          <div class="project-footer">
            <span class="project-category">
              Web Application
            </span>

            <a
              href="https://support.northronics.net/"
              class="project-link"
              target="_blank"
              rel="noopener noreferrer"
            >
              Live Demo
              <span aria-hidden="true">↗</span>
            </a>
          </div>
        </article>

        <!-- CSS NC II LEARNING PORTAL -->
        <article class="project-card">
          <div class="project-image-wrapper">
            <img
              src="/images/css-learning.png"
              alt="CSS NC II Learning Portal homepage"
              class="project-image"
            />
          </div>

          <div class="project-top">
            <div class="project-icon">
              <svg
                viewBox="0 0 24 24"
                fill="none"
                stroke="currentColor"
                stroke-width="1.7"
                stroke-linecap="round"
                stroke-linejoin="round"
              >
                <path
                  d="M4 5.5A2.5 2.5 0 0 1 6.5 3H20v16H6.5A2.5 2.5 0 0 0 4 21.5z"
                />
                <path d="M4 5.5v16" />
                <path d="M8 7h8" />
                <path d="M8 11h8" />
                <path d="M8 15h5" />
              </svg>
            </div>

            <span class="project-type">IN DEVELOPMENT</span>
          </div>

          <h3>CSS NC II Learning Portal</h3>

          <p class="project-description">
            An online learning portal for Computer Systems Servicing
            NC II, with organized learning resources, user
            authentication, and lesson progress tracking.
          </p>

          <div class="project-tags">
            <span>Vue.js</span>
            <span>TypeScript</span>
            <span>Django</span>
            <span>DRF</span>
            <span>PostgreSQL</span>
          </div>

          <div class="project-footer">
            <span class="project-category">
              Learning Platform
            </span>

            <a
              href="https://css-learning-myk8.onrender.com/"
              class="project-link"
              target="_blank"
              rel="noopener noreferrer"
            >
              Live Demo
              <span aria-hidden="true">↗</span>
            </a>
          </div>
        </article>

        <!-- LINE FOLLOWER ROBOT -->
        <article class="project-card">
          <div class="project-image-wrapper">
            <img
              src="/images/line-follower-bot.png"
              alt="Arduino-based line follower robot"
              class="project-image"
            />
          </div>

          <div class="project-top">
            <div class="project-icon">
              <svg
                viewBox="0 0 24 24"
                fill="none"
                stroke="currentColor"
                stroke-width="1.7"
                stroke-linecap="round"
                stroke-linejoin="round"
              >
                <rect x="5" y="7" width="14" height="10" rx="2" />
                <circle cx="8" cy="19" r="2" />
                <circle cx="16" cy="19" r="2" />
                <path d="M9 7V4h6v3" />
                <path d="M9 12h6" />
                <path d="M12 10v4" />
              </svg>
            </div>

            <span class="project-type">ROBOTICS PROJECT</span>
          </div>

          <h3>Line Follower Robot</h3>

          <p class="project-description">
            A mobile robot designed to follow a track using
            reflectance sensors, motor control, and control logic
            for navigating a line-following course.
          </p>

          <div class="project-tags">
            <span>Arduino</span>
            <span>QTR Sensor</span>
            <span>TB6612FNG</span>
            <span>Motor Control</span>
            <span>PID</span>
          </div>

          <div class="project-footer">
            <span class="project-category">
              Embedded Systems
            </span>

            <a href="#contact" class="project-link">
              Discuss Project
              <span aria-hidden="true">↗</span>
            </a>
          </div>
        </article>

        <!-- SCARF SMARTFAN -->
        <article class="project-card">
          <div class="project-image-wrapper">
            <img
              src="/images/scarf-smartfan.png"
              alt="SCARF ESP32 smart fan project"
              class="project-image"
            />
          </div>

          <div class="project-top">
            <div class="project-icon">
              <svg
                viewBox="0 0 24 24"
                fill="none"
                stroke="currentColor"
                stroke-width="1.7"
                stroke-linecap="round"
                stroke-linejoin="round"
              >
                <circle cx="12" cy="10" r="8" />
                <circle cx="12" cy="10" r="2" />
                <path d="M12 8c-1-4 2-5 4-4 2 2 0 4-4 6" />
                <path d="M14 10c4-1 5 2 4 4-2 2-4 0-6-4" />
                <path d="M12 12c1 4-2 5-4 4-2-2 0-4 4-6" />
                <path d="M10 10c-4 1-5-2-4-4 2-2 4 0 6 4" />
                <path d="M9 18h6" />
                <path d="M10 21h4" />
              </svg>
            </div>

            <span class="project-type">IOT PROJECT</span>
          </div>

          <h3>SCARF SmartFan</h3>

          <p class="project-description">
            An ESP32-based smart fan project integrating sensors
            and automated control features to monitor environmental
            conditions and support intelligent fan operation.
          </p>

          <div class="project-tags">
            <span>ESP32</span>
            <span>IoT</span>
            <span>Sensors</span>
            <span>Embedded C++</span>
          </div>

          <div class="project-footer">
            <span class="project-category">
              Embedded Systems
            </span>

            <a href="#contact" class="project-link">
              Discuss Project
              <span aria-hidden="true">↗</span>
            </a>
          </div>
        </article>
      </div>
    </div>
  </section>
</template>

<style scoped>
/* =========================
   SECTION
========================= */

.projects {
  padding: 5rem 0;
  border-top: 1px solid #122638;
}

.projects-container {
  max-width: 1200px;
  margin: 0 auto;
  padding: 0 2rem;
}

/* =========================
   HEADER
========================= */

.projects-header {
  display: flex;
  justify-content: space-between;
  align-items: flex-end;
  gap: 2rem;
  margin-bottom: 2rem;
}

.section-label {
  margin: 0 0 0.5rem;
  color: #2196f3;
  font-size: 0.8rem;
  font-weight: 700;
  letter-spacing: 0.15rem;
}

.projects h2 {
  margin: 0;
  color: #ffffff;
  font-size: 2.4rem;
  line-height: 1.1;
  letter-spacing: -0.03em;
}

.projects-tagline {
  margin: 0;
  color: #71869a;
  font-size: 0.9rem;
  line-height: 1.6;
  text-align: right;
}

/* =========================
   PROJECT GRID
========================= */

.projects-grid {
  display: grid;
  grid-template-columns: repeat(3, minmax(0, 1fr));
  gap: 1.25rem;
}

/* =========================
   PROJECT CARD
========================= */

.project-card {
  position: relative;
  display: flex;
  flex-direction: column;
  min-width: 0;
  min-height: 390px;
  padding: 1.5rem;
  overflow: hidden;

  border: 1px solid #1c344a;
  border-radius: 0.75rem;

  background: linear-gradient(
    145deg,
    rgba(13, 32, 48, 0.95),
    rgba(7, 17, 28, 0.98)
  );

  transition:
    transform 0.3s ease,
    border-color 0.3s ease,
    box-shadow 0.3s ease;
}

.project-card::before {
  content: "";
  position: absolute;
  top: 0;
  left: 0;
  width: 3px;
  height: 60px;
  background: #2196f3;
  z-index: 1;
}

.project-card:hover {
  transform: translateY(-5px);
  border-color: #2196f3;

  box-shadow:
    0 15px 35px rgba(0, 0, 0, 0.25),
    0 0 20px rgba(33, 150, 243, 0.08);
}

/* =========================
   PROJECT IMAGES
========================= */

.project-image-wrapper {
  height: 180px;
  margin: -1.5rem -1.5rem 1.5rem;
  overflow: hidden;
  border-bottom: 1px solid #1c344a;
  background: #07111c;
}

.project-image {
  display: block;
  width: 100%;
  height: 100%;
  object-fit: cover;
  object-position: top;
  transition: transform 0.35s ease;
}

.project-card:hover .project-image {
  transform: scale(1.04);
}

/* =========================
   CARD TOP
========================= */

.project-top {
  display: flex;
  justify-content: space-between;
  align-items: center;
  gap: 1rem;
  margin-bottom: 1.5rem;
}

.project-icon {
  display: flex;
  align-items: center;
  justify-content: center;
  width: 48px;
  height: 48px;
  color: #2196f3;
}

.project-icon svg {
  width: 100%;
  height: 100%;
}

.project-type {
  padding: 0.4rem 0.55rem;
  border: 1px solid #24425a;
  border-radius: 0.3rem;
  color: #8da8bf;
  font-size: 0.62rem;
  font-weight: 700;
  letter-spacing: 0.06rem;
  text-align: center;
}

/* =========================
   CARD CONTENT
========================= */

.project-card h3 {
  margin: 0 0 0.85rem;
  color: #ffffff;
  font-size: 1.2rem;
  line-height: 1.4;
}

.project-description {
  margin: 0;
  color: #91a4b5;
  font-size: 0.88rem;
  line-height: 1.7;
}

/* =========================
   TECHNOLOGY TAGS
========================= */

.project-tags {
  display: flex;
  flex-wrap: wrap;
  gap: 0.5rem;
  margin-top: 1.5rem;
}

.project-tags span {
  padding: 0.4rem 0.65rem;
  border: 1px solid #1c344a;
  border-radius: 0.35rem;
  background: rgba(15, 36, 54, 0.65);
  color: #aebdca;
  font-size: 0.72rem;
  line-height: 1.2;
}

/* =========================
   CARD FOOTER
========================= */

.project-footer {
  display: flex;
  justify-content: space-between;
  align-items: center;
  gap: 1rem;
  margin-top: auto;
  padding-top: 1.5rem;
}

.project-category {
  color: #71869a;
  font-size: 0.75rem;
}

.project-link {
  display: inline-flex;
  align-items: center;
  gap: 0.4rem;
  color: #2196f3;
  font-size: 0.8rem;
  font-weight: 600;
  text-decoration: none;
  white-space: nowrap;

  transition:
    color 0.25s ease,
    gap 0.25s ease;
}

.project-link:hover {
  gap: 0.65rem;
  color: #64b5f6;
}

/* =========================
   RESPONSIVE
========================= */

@media (max-width: 1000px) {
  .projects-grid {
    grid-template-columns: repeat(2, minmax(0, 1fr));
  }
}

@media (max-width: 768px) {
  .projects {
    padding: 4rem 0;
  }

  .projects-header {
    flex-direction: column;
    align-items: flex-start;
    gap: 1rem;
  }

  .projects-tagline {
    text-align: left;
  }

  .projects h2 {
    font-size: 2rem;
  }
}

@media (max-width: 560px) {
  .projects-grid {
    grid-template-columns: 1fr;
  }

  .project-card {
    min-height: 360px;
  }
}
</style>