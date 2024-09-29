<p align="center" ><img  src = "R.jpeg" width = 1400px height= 450px></p>
<h1 align="center">Hi 👋, I'm Rusith Sashika</h1>
<h3 align="center">A passionate full stack developer from SriLanka</h3>
<p align="center"> <img src="https://komarev.com/ghpvc/?username=Rusith-S&label=Profile%20views&color=0e75b6&style=flat" alt="rusith2001" /> </p>

- 🎓 I’m an Undergraduate
  
- 🌱 I’m currently learning **Springboot, Full stack Development, ORDBMS**
  
- 🔗 Visit my Portfolio https://rusith-s.github.io/Rusith-Portfolio/
  
- 💬 Ask me about **HTML, CSS, SQL, JavaScript**
  
- 📩 Feel free to reach me out **rusithsashika@gmail.com**

- ⚡ I'm looking for an internship
  
- ⬇ Download my CV <a href="Rusith_Sashika_CV.pdf" download> Rusith Sashika CV.pdf</a>
 
- ⚡ Fun fact **call me as Russa**
  
<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

name: generate animation

on:
  # run automatically every 12 hours
  schedule:
    - cron: "0 */12 * * *" 
  
  # allows to manually run the job at any time
  workflow_dispatch:
  
  # run on every push on the master branch
  push:
    branches:
    - main
    
  

jobs:
  generate:
    runs-on: ubuntu-latest
    timeout-minutes: 10
    
    steps:
      # generates a snake game from a github user (<github_user_name>) contributions graph, output a svg animation at <svg_out_path>
      - name: Generate github-contribution-grid-snake.svg
        uses: Platane/snk/svg-only@v2
        with:
          github_user_name: AravindaJogi
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark
      # push the content of <build_dir> to a branch
      # the content will be available at https://raw.githubusercontent.com/<github_user>/<repository>/<target_branch>/<file> , or as github page
      - name: Push github-contribution-grid-snake.svg to the output branch
        uses: crazy-max/ghaction-github-pages@v2.6.0
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}

<p align="center">
<!--- stats (start) -->
<img src="https://media.giphy.com/media/iY8CRBdQXODJSCERIr/giphy.gif" width="35" align ="center"><b>My Github Stats</b>
<table align="center">
  <tr border="none">
    <td width="50%" align="center">
      
  <img  align="center"  src="https://github-readme-stats.vercel.app/api?username=Rusith-S&title_color=7A7ADB&icon_color=2234AE&text_color=D3D3D3&bg_color=0,000000,130F40&show_icons=true&count_private=true" />
  
  <br></br>
  
  <img  title="🔥 Get streak stats for your profile at git.io/streak-stats" alt="Mark streak" src="https://github-readme-streak-stats.herokuapp.com/?user=Rusith-S&theme=outrun&hide_border=false"/>   
  
  </td>

  <td width="50%" align="center">

  <img  align="center"  src="https://github-readme-stats.anuraghazra1.vercel.app/api/top-langs/?username=Rusith-S&title_color=7A7ADB&icon_color=2234AE&text_color=D3D3D3&bg_color=0,000000,130F40&hide_border=false&no-bg=true&no-frame=true&langs_count=10"/>
    
  </td>
</tr>
</table>
<!--- trophy (start) -->
<div align=center>
  <a href="https://github.com/ryo-ma/github-profile-trophy" title="Go to Source">
      <img align="center" width=84% src="https://github-profile-trophy.vercel.app/?username=Rusith-S&theme=radical&row=1&column=7&margin-h=15&margin-w=5&no-bg=true" alt="TROPHY" />
    </a>
</div>
<!--- trophy (start) -->

</p>        
<!--- stats (end) -->

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">
<!--h1 without bottom border-->
<div id="user-content-toc">
  <ul align="center">
    <summary><h2 style="display: inline-block">Technologies That I Know👨🏻‍💻</h2></summary>
  </ul>
</div>
<!--tech stack icons-->
<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=bootstrap,c,cpp,css,express,angular,figma,anaconda,androidstudio,git,github,html,idea,eclipse,java,python,js,php,kotlin,mongodb,firebase,mysql,nodejs,postman,py,react,vscode&perline=14" />
  </a>
</p>                                                                                                                              

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">
<!-- Connect with me -->
<!--h2 without bottom border-->
<div id="user-content-toc">
  <ul align="center">
    <summary><h2 style="display: inline-block">Connect With Me🤝</h2></summary>
  </ul>
</div>
<p align="center">
<a href="https://bit.ly/3DiDN9t" target="blank"><img align="center" src="https://user-images.githubusercontent.com/88904952/234979284-68c11d7f-1acc-4f0c-ac78-044e1037d7b0.png" alt="linkedin" height="50" width="50" /></a>
<a href="https://bit.ly/48WdkN4" target="blank"><img align="center" src="https://user-images.githubusercontent.com/88904952/234981169-2dd1e58f-4b7e-468c-8213-034ba62156c3.png" alt="instagram" height="50" width="50" /></a>
<a href="https://fb.com/rusithsashika19" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/facebook.svg" alt="rusithsashika19" height="50" width="50" /></a>

</p>
<!--horizontal divider(gradiant)-->
<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

