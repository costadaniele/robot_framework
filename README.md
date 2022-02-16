# Robot framework

### 1. Instalar python 

   https://www.python.org/downloads/

### 2. Direcionar pasta do Python para a variável do sistema.

   - Editar as variáveis de ambiente do sistema.
   - Novo - copiar caminho da pasta do python. 

### 3. Abrir cmd - para verificar se a versão foi instalada

   `python --version`
   <br/>
   `pip --version`

## Instalação robot

   `pip install robotframework`
   <br/>
   `robot --version`
   
## Instalar webdriver 

   https://chromedriver.storage.googleapis.com/index.html?path=98.0.4758.102/
   
   - colocar na pasta que se encontra o python (extrair zip)
   - instalar
   - adicionar no path 

## Rodar robot no VSC - cmd
    
   - selecionar arquivo.robot
    
   - Selecionar opção colocando entre parênteses
    
   `- robot -d Results -t ' ' NomeDoArquivo.robot`
   
   - Selecionar todas as opções
   
   ` robot -d Results  NomeDoArquivo.robot `

## Outras extensões da framework

   `pip install robotframework-csvlib`
   <br/>
   `pip install --upgrade robotframework-seleniumlibrary`
   <br/>
   `pip install robotframework-faker`


### Erro screenshot no chrome

`pip install Pillow`
