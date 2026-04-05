# Antonio Leo

### Game Programmer | Gameplay Systems | Unreal Engine Developer
<div style="display: flex; gap: 10px; align-items: center; flex-wrap: wrap; margin-top: 10px;">
  <a href="https://www.linkedin.com/in/antonio-leo-4290a535a/">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="assets/Antonio Leo_Resume_2026.pdf" target="_blank">
    <img src="https://img.shields.io/badge/Resume-000000?style=for-the-badge&logo=readthedocs&logoColor=white" />
  </a>
  <button onclick="copyEmail()" id="emailBtn" style="border:none; background:none; padding:0; cursor:pointer;">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white">
  </button>
  <a href="https://github.com/AxxL28">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
  </a>
  <a href="https://www.youtube.com/@antonioleo2141">
    <img src="https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white" />
  </a>

</div>

<script>
function copyEmail() {
  const email = "tonysoccerleo@gmail.com";
  navigator.clipboard.writeText(email);

  const btn = document.getElementById("emailBtn");
  const original = btn.innerHTML;

  btn.innerHTML = '<img src="https://img.shields.io/badge/Copied-2ECC71?style=for-the-badge&logo=gmail&logoColor=white">';

  setTimeout(() => {
    btn.innerHTML = original;
  }, 1500);
}
</script>
