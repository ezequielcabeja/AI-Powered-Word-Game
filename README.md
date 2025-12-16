# 🎮 AI-Powered Guessing Game | Alura Immersion + Google Gemini

![Python](https://img.shields.io/badge/Python-3.9%2B-blue)
![Google Gemini](https://img.shields.io/badge/Google-Gemini-red)
![Game](https://img.shields.io/badge/Project-Game-orange)
![License](https://img.shields.io/badge/License-Educational-green)

---

## About the Project | Sobre o Projeto

**EN 🇬🇧**
This project is an **AI-powered guessing game** developed by combining two coding blocks learned during the **Alura Immersion**. The game features **AI-generated hints powered by Google Gemini**, multiple difficulty levels, and a limited number of attempts, creating a more engaging and challenging gameplay experience.

**PT 🇧🇷 / 🇵🇹**
Este projeto é um **jogo de adivinhação com suporte de IA**, desenvolvido a partir da junção de dois blocos de código aprendidos durante a **Imersão da Alura**. O jogo conta com **dicas geradas pelo Google Gemini**, níveis de dificuldade e número limitado de tentativas, tornando a experiência mais envolvente e desafiadora.

---

## Purpose | Objetivo

**EN**

* Practice Python programming through a complete game
* Integrate Generative AI (Google Gemini) into an application
* Apply game logic such as levels, attempts, and feedback
* Strengthen problem-solving and logical thinking skills

**PT**

* Praticar programação em Python através de um jogo completo
* Integrar IA Generativa (Google Gemini) em uma aplicação
* Aplicar lógica de jogo como níveis, tentativas e feedback
* Fortalecer habilidades de raciocínio lógico e resolução de problemas

---

## 🧠 Skills Demonstrated | Competências Demonstradas

**EN**

* Python programming fundamentals
* Game logic and control flow
* Conditional statements and loops
* Integration with Google Gemini API
* Prompt-based AI interaction
* Error handling and user feedback
* Modular and readable code structure

**PT**

* Fundamentos de programação em Python
* Lógica de jogos e controle de fluxo
* Estruturas condicionais e laços de repetição
* Integração com a API do Google Gemini
* Interação com IA baseada em prompts
* Tratamento de erros e feedback ao usuário
* Estrutura de código modular e legível

---

## App Features | Funcionalidades da Aplicação

**EN**

* Guessing game with increasing difficulty levels
* Limited number of attempts per round
* AI-generated hints using Google Gemini
* Dynamic feedback based on player actions
* Simple and interactive command-line interface
* Educational focus with engaging gameplay

**PT**

* Jogo de adivinhação com níveis de dificuldade progressivos
* Número limitado de tentativas por rodada
* Dicas geradas por IA utilizando o Google Gemini
* Feedback dinâmico com base nas ações do jogador
* Interface simples e interativa em terminal
* Foco educacional aliado a uma experiência divertida

---

## Repository Structure | Estrutura do Repositório

```
AI-Powered-Word-Game/
│
├── app.ipynb
└── README.md
```

---

## ⚙️ Requirements | Requisitos

**EN**

* Python 3.9 or higher
* Google Colab
* Google Gemini API Key

**PT**

* Python 3.9 ou superior
* Google Colab
* Chave de API do Google Gemini

---

## ▶️ How to Run | Como Executar

### Google Colab (Recommended)

**EN 🇬🇧**

1. Open **Google Colab**: [https://colab.research.google.com/](https://colab.research.google.com/)
2. Upload the file `app.ipynb` **or** open it directly from GitHub using *File → Open notebook → GitHub*.
3. Make sure the required libraries are installed directly in the notebook cells.
4. Configure your **Google Gemini API key** in the cell indicated in the notebook.
5. Run the notebook cells **from top to bottom**.
6. Play the game directly through the notebook output.

**PT 🇧🇷 / 🇵🇹**

1. Abra o **Google Colab**: [https://colab.research.google.com/](https://colab.research.google.com/)
2. Envie o arquivo `app.ipynb` **ou** abra-o diretamente a partir do GitHub em *Arquivo → Abrir notebook → GitHub*.
3. Certifique-se de que as bibliotecas necessárias são instaladas diretamente nas células do notebook.
4. Configure a sua **chave de API do Google Gemini** na célula indicada do notebook.
5. Execute as células do notebook **de cima para baixo**.
6. Jogue diretamente através da saída do notebook.

---

## ⚠️ Notes | Observações

**EN**
If you encounter any issues related to the AI hints, make sure your **Google Gemini API key** is correctly configured before running the application again.

**PT**
Caso encontre algum problema relacionado às dicas de IA, verifique se a sua **chave de API do Google Gemini** está corretamente configurada antes de executar o jogo novamente.

## How the Game Works | Como o Jogo Funciona

**EN 🇬🇧**

1. The game starts by randomly selecting a secret number within a predefined range.
2. The player chooses a difficulty level, which determines the number of attempts available.
3. On each turn, the player inputs a guess directly in the notebook interface.
4. After each attempt, the game provides feedback indicating whether the guess is too high, too low, or correct.
5. If enabled, **AI-generated hints powered by Google Gemini** are provided to help the player refine their guesses.
6. The game ends when the player guesses the correct number or runs out of attempts.
7. A final message summarizes the result and encourages replay.

**PT 🇧🇷 / 🇵🇹**

1. O jogo começa com a escolha aleatória de um número secreto dentro de um intervalo definido.
2. O jogador seleciona um nível de dificuldade, que determina a quantidade de tentativas disponíveis.
3. A cada rodada, o jogador insere um palpite diretamente na interface do notebook.
4. Após cada tentativa, o jogo fornece feedback indicando se o palpite está acima, abaixo ou correto.
5. Quando ativadas, **dicas geradas por IA com Google Gemini** auxiliam o jogador a ajustar seus palpites.
6. O jogo termina quando o jogador acerta o número ou quando as tentativas se esgotam.
7. Uma mensagem final apresenta o resultado e incentiva uma nova partida.

---

## Game Logic Flow | Fluxo da Lógica do Jogo

```
Start Game
   │
   ▼
Generate Secret Number
   │
   ▼
Select Difficulty Level
   │
   ▼
Set Number of Attempts
   │
   ▼
Player Makes a Guess
   │
   ▼
Is Guess Correct?
   ├── Yes → 🎉 Player Wins → End Game
   │
   └── No
        │
        ▼
   Attempts Remaining?
        ├── Yes
        │     │
        │     ▼
        │  Provide Feedback
        │  (Too High / Too Low)
        │     │
        │     ▼
        │  AI Hint (Gemini)
        │     │
        │     └── Back to Player Guess
        │
        └── No → ❌ Game Over → End Game
```

**EN**
This diagram represents the core decision flow of the game, highlighting player interaction, feedback loops, and the optional use of AI-generated hints.

**PT**
Este diagrama representa o fluxo principal de decisões do jogo, destacando a interação do jogador, os ciclos de feedback e o uso opcional de dicas geradas por IA.

---

## 👤 Author | Autor

Developed by / Desenvolvido por:

**- [Ezequiel Tchimbaya Cachapeu Paulo](https://github.com/ezequielcabeja)**

---

## 📄 License | Licença

**EN**
This project is intended for **educational and portfolio purposes**.

**PT**
Este projeto é destinado a **fins educacionais e de portfólio**.

---

⭐ If this repository helped you, consider giving it a star!

⭐ Se este repositório te ajudou, considera deixar uma estrela!
