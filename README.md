# MoonVitorGame
# 👹 MoonVitorBoos

Desenvolvimento de um jogo com o objetivo de aplicar diferentes técnicas de inteligência artificial para controlar inimigos. Atualmente o projeto possui dois cenários, o primeiro onde inimigos controlados por uma State Machine simples, exstem em modo de patrulha, e ao detectar o jogador (um Sapo Samurai muito descolado) partem para o ataque! Outro tipo de inimigo presente é o um crocodilo. Seu comportamento é aguardar até que o jogador não tenha mais seu ataque (que é um recurso esgotável) então ele persegue o jogador e o ataca! 

Por Fim, na Segunda cena, existe uma BossFight com o MOONVITOR, inimigo final do jogo, formado por fotos que tirei de um amigo, ele é controlado por GOAP e A* de modo que possa procurar a melhor rota entre suas ações (Ataque com as Mãos, Ataque com Estrelas, Curar, e Cabeçada Teleguida) para atingir seu objetivo com o menor custo, a depender do estado do mundo (açoes do jogador) você tem o que é preciso para derrota-lo?! 🕹️🕹️

Provavelmente não 🔥🔥

---

## 📸 Demonstração


<p align="center">
  <img src="./Assets/Readme%20Assets/Captura%20de%20tela%202025-09-19%20154050.png" width="400"/>
  <img src="./Assets/Readme%20Assets/Captura%20de%20tela%202025-09-19%20154036.png" width="400"/>
</p>



---

## 🛠 Tecnologias Utilizadas

- [Godot Engine](https://godotengine.org/) (versão 4.4)
- Linguagem: **GDScript**
- Sistema de IA: **GOAP**, **A***, **Steering Behaviors**, **State Machines**


---

## 🚀 Como Rodar o Projeto

Clone este repositório e abra o projeto no Godot Engine:

```bash
git clone https://github.com/HiioCom2i/MoonVitorBoss.git
cd MoonVitorBoss
