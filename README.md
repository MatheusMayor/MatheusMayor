- 👋 Hi, I’m @MatheusMayor
- 👀 I’m interested in ...prograr 
- 🌱 I’m currently learning ...C#, C++, Html, Css, Java Script, Phython, Ruby...
- 💞️ Estou a procura de jobs voltados a Desenvolvedor Frontend...
- 📫 Instagram:@sieversmayor47

<!---
MatheusMayor/MatheusMayor is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
<div align="center">
  <a href="https://github.com/MatheusMayor">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=MatheusMayor&show_icons=true&theme=dracula&include_all_commits=true&count_private=true"/>
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=MatheusMayor&layout=compact&langs_count=7&theme=dracula"/>
</div>
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
