<div align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=32&duration=2800&pause=2000&color=A9FEF7&center=true&vCenter=true&width=940&lines=Hello+World!+I'm+a+Full+Stack+Developer+%F0%9F%91%8B;Welcome+to+my+GitHub+Profile!;Let's+build+something+amazing+together!" alt="Typing SVG" />
</div>

<div align="center">
  <img src="https://raw.githubusercontent.com/iampavangandhi/iampavangandhi/master/gifs/Hi.gif" width="40px" style="margin-left: 10px;">
</div>

<p align="center">
  <em>"I would like to change the world, but they won't give me the source code."</em>
</p>

<div align="center">
  <img src="https://user-images.githubusercontent.com/55005374/95673501-37764680-0b66-11eb-8ee1-d4f4a2b285d9.gif" width="70%" />
</div>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

## 🚀 Tech Stack & Tools

<div align="center">
  
### Languages
<p>
  <img src="https://skillicons.dev/icons?i=python,js,html,css" />
</p>

### Frameworks & Libraries
<p>
  <img src="https://skillicons.dev/icons?i=django,react,bootstrap" />
</p>

### Databases & Tools
<p>
  <img src="https://skillicons.dev/icons?i=mysql,git,github,vscode" />
</p>

</div>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

## 📊 GitHub Analytics

<div align="center">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=hubaibp&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true"/>
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=hubaibp&layout=compact&langs_count=8&theme=tokyonight"/>
</div>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=hubaibp&theme=tokyonight" alt="GitHub Streak" />
</div>

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=hubaibp&theme=tokyo-night&bg_color=1a1b27&color=70a5fd&line=bf91f3&point=38bdae&area=true&hide_border=true" />
</div>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

## 🏆 GitHub Trophies

<div align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=hubaibp&theme=tokyonight&no-frame=false&no-bg=false&margin-w=4" />
</div>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

## 🐍 Contribution Snake

<div align="center">
  <img src="https://github.com/hubaibp/hubaibp/blob/output/github-contribution-grid-snake.svg" alt="Snake animation" />
</div>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

## 💼 What I'm Working On

<div align="center">
  
```python
class Developer:
    def __init__(self):
        self.name = "Hubaib"
        self.role = "Full Stack Developer"
        self.language_spoken = ["Python", "JavaScript", "HTML", "CSS"]
        self.frameworks = ["Django", "React", "Bootstrap"]
        self.databases = ["MySQL"]
        self.current_focus = "Building amazing web applications"
        
    def say_hi(self):
        print("Thanks for dropping by! Let's connect and build something amazing together!")

me = Developer()
me.say_hi()
```

</div>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

## 📬 Let's Connect!

<div align="center">
  
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:27hubaib@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/hubaibp)
[![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://instagram.com/hubaib_p)

</div>

<div align="center">
  <img src="https://komarev.com/ghpvc/?username=hubaibp&label=Profile%20views&color=0e75b6&style=flat" alt="Profile views" />
</div>

<div align="center">
  <h3>⭐️ From <a href="https://github.com/hubaibp">hubaibp</a></h3>
</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=100&section=footer"/>
```

## Key Improvements Made:

1. **Animated Typing Header**: Added a dynamic typing animation for the greeting
2. **Modern Tech Stack Icons**: Used `skillicons.dev` for cleaner, more modern icons
3. **Enhanced GitHub Stats**: Added streak stats and activity graph
4. **GitHub Trophies**: Showcases achievements and milestones
5. **Contribution Snake**: Animated snake eating contributions (requires GitHub Action setup)
6. **Code Block**: Added a creative Python class representation
7. **Modern Badges**: Replaced icon images with styled badges for social links
8. **Visual Separators**: Added animated dividers between sections
9. **Profile Views Counter**: Added visitor counter
10. **Consistent Theme**: Used Tokyo Night theme throughout for cohesion
11. **Better Layout**: Improved spacing and organization

## Optional: GitHub Action for Snake Animation

To enable the contribution snake animation, create this GitHub Action:

```yaml:.github/workflows/snake.yml
name: Generate Snake

on:
  schedule:
    - cron: "0 */6 * * *"
  workflow_dispatch:

jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v2
      - uses: Platane/snk@master
        id: snake-gif
        with:
          github_user_name: hubaibp
          svg_out_path: dist/github-contribution-grid-snake.svg
      - uses: crazy-max/ghaction-github-pages@v2.1.3
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
