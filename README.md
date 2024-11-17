# Hello There👋

### My name is Chayathon Rungrueang, I study Computer engneering at Kasetsart University Sriracha campus
### I'm interested in **Enbedded System** ,**Cloud Computing** ,**FPGA Programing** ,**RTOS in Embedded System**

### **Language and Tools**
[![My Skills](https://skillicons.dev/icons?i=c,cpp,js,html,css,java,docker,kubernetes,postman,arduino,linux,azure)](https://skillicons.dev)
### **Data base**
[![My Skills](https://skillicons.dev/icons?i=mongodb,mysql)](https://skillicons.dev)


![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=ThirdChyr&show_icons=true&theme=dark)

name: ThirdChyr
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
      - uses: anmol098/waka-readme-stats@master
        with:
          WAKATIME_API_KEY: ${{ secrets.WAKATIME_API_KEY }}
          GH_TOKEN: ${{ secrets.GH_TOKEN }}
