function setupToggle(buttonId, listId) {
  const btn = document.getElementById(buttonId);
  const list = document.getElementById(listId);

  btn.addEventListener("click", () => {
    const isHidden = list.classList.toggle("hidden");

    btn.textContent = isHidden ? "Show" : "Hide";
    btn.textContent += buttonId === "toggleSkills" ? " Skills" : " Projects";

    btn.setAttribute("aria-expanded", (!isHidden).toString());
  });
}

// add a small CSS helper class with JS (or place it in CSS if you want)
const style = document.createElement("style");
style.textContent = `.hidden{ display:none !important; }`;
document.head.appendChild(style);

setupToggle("toggleSkills", "skillsList");
setupToggle("toggleProjects", "projectsList");

// footer year
document.getElementById("year").textContent = new Date().getFullYear();
