Visualização
============

Para apenas visualizar um arquivo, basta clicar em seu nome a partir da página
do projeto no GitHub, mas **não na versão _mobile_** (o GitHub exibirá apenas o
código fonte na versão para celular). Confira o que há em cada arquivo:

* **Outliers.ipynb**: detecção de *pontos fora da curva* nos gastos da cota para
o exercício da atividade parlamentar.

Instalação
==========

Usaremos *virtualenv* para instalar pacotes Python na versão adequada dentro da
pasta *venv*.

Requisitos
----------
* Python 3.5.2 ou mais recente (não testado com versões anteriores)

Para instalar os demais requisitos, primeiro crie e ative o ambiente desta
pasta. Em Linux, execute:
```bash
pyvenv venv
source venv/bin/activate
```
Para Windows:
```bat
pyvenv venv
venv\Scripts\activate.bat
```

Atualize os pacotes básicos:
```
pip install --upgrade pip setuptools
```

Por fim, instale os demais requisitos:
```
pip install -r requisitos.txt --upgrade
```

Executando
==========
Caso ainda não tenha ativado o virtualenv na janela atual, ative-o:
```bash
# Para Linux
source venv/bin/activate
```
```bat
REM Para Windows
venv\Scripts\activate.bat
```

Depois, execute `jupyter notebook` e uma página abrirá no seu navegador.
Clique no arquivo _*.ipynb_ desejado para visualizá-lo.
Para executar o código e calcular os resultados novamente,
vá em *Cell*, clique em *Run all* e aguarde.
