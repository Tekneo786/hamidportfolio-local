 HamidPortfolio.local — My Local DevOps Project
Overview

This project showcases my locally hosted portfolio website, built and configured from scratch inside WSL (Ubuntu) using Apache2.

It’s served under my custom local domain:

hamidportfolio.local

The project demonstrates a real-world DevOps workflow that combines Linux administration, networking, DNS mapping, and front-end design — all running locally like a miniature production environment.

Technologies & Tools
Category	Tools / Technologies
OS & Environment	Ubuntu (WSL), Windows 11
Web Server	Apache2 (Virtual Hosts)
Configuration	/etc/apache2/sites-available/
Networking	Local DNS mapping (Windows hosts file)
CLI Tools	systemctl, nano, curl, netstat, hostname -I, a2ensite, a2dissite
Front-End	HTML, CSS (Galaxy theme)
Version Control	Git & GitHub
 Learning Reflection

This project was built alongside my CoderCo DevOps modules, where I’ve been learning to connect theory with practice through structured note-taking and repetition.

My process for each module:

 Purpose: Identify what I’m learning and why it matters.

 Key Terms & Concepts: Understand the definitions and context.

 Commands to Use: Practice and memorize syntax through repetition.

 Explain It in My Own Words: Reinforce understanding and communication skills.

Through this project, I strengthened my understanding of:

How Apache2 serves files through the document root

How to configure Virtual Hosts to serve multiple sites

How Windows hosts file can mimic DNS resolution locally

How to troubleshoot real errors like ERR_CONNECTION_REFUSED, port conflicts, and permissions

The end-to-end workflow from setup → testing → deployment → reflection

This hands-on experience mirrors real DevOps work — diagnosing, adjusting, and verifying system behaviour until everything runs smoothly.

 Visual Design

I designed a galaxy-themed portfolio using a blue–purple gradient background to represent creativity, technology, and exploration.

Key section of my HTML:

<h1>Welcome to My Page</h1>
<p>
  Hi, I'm <strong>Hamid Haider</strong> — a <strong>Cloud DevOps Engineer in training</strong>, 
  showcasing my journey through automation, cloud projects, and continuous learning.
</p>


The design is lightweight, responsive, and ready for future expansion (e.g., adding “Projects” and “Contact” sections).

 Folder Structure
hamidportfolio.local/
│
├── index.html             # Main portfolio page
├── .gitignore             # Ignored files (logs, backups, etc.)
└── README.md              # Project documentation

🔗 Related LinkedIn Post

 Read my full LinkedIn post about this project

 Key Takeaway

DevOps isn’t about memorising — it’s about understanding, breaking, fixing, and building again until you master the process.

 Author

Hamid Haider
Cloud DevOps Engineer in Training
🔗 LinkedIn
 | GitHub
