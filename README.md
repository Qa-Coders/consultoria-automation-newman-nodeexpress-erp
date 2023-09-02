# consultoria-automation-postman-nodeexpress-erp

## Consultoria automation postman nodeexpress erp
Este repositório tem uma página de publicação do "report" do teste que utiliza o Github Pages para servir páginas estáticas. Esse relatório será renovado todas as vezes que o teste for realizado.


# API-QA.CODERS
# AUTOMAÇÃO BACK-END

**PROJETO QA.CODERS ACADEMY - AUTOMAÇÃO DA API'S**
# HACKATHON

# :test_tube: Projeto de Testes Automatizados de API | Postman | JSON Schema | Newman | GitHub Actions :test_tube:
---
# :information_source: Introdução 
Esse projeto "consultoria-automation-newman-nodeexpress-erp", desenvolvido para um Hackathon de API do Qa.Coders Academy, é executado em um ambiente de desenvolvimento na API ["user"](https://develop.qacoders-academy.com.br/api/user/register), com o objetivo de nos aprofundarmos um pouco mais nos estudos sobre validações de testes de API (Ex.: JSON Schema, geração de massa de dados dinâmicos, etc) nas ferramentas Postman, Newman e GitHub Actions.

---
# :dart: Executar testes automatizados de API da collection e environment, Gerar e armazenar relatório html no GitHub Actions 
- Nesse repositório, acessar a aba "Actions"
- Na seção "Actions", clicar em "ERP Postman Automation API Test"
- Em "This workflow has a workflow_dispatch event trigger.", clicar em "Run workflow" > "Run workflow" para executar testes automatizados de API da collection e environment entre as requisições, Gerar e armazenar relatório html no GitHub Actions
- Após o término da execução, clicar na run "ERP Postman Automation API Test"
- Na seção "Artifacts", clicar em "report"
- Na janela aberta, escolher um diretório para baixar a pasta compactada "report.zip"

# :female_detective: Verificar no navegador padrão o relatório html gerado e armazenado anteriormente no GitHub Actions e descompactado no computador :male_detective: 
- Abrir uma janela do "Windows Explorer"
- Acessar o diretório onde foi baixada a pasta compactada "report.zip" anteriormente
- Descompactar a pasta
- Acessar a pasta descompactada "report"
- Clicar 2 vezes sob o relatório "index.html" gerado e armazenado anteriormente no GitHub Actions e descompactado para ser aberto e verificado no navegador padrão no computador

  
# :warning: Antes de clonar ou executar esse projeto localmente no computador, é necessário seguir as instruções abaixo :point_down:

## :hammer_and_wrench: Janela do "Windows Explorer", criar uma pasta "tools"
- Abrir uma janela do "Windows Explorer"
- Acessar o diretório "C:"
- Criar uma pasta "tools"


## :hammer_and_wrench: Cmder (Console Emulator)
- Baixar o [Console Emulator (cmder)](https://github.com/cmderdev/cmder/releases/download/v1.3.5/cmder.zip)
- Clicar com botão direito na pasta compactada > Extrair para "cmder"
- Mover a pasta descompactada "cmder" para o diretório "C:\tools" criado anteriormente
- Acessar o diretório "C:\tools\cmder"
- Clicar com botão direito no executável "cmder.exe" > Enviar para > Área de trabalho (criar atalho)
- Acessar a Área de Trabalho
- Clicar 2 vezes no atalho "Cmder - Atalho"
- Clicar na opção "Unblock and Continue"


## :hammer_and_wrench: Instalar as dependências necessárias 
### Desinstalar completamente Node.js e npm que já foram instalados em algum outro momento
- Seguir os passos apresentados nesse link ["COMO REMOVER COMPLETAMENTE O NODE.JS DO WINDOWS?"](https://acervolima.com/como-remover-completamente-o-node-js-do-windows/#:~:text=Pesquise%20por%20programa%20e%20recursos,js%20e%20desinstale-o.)
  
### Node versão 18.12.1
- Baixar e instalar o [node v18.12.1](https://nodejs.org/dist/v18.12.1/) > node-v18.12.1-x64.msi
- Abrir um novo cmder ou outro terminal de preferência
- Informar o comando abaixo para confirmar se o node realmente foi instalado
```
node --version
```
- Verificar se foi retornada a mesma versão do node instalada anteriormente
```
v18.12.1
```
- Informar o comando abaixo para confirmar se o npm realmente foi instalado
```
npm --version
```
- E verificar se foi retornada essa mesma versão do npm:
```
8.19.2
```

### newman
- No cmder ou terminal aberto anteriormente, informar o comando abaixo para instalar o newman
```
npm install -g newman
```
- Informar o comando abaixo para verificar se foi retornada alguma versão e confirmar se o newman realmente foi instalado
```
newman --version
```

### newman-reporter-htmlextra
- No cmder ou terminal aberto anteriormente, informar o comando abaixo para instalar o newman-reporter-htmlextra
```
npm install -g newman-reporter-htmlextra
```
- Informar o comando abaixo para verificar se foi retornada alguma versão e confirmar se o newman-reporter-htmlextra realmente foi instalado
```
newman-reporter-htmlextra --version
```
- Fechar esse cmder ou terminal

### Baixar, instalar e configurar o git
- Caso ainda não tenha o git baixado e instalado, acessar o site do [git](https://git-scm.com/download/win), baixar e instalar
- Caso ainda não tenha configurado o git, seguir os passos apresentados nesse link [Configure a ferramenta](https://training.github.com/downloads/pt_BR/github-git-cheat-sheet/#:~:text=Configure%20a%20ferramenta) e configurar


## :hammer_and_wrench: Clonar o projeto
- Abrir uma janela do "Windows Explorer"
- Acessar o diretório onde será clonado o projeto "consultoria-automation-newman-nodeexpress-erp"
- Copiar esse diretório 
- Abrir um novo cmder 
- Informar o comando abaixo para acessar onde será clonado o projeto
```
cd "<diretório copiado anteriormente>"
```
Ex.: 
```
cd "C:\PROJETOS\Automação\Postman"
```
- Informar o comando abaixo para clonar este repositório via "HTTPS"
```
git clone https://github.com/Qa-Coders/consultoria-automation-newman-nodeexpress-erp.git
```
- Ou informar o comando abaixo para clonar este repositório via "SSH"
```
git clone git@github.com:Qa-Coders/consultoria-automation-newman-nodeexpress-erp.git
```


# :dart: Executar testes automatizados de API da collection e environment e Gerar relatório diretamente no terminal no computador
- No cmder aberto anteriormente, informar o comando abaixo para acessar o projeto “consultoria-automation-newman-nodeexpress-erp”
```
cd "consultoria-automation-newman-nodeexpress-erp"
```
Ex.: 
```
C:\PROJETOS\Automação\Postman\consultoria-automation-newman-nodeexpress-erp
```
- Informar o comando abaixo para executar testes automatizados de API da collection e environment e Gerar relatório diretamente no terminal
```
newman run ./nome-collection.json -e ./nome-environment.json 
```
Ex.: 
```
newman run ./AutomacaoPartners.postman_collection.json -e ./Partners.postman_environment.json 
```

# :dart: Executar testes automatizados de API da collection e environment e Gerar relatório html na pasta "docs" no computador
- No cmder aberto anteriormente, informar o comando abaixo para executar testes automatizados de API da collection e environment e Gerar relatório html na pasta "report" no computador (comando semelhante ao que é utilizado no "Step 3" do "ERP Postman Automation API Test" em ".github > workflows > ci_ApiServerest.yml" no GitHub Actions)
```
newman run ./nome-collection.json -e ./nome-environment.json --reporters cli, -r htmlextra --reporter-htmlextra-export ./docs/nome-report.html
```
Ex.: 
```
newman run ./AutomacaoPartners.postman_collection.json -e ./Partners.postman_environment.json --reporters cli, -r htmlextra --reporter-htmlextra-export ./docs/index.html
```
- Fechar esse cmder

---
# :female_detective: Verificar no navegador padrão o relatório html gerado na pasta "docs" anteriormente no computador :male_detective: 
- Abrir uma janela do "Windows Explorer"
- Acessar o diretório onde foi clonado o projeto “consultoria-automation-newman-nodeexpress-erp”

Ex.: 
```
C:\PROJETOS\Automação\Postman\consultoria-automation-newman-nodeexpress-erp
```
- Acessar a pasta "docs" 
- Clicar 2 vezes sob o relatório "index.html" gerado anteriormente no computador para ser aberto e verificado no navegador padrão

---
### Feito com ❤️ por Andressa Karla, Camila Teixeira e Camila Aires :wave: 

### [![Linkedin](https://img.shields.io/badge/-LinkedIn-595D60?style=plastic&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/andressakarla//)](https://www.linkedin.com/in/andressakarla/) [![Linkedin](https://img.shields.io/badge/-LinkedIn-595D60?style=plastic&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/andressakarla//)](https://www.linkedin.com/in/camila-teixeira-05826a132/) [![Linkedin](https://img.shields.io/badge/-LinkedIn-595D60?style=plastic&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/andressakarla//)](https://www.linkedin.com/in/camiilaaires/)

---



