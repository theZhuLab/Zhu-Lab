<section class="hero-local" style="background-image: url('/Zhu-Lab/images/whitaker.jpg'); background-size: cover; background-position: center; background-repeat: no-repeat; min-height: 400px; display: flex; align-items: center; justify-content: center; position: relative; z-index: 1;">
  <div class="hero-content" style="text-align: center;">
    <h1 class="hero-content h1" style="color: #ffffff; font-size: 4rem; text-shadow: 2px 2px 8px rgba(0, 0, 0, 0.7);">
      <a href="/Zhu-Lab/" class="text-white text-4xl md:text-6xl font-bold text-shadow-lg">Zhu Lab</a>
    </h1>
  </div>

  <div id="nav-toggle-btn" class="nav-toggle-btn" style="position: absolute; top: 2rem; right: 2rem; display: block; cursor: pointer; font-size: 1.75rem; color: white; text-shadow: 1px 1px 4px rgba(0, 0, 0, 0.5);">
    <i class="fas fa-bars"></i>
  </div>

  <nav id="main-nav" class="header-nav" style="position: absolute; top: 6rem; right: 2rem; width: 250px; background-color: white; border-radius: 0.5rem; box-shadow: 0 4px 6px -1px rgb(0 0 0 / 0.1), 0 2px 4px -2px rgb(0 0 0 / 0.1); padding: 0.5rem; display: flex; flex-direction: column; transform-origin: top right; transform: scaleY(0); transition: transform 0.3s ease-in-out; z-index: 99;">
    <a href="/Zhu-Lab/research/" class="hover:bg-gray-200 transition-colors block">Research</a>
    <a href="/Zhu-Lab/projects/" class="hover:bg-gray-200 transition-colors block">Projects</a>
    <div class="dropdown">
      <div id="team-dropdown-btn" class="dropdown-btn hover:bg-gray-200 transition-colors flex items-center justify-between">
        Team
        <span class="ml-2 text-sm">▼</span>
      </div>
      <div id="team-dropdown-content" class="dropdown-content" style="display: none; flex-direction: column; background-color: #f3f4f6; width: 100%;">
        <a href="/Zhu-Lab/team/current/" class="block p-4 hover:bg-gray-100 rounded-md">Current Members</a>
        <a href="/Zhu-Lab/team/alumni/" class="block p-4 hover:bg-gray-100 rounded-md">Alumni</a>
      </div>
    </div>
    <a href="/Zhu-Lab/blog/" class="hover:bg-gray-200 transition-colors block">Blog</a>
    <a href="/Zhu-Lab/contact/" class="hover:bg-gray-200 transition-colors block">Contact</a>
  </nav>
</section>

<script>
  const navToggleBtn = document.getElementById('nav-toggle-btn');
  const mainNav = document.getElementById('main-nav');
  const teamDropdownBtn = document.getElementById('team-dropdown-btn');
  const teamDropdownContent = document.getElementById('team-dropdown-content');

  navToggleBtn.addEventListener('click', () => {
    mainNav.classList.toggle('is-open');
    mainNav.style.transform = mainNav.classList.contains('is-open') ? 'scaleY(1)' : 'scaleY(0)';
  });

  teamDropdownBtn.addEventListener('click', () => {
    teamDropdownContent.classList.toggle('is-open');
    teamDropdownContent.style.display = teamDropdownContent.classList.contains('is-open') ? 'flex' : 'none';
  });
</script>
---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

If you are interested to learn more about Zhu Lab, please reach out using the information below. 

{%
  include button.html
  type="email"
  text="cheng.zhu@bme.gatech.edu"
  link="cheng.zhu@bme.gatech.edu"
%}
{%
  include button.html
  type="phone"
  text="(404) 894-3269"
  link="+1-404-894-3269"
%}
{%
  include button.html
  type="Address"
  text="U.A. Whitaker"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://share.google/Kikzr4Er9HRltu5dz"
%}


