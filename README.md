# Trabalho de robótica - 7
Este documento tem como objetivo apresentar o código produzido no trabalho 7.
## Execução
A forma mais simples de executar é com o seguinte comandos:
```bash
python3 calibration.py
```
Sem passar nenhum parametro, vai pegar as imagens do diretório `./images` ,
caso queira utilizar outro conjutno de imagens execute da seguinte forma:
```bash
python calibration.py --dir images_directory
```
### Depedencias
O programa faz uso de algumas biblioteca python, então é necessária instalar
elas antes de executar o softare.
#### Instalação via pipenv ( recomendado)
Para instalar via pipenv execute os seguintes comandos:
```bash
pipenv install
pipenv shell
```
#### Instalação via pip3
Para instala via pip3, instale os seguintes pacotes:
```bash
pip3 install opencv-python numpy
```
