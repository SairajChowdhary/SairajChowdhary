### Namaste🙏🏻

<!--
**SairajChowdhary/SairajChowdhary** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

- 🔭 I’m currently working on improving my Competitive programming and Data structures design.
- 🌱 I’m currently learning C++ and DSA.
- 👯 I’m looking to collaborate on game dev and systems design.
- 🤔 I’m looking for help with C++ advanced Programming.
- 💬 Ask me about C/C++ or Webdev.
- 📫 How to reach me: 

If you are facing an issue or error with 2nd car collision, here's how to fix it.
--> int collision() {
if (enemyY[0] + 4 >= 23) {
if (enemyX[0] + 4 - carPos >= 0 && enemyX[0] + 4 - carPos < 9) {
return 1;
}
}
if (enemyY[1] + 4 >= 23) {
if (enemyX[1] + 4 - carPos >= 0 && enemyX[1] + 4 - carPos < 9) {
return 1;
}
}
return 0;
}

# Hi there, I'm Sairaj Chowdhary 👋

**Data Scientist & Student**  
Passionate about leveraging data to solve real-world problems and building impactful web applications.

---

## 🚀 Skills

- **Languages:** Python, C++
- **Machine Learning:** Scikit-learn, Pandas, NumPy
- **Web Development:** HTML, CSS, Anime.js, Chart.js, Tailwind CSS
- **Others:** Problem-solving, Data Visualization.

---

## 🌟 Featured Projects

- [**SairajsFinanceClub**](https://github.com/SairajChowdhary/SairajsFinanceClub)  
  _A platform for financial analytics and tools, empowering users to make smarter money decisions._

- [**API-tite**](https://github.com/SairajChowdhary/API-tite)  
  _A flexible framework for building and consuming APIs with ease._

- [**AD-recommendation**](https://github.com/SairajChowdhary/AD-recommendation)  
  _A machine learning project focused on advanced ad recommendation systems._

---

## 📈 GitHub Stats

![SairajChowdhary's GitHub Stats](https://github-readme-stats.vercel.app/api?username=SairajChowdhary&show_icons=true&theme=radical)

---
<!-- Game-like Racing Animation -->
<p align="center">
  <svg width="500" height="160" viewBox="0 0 500 160" fill="none" xmlns="http://www.w3.org/2000/svg">
    <rect width="500" height="160" fill="#191970"/>
    <!-- Road -->
    <rect y="100" width="500" height="35" fill="#444"/>
    <!-- Finish Line -->
    <g>
      <rect x="420" y="80" width="12" height="55" fill="#fff" />
      <rect x="420" y="80" width="6" height="6" fill="#000"/>
      <rect x="426" y="86" width="6" height="6" fill="#000"/>
      <rect x="420" y="92" width="6" height="6" fill="#000"/>
      <rect x="426" y="98" width="6" height="6" fill="#000"/>
      <rect x="420" y="104" width="6" height="6" fill="#000"/>
      <rect x="426" y="110" width="6" height="6" fill="#000"/>
      <rect x="420" y="116" width="6" height="6" fill="#000"/>
      <rect x="426" y="122" width="6" height="6" fill="#000"/>
    </g>
    <!-- Racing Car -->
    <g>
      <rect id="car" x="40" y="110" width="55" height="20" rx="8" fill="#FF3B3F">
        <animate attributeName="x" values="40;400;40" keyTimes="0;0.5;1" dur="4s" repeatCount="indefinite" />
      </rect>
      <!-- Car Windows -->
      <rect x="50" y="114" width="15" height="8" rx="2" fill="#87CEEB">
        <animate attributeName="x" values="50;410;50" keyTimes="0;0.5;1" dur="4s" repeatCount="indefinite" />
      </rect>
      <!-- Wheels -->
      <circle cx="55" cy="132" r="5" fill="#222">
        <animate attributeName="cx" values="55;415;55" keyTimes="0;0.5;1" dur="4s" repeatCount="indefinite" />
      </circle>
      <circle cx="85" cy="132" r="5" fill="#222">
        <animate attributeName="cx" values="85;445;85" keyTimes="0;0.5;1" dur="4s" repeatCount="indefinite" />
      </circle>
      <!-- Speed Lines -->
      <rect x="33" y="120" width="12" height="2" fill="#FFD700" opacity="0.6">
        <animate attributeName="x" values="33;393;33" keyTimes="0;0.5;1" dur="4s" repeatCount="indefinite" />
      </rect>
      <rect x="30" y="125" width="8" height="2" fill="#00FFE7" opacity="0.7">
        <animate attributeName="x" values="30;390;30" keyTimes="0;0.5;1" dur="4s" repeatCount="indefinite" />
      </rect>
    </g>
    <!-- Road Stripes -->
    <g>
      <rect x="0" y="117" width="38" height="4" fill="#fff">
        <animate attributeName="x" from="0" to="500" dur="2s" repeatCount="indefinite" />
      </rect>
      <rect x="100" y="117" width="38" height="4" fill="#fff">
        <animate attributeName="x" from="100" to="600" dur="2s" repeatCount="indefinite" />
      </rect>
      <rect x="200" y="117" width="38" height="4" fill="#fff">
        <animate attributeName="x" from="200" to="700" dur="2s" repeatCount="indefinite" />
      </rect>
      <rect x="300" y="117" width="38" height="4" fill="#fff">
        <animate attributeName="x" from="300" to="800" dur="2s" repeatCount="indefinite" />
      </rect>
    </g>
    <!-- Game Title -->
    <text x="250" y="60" text-anchor="middle" fill="#fff" font-family="Verdana" font-size="28" font-weight="bold" letter-spacing="2">
      🚦 GitHub Racer 🚗
    </text>
    <!-- Level Up (animated text) -->
    <text x="250" y="90" text-anchor="middle" fill="#FFD700" font-family="Verdana" font-size="18" font-weight="bold" letter-spacing="2">
      <tspan>
        <animate attributeName="opacity" values="0;1;0" keyTimes="0;0.3;1" dur="4s" repeatCount="indefinite" begin="2s"/>
        LEVEL UP!
      </tspan>
    </text>
  </svg>
</p>

<!-- Confetti Effect Animation -->
<p align="center">
  <svg width="400" height="100" viewBox="0 0 400 100">
    <g>
      <circle cx="50" cy="10" r="3" fill="#FF3B3F">
        <animate attributeName="cy" values="10;90" dur="1.6s" repeatCount="indefinite"/>
        <animate attributeName="opacity" values="1;0" dur="1.6s" repeatCount="indefinite"/>
      </circle>
      <circle cx="150" cy="10" r="3" fill="#FFD700">
        <animate attributeName="cy" values="10;90" dur="1.3s" repeatCount="indefinite" begin="0.3s"/>
        <animate attributeName="opacity" values="1;0" dur="1.3s" repeatCount="indefinite" begin="0.3s"/>
      </circle>
      <circle cx="250" cy="10" r="3" fill="#00FFAB">
        <animate attributeName="cy" values="10;90" dur="1.5s" repeatCount="indefinite" begin="0.6s"/>
        <animate attributeName="opacity" values="1;0" dur="1.5s" repeatCount="indefinite" begin="0.6s"/>
      </circle>
      <circle cx="350" cy="10" r="3" fill="#00BFFF">
        <animate attributeName="cy" values="10;90" dur="1.2s" repeatCount="indefinite" begin="0.2s"/>
        <animate attributeName="opacity" values="1;0" dur="1.2s" repeatCount="indefinite" begin="0.2s"/>
      </circle>
      <rect x="80" y="10" width="5" height="5" fill="#9B30FF">
        <animate attributeName="y" values="10;90" dur="1.7s" repeatCount="indefinite" begin="0.4s"/>
        <animate attributeName="opacity" values="1;0" dur="1.7s" repeatCount="indefinite" begin="0.4s"/>
      </rect>
      <rect x="180" y="10" width="5" height="5" fill="#FF8C00">
        <animate attributeName="y" values="10;90" dur="1.2s" repeatCount="indefinite" begin="0.8s"/>
        <animate attributeName="opacity" values="1;0" dur="1.2s" repeatCount="indefinite" begin="0.8s"/>
      </rect>
      <rect x="280" y="10" width="5" height="5" fill="#39FF14">
        <animate attributeName="y" values="10;90" dur="1.4s" repeatCount="indefinite" begin="1.1s"/>
        <animate attributeName="opacity" values="1;0" dur="1.4s" repeatCount="indefinite" begin="1.1s"/>
      </rect>
      <rect x="380" y="10" width="5" height="5" fill="#FFC0CB">
        <animate attributeName="y" values="10;90" dur="1.5s" repeatCount="indefinite" begin="0.7s"/>
        <animate attributeName="opacity" values="1;0" dur="1.5s" repeatCount="indefinite" begin="0.7s"/>
      </rect>
    </g>
    <text x="200" y="55" text-anchor="middle" fill="#222" font-family="Verdana" font-size="20" font-weight="bold">
      🎉 Achievement Unlocked! 🎉
    </text>
  </svg>
</p>

<!--
Want to connect or know more? Add your social links or a fun fact here!
-->
