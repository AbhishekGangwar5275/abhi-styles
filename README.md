# abhi-styles
portfolio
/* Reset & base styles */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Segoe UI', sans-serif;
  background-color: oklab(98.212% 0 -0.00011 / 0.482);
  color: #333;
  line-height: 1.6;
}

header {
  background: #11587870;
  color: lch(100% 0.01 296.81);
  padding: 1rem 0;
}

nav {
  max-width: 1000px;
  margin: auto;
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 0 1rem;
}

nav ul {
  display: flex;
  gap: 1rem;
  list-style: none;
}

nav a {
  color: white;
  text-decoration: none;
}

.hero {
  text-align: center;
  padding: 2rem;
  background: #444;
}

.hero span {
  color: #ff00ee;
}

main {
  max-width: 1000px;
  margin: 2rem auto;
  padding: 0 1rem;
}

section {
  margin-bottom: 3rem;
}

.projects .project-list {
  display: flex;
  flex-wrap: wrap;
  gap: 1rem;
}

.project-card {
  background: white;
  padding: 1rem;
  border: 1px solid #ddd;
  flex: 1 1 45%;
}

.contact form {
  display: flex;
  flex-direction: column;
  gap: 0.5rem;
}

input, textarea {
  padding: 0.5rem;
  border: 1px solid #ccc;
  border-radius: 4px;
}

button {
  padding: 0.7rem;
  background: #00d4ff;
  color: white;
  border: none;
  cursor: pointer;
}

footer {
  text-align: center;
  padding: 1rem;
  background: #333;
  color: white;
}

