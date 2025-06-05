# 🧠 Console Memory Match - C#

> A console-based memory matching game written in C#.  
> Um jogo da memória no terminal, desenvolvido em C#.

---

## 📌 Description | Descrição

**EN:**  
This is a classic **Memory Match** game implemented in the console using C#. The game displays a grid of hidden values, and the player flips two at a time trying to find matching pairs. The objective is to match all pairs with the least number of moves.

**PT-BR:**  
Este é o clássico **Jogo da Memória** implementado no terminal usando C#. O jogo mostra uma grade com valores ocultos, e o jogador vira dois por vez tentando encontrar pares iguais. O objetivo é encontrar todos os pares com o menor número de jogadas possível.

---

## ✅ Features | Funcionalidades

- [x] Grid with hidden values | Grade com valores ocultos  
- [x] Interactive flipping of cards | Virar cartas interativamente  
- [x] Matching logic and validation | Lógica de correspondência de pares  
- [x] Move counter and feedback | Contador de jogadas e mensagens  
- [x] Clean console UI | Interface limpa no terminal  

---

## ▶️ Running the Game | Executando o Jogo

> 🛠️ Requires [.NET SDK](https://dotnet.microsoft.com/download) installed

```bash
dotnet run
The game runs directly in the terminal interface.
O jogo é executado diretamente no terminal.

🎮 How to Play | Como Jogar
EN:

The board is displayed with hidden values.

You are prompted to enter coordinates for two positions.

If the values match, they stay revealed.

Continue until all pairs are matched.

PT-BR:

O tabuleiro é exibido com valores ocultos.

Você deve digitar as coordenadas de duas posições.

Se os valores forem iguais, permanecem visíveis.

Continue até que todos os pares sejam encontrados.

📁 Project Structure | Estrutura do Projeto
arduino
Copiar
Editar
/Program.cs         # Lógica principal do jogo da memória
/README.md          # Documentação do projeto
🧠 Example Output | Exemplo de Saída
txt
Copiar
Editar
  0 1 2
0 * * *
1 * * *
2 * * *

Enter first card (e.g., 0 1): 
Enter second card (e.g., 1 2): 
Match! 🔁

Moves: 4
Pairs matched: 2/6
🗂️ Versioning | Versionamento
v1.0.0 – Initial version:

Memory grid logic

Pair comparison system

Win condition with minimal UI

📜 License | Licença
This project is licensed under the MIT License.
Este projeto está licenciado sob a Licença MIT.

🙌 Contributions | Contribuições
Feel free to contribute ideas or enhancements.
Sinta-se à vontade para contribuir com ideias ou melhorias.

✉️ Contact | Contato
Created by Savio Fagundes
Criado por Savio Fagundes

markdown
Copiar
Editar
