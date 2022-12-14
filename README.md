


<!DOCTYPE html>
<html lang="en" data-color-mode="auto" data-light-theme="light" data-dark-theme="dark" data-a11y-animated-images="system">
  <head>
<p align="center" dir="auto" name="topo">
    <a href="#o-projeto">O Projeto</a> | 
    <a href="#tecnologias">Tecnologias</a> | 
    <a href="#objetivos">Objetivos da Sprint</a> | 
    <a href="#levantamento">Levantamento de Requisitos</a> |  
    <a href="#prototipo">Protótipo</a> | 
    <a href="#org-equipe">Organização da Equipe</a> | 
    <a href="#org-repo">Organização do Repositório</a>
</p>

# API_MirageGroup

<div align="center"  dir="auto">
<img id="logo" src="docs/miragegroup-logo.png" alt="logo-mirage-group" width=400px>
</div>


<h3 align="center" dir="auto">Repositório do projeto de API do 1º semestre do MirageGroup, da 1º turma de ADS da Fatec SJC 2022.</h3>

<div align="center" dir="auto">
<h3>### Entregas de Sprints</h3>

Cada entrega foi realizada a partir da criação de uma **tag**. Observe a relação a seguir:
| Sprint| Tag | Lançamento | Status | Histórico |
|:-----:|:-------------:|:----------:|:---------:|:---------:|
| 01 | [sprint-01](https://github.com/MirageGroup/API_MirageGroup/tree/entrega/sprint-1) | 18/09/2022 | Entregue | [ver relatório](https://github.com/MirageGroup/API_MirageGroup/blob/entrega/sprint-1/README.md) |
| 02 | [sprint-02](https://github.com/MirageGroup/API_MirageGroup/tree/entrega/sprint-2) | 09/10/2022 | Entregue | [ver relatório](https://github.com/MirageGroup/API_MirageGroup/tree/entrega/sprint-2#readme) |
| 03 | [sprint-03](https://github.com/MirageGroup/API_MirageGroup/tree/entrega/sprint-3) | 06/11/2022 | Entregue | [ver relatório](https://github.com/MirageGroup/API_MirageGroup/blob/entrega/sprint-3/README.md) |
| 04 | [sprint-04](https://github.com/MirageGroup/API_MirageGroup/tree/entrega/sprint-4) | 27/11/2022 | Entregue | [ver relatório](https://github.com/MirageGroup/API_MirageGroup/blob/entrega/sprint-4/README.md) |

→ [Voltar ao topo](#topo)
</div>

# Iniciar
Clone o repositório para o seu computador, abra o repositório com o VS Code, abra o terminal, troque para o cmd e use esse comando:
```bash
python -m venv venv && venv\Scripts\activate && pip install -r requirements.txt && python main.py
```

  <h1 align="center" dir="auto"><a id="user-content--sprint-1-08032021-a-28032021-" class="anchor" aria-hidden="true" href="#-sprint-1-08032021-a-28032021-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a> Sprint 4: 07/11/2022 a 27/11/2022 <br> <a href="" target="_blank" align="center"><img src="https://img.shields.io/badge/API%20Status-Entregue-brightgreen"></a> </h1> <br>

<img src="docs/mvp-sprint4.gif"><br>

<br>

<h2 align="center">O Projeto</h2>

![API Sprint 3 (1)](https://user-images.githubusercontent.com/111614142/204145483-193e4566-5e09-4b4b-b632-3f78abca74f2.png)

<br>

<h2 align="center">Tecnologias</h2>

![API Sprint 2 (1)](https://user-images.githubusercontent.com/111614142/200129675-2a913fcb-76cd-4788-8c1a-8c02b10d4cc4.png)



<span id="user-content-objetivos">
<h2 align="center" dir="auto"><a id="user-content-dart-objetivos-da-sprint" class="anchor" aria-hidden="true" href="#dart-objetivos-da-sprint"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a><g-emoji class="g-emoji" alias="dart" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f3af.png">🎯</g-emoji> Objetivos da Sprint</h2>

<br>

![objetivos](https://user-images.githubusercontent.com/56747051/204163427-00c80b24-2ab3-443d-8448-2361b54e6426.jpg)


<p dir="auto">→ <a href="#topo">Voltar ao topo</a></p>
<span id="user-content-levantamento">
<h2 align="center" dir="auto"><a id="user-content-pencil-levantamento-de-requisitos" class="anchor" aria-hidden="true" href="#pencil-levantamento-de-requisitos"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a><g-emoji class="g-emoji" alias="memo" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f4dd.png">📝</g-emoji> Levantamento de Requisitos</h2>
<p dir="auto">Antes de desenvolver o projeto, foi preciso denifir os desejos do cliente, organizando-os de acordo com suas prioridades e documentando com técnicas de Engenharia de Software. Para este levantamento de requisitos, o Product Owner do grupo esteve em contato constante com o cliente, questionando suas vontades e necessidades a fim de esculpir um plano de ação que satisfazesse seus pedidos, na medida do possível. Dessa forma, foi criado um backlog do produto, contendo suas funcionalidades e características principais, além de sprint backlogs e user stories, que são itens complementares para auxiliar a organização da equipe em relação às tarefas a serem desenvolvidas.</p>

<h3><g-emoji class="g-emoji" alias="pushpin" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f4cc.png"></g-emoji> Para verificar os backlogs das sprints e do produto, <a href="https://docs.google.com/spreadsheets/d/1KEpwnI85trRT_4ub3DmxdunUp8wq5imWWMSLXApkoH4/edit#gid=0">clique aqui</a>.</h3>
</ul>

<p dir="auto">→ <a href="#topo">Voltar ao topo</a></p>
<span id="user-content-prototipo">
<h2 align="center" dir="auto"><a id="user-content-desktop_computer-protótipo" class="anchor" aria-hidden="true" href="#desktop_computer-protótipo"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a><g-emoji class="g-emoji" alias="desktop_computer" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f5a5.png">✏️</g-emoji> Protótipo</h2>
<p dir="auto">Depois da definição do wireframe, iniciou-se o trabalho de codificação, passando os desenhos para arquivos HTML e CSS. O protótipo já conta com cores, tipografia e exemplos do resultado de uma busca, proporcionando a experiência esperada que o usuário terá ao manipular o produto final.</p>
<ul dir="auto">
<li>A primeira fase do protótipo dinâmico foi realizada também com a utilização do Figma, onde é possível acessar o protótipo por meio <a href="https://www.figma.com/file/udYrASpRvbCkks3O2nTWLZ/Untitled?node-id=0%3A1" rel="nofollow">deste link</a>.</li>
</ul>

<span id="user-content-org-equipe">
<h2 align="center" dir="auto"><a id="user-content-busts_in_silhouette-organização-da-equipe" class="anchor" aria-hidden="true" href="#busts_in_silhouette-organização-da-equipe"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a><g-emoji class="g-emoji" alias="busts_in_silhouette" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f465.png">👥</g-emoji> Organização da Equipe</h2>
<div align="center" dir="auto">
<p dir="auto">Para melhor organização do projeto, foi levantado as habilidades técnicas da equipe assim que decididas as ferramentas e tecnologias que seriam usadas, dividindo provisoriamente os integrantes em dois times principais: time Frontend e time backend, cada um com responsabilidades distintas mas sempre em comunicação.</p>
<ul dir="auto">
<li>A documentação e acompanhamento de atividades ficou a cargo da Scrum Master da equipe, que também colaborava com os dois times de trabalho.


</ul>
</li>
</ul>

<h2>Equipe<h2>
  
![API Sprint 3 (2)](https://user-images.githubusercontent.com/111614142/204145671-e6198771-efa2-400a-8b8d-9d443c0abd9b.png)

|    Função    | Nome                     |                     GitHub                     |                    Linkedin                    |
| :----------: | :----------------------- | :--------------------------------------------: | :--------------------------------------------: |
| Scrum Master | Pedro Henrique Pucci     |   [GitHub](https://github.com/pedro11pucci)    | [Linkedin](https://www.linkedin.com/in/pedro-p-122962234/)|
|      PO      | Hugo Henrique da Silva   |    [GitHub](https://github.com/Hugohs98)       | [Linkedin](https://www.linkedin.com/in/hugo-silva-2bb757210/)|
|   Dev Team   | Gustavo Henrique Pereira |    [GitHub](https://github.com/gustavohpereira)| [Linkedin](https://www.linkedin.com/in/gustavohpa/) |
|   Dev Team   | Gustavo Alves dos Santos |    [GitHub](https://github.com/ogustavoalves)  | [Linkedin](https://www.linkedin.com/in/gustavo-alves-073640248/) |
|   Dev Team   | Erik Zanetti Ferraz      |    [GitHub](https://github.com/ErikZFerraz)    | [Linkedin](https://www.linkedin.com/in/erik-zanetti-ferraz-09895a180/) |
|   Dev Team   | Victor Guilherme Branco  |    [GitHub](https://github.com/VictorGuui)     | [Linkedin](https://www.linkedin.com/in/victor-branco-323386190/) |
|   Dev Team   | Vinicius Henrique dos Santos Rodrigues |    [GitHub](https://github.com/vinicius123henrique321) | [Linkedin](https://www.linkedin.com/in/vinicius-henrique-1a016524a/)|
</div>


<p dir="auto">→ <a href="#topo">Voltar ao topo</a></p>
<span id="user-content-org-repo">
<h4 dir="auto"><a id="user-content-file_folder-organização-do-repositório" class="anchor" aria-hidden="true" href="#file_folder-organização-do-repositório"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a><g-emoji class="g-emoji" alias="file_folder" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f4c1.png">📁</g-emoji> Organização do Repositório</h4>
<p dir="auto">Tendo em vista o trabalho remoto que a equipe teria que se encaixar, foram definidos alguns padrões para a configuração do ambiente de trabalho compartilhado sempre se manter organizado, garantindo transparência e fácil acesso ao que se deseja a qualquer um de interesse.</p>
<p dir="auto">→ <a href="#topo">Voltar ao topo</a></p>



</body>
</html>

