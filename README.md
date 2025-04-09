# pongAI

Pong com Machine Learning
Este repositório reúne um projeto que integra o clássico jogo de Pong com técnicas de Machine Learning por Reforço. O objetivo é treinar uma Inteligência Artificial (IA) para jogar Pong utilizando algoritmos como Q-Learning, permitindo posteriormente que o usuário jogue contra a IA treinada. Além disso, o projeto conta com uma interface visualmente atrativa e uma estrutura modular, ideal para estudos e inclusão em portfólios.

Visão Geral
Objetivo:
Desenvolver um jogo de Pong integrado com aprendizado por reforço, onde a IA é treinada para jogar e, em seguida, o usuário pode desafiar a IA.

Funcionalidades:

Jogo de Pong com gráficos e sons atrativos.

Treinamento da IA utilizando Q-Learning, com registro detalhado de métricas (número de episódios, recompensa, evolução das gerações, etc.).

Modo de jogo para partidas entre humano e IA.

Análise e visualização de dados do treinamento por meio de gráficos e notebooks.

Estrutura do Projeto

pong-ml/
├── docs/                  
│   └── projeto.pdf        # Documentação detalhada: diagramas, explicações, desafios e soluções
├── assets/                
│   ├── images/            # Recursos visuais: sprites, fundos
│   └── sounds/            # Efeitos sonoros e músicas de fundo
├── src/                   
│   ├── game.py            # Lógica do jogo: definição de bola, raquetes e renderização
│   ├── agent.py           # Implementação do agente de Q-Learning
│   ├── environment.py     # Ambiente estilo Gym para treinamento (reset, step, render)
│   ├── train.py           # Script para treinamento do agente e registro de métricas
│   ├── play.py            # Script para partida entre jogador e IA
│   └── utils.py           # Funções auxiliares (salvar/carregar métricas e logs)
├── notebooks/             
│   └── exploratory_analysis.ipynb   # Análises e visualizações dos dados do treinamento
├── requirements.txt       # Dependências do projeto (pygame, numpy, matplotlib, etc.)
└── README.md              # Visão geral, instruções de execução e contribuições


Tecnologias Utilizadas
Python: Linguagem de programação principal.

Pygame: Framework para desenvolvimento de jogos.

NumPy: Manipulação de arrays e cálculos.

Matplotlib: Visualização de dados e geração de gráficos.

Como Executar
Clone o repositório:


git clone https://github.com/seu_usuario/pong-ml.git


Instale as dependências:

cd pong-ml
pip install -r requirements.txt
Treinar a IA:

Execute o script de treinamento:

python src/train.py
Jogar contra a IA:

Após o treinamento, inicie o jogo para desafiar a IA:

python src/play.py
Documentação e Análises
Documentação Completa:
Consulte o diretório docs/ para um PDF com detalhes do projeto, fluxogramas e explicações sobre as escolhas de design e algoritmos utilizados.

Análise de Dados:
Utilize os notebooks em notebooks/ para visualizar as métricas de treinamento, como evolução da recompensa média e número de gerações necessárias para o aprendizado.

Contribuições
Contribuições e sugestões são muito bem-vindas! Se você deseja colaborar, abra uma issue ou envie um pull request com suas melhorias e novas funcionalidades.
