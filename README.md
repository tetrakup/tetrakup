<p align="left">
  <img src="https://komarev.com/ghpvc/?username=tetrakup&label=Profil%20Görüntüleme&color=0e75b6&style=flat" alt="Profil Görüntüleme" />
</p>

## Diller ve Araçlar:

<p align="left">
  <a href="https://www.w3schools.com/cs/" target="_blank">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/csharp/csharp-original.svg" alt="C#" width="20" height="20"/>
  </a>
  <a href="https://docs.microsoft.com/en-us/sql/" target="_blank">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/microsoftsqlserver/microsoftsqlserver-plain-wordmark.svg" alt="SQL Server" width="20" height="20"/>
  </a>
  <a href="https://www.mysql.com/" target="_blank">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="MySQL" width="20" height="20"/>
  </a>
  <a href="https://laravel.com/" target="_blank">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/laravel/laravel-plain-wordmark.svg" alt="Laravel" width="20" height="20"/>
  </a>
  <a href="https://www.python.org" target="_blank">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="Python" width="20" height="20"/>
  </a>
  <a href="https://www.php.net" target="_blank">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/php/php-original.svg" alt="PHP" width="20" height="20"/>
  </a>
  <a href="https://www.w3.org/html/" target="_blank">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="HTML5" width="20" height="20"/>
  </a>
  <a href="https://www.w3.org/Style/CSS/" target="_blank">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="CSS3" width="20" height="20"/>
  </a>
  <a href="https://flutter.dev" target="_blank">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/flutter/flutter-original.svg" alt="Flutter" width="20" height="20"/>
  </a>
  <a href="https://git-scm.com/" target="_blank">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/git/git-original.svg" alt="Git" width="20" height="20"/>
  </a>
  <a href="https://www.linux.org/" target="_blank">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" alt="Linux" width="20" height="20"/>
  </a>
  <a href="https://opencv.org/" target="_blank">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/opencv/opencv-original.svg" alt="OpenCV" width="20" height="20"/>
  </a>
  <a href="https://www.tensorflow.org/" target="_blank">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/tensorflow/tensorflow-original.svg" alt="TensorFlow" width="20" height="20"/>
  </a>
</p>


## GitHub İstatistikleri:

<p align="left">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=tetrakup&theme=tokyo-night" alt="En Çok Kullanılan Diller" />
</p>

<p align="left">
  <img src="https://github-readme-stats.vercel.app/api?username=tetrakup&show_icons=true" alt="GitHub İstatistikleri" />
</p>
<img src="https://github-readme-activity-graph.vercel.app/graph?username=tetrakup&theme=tokyo-night">

<!--START_SECTION:waka-->
name: Waka Readme

on:
  # for manual workflow trigger
  workflow_dispatch:
  schedule:
    # runs at 12 AM UTC (5:30 AM IST)
    - cron: "0 0 * * *"

jobs:
  update-readme:
    name: WakaReadme DevMetrics
    runs-on: ubuntu-latest
    steps:
        # this action name
      - uses: athul/waka-readme@master # do NOT replace with anything else
        with:
          GH_TOKEN: ${{ secrets.GH_TOKEN }} # optional if on profile readme
          WAKATIME_API_KEY: ${{ secrets.WAKATIME_API_KEY }} # required
          ### meta
          API_BASE_URL: https://wakatime.com/api # optional
          REPOSITORY: YOUR_GITHUB_USERNAME/YOUR_REPOSITORY_NAME # optional
          ### content
          SHOW_TITLE: true # optional
          SECTION_NAME: waka # optional
          BLOCKS: -> # optional
          CODE_LANG: rust # optional
          TIME_RANGE: all_time # optional
          LANG_COUNT: 10 # optional
          SHOW_TIME: true # optional
          SHOW_TOTAL: true # optional
          SHOW_MASKED_TIME: false # optional
          STOP_AT_OTHER: true # optional
          IGNORED_LANGUAGES: YAML JSON TOML # optional
          ### commit
          COMMIT_MESSAGE: Updated waka-readme graph with new metrics # optional
          TARGET_BRANCH: master # optional
          TARGET_PATH: README.md # optional
          COMMITTER_NAME: GitHubActionBot # optional
          COMMITTER_EMAIL: action-bot@github.com # optional
          AUTHOR_NAME: YOUR_NAME # optional
          AUTHOR_EMAIL: YOUR@EMAIL.com # optional
          # you can populate email-id with secretes instead
<!--END_SECTION:waka-->
