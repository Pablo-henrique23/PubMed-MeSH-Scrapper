# MeSH Entry Terms String Generator
Recebe um link de uma doença do [MeSH](https://www.ncbi.nlm.nih.gov/mesh/), localiza os Entry Terms e cria uma string para ser utilizada no PubMed, além do link direto para o site.

Exemplo:
      ![Captura de tela em 2023-09-21 23-37-59](https://github.com/zecabum/MeSH-Entry-Terms-String-Generator/assets/105394456/d8453ab4-0fcb-4c9e-8b82-64a080e5889e)


## Requisitos
Python3 e [pip](https://pip.pypa.io/en/stable/)

## Instalação

### Windows
Baixe os arquivos pelo [link](https://www.github.com/zecabum/MeSH-Entry-Terms-string-generator/archive/refs/heads/main.zip) e extraia-os numa pasta

Depois disso, abra o CMD e use o comando ```cd``` seguido do caminho até a pasta em que os arquivos foram extraídos.

E finalmente
```bash
pip install -r requirements.txt
```
### Linux
Use ```git clone``` para fazer o download dos arquivos
```bash
git clone https://github.com/zecabum/MeSH-Entry-Terms-String-Generator.git
```
```bash
cd MeSH-Entry-Terms-String-Generator/
```
```bash
pip install -r requirements.txt
```
## Utilizaçao
### Windows
```bash
python main.py
```
### Linux
```bash
python3 main.py
```

## Erros
Durante a execução do script, pode ocorrer um erro de conexão devido à requisição que ele precisa fazer. Caso isso ocorra, apenas execute-o novamente, pois o erro deve sumir automaticamente após 1 ou 2 tentativas a mais.
