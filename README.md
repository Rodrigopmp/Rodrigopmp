## Olá, sou Rodrigo Pinheiro👋
- 🌱 Estudante de Ciência da Computação no IMT
- 📫 Email de contato: Rodrigopmp2007@gmail.com
- 😄 Pronouns: Ele/Dele
- 🔥 Fun fact: Gaming enthusiast

![Jokes Card](https://readme-jokes.vercel.app/api)

<div style="display: inline_block"><br>
  <img align="center" alt="Ro-Js" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-plain.svg">
  <img align="center" alt="Ro-React" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original.svg">
  <img align="center" alt="Ro-HTML" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original.svg">
  <img align="center" alt="Ro-CSS" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original.svg">
  <img align="center" alt="Ro-Python" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg">

</div>

##

<div> 
  <a href="https://instagram.com/pinheiro.rodrig0" target="_blank"><img src="https://img.shields.io/badge/-Instagram-%23E4405F?style=for-the-badge&logo=instagram&logoColor=white" target="_blank"></a>
  <a href = "mailto:rodrigopmp2007@gmail.com"><img src="https://img.shields.io/badge/-Gmail-%23333?style=for-the-badge&logo=gmail&logoColor=white" target="_blank"></a>
  <a href="https://www.linkedin.com/in/rodrigo-perri-mendes-pinheiro-885485321" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a> 
  
</div>

##

<div>
<a href="https://github.com/Rodrigopmp">
<img height="180em" src="https://github-readme-stats.vercel.app/api?username=rodrigopmp&show_icons=true&theme=dark&include_all_commits=true&count_private=true"/>
<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=rodrigopmp&layout=compact&langs_count=16&theme=dark"/>
</div>

name: Generate Datas

on:
  schedule: # execute every 12 hours
    - cron: "* */12 * * *"
  workflow_dispatch:

jobs:
  build:
    name: Jobs to update datas
    runs-on: ubuntu-latest
    steps:
      # Snake Animation
      - uses: Platane/snk@master
        id: snake-gif
        with:
          github_user_name: rodrigopmp
          svg_out_path: dist/github-contribution-grid-snake.svg

  - uses: crazy-max/ghaction-github-pages@v2.1.3
      with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}

  ![Snake animation](https://github.com/rodrigopmp/rodrigopmp/blob/output/github-contribution-grid-snake.svg)
