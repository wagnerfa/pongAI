# pongAI


#PONG COM MACHINE LEARNING


Este repositório contém um projeto que integra o clássico jogo de Pong com técnicas de Aprendizado por Reforço (Q-Learning).
A IA é treinada para jogar Pong e, posteriormente, o jogador pode desafiá-la. O projeto possui uma estrutura modular e uma 
interface visual atrativa, ideal para fins de estudo e portfólio.

----------------------------
🎯 OBJETIVO
----------------------------
- Desenvolver um jogo de Pong com IA treinada via aprendizado por reforço.
- Permitir o modo de jogo humano vs IA treinada.
- Documentar todo o processo de forma clara, com visualização de métricas.

----------------------------
🚀 FUNCIONALIDADES
----------------------------
- Jogo de Pong com gráficos e sons atrativos.
- Treinamento da IA utilizando Q-Learning com registro de métricas.
- Modo de jogo humano vs IA treinada.
- Visualização das recompensas, número de episódios e desempenho da IA.

----------------------------
📁 ESTRUTURA DO PROJETO
----------------------------

pong-ml/
├── docs/                          → Documentação (PDFs, diagramas, etc.)
│   └── projeto.pdf
├── assets/                        → Recursos visuais e sonoros
│   ├── images/                    → Sprites, fundos
│   └── sounds/                    → Efeitos sonoros
├── src/                           → Código-fonte principal
│   ├── game.py                    → Lógica do jogo (bola, raquetes, renderização)
│   ├── agent.py                   → Agente Q-Learning
│   ├── environment.py             → Ambiente tipo Gym para IA
│   ├── train.py                   → Treinamento da IA
│   ├── play.py                    → Modo jogador vs IA
│   └── utils.py                   → Utilitários (log, salvar métricas)
├── notebooks/                     → Análises e gráficos
│   └── exploratory_analysis.ipynb
├── requirements.txt               → Dependências do projeto
└── README.txt                     → Este arquivo

----------------------------
🧰 TECNOLOGIAS UTILIZADAS
----------------------------
- Python
- Pygame
- NumPy
- Matplotlib

----------------------------
▶️ COMO EXECUTAR
----------------------------

1. Clone o repositório:
   git clone https://github.com/seu_usuario/pong-ml.git

2. Acesse o diretório:
   cd pong-ml

3. Instale as dependências:
   pip install -r requirements.txt

4. Treine a IA:
   python src/train.py

5. Jogue contra a IA:
   python src/play.py

----------------------------
📊 DOCUMENTAÇÃO E MÉTRICAS
----------------------------
- Documentação técnica disponível na pasta 'docs/'
- Gráficos de desempenho e notebooks interativos em 'notebooks/'

----------------------------
🤝 CONTRIBUIÇÕES
----------------------------
Contribuições são bem-vindas! Envie um pull request ou abra uma issue com melhorias ou ideias.

----------------------------
📄 LICENÇA
----------------------------
Este projeto está licenciado sob a Licença MIT.


Análise de Dados:
Utilize os notebooks em notebooks/ para visualizar as métricas de treinamento, como evolução da recompensa média e número de gerações necessárias para o aprendizado.

Contribuições
Contribuições e sugestões são muito bem-vindas! Se você deseja colaborar, abra uma issue ou envie um pull request com suas melhorias e novas funcionalidades.
