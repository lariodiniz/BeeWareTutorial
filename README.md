# BeeWareTutorial
 Repositório contendo o código do tutorial do BeeWare que segui

## Passo a Passo para criar um projeto BeeWare (no windows)
 1 - crie um ambiente virtual (Eu utilizo o Anaconda)
 ```
 conda create --name NOMEDOAMBIENTE python=VERSAODOPYTHON
 ```

 2 - Instale o brifecase
 ```
 pip install briefcase
 ```
 
 3 - Inicie um novo projeto
 ```
 briefcase new
 ```
 Nota: Esse processo irá te fazer varias perguntas, responda elas de acordo com as informações do seu projeto.
 
 4 - Entre na pasta criada
 ```
 cd NOMEDAPASTA
 ```
 5 - Execute o Aplicativo em modo de desenvolvedor
 ```
 briefcase dev
 ```

## Passo a Passo para empacotar um projeto BeeWare (no windows)
 1 - crie os arquivos de configurações iniciais. na pasta do projeto execute:
 ```
 briefcase create
 ```

 2 - Construa seu aplicativo
 ```
 briefcase build
 ```

 3 - Execute o Aplicativo
 ```
 briefcase run
 ```

 4 - Empacote o Aplicativo
 ```
 briefcase package
 ```

 
## Passo a Passo para atualizar um projeto  já empacotado BeeWare (no windows)
 1 - Faça as modificações necessarias

 2 - Atualize seu aplicativo
 ```
 briefcase update
 ```
 Nota o update comando tem alguns comandos extras para situações especificas
     - Reinstalar Dependencias:
     ```
     briefcase update -d
     ```
     - Reinstalar Recursos:
     ```
     briefcase update -r
     ```

## Passo a Passo para empacotar um projeto BeeWare para android (no windows)
 1 - crie os arquivos de configurações iniciais. na pasta do projeto execute:
 ```
 briefcase create android
 ```

 2 - Construa seu aplicativo
 ```
 briefcase build
 ```

 3 - Execute o Aplicativo
 ```
 briefcase run android
 ```

 4 - Empacote o Aplicativo
 ```
 briefcase package
 ```
