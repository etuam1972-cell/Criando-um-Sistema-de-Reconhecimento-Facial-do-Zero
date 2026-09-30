Sistema de Reconhecimento Facial Multi-Face com TensorFlow e OpenCV

Este projeto implementa um pipeline completo de Detecção e Reconhecimento Facial em Python utilizando TensorFlow/Keras e OpenCV. O sistema é capaz de identificar e classificar múltiplas faces simultaneamente em uma única imagem.

📌 Arquitetura do Projeto

O sistema opera em duas etapas encadeadas:

Detecção Facial: Localiza todas as faces na imagem de entrada e gera as caixas delimitadoras (bounding boxes).

Classificação Facial: Recorta a região de interesse (ROI) correspondente a cada face detectada, pré-processa e aplica um modelo de aprendizado profundo (ex: MobileNetV2) para identificar o indivíduo e a probabilidade associada.

📁 Estrutura de Arquivos

.
├── main.py              # Script principal de execução e plotagem
├── requirements.txt     # Dependências do projeto Python
├── README.md            # Documentação do projeto
└── baixados.jpg         # Imagem de entrada/teste


🚀 Como Executar

1. Pré-requisitos

Certifique-se de ter o Python 3.8+ instalado em sua máquina.

2. Instalação das Dependências

Clone ou baixe o repositório, navegue até a pasta do projeto e instale os pacotes requeridos:

pip install -r requirements.txt


3. Execução do Script

Para rodar a detecção e exibir o resultado visual:

Criando um Sistema de Reconhecimento Facial do Zero.py


📊 Classes do Classificador

O modelo padrão suporta a identificação dos seguintes membros do elenco de The Big Bang Theory:

amy

bernadette

leonard

penny

raj

sheldon

🛠️ Tecnologias Utilizadas

TensorFlow / Keras: Construção e inferência da rede de classificação.

OpenCV: Processamento de imagem e detecção de faces (Haar Cascade / Deep Learning detector).

Matplotlib: Exibição e anotação gráfica dos resultados.

NumPy: Manipulação e matrizes de arrays de imagem.
