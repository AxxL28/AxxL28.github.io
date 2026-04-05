<html lang="en">
<head>
<meta charset="UTF-8">
<title>Antonio Leo Portfolio</title>
<style>

  body { 
    font-family: Arial, sans-serif; 
    background-color: #1b0b3b; 
    margin:0; 
    padding:0; 
    color:#ffffff; 
    text-align: center;
  }

  /* Banner */
  .banner { 
    background-color:#2B2D42; 
    color:white; 
    text-align:center; 
    padding:40px 20px; 
  }
  .banner h1 { margin:0; font-size:3em; }
  .banner h3 { margin:10px 0 20px 0; font-weight:normal; }
  .icon-links a { margin: 0 5px; display:inline-block; }

  /* Content */
  .content { max-width:900px; margin:30px auto; padding:0 20px; text-align:center; }
  .section { margin-bottom:40px; }
  .section h2 { border-bottom:2px solid #ffffff; padding-bottom:5px; margin-bottom:15px; color:#ffffff; }
  p.summary { font-size:1.1em; line-height:1.6; }

  /* Tech icons */
  .tech-icons img { width:40px; margin:5px; }

  /* Projects */
  .project { margin-bottom:50px; text-align:center; }
  .project h3 { color:#ffffff; margin-bottom:5px; }
  .project p { margin-bottom:15px; }

  .video-preview {
    position: relative;
    display: inline-block;
    width: 100%;
    max-width: 640px;
    margin-bottom: 15px;
  }
  .video-preview img {
    width: 100%;
    border-radius: 5px;
    display: block;
  }
  .video-preview .play-button {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    font-size: 60px;
    color: white;
    opacity: 0.8;
    pointer-events: none;
  }

  .project-details { 
    background-color:#2B2D42; 
    padding:15px; 
    border-radius:5px; 
    text-align: left;
    display: inline-block;
    max-width: 640px;
  }
  .project-details h4 { margin-top:0; color:#ffffff; }
  .project-details ul { padding-left: 20px; }

  /* Links styling for better contrast */
  a img { border-radius:5px; }

</style>
</head>
<body>

<div class="banner">
  <h1>Antonio Leo</h1>
  <h3>Game Programmer | Gameplay Systems | Unreal Engine Developer</h3>
  <div class="icon-links">
    <a href="https://linkedin.com/in/antonio-leo-4290a535a/" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a>
    <a href="assets/Antonio Leo_Resume_2026.pdf" target="_blank"><img src="https://img.shields.io/badge/Resume-000000?style=for-the-badge&logo=readthedocs&logoColor=white"></a>
    <a href="mailto:tonysoccerleo@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"></a>
    <a href="https://github.com/AxxL28" target="_blank"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"></a>
    <a href="https://youtube.com/@antonioleo2141" target="_blank"><img src="https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white"></a>
  </div>
</div>

<div class="content">
  <div class="section">
    <p class="summary">
      Game programmer focused on building responsive, scalable gameplay systems using Unreal Engine and C++. Experienced in developing core mechanics, AI behaviors, and modular architectures. Passionate about creating polished player experiences and continuously improving technical and problem-solving skills.
    </p>
  </div>

  <div class="section">
    <h2>Tech Stack</h2>
    <h3>Game Engines</h3>
    <div class="tech-icons">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/unrealengine/unrealengine-original.svg">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/unity/unity-original.svg">
    </div>
    <h3>Programming Languages</h3>
    <div class="tech-icons">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/cplusplus/cplusplus-original.svg">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/csharp/csharp-original.svg">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg">
    </div>
    <h3>Development Tools</h3>
    <div class="tech-icons">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/visualstudio/visualstudio-original.svg">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vscode/vscode-original.svg">
    </div>
    <h3>Version Control & Collaboration</h3>
    <div class="tech-icons">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/jira/jira-original.svg">
    </div>
  </div>

  <div class="section">
    <h2>Projects</h2>

    <div class="project">
      <h3>Epic Adventure RPG</h3>
      <p>A 3D action RPG built in Unreal Engine featuring dynamic combat, AI enemies, and an open-world exploration system.</p>

      <div class="video-preview">
        <a href="https://www.youtube.com/watch?v=YOUR_VIDEO_ID" target="_blank">
          <img src="https://img.youtube.com/vi/YOUR_VIDEO_ID/hqdefault.jpg" alt="Epic Adventure RPG Preview">
          <div class="play-button">&#9658;</div>
        </a>
      </div>

      <div class="project-details">
        <h4>My Contributions:</h4>
        <ul>
          <li>Designed and implemented the modular combat system using Unreal Engine C++.</li>
          <li>Developed AI behavior trees for enemies and NPC interactions.</li>
          <li>Optimized level streaming and performance for large open-world environments.</li>
          <li>Integrated multiplayer networking for co-op gameplay.</li>
        </ul>
      </div>
    </div>

  </div>
</div>

</body>
</html>
