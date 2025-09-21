# rock-paper-scissors.py
#🌑📄✂ Pedra, Papel e Tesoura – Python | Treino de lógica ,estruturas condicionais e aplicação de listas e random.

![Badge](https://img.shields.io/badge/Feito_por-Pedr0Taker-blue?style=for-the-badge)
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
![v1](https://github.com/user-attachments/assets/8eb7f8fd-eb60-442f-93ed-c1f19c244e5d)

---
# Versão 2 - Evolução com erros
Aqui tentei avançar, mas o código estava com problemas:
- Uso incorreto de `{}` (criando conjuntos em vez de strings).
- Uso errado de `random.random()` (não aceita parâmetros).
- Estrutura `if/elif` incorreta.
- Não havia tratamento de **empate**.
![v2](https://github.com/user-attachments/assets/3a3d06e4-fb23-40f1-9587-56ca27fe4c54)

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

---

## 🚀 Como Rodar
```bash
git clone https://github.com/Pedr0Taker/pedr0taker-rps.git
cd pedr0taker-rps
python pedra_papel_tesoura.py

