Gerenciador de Tarefas Modular

Um aplicativo de terminal interativo para gerenciamento de tarefas (To-Do List), construído 100% em Python. 

Este projeto evolui os conceitos de listas e loops ao introduzir a **Modularização**. Em vez de agrupar toda a lógica no menu principal, as operações foram separadas em funções dedicadas, resultando em um código mais limpo, sustentável e profissional.

 Funcionalidades (CRUD)

O sistema possui um menu interativo com as seguintes operações:
- **[C]reate:** Adiciona novas tarefas à lista com feedback visual.
- **[R]ead:** Exibe todas as tarefas cadastradas de forma formatada (inclui verificação de lista vazia).
- **[D]elete:** Remove tarefas específicas, com tratamento de erro para itens não encontrados.
- **UX/UI no Terminal:** Utiliza comandos matemáticos de impressão (`\n * 50`) para limpar a tela e pausas estratégicas (`input`) para melhorar a experiência do usuário.

 Tecnologias e Conceitos Utilizados

- **Python 3**
- Modularização com Funções (`def`, passagem de parâmetros)
- Estruturas de Dados (`Listas`)
- Estruturas de Repetição (`while True`, `for`)
- Estruturas Condicionais (`if`, `elif`, `else`)
- Interação avançada de terminal (Limpeza de tela e pausas de leitura)

 Como executar o projeto

1. Certifique-se de ter o Python instalado na sua máquina.
2. Clone este repositório ou baixe o arquivo principal (ex: `pytask.py`).
3. Abra o terminal e rode o comando:
   ```bash
   python pytask.py
