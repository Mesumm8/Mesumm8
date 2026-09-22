<div align="center">

# Hi, I'm Mesum Hussain 👋

### Full-Stack Developer · Mobile & Web · AI-driven systems

<a href="https://mesumfolio.netlify.app/"><img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=firefox&logoColor=FF7139"/></a>
<a href="https://linkedin.com/in/mmesumhussain"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="https://stackoverflow.com/users/23028191"><img src="https://img.shields.io/badge/Stack_Overflow-FE7A16?style=for-the-badge&logo=stack-overflow&logoColor=white"/></a>
<a href="mailto:mesummm8@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0f2027,50:2c5364,100:00c9a7&height=4&width=1000" width="100%"/>

</div>

<br>

### 💫 About Me

Full-Stack Developer building cross-platform mobile & web apps with **Python (Flask), Java, JavaScript, Flutter & Firebase**. I love clean architecture, REST APIs, and wiring AI into real products.

<br>

### 🧠 Tech Stack

<div align="center">

<img src="https://skillicons.dev/icons?i=java,js,html,css,py,dotnet&theme=dark" /><br>
<img src="https://skillicons.dev/icons?i=flask,django,fastapi,flutter,bootstrap,tailwind&theme=dark" /><br>
<img src="https://skillicons.dev/icons?i=firebase,postgres,sqlite,mysql,mongodb,nginx&theme=dark" /><br>
<img src="https://skillicons.dev/icons?i=aws,azure,cloudflare,vercel,netlify,kubernetes&theme=dark" /><br>
<img src="https://skillicons.dev/icons?i=numpy,pandas,sklearn,tensorflow,git,github&theme=dark" /><br>
<img src="https://skillicons.dev/icons?i=figma,gradle,githubactions,oracle,nvidia&theme=dark" />

</div>

<br>

### 👾 Contribution Graph — Pac-Man Edition

<div align="center">

<!-- pacman -->
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Mesumm8/Mesumm8/output/pacman-contribution-graph-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Mesumm8/Mesumm8/output/pacman-contribution-graph.svg">
  <img alt="pacman contribution graph" src="https://raw.githubusercontent.com/Mesumm8/Mesumm8/output/pacman-contribution-graph.svg">
</picture>

</div>

<details>
<summary><b>⚙️ One-time setup (click to expand)</b></summary>

<br>

1. In your `Mesumm8/Mesumm8` repo, create `.github/workflows/pacman.yml`:

    ```yaml
    name: generate arcade contribution graphs

    on:
      schedule:
        - cron: '0 0 * * *'   # daily
      workflow_dispatch:
      push:
        branches: [main]

    jobs:
      generate:
        permissions:
          contents: write
        runs-on: ubuntu-latest
        timeout-minutes: 20
        steps:
          - name: generate contribution graph SVGs
            uses: abozanona/pacman-contribution-graph@main
            with:
              github_user_name: ${{ github.repository_owner }}
              games: 'pacman'

          - name: push SVGs to the output branch
            uses: crazy-max/ghaction-github-pages@v3.1.0
            with:
              target_branch: output
              build_dir: dist
            env:
              GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
    ```

2. Go to **Settings → Actions → General → Workflow permissions** and enable **Read and write permissions**.
3. Go to the **Actions** tab and run the `generate arcade contribution graphs` workflow once manually. It publishes the SVG to a new `output` branch — the image above then renders and refreshes daily.

</details>

<br>

### 📊 GitHub Stats

<div align="center">

<img src="https://github-readme-stats.shion.dev/api?username=Mesumm8&theme=radical&hide_border=true&include_all_commits=true&count_private=true&rank_icon=github" height="165"/>
<img src="https://streak-stats.demolab.com/?user=Mesumm8&theme=radical&hide_border=true&timezone=Asia/Muscat&mode=daily" height="165"/>

<img src="https://github-readme-stats.shion.dev/api/top-langs/?username=Mesumm8&theme=radical&hide_border=true&layout=compact&langs_count=10"/>

</div>

### 🏆 Trophies

<div align="center">

<img src="https://github-profile-trophy.vercel.app/?username=Mesumm8&theme=radical&no-frame=true&no-bg=true&margin-w=6&row=1"/>

</div>

### ✍️ Random Dev Quote

<div align="center">

<img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=radical"/>

</div>

### 🔝 Top Contributed Repo

<div align="center">

<img src="https://github-contributor-stats.vercel.app/api?username=Mesumm8&limit=5&theme=radical&combine_all_yearly_contributions=true"/>

</div>

<br>

<div align="center">

[![](https://komarev.com/ghpvc/?username=Mesumm8&style=for-the-badge&color=blueviolet)](https://visitcount.itsvg.in)

</div>


<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00c9a7,100:0f2027&height=100&section=footer" width="100%"/>

</div>
