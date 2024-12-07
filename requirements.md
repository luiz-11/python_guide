# Bibliotecas Necessárias para o Projeto Python Guide / Required Libraries for the Python Guide Project  

## 📦 Como Instalar as Bibliotecas / How to Install the Libraries  

Todas as bibliotecas necessárias estão listadas no arquivo `requirements.md`. Para que o `pip` consiga instalar as dependências, você precisará renomear o arquivo para `requirements.txt`. Para fazer isso, use o seguinte comando:  
All the required libraries are listed in the `requirements.md` file. For `pip` to install the dependencies, you need to rename the file to `requirements.txt`. To do this, use the following command:  

```bash
mv requirements.md requirements.txt
````

Após renomear o arquivo, para instalar todas as bibliotecas de uma vez, use:
After renaming the file, to install all libraries at once, use:

```bash
pip install -r requirements.txt
```

### Bibliotecas Incluídas / Included Libraries  
- **`jupyterlab==3.6.3`**: Para criar e editar notebooks interativos / For creating and editing interactive notebooks.  
- **`numpy==1.25.2`**: Operações com arrays e cálculos matemáticos / Array operations and mathematical calculations.  
- **`pandas==2.0.3`**: Manipulação e análise de dados / Data manipulation and analysis.  
- **`matplotlib==3.7.2`**: Criar gráficos e visualizações / For creating graphs and visualizations.  
- **`seaborn==0.12.2`**: Gráficos estatísticos avançados / Advanced statistical visualizations.  
- **`scipy==1.11.1`**: Ferramentas para computação científica / Tools for scientific computing.  

---  

## 🛠️ Passo a Passo para Configurar o Ambiente / Step-by-Step Guide to Set Up the Environment  

### 1. Instale o Python / Install Python  
Certifique-se de que o Python está instalado no seu computador. Baixe a versão mais recente aqui:  
Make sure Python is installed on your computer. Download the latest version here:  
[Baixar Python / Download Python](https://www.python.org/downloads/)  

### 2. Instale o Jupyter Notebook / Install Jupyter Notebook  
Depois de instalar o Python, instale o Jupyter Notebook com o comando:  
After installing Python, install Jupyter Notebook using the command:  

```bash
pip install jupyterlab
````

Para abrir o Jupyter Notebook, execute:  
To open Jupyter Notebook, run:  

```bash
jupyter notebook
````

Isso abrirá uma interface no navegador para acessar os notebooks do projeto.  
This will open a browser interface to access the project notebooks.  

### 3. Instale as Bibliotecas do Projeto / Install Project Libraries  
Para instalar todas as dependências, siga os passos abaixo:  
To install all dependencies, follow these steps:  
1. No terminal, navegue até o diretório onde está o arquivo `requirements.txt`.  
   In the terminal, navigate to the directory where the `requirements.txt` file is located.  
2. Execute o comando: / Run the command:  

```bash
pip install -r requirements.txt
````

Pronto! As bibliotecas estarão configuradas para uso.  
You're all set! The libraries will be ready to use.  

### 4. Links Úteis / Useful Links  
Se precisar de mais informações, aqui estão alguns recursos úteis:  
If you need more information, here are some helpful resources:  
- [Documentação do Jupyter Notebook / Jupyter Notebook Documentation](https://jupyter.org/documentation)  
- [Como instalar e usar o pip / How to Install and Use pip](https://pip.pypa.io/en/stable/installation/)  
- [Documentação do NumPy / NumPy Documentation](https://numpy.org/doc/)  
- [Documentação do Pandas / Pandas Documentation](https://pandas.pydata.org/docs/)  
- [Documentação do Matplotlib / Matplotlib Documentation](https://matplotlib.org/stable/contents.html)  
- [Documentação do Seaborn / Seaborn Documentation](https://seaborn.pydata.org/)  
- [Documentação do SciPy / SciPy Documentation](https://scipy.org/docs.html)  

### 5. Teste Sua Instalação / Test Your Installation  
Para verificar se tudo foi instalado corretamente, crie um notebook e execute este código:  
To check if everything was installed correctly, create a notebook and run this code:  
```python
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
import scipy

```bash
print("Todas as bibliotecas foram instaladas com sucesso!")  # Libraries installed successfully!
````

Se estiver tudo certo, você verá a mensagem:
If everything is correct, you'll see the message:
"Todas as bibliotecas foram instaladas com sucesso!" / "Libraries installed successfully!"
