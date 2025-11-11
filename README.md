This is a modern, single-page portfolio website built with HTML, CSS, and JavaScript, designed in a black and gold theme. It includes:

About Me

Skills / Tech Stack

Projects

Contact Form (opens Gmail or default email app)

Social Links

No backend required — everything runs on static HTML/CSS/JS.

📁 Project Structure
portfolio/
├── index.html        # Main portfolio file (all-in-one)
├── README.md         # This documentation


CSS and JS are included inside index.html. You can separate them if desired.

⚙️ How to Use & Edit
1️⃣ Logo

Replace the logo text:

<div class="logo">MY LOGO</div>


Example:

<div class="logo">name Portfolio</div>

2️⃣ About Section

Replace bio and profile image:

<div class="profile-box">Profile Photo</div>

<p>Hello! I'm a web developer passionate about modern design, clean code, and creating digital experiences that stand out.</p>

3️⃣ Social Links

Update the links to your own accounts:

<div class="social-links">
  <a href="https://linkedin.com/in/yourusername" target="_blank">LinkedIn</a>
  <a href="https://github.com/yourusername" target="_blank">GitHub</a>
  <a href="https://twitter.com/yourusername" target="_blank">Twitter</a>
  <a href="https://instagram.com/yourusername" target="_blank">Instagram</a>
</div>


Just replace the URLs with your profiles.

4️⃣ Skills Section

Add or remove skills:

<div class="skill-grid">
  <div class="skill">HTML</div>
  <div class="skill">CSS</div>
  <div class="skill">JavaScript</div>
  <div class="skill">React</div>
  <div class="skill">Node.js</div>
  <div class="skill">Python</div>
</div>

5️⃣ Projects Section

Edit project title, description, image, and link:

<div class="project">
  <div class="project-image">Project Image</div>
  <div class="project-info">
    <h3>Project Title</h3>
    <p>Brief description of your project.</p>
    <a href="#" class="btn">View</a>
  </div>
</div>


Replace "Project Image" with an <img> tag if you have images:

<img src="images/project1.png" alt="Project 1" class="project-image">

6️⃣ Contact Form

Update your email in this JS snippet:

const mailtoLink = `mailto:yourname@gmail.com?subject=Portfolio Message from ${encodeURIComponent(name)}&body=${encodeURIComponent(message + "\n\nSender: " + email)}`;


Replace yourname@gmail.com with your email

Visitors click Send Message → opens email client with pre-filled info

🎨 Customize Colors
body { background-color: #000; color: #fff; }          /* Page background and text */
.logo, h2, .skill, .btn { color: #d4af37; }           /* Gold elements */
.btn:hover { background: #e8c547; }                   /* Hover effect for buttons */


Change #d4af37 to any color of your choice.

🖌️ Fonts

Replace font with Google Fonts or others:

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;700&display=swap" rel="stylesheet">

📱 Responsive Design

Desktop / tablet / mobile friendly

About section stacks vertically on small screens

Skill and project grids adjust automatically

✅ Quick Steps to Personalize

Replace logo, bio, and profile image

Update social links

Edit skills

Update projects (title, description, images, links)

Set your email in the JS mailto

Optionally tweak colors, fonts, and layout

created my Mary Kamau
