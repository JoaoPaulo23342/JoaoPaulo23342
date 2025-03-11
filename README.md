
[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=300&size=50&duration=4000&pause=1000&color=FFF&center=true&vCenter=true&random=false&width=1000&lines=Hello%2C+my+name+is+João+Paulo;I'm+19+years+old;I'm+a+Software+Developer;I'm+from+Brazil;welcome%3A)](https://git.io/typing-svg)

<br>
<br>

# Nome da Actions:  
name: Snake Game

# Controlador do tempo que sera feito a atualização dos arquivos.
on:
  schedule:
      # Será atualizado a cada 5 horas.
    - cron: "0 */5 * * *"

# Permite executar na na lista de Actions (utilizado para testes de build).
  workflow_dispatch:

# Regras
jobs:
  build:
    runs-on: ubuntu-latest
    steps:

    # Checks repo under $GITHUB_WORKSHOP, so your job can access it
      - uses: actions/checkout@v2

    # Repositorio que será utilizado para gerar os arquivos.
      - uses: Platane/snk@master
        id: snake-gif
        with:
          github_user_name: JoaoPaulo23342
          gif_out_path: dist/github-contribution-grid-snake.gif
          svg_out_path: dist/github-contribution-grid-snake.svg

      - run: git status

      # Para as atualizações.
      - name: Push changes
        uses: ad-m/github-push-action@master
        with:
          github_token: ${{ secrets.GITHUB_TOKEN }}
          branch: master
          force: true

      - uses: crazy-max/ghaction-github-pages@v2.1.3
        with:
          # the output branch we mentioned above
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}




<div align="center"> 


</a>


 
</a>


<a >
<img align="center"  
</a>


<a  href="https://www.linkedin.com/in/joao-paulo-01b137315/" target=_blank>
<img align="center"  height="80" width="80" src="https://github.com/carolbarbosa101/carolbarbosa101/assets/44561610/bc26a6f8-f0d3-4f15-82e1-55680c48f269">
</a>

</div>
<br>

<div align="center" >
   
[![Ashutosh's github activity graph](https://github-readme-activity-graph.vercel.app/graph?username=JoaoPaulo23342&bg_color=101013&color=f2f2f2&line=3d0de7&point=403d3d&area=true&hide_border=true)](https://github.com/ashutosh00710/github-readme-activity-graph)

</div>


### Main skills:
<div align="left"> 
<img align="left" height="84" width="84" src="https://github.com/carolbarbosa101/carolbarbosa101/assets/44561610/670ce35c-0b3c-4bec-ba1e-797c40ebcfc6">

<img align="left" height="80" width="80" src="https://github.com/carolbarbosa101/carolbarbosa101/assets/44561610/5d8aa673-1335-459f-a3c8-7149be4296d6">

<img align="left"  height="80" width="80" src="https://github.com/carolbarbosa101/carolbarbosa101/assets/44561610/b8182e38-59d0-4707-96dd-57781d7fa0cd">

<img align="left"  height="80" width="80" src="https://github.com/carolbarbosa101/carolbarbosa101/assets/44561610/e3520d7c-c3c2-4dff-90e2-86355adc6f7c">

<img align="left"  height="80" width="80" src="https://github.com/carolbarbosa101/carolbarbosa101/assets/44561610/2a52f515-32c0-419a-8550-d196743d93dd">

<img align="left"  height="80" width="80" src="https://github.com/carolbarbosa101/carolbarbosa101/assets/44561610/67a682a9-e93d-4eed-831c-037ec6d536cc">

<img align="left"  height="80" width="80" src="https://github.com/carolbarbosa101/carolbarbosa101/assets/44561610/bea3fe91-c320-4c5f-918e-fa6abe8ec1cc">

<img align="left"  height="80" width="80" src="https://github.com/carolbarbosa101/carolbarbosa101/assets/44561610/5d7b8d42-878a-4d07-aebc-f2af02475be6">

</div>

<br>
<br> 
<br>
<br>
<br>
<br> 


<h2 align="left"> Studying in this moment: </h2>


<div align="left"> 

<img align="left"  height="80" width="80" src="https://github.com/carolbarbosa101/carolbarbosa101/assets/44561610/e3520d7c-c3c2-4dff-90e2-86355adc6f7c">

<img align="left"  height="80" width="80" src="https://github.com/carolbarbosa101/carolbarbosa101/assets/44561610/2a52f515-32c0-419a-8550-d196743d93dd">

<img align="left"  height="80" width="80" src="https://github.com/carolbarbosa101/carolbarbosa101/assets/44561610/67a682a9-e93d-4eed-831c-037ec6d536cc">

<img align="left"  height="80" width="80" src="https://github.com/carolbarbosa101/carolbarbosa101/assets/44561610/bea3fe91-c320-4c5f-918e-fa6abe8ec1cc">

<img align="left"  height="80" width="80" src="https://github.com/carolbarbosa101/carolbarbosa101/assets/44561610/5d7b8d42-878a-4d07-aebc-f2af02475be6">

</div>


<div align="center">
  
<br>
<br>
<br>
<br>

<p align="centre"><b>Visitors Count</b></p> 
  
<p align="center"><img align="center" src="https://visit-counter.vercel.app/counter.png?page=https://github.com/JoaoPaulo23342?tab=overview&from=2024-11-01&to=2024-11-01&s=50&c=db006a&bg=00000000&no=7&ff=digi&tb=Visits%3A++&ta=" /></p> 
<br>
</div>


<div align="center">
<h3>
<img align="center" >
</a>
</div>

<br>
<br> 











