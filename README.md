



<div align="center">  
<img width=100% src="https://capsule-render.vercel.app/api?type=waving&color=ff23a4&height=80&section=header"/>

[![Typing SVG](https://readme-typing-svg.herokuapp.com/?color=ff91a4&size=35&center=true&vCenter=true&width=1000&lines=HELLO,+My+name+is+Alexandre+Alves;I'm+42+years+old;I'm+from+Brazil;I+am+studying+Software+Development;Be+Welcome!+:%29)](https://git.io/typing-svg)

[![Ashutosh's github activity graph](https://github-readme-activity-graph.vercel.app/graph?username=alexande-alves&bg_color=0d1117&color=b13583&line=b13583&point=ff9494&area=true&hide_border=true)](https://github.com/ashutosh00710/github-readme-activity-graph)



<div>
⚡ Apaixonado por tecnologia
⚡ Estudante de Desenvolvimento Mobile - Unopar - EAD<br>
⚡ Bolsita na Cubos Academy- Desenvolvimento de Software<br>
⚡ Bolsista Sharp Coders - Fullstac
⚡ Carioca, morando em Rio de Janeiro

📫 Como falar comigo... <br>
 </div>
 
 <div align="center">
 <br>
<a href="https://www.linkedin.com/in/alexandre-alves-de-souza-688b61248/" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a> 
<a href="mailto:alvestaq@gmail.com" target="_blank"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" target="_blank"></a> 
</div>
<br>
   <br>
<div style="display: inline_block" align="center"><br>

<div align="center">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" height="40" alt="javascript logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" height="40" alt="typescript logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" height="40" alt="java logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" height="40" alt="nodejs logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" height="40" alt="html5 logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" height="40" alt="css3 logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/wordpress/wordpress-original.svg" height="40" alt="wordpress logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" height="40" alt="mysql logo"  />
</div>



<h2 align="left">Hi 👋! My name is ... and I'm a ..., from ....</h2>

###

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=alexande-alves&hide_title=false&hide_rank=false&show_icons=true&include_all_commits=true&count_private=true&disable_animations=false&theme=dracula&locale=en&hide_border=false" height="150" alt="stats graph"  />
  <img src="https://github-readme-stats.vercel.app/api/top-langs?username=alexande-alves&locale=en&hide_title=false&layout=compact&card_width=320&langs_count=5&theme=dracula&hide_border=false" height="150" alt="languages graph"  />
</div>

###

name: Generate snake animation

on:
  schedule: # execute every 12 hours
    - cron: "* */12 * * *"

  workflow_dispatch:

  push:
    branches:
    - master

jobs:
  generate:
    runs-on: ubuntu-latest

    steps:
      - name: generate snake.svg
        uses: Platane/snk/svg-only@v2
        with:
          github_user_name: ${{ github.repository_owner }}
          outputs: dist/snake.svg


      - name: push snake.svg to the output branch
        uses: crazy-max/ghaction-github-pages@v2.6.0
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
###



##

###


<img src="https://raw.githubusercontent.com/alexande-alves/alexande-alves/output/snake.svg" alt="Snake animation" />

###  
  
