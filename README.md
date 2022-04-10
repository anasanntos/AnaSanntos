Oiii!Eu sou Ana Sanntos.
**anasanntos/AnaSanntos** 
Puc Minas
Here are some ideas to get you started:

- 🔭 Trabalho com Front-End
- 🌱 Estudando javascript, HTML e CSS.
- 😄 Pronomes ela/dela
- ⚡ Conatate-me no email: acssribeiro@pucminas.com
-->
<a href="https://github.com/anasanntos">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=anasanntos&show_icons=true&theme=dracula&include_all_commits=true&count_private=true"/>
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=anasanntos&layout=compact&langs_count=7&theme=dracula"/>
 name: Generate Datas
@@ -10,14 +10,6 @@ jobs:
    name: Jobs to update datas
    runs-on: ubuntu-latest
    steps:
      # Summary Cards
      - uses: actions/checkout@v2
      - uses: vn7n24fzkq/github-profile-summary-cards@release
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
        with:
          USERNAME: ${{ github.repository_owner }}

      # Snake Animation
      - uses: Platane/snk@master
        id: snake-gif



  
