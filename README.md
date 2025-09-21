# rock-paper-scissors.py
#🌑📄✂ Pedra, Papel e Tesoura – Python | Treino de lógica ,estruturas condicionais e aplicação de listas e random.

![Badge](https://img.shields.io/badge/Feito_por-Pedr0sun-blue?style=for-the-badge)
![Badge](https://img.shields.io/badge/Python-3.x-yellow?style=for-the-badge)
![Badge](https://img.shields.io/badge/Status-Concluído-brightgreen?style=for-the-badge)
🛠 Tecnologias
- Python 3.x
- Biblioteca `random`
- Execução em terminal
# 🎯 Sobre o Projeto
Projeto simples para treinar **lógica de programação** e **estruturas condicionais**.  
O jogo segue as regras clássicas: Pedra > Tesoura, Tesoura > Papel, Papel > Pedra.  
---

## 📸 Desenvolvimento
# Versão 1 - Início do código
Primeira tentativa, sem opção de empate e apenas começando a estruturar a lógica.
![v1](https://github.com/user-attachments/assets/8d96ea47-36b6-4867-b520-983134cb027d)


---
# Versão 2 - Evolução com erros
Aqui tentei avançar, mas o código estava com problemas:
- Uso incorreto de `{}` (criando conjuntos em vez de strings).
- Uso errado de `random.random()` (não aceita parâmetros).
- Estrutura `if/elif` incorreta.
- Não havia tratamento de **empate**.
![v2](https://github.com/user-attachments/assets/0e479c26-4572-4228-8b0d-036e20a08e17)

---

# Versão 3 - Quase finalizado
Já estava funcionando melhor, porém:
- Ainda sem **armazenamento** de partidas.
- Algumas possibilidades não eram tratadas corretamente.
- Variáveis sem o devido `int` em alguns lugares.
![v3](https://github.com/user-attachments/assets/63bbef83-bef3-499b-b92b-bdcd70a9c374)

---

#Versão Final
Na versão final, o jogo está totalmente funcional:
- Escolha do jogador e da CPU.
- Tratamento de **todas as possibilidades**.
- Incluído caso de **empate**.
- **Histórico de partidas** armazenado em lista.
![Final](https://github.com/user-attachments/assets/93c37f3e-4b51-4f82-8d62-28d586006919)

---

## 🚀 Como Rodar
```bash
# Clone o repositório
git clone https://github.com/Pedr0sun/pedr0sun-rps.git

# Entre na pasta do projeto
cd rock-paper-scissors

# Execute o jogo
rock-paper-scissors.py

