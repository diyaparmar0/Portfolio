import React from "react";
import "./App.css";

export default function App() {
  return (
    <div className="app">
      {/* Navbar */}
      <nav className="navbar">
        <h1>👩‍💻Diya Parmar</h1>
        <div class="sidebar">
  <a href="#about">👩‍💻 About</a>
  <a href="#skills">🛠️ Skills</a>
  <a href="#projects">🚀 Projects</a>
  <a href="#contact">📞 Contact</a>
</div>
      </nav>

      <section className="hero">
        <h2>Hi, I'm Diya 👋</h2>
        <p>Aspiring Software Developer | Java | DSA | Web Development</p>
      </section>

      <section id="about" className="section">
        <h2>About Me</h2>
      <p>
I am a passionate and dedicated Computer Science student 👩‍💻 with a strong interest in software development and problem-solving.  
I enjoy working with technologies like Java, Data Structures & Algorithms, and Web Development to build efficient and user-friendly applications 💻.  

I have hands-on experience in developing projects such as AI-based applications 🤖, web-based tools 🌐, and interactive JavaScript applications.  
These projects have helped me strengthen my understanding of programming concepts and improve my practical skills.  

I am continuously learning and exploring new technologies to stay updated with industry trends 📚.  
I am particularly interested in backend development using Java and Spring Boot, as well as building intelligent systems using AI/ML concepts 🧠.  

My goal is to secure a challenging opportunity where I can apply my skills, contribute to meaningful projects, and grow as a software developer 🚀.
</p>
      </section>

      {/* Skills */}
      <section id="skills" className="section">
        <h2>Skills</h2>
       <section id="skills" className="section">
  <h2>🛠️ Skills</h2>

  <div className="cards">

    <div className="card">
      <h3>Java ☕</h3>
      <p>Strong understanding of OOP concepts, collections, and problem-solving using Java.</p>
    </div>

    <div className="card">
      <h3>Python 🐍</h3>
      <p>Used for scripting and basic machine learning projects with libraries like NumPy and Pandas.</p>
    </div>

    <div className="card">
      <h3>DSA 🧠</h3>
      <p>Good knowledge of data structures and algorithms like arrays, linked lists, trees, and sorting.</p>
    </div>

    <div className="card">
      <h3>HTML 🌐</h3>
      <p>Creates structured and semantic web pages using modern HTML5 elements.</p>
    </div>

    <div className="card">
      <h3>CSS 🎨</h3>
      <p>Designs responsive and attractive layouts using Flexbox, Grid, and animations.</p>
    </div>

    <div className="card">
      <h3>JavaScript ⚡</h3>
      <p>Handles DOM manipulation, events, and interactive web functionality.</p>
    </div>

    <div className="card">
      <h3>React ⚛️</h3>
      <p>Builds dynamic user interfaces using components, props, and hooks.</p>
    </div>

    <div className="card">
      <h3>SQL 🗄️</h3>
      <p>Writes queries for data retrieval, joins, and database management.</p>
    </div>

    <div className="card">
      <h3>PostgreSQL 🐘</h3>
      <p>Manages relational databases and performs CRUD operations efficiently.</p>
    </div>

    <div className="card">
      <h3>Spring 🌱</h3>
      <p>Understands dependency injection and building backend applications using Spring framework.</p>
    </div>

    <div className="card">
      <h3>Spring Boot 🚀</h3>
      <p>Develops REST APIs and backend services with minimal configuration.</p>
    </div>

  </div>
</section>
      </section>

      {/* Projects */}
      <section id="projects" className="section">
        <h2>Projects</h2>
        <div className="cards">
          <div className="card">
            <h3>🤖 Personal Chat Assistant </h3>
            <p>Developed an AI-powered personal assistant that can respond to user queries 💬,  
provide information 📚, and perform basic tasks ⚙️.  
The assistant uses Natural Language Processing 🧠 to understand input and generate meaningful responses ✨.  

Features:  
• Answer general questions ❓  
• Basic conversation handling 🗣️  
• User-friendly interface   

Technologies: JavaScript / Python 💻, NLP Concepts 🧠  </p>
          </div>
          <div className="card">
            <h3>Currency Exchange Web Application 💱 </h3>
            <p>Developed a web-based application that converts one currency into another 🔄 based on user input.  
The application allows users to select currencies and instantly view converted values with a simple and interactive interface.  

Features:  
• Currency conversion between multiple currencies 🌍  
• Instant calculation based on input ⚡  
• Clean and user-friendly interface 🖥️  

Technologies: HTML 🧱, CSS 🎨, JavaScript 
 </p>
 </div>
 <div className="card">
  <h3>Guess My Number 🎯</h3>
  <p >
Developed an interactive number guessing game where the user tries to guess a randomly generated number 🔢.  
The application provides hints like "Too High" 📈 or "Too Low" 📉 to guide the user.  

Features:  
• Random number generation 🎲  
• User input handling ⌨️  
• Score tracking system 🏆  
• Instant feedback (High / Low) ⚡  

Technologies: HTML 🧱, CSS 🎨, JavaScript ⚡</p>
 </div>
          
        </div>
      </section>
      {/* Achievements */}
<section id="achievements" className="section">
  <h2>🏆 Achievements</h2>
  <ul className="achievements">
    <li>✔ Solved 200+ DSA problems on coding platforms 🧠</li>
    <li>✔ Completed NPTEL course on Cloud / AI ☁️</li>
    <li>✔ Built multiple real-world projects using Java & Web Technologies 💻</li>
    <li>✔ Strong understanding of Data Structures & Algorithms</li>
  </ul>
</section>

      {/* Contact */}
     {/* Contact */}
<section id="contact" className="section">
  <h2>📞 Contact</h2>
  
  <p>📧 Email: diyaparmar1011@gmail.com</p>
  <p>📱 Phone: +91 6263850135</p>

  <p>
    🔗 GitHub: 
    <a href="https://github.com/yourusername" target="_blank">
      https://github.com/account
    </a>
  </p>

  <p>
    💼 LinkedIn: 
    <a href="https://linkedin.com/in/yourprofile" target="_blank">
      www.linkedin.com/in/diya-parmar-3188b5251
    </a>
  </p>
</section>
    </div>
  );
}
