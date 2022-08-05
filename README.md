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
 # Snake Animation
  - uses: Platane/snk@master
    id: snake-gif
    with:
      github_user_name: camilamaraschin
      svg_out_path: dist/github-contribution-grid-snake.svg
  - uses: crazy-max/ghaction-github-pages@v2.1.3
    with:
      target_branch: output
      build_dir: dist
    env:
      GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
