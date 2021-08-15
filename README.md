<h1 align='center'>< Hello world! /></h1>
<br>

My name is **Sirvan**.


# 📈 Stats:
<div align='center'>
<span align='left'>
    <img src='https://github-readme-stats.vercel.app/api?username=SirvanCheraghi&show_icons=true&count_private=true&hide_border=true&show_icons=true&theme=radical' alt='Github stats' align='center' />
</span>
<span align='right'>
    <img src='https://github-readme-streak-stats.herokuapp.com/?user=SirvanCheraghi&show_icons=true&count_private=true&hide_border=true&show_icons=true&theme=radical' alt='Github stats' align='center' />
</span>
</div>
<br>
<div align='center'>
    <img src='https://github-readme-stats.vercel.app/api/top-langs/?username=SirvanCheraghi&layout=compact&show_icons=true&count_private=true&hide_border=true&show_icons=true&theme=radical' alt='Languages' align='center' />
</div>
<br>
name: Waka Readme

on:
  schedule:
    # Runs at 12am IST
    - cron: '30 18 * * *'
  workflow_dispatch:
jobs:
  update-readme:
    name: Update Readme with Metrics
    runs-on: ubuntu-latest
    steps:
      - uses: SirvanCheraghi/waka-readme-stats@master
        with:
          WAKATIME_API_KEY: ${{ secrets.WAKATIME_API_KEY }}
          GH_TOKEN: ${{ secrets.GH_TOKEN }}

<div align='center'>
    <img src='https://github-readme-stats.vercel.app/api/wakatime?username=SirvanCheraghi&layout=compact&show_icons=true&count_private=true&hide_border=true&show_icons=true&theme=radical' alt='Languages over last 7 days ' align='center' />
</div>
<br>
