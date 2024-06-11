><div id="header" align="center">
>    <h1 align="center">About Me</h1>
>    <h3 align="left">Hi, I'm `Adrian`. I'm a 17-year-old programmer from Germany. I love coding and spend a lot of my time improving my skills and exploring new technologies. I also enjoy playing video games, which helps me relax and gives me new ideas for my projects. I'm not always the most persistent person, but I try my best to keep moving forward and make progress.</h3>
></div>

> <div id="statistic">
>  <h1 align="center">statistic</h1>
>  <img src="https://streak-stats.demolab.com?user=adgangster007&theme=transparent&fire=EB5454" alt="GitHub Streak"/>
>  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=adgangster007&layout=compact&theme=transparent" alt="Top Languages"/>
>    <p> <img src="https://komarev.com/ghpvc/?username=adgangster007&label=Profile%20views&color=0e75b6&style=flat" alt="adgangster007" /> </p>
></div>

> <h1 align="center">Profile Section</h1>
> 👩‍💻 I'm currently working on a Minecraft Server
>
> ## Languages
> [![My Skills](https://skillicons.dev/icons?i=javascript,php,py,html,css&theme=dark)](https://skillicons.dev)
>
> ## Tools
> [![My Skills](https://skillicons.dev/icons?i=docker,mongodb,mysql,sqlite&theme=dark)](https://skillicons.dev)
>
> ## Editors
>[![My Skills](https://skillicons.dev/icons?i=phpstorm,webstorm,vscode&theme=dark)](https://skillicons.dev)

><div id="badges" align="center">
>  <a href="https://discord.gg/phKhFpcy">
>    <img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="LinkedIn Badge"/>
>  </a>
></div>

- uses: Platane/snk@v3
  with:
    # github user name to read the contribution graph from (**required**)
    # using action context var `github.repository_owner` or specified user
    github_user_name: ${{ github.repository_owner }}

    # list of files to generate.
    # one file per line. Each output can be customized with options as query string.
    #
    #  supported options:
    #  - palette:     A preset of color, one of [github, github-dark, github-light]
    #  - color_snake: Color of the snake
    #  - color_dots:  Coma separated list of dots color.
    #                 The first one is 0 contribution, then it goes from the low contribution to the highest.
    #                 Exactly 5 colors are expected.
    outputs: |
      dist/github-snake.svg
      dist/github-snake-dark.svg?palette=github-dark
      dist/ocean.gif?color_snake=orange&color_dots=#bfd6f6,#8dbdff,#64a1f4,#4b91f1,#3c7dd9
