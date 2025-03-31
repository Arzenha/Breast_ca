# Breast_ca

## Descrição
Este projeto realiza uma análise dos dados de câncer de mama. Ele inclui tratamento de dados, visualização de gráficos e criação de modelos preditivos. Os dados utilizados foram extraídos do Kaggle.

## Funcionalidades
- Tratamento e limpeza de dados.
- Análise exploratória dos dados com visualização gráfica.
- Criação e avaliação de modelos de machine learning para prever a presença de câncer de mama.

## Tecnologias Utilizadas
- **Jupyter Notebook**: Ferramenta utilizada para desenvolver e documentar o projeto.
- **Python**: Linguagem de programação principal utilizada no desenvolvimento do projeto.
- **Bibliotecas Python**:
  - `pandas`: Para manipulação e análise de dados.
  - `numpy`: Para operações numéricas.
  - `matplotlib` e `seaborn`: Para visualização de dados.
  - `scikit-learn`: Para criação e avaliação de modelos de machine learning.

## Pré-requisitos
- Python 3.x instalado na máquina.
- Jupyter Notebook instalado.
- Bibliotecas Python necessárias instaladas (pandas, numpy, matplotlib, seaborn, scikit-learn).

## Instalação
1. Clone o repositório para a sua máquina local:
    ```bash
    git clone https://github.com/Arzenha/Breast_ca.git
    ```
2. Navegue até o diretório do projeto:
    ```bash
    cd Breast_ca
    ```
3. Crie e ative um ambiente virtual (opcional, mas recomendado):
    ```bash
    python -m venv venv
    source venv/bin/activate  # No Windows, use `venv\Scripts\activate`
    ```
4. Instale as dependências necessárias:
    ```bash
    pip install pandas numpy matplotlib seaborn scikit-learn jupyter
    ```

## Como Usar
1. Inicie o Jupyter Notebook:
    ```bash
    jupyter notebook
    ```
2. Abra o arquivo `Breast_ca.ipynb` no Jupyter Notebook.
3. Execute as células do notebook para realizar a análise dos dados de câncer de mama.

## Estrutura do Projeto
- `Breast_ca.ipynb`: Notebook principal contendo o código para tratamento de dados, análise exploratória e criação de modelos.
- `data/`: Diretório contendo os dados utilizados no projeto.

## Contribuição
Se você deseja contribuir para o projeto, siga os passos abaixo:
1. Fork o repositório.
2. Crie uma nova branch:
    ```bash
    git checkout -b feature/nome-da-sua-feature
    ```
3. Faça as alterações necessárias e commit:
    ```bash
    git commit -m "Descrição das alterações"
    ```
4. Envie as alterações para o repositório remoto:
    ```bash
    git push origin feature/nome-da-sua-feature
    ```
5. Abra um Pull Request explicando as alterações feitas.

## Licença
Este projeto está licenciado sob a [Licença MIT](LICENSE).
