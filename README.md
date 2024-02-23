### Desafio Cientista de Dados Indicium.

Desafio proposto pela Indicium para o programa Lighthouse. O objetivo é desenvolver um modelo de previsão de preços a partir do dataset oferecido, e avaliar tal modelo utilizando as métricas de avaliação que mais fazem sentido para o problema.

#### Instruções para execução do código.

Para execução com projeto, é necessário que sua máquina tenha instalado o python e seu gerenciador de pacotes, o pip. Assim podemos seguir os seguintes passos:

- Foram utilizadas as versões:
  - Python 3.9.18
  - Conda 22.11.1
  - Jupyter notebook 7.0.8

- Baixe o repositório em sua máquina, ou clone no terminal com o comando:

```
git clone https://github.com/Jtani/desafio_indicium-LH_CD_JOOJITANI.git
```

- Criação do ambiente virtual para instalação das dependências (se atente a versão do python utilizada)

- Com o ambiente já instalado e ativado, precisamos agora instalar as dependências, no jupyter notebook, digite:
```
!pip install -r requirements.txt
```

- Caso queira abrir o modelo em pickle basta digitar no notebook:

```
modelo = pickle.load(open(modelo_previsao.pkl', 'rb'))
```

As respostas de todas as questões estão no arquivo ipynb
