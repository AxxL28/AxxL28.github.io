<html lang="en">
<head>
<meta charset="UTF-8">
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
    background-color: #1b0b3b; /* unified dark purple */
    color: white; 
    text-align: center; 
    padding: 40px 20px; 
  }
  .banner h1 { margin:0; font-size:3em; }
  .banner h3 { margin:10px 0 20px 0; font-weight:normal; }

  /* Tech Stack Icons */
  .tech-stack { 
    display: flex; 
    justify-content: center; 
    flex-wrap: wrap; 
    gap: 15px; 
    margin: 20px 0; 
  }
  .tech-stack .icon-wrapper { 
    background-color: #bfbfbf; /* light grey background */
    padding: 10px; 
    border-radius: 10px; 
    display: flex; 
    align-items: center; 
    justify-content: center; 
    width: 60px; 
    height: 60px; 
  }
  .tech-stack img { 
    width: 50px; 
    height: 50px; 
    background: transparent; /* ensure no white background */
  }

  /* Content */
  .content { max-width:900px; margin:30px auto; padding:0 20px; text-align:center; }
  .section { margin-bottom:40px; }
  p.summary, .project p { 
    font-size:1.1em; 
    line-height:1.6; 
    background-color:#2B2D42; /* navy background like contributions */
    padding: 15px; 
    border-radius: 5px;
    display: inline-block;
    text-align: left;
    max-width: 900px;
    margin: 10px auto;
  }

  /* Projects */
  .project { margin-bottom:50px; text-align:center; }
  .project h2 { color:#ffffff; margin-bottom:5px; }

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
  .project-details h4, .project-details h3 { margin-top:0; color:#ffffff; }
  .project-details ul { padding-left: 20px; }

  /* Links styling for better contrast */
  .icon-links { margin-top: 30px; }
  .icon-links a { margin: 0 5px; display:inline-block; }

</style>
</head>
<body>

<div class="banner">
  <h1>Antonio Leo</h1>
  <h2>Game Developer | Systems Programmer & Architect | C++ & Unreal Engine Specialist</h2>
  <!-- Social Links -->
  <div class="icon-links">
    <a href="https://linkedin.com/in/antonio-leo-4290a535a/" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a>
    <a href="https://axxl28.github.io/Antonio_Leo_Resume_2026.pdf"><img src="https://img.shields.io/badge/Resume-000000?style=for-the-badge&logo=readthedocs&logoColor=white"></a>
    <a href="mailto:tonysoccerleo@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"></a>
    <a href="https://github.com/AxxL28" target="_blank"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"></a>
    <a href="https://youtube.com/@antonioleo2141" target="_blank"><img src="https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white"></a>
  </div>
  <!-- Tech Stack Icons -->
  <div class="tech-stack">
    <div class="icon-wrapper"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/unrealengine/unrealengine-original.svg"></div>
    <div class="icon-wrapper"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/unity/unity-original.svg"></div>
    <div class="icon-wrapper"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/cplusplus/cplusplus-original.svg"></div>
    <div class="icon-wrapper"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/csharp/csharp-original.svg"></div>
    <div class="icon-wrapper"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg"></div>
    <div class="icon-wrapper"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg"></div>
    <div class="icon-wrapper"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg"></div>
    <div class="icon-wrapper"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/visualstudio/visualstudio-original.svg"></div>
    <div class="icon-wrapper"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vscode/vscode-original.svg"></div>
    <div class="icon-wrapper"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg"></div>
    <div class="icon-wrapper"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/jira/jira-original.svg"></div>
  </div>
</div>

<div class="content">
  <div class="section">
    <p class="summary">
      Gameplay programmer specializing in building robust and scalable systems using Unreal Engine and C++. Experienced in designing and implementing core gameplay mechanics, AI behaviors, and modular architectures. Skilled in writing efficient, maintainable, and network-ready code, with a strong focus on system optimization, debugging, and clean software design practices.
    </p>
  </div>

  <div class="section">
    <h1>Projects</h1>

    <div class="project">
      <h2>Blood and Lineage</h2>
      <p>
        A 3D roguelike-Musou hybrid built in Unreal Engine, featuring dynamic combat, unique enemy designs, and procedurally generated levels for endless replayability.
      </p>
      <div class="video-preview">
        <a href="https://youtu.be/oWBnQoz2f60" target="_blank">
          <img src="https://img.youtube.com/vi/oWBnQoz2f60/hqdefault.jpg" alt="Blood and Lineage Preview">
          <div class="play-button">&#9658;</div>
        </a>
      </div>

      <div class="project-details">
        <h2>My Contributions</h2>
      
        <h3>Ability System Design & Implementation</h3>
        <ul>
          <li>Architected and implemented the core system for modular gameplay abilities.</li>
          <li>Designed and developed 13 out of 16 unique gameplay abilities.</li>
          <li>Implemented full network replication for all abilities to ensure multiplayer consistency.</li>
          <li>Integrated animations and visual effects for all abilities, maintaining high polish and responsiveness.</li>
        </ul>
      
        <h3>Character Class System Design & Implementation</h3>
        <ul>
          <li>Engineered a scalable architecture to support multiple unique character classes.</li>
          <li>Implemented custom camera behavior for optimized player experience.</li>
          <li>Developed distinct basic attacks and mechanics for each character class.</li>
          <li>Networked all animations, effects, attacks, and camera functionality efficiently.</li>
        </ul>
      
        <h3>Team Leadership & Project Support</h3>
        <ul>
          <li>Led team operations, fostering effective collaboration and maintaining motivation.</li>
          <li>Organized tasks, meetings, and project workflow to ensure timely progress and smooth coordination.</li>
          <li>Assisted in debugging and maintaining project stability throughout development.</li>
          <li>Promoted a positive team culture, encouraging communication and problem-solving.</li>
        </ul>
      </div>
    </div>

  </div>
</div>

</body>
</html>
