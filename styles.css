/* Redesigned Variables */
:root {
  --color-bg: #1e1e2f;
  --color-accent: #ff6b6b;
  --color-accent-dark: #d94f4f;
  --color-secondary: #3dc5a6;
  --color-secondary-dark: #2ba38a;
  --color-text-light: #eaeaea;
  --color-text-muted: #b5b5c2;
  --color-shadow: rgba(0, 0, 0, 0.25);

  --font-base: 'Poppins', 'Segoe UI', sans-serif;
  --radius: 18px;
  --transition: 0.4s ease-in-out;
}

/* Reset */
*,
*::before,
*::after {
  box-sizing: border-box;
}

body {
  margin: 0;
  font-family: var(--font-base);
  background: var(--color-bg);
  color: var(--color-text-light);
  line-height: 1.7;
  scroll-behavior: smooth;
}

/* Navigation */
nav.navbar {
  background: linear-gradient(to right, #1e1e2f, #2f2f46);
  padding: 1rem 2rem;
  display: flex;
  justify-content: space-between;
  align-items: center;
  box-shadow: 0 3px 12px var(--color-shadow);
  position: sticky;
  top: 0;
  z-index: 999;
}

.logo {
  font-weight: bold;
  font-size: 1.75rem;
  color: var(--color-accent);
  text-transform: uppercase;
  letter-spacing: 2px;
}

.menu-toggle {
  display: none;
  background: transparent;
  border: none;
  color: var(--color-text-light);
  font-size: 2rem;
  cursor: pointer;
}

/* Nav links */
.nav-links {
  display: flex;
  gap: 2rem;
  list-style: none;
}

.nav-links a {
  color: var(--color-text-muted);
  text-decoration: none;
  font-weight: 600;
  padding: 0.4rem 0.6rem;
  border-radius: 6px;
  transition: background var(--transition), color var(--transition);
}

.nav-links a:hover,
.nav-links a:focus {
  background: var(--color-accent);
  color: #fff;
}

/* Header */
header {
  text-align: center;
  padding: 5rem 1rem 7rem;
  background: linear-gradient(135deg, #3d3d5c, #ff6b6b);
  clip-path: ellipse(150% 100% at 50% 0%);
  color: white;
  position: relative;
}

.profile-pic {
  width: 160px;
  height: 160px;
  border-radius: 50%;
  border: 6px solid #fff;
  object-fit: cover;
  box-shadow: 0 10px 25px var(--color-shadow);
  margin-bottom: 1rem;
  transition: transform 0.3s ease;
}

.profile-pic:hover {
  transform: scale(1.08);
}

header h1 {
  font-size: 3rem;
  font-weight: 800;
  margin: 0.5rem 0;
  color: #ffffff;
}

header h2 {
  font-size: 1.5rem;
  font-weight: 400;
  color: #ffe8e8;
  font-style: italic;
}

header p {
  max-width: 600px;
  margin: 1rem auto;
  color: var(--color-text-muted);
}

/* Main Content */
main {
  background: #2f2f46;
  margin: -5rem auto 3rem;
  border-radius: var(--radius);
  padding: 3rem 2rem;
  max-width: 960px;
  box-shadow: 0 10px 35px var(--color-shadow);
}

/* Sections */
section {
  margin-bottom: 3rem;
}

section h2 {
  font-size: 2.2rem;
  border-left: 5px solid var(--color-secondary);
  padding-left: 1rem;
  margin-bottom: 1.5rem;
  color: var(--color-secondary);
  text-transform: uppercase;
  letter-spacing: 1px;
}

/* Articles */
article {
  background: #393952;
  padding: 1.25rem 1.5rem;
  border-radius: var(--radius);
  margin-bottom: 1.5rem;
  border-left: 4px solid var(--color-accent);
  transition: box-shadow var(--transition);
}

article:hover {
  box-shadow: 0 6px 18px rgba(255, 107, 107, 0.3);
}

article h3 {
  color: var(--color-accent);
  font-size: 1.3rem;
  margin-bottom: 0.5rem;
}

article p em {
  color: var(--color-text-muted);
  font-style: italic;
  display: block;
  font-size: 0.95rem;
  margin-bottom: 0.5rem;
}

/* Lists */
ul {
  list-style: circle inside;
  color: var(--color-text-muted);
  font-weight: 500;
  margin-top: 0.5rem;
}

/* Skills */
.skills-container {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
  gap: 2rem;
}

.skill-div {
  background: linear-gradient(to top right, #2a2a3b, #414163);
  border-radius: var(--radius);
  padding: 1.2rem 1.5rem;
  box-shadow: 0 5px 20px var(--color-shadow);
  transition: transform var(--transition);
}

.skill-div:hover {
  transform: translateY(-5px);
}

.skill-div h4 {
  color: var(--color-secondary);
  font-size: 1.15rem;
  font-weight: 700;
  margin-bottom: 0.6rem;
}

.skill-div p {
  color: var(--color-text-muted);
  font-weight: 600;
}

/* Links */
a {
  color: var(--color-accent);
  text-decoration: none;
  font-weight: 700;
}

a:hover {
  color: var(--color-accent-dark);
  text-decoration: underline;
}

/* Contact Form */
form {
  max-width: 500px;
  margin-top: 2rem;
}

form input,
form textarea {
  width: 100%;
  padding: 1rem;
  margin-bottom: 1.2rem;
  border: none;
  border-radius: 12px;
  font-size: 1rem;
  font-family: inherit;
  background: #44445e;
  color: var(--color-text-light);
  box-shadow: inset 0 0 4px rgba(255, 255, 255, 0.05);
}

form input:focus,
form textarea:focus {
  outline: none;
  border: 2px solid var(--color-secondary);
  box-shadow: 0 0 10px rgba(61, 197, 166, 0.3);
}

form button {
  background: var(--color-accent);
  color: white;
  padding: 0.8rem 2.5rem;
  border: none;
  border-radius: 20px;
  font-weight: 700;
  font-size: 1rem;
  cursor: pointer;
  transition: background var(--transition), box-shadow var(--transition);
  box-shadow: 0 8px 18px rgba(255, 107, 107, 0.4);
}

form button:hover {
  background: var(--color-accent-dark);
  box-shadow: 0 12px 28px rgba(217, 79, 79, 0.5);
}

/* Footer */
footer {
  background: #1a1a27;
  color: #bbb;
  text-align: center;
  padding: 2rem 1rem;
  font-size: 0.9rem;
  border-top: 1px solid #333;
}

footer a {
  color: var(--color-secondary);
}

footer a:hover {
  color: #55fccc;
}

/* Back to Top Button */
#back-to-top {
  position: fixed;
  bottom: 2rem;
  right: 2rem;
  width: 3.2rem;
  height: 3.2rem;
  background: var(--color-secondary);
  color: #fff;
  border: none;
  border-radius: 50%;
  font-size: 1.5rem;
  display: flex;
  align-items: center;
  justify-content: center;
  cursor: pointer;
  opacity: 0;
  pointer-events: none;
  transition: opacity var(--transition);
  box-shadow: 0 5px 20px rgba(61, 197, 166, 0.4);
}

#back-to-top.show {
  opacity: 1;
  pointer-events: auto;
}

/* Responsive */
@media (max-width: 768px) {
  .menu-toggle {
    display: block;
  }

  .nav-links {
    flex-direction: column;
    background: #2f2f46;
    position: absolute;
    top: 100%;
    right: 0;
    width: 250px;
    transform: translateX(100%);
    transition: transform 0.3s ease;
    box-shadow: -4px 0 15px var(--color-shadow);
    padding: 1.5rem 1rem;
  }

  .nav-links.active {
    transform: translateX(0);
  }

  .nav-links a {
    font-size: 1.1rem;
    color: var(--color-text-light);
  }
}

@media (max-width: 480px) {
  header h1 {
    font-size: 2.4rem;
  }

  header h2 {
    font-size: 1.1rem;
  }

  main {
    padding: 2rem 1rem;
    margin: -4rem 1rem 2rem;
  }
}
