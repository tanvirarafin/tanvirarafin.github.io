---
layout: page
permalink: /people/
title: SPIRE Lab
description: Current and former members of the Security, Privacy, and Reverse Engineering Lab at GMU.
nav: true
nav_order: 5
---

<div class="people-tabs">
  <div class="tab-nav">
    <button class="ptab active" onclick="showPTab(event,'current')">Current Members</button>
    <button class="ptab" onclick="showPTab(event,'former')">Former Students</button>
  </div>

  <div id="tab-current" class="ptab-pane active">
    <div class="people-profile">
      <img src="/assets/img/prof_pic.jpg" alt="Dr. Tanvir Arafin" class="people-img">
      <div class="people-bio">
        <h3>Dr. Tanvir Arafin</h3>
        <p class="people-role">PI &mdash; Assistant Professor, Cyber Security Engineering</p>
        <p>I am a tenure-track Assistant Professor at the <a href="https://cybersecurity.gmu.edu">Department of Cyber Security Engineering</a> at <a href="https://www.gmu.edu">George Mason University</a>. I received my M.S. and Ph.D. degrees from the <a href="https://ece.umd.edu">Electrical and Computer Engineering Department</a> at the <a href="https://umd.edu">University of Maryland, College Park</a>, in 2016 and 2018. My research explores security opportunities in <strong>emerging computer architecture</strong>, examines the <strong>weaknesses in autonomous systems</strong>, and builds hardware-derived primitives for developing <strong>trusted computation frameworks</strong>.</p>
        <p class="people-contact">322 Research Hall &bull; 10401 York River Road &bull; Fairfax, VA 22030</p>
      </div>
    </div>
  </div>

  <div id="tab-former" class="ptab-pane">
    <h3 class="people-group">Ph.D. Students</h3>

    <div class="people-profile">
      <img src="/assets/img/yanze.png" alt="Yanze Wu" class="people-img">
      <div class="people-bio">
        <h4>Yanze Wu</h4>
        <p class="people-role">Ph.D. Student, Cyber Security Engineering</p>
        <p>Yanze is a PhD student in the Department of Cyber Security Engineering at George Mason University. He is a member of the SPIRE Lab, advised by Prof. Arafin. His research interests include post-quantum cryptography, reconfigurable computing, and hardware security. He received his M.S. degree in Communication and Information Systems from Hohai University in 2023.</p>
      </div>
    </div>

    <div class="people-profile">
      <img src="/assets/img/generic_person.svg" alt="Wangxinlei Chen" class="people-img">
      <div class="people-bio">
        <h4>Wangxinlei Chen</h4>
        <p class="people-role">Ph.D. Student, Cyber Security Engineering</p>
        <p>Wangxinlei is a Ph.D. student in the Department of Cyber Security Engineering at George Mason University. He is a member of the SPIRE Lab, advised by Prof. Arafin. His dissertation research focuses on hardware design for secure autonomous systems. Expected graduation: Fall 2028.</p>
      </div>
    </div>

    <div class="people-profile">
      <img src="/assets/img/generic_person.svg" alt="Max Duverneuil" class="people-img">
      <div class="people-bio">
        <h4>Max Duverneuil</h4>
        <p class="people-role">Ph.D. Student, Cyber Security Engineering</p>
        <p>Max is a Ph.D. student in the Department of Cyber Security Engineering at George Mason University. He is a member of the SPIRE Lab, advised by Prof. Arafin. His dissertation research focuses on microarchitecture-based power attacks and countermeasures. Expected graduation: Spring 2030.</p>
      </div>
    </div>

    <div class="people-profile">
      <img src="/assets/img/raja.jpeg" alt="Raja Kumar Janga" class="people-img">
      <div class="people-bio">
        <h4>Raja Kumar Janga</h4>
        <p class="people-role">Graduate Student, Electrical and Computer Engineering</p>
        <p>Raja is a graduate student in the Electrical and Computer Engineering Department at George Mason University and a Graduate Research Assistant in the SPIRE Lab. His research interests include hardware design, 3D-ICs, and supply chain vulnerabilities. He received his B.Tech in Electrical, Electronics and Communication Engineering from IIT Rajiv Gandhi University of Knowledge Technologies, India.</p>
      </div>
    </div>

    <h3 class="people-group">Undergraduate Researchers</h3>

    <div class="people-profile">
      <img src="/assets/img/aldur.png" alt="Al Dur Almaknoon" class="people-img">
      <div class="people-bio">
        <h4>Al Dur Almaknoon bint Salim Abdullah Al Rawas</h4>
        <p class="people-role">Undergraduate Researcher, Cyber Security Engineering</p>
        <p>Al Dur is a Cyber Security Engineering graduate from the Sultanate of Oman. She transferred to Mason from the University of South Florida, where she was technical lead of the Google Developer Student Club. At GMU she graduated with outstanding distinction, contributed to a Threat-Hunting research project funded by CCI Nova, and was an active member of the Mason Competitive Cyber Club. Her research in the SPIRE Lab focused on Robot Operating System vulnerabilities.</p>
      </div>
    </div>

    <div class="people-profile">
      <img src="/assets/img/philip.png" alt="Philip Stavrev" class="people-img">
      <div class="people-bio">
        <h4>Philip Stavrev</h4>
        <p class="people-role">Undergraduate Researcher, Computer Science</p>
        <p>Philip is an undergraduate student in the Computer Science Department at George Mason University and a member of the SPIRE Lab. His research interests include driverless cars, machine learning, and artificial intelligence.</p>
      </div>
    </div>
  </div>
</div>

<style>
.people-tabs { margin-top: 1rem; }
.tab-nav { display: flex; gap: 0; border-bottom: 2px solid var(--global-divider-color, #dee2e6); margin-bottom: 1.5rem; }
.ptab {
  background: none;
  border: none;
  border-bottom: 3px solid transparent;
  margin-bottom: -2px;
  padding: 0.6rem 1.2rem;
  font-size: 0.95rem;
  font-weight: 500;
  cursor: pointer;
  color: var(--global-text-color-light, #666);
  transition: color 0.15s, border-color 0.15s;
}
.ptab:hover { color: var(--global-theme-color, #1565c0); }
.ptab.active { color: var(--global-theme-color, #1565c0); border-bottom-color: var(--global-theme-color, #1565c0); }
.ptab-pane { display: none; }
.ptab-pane.active { display: block; }
.people-profile {
  display: flex;
  gap: 1.5rem;
  align-items: flex-start;
  margin-bottom: 2rem;
  padding-bottom: 1.5rem;
  border-bottom: 1px solid var(--global-divider-color, #eee);
}
.people-profile:last-of-type { border-bottom: none; }
.people-img { width: 120px; height: 120px; object-fit: cover; border-radius: 4px; flex-shrink: 0; }
.people-bio h3, .people-bio h4 { margin: 0 0 0.2rem; }
.people-role { font-style: italic; color: var(--global-text-color-light, #666); margin: 0 0 0.5rem; font-size: 0.9rem; }
.people-contact { font-size: 0.85rem; color: var(--global-text-color-light, #666); margin-top: 0.5rem; }
.people-group { margin: 1.5rem 0 1rem; color: var(--global-theme-color, #1565c0); font-size: 1rem; text-transform: uppercase; letter-spacing: 0.05em; }
</style>

<script>
function showPTab(e, name) {
  document.querySelectorAll('.ptab').forEach(function(b){ b.classList.remove('active'); });
  document.querySelectorAll('.ptab-pane').forEach(function(p){ p.classList.remove('active'); });
  e.currentTarget.classList.add('active');
  document.getElementById('tab-' + name).classList.add('active');
}
</script>
