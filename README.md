# Controle de Versionamento 


No desenvolvimento de um software, a equipe trabalha para implementar melhorias, adicionar novas funcionalidades, corrigir bugs e aprimorar o desempenho dos sistemas. É  um trabalho constante, e para fazer isso de uma forma eficiente proporcionando que diferentes desenvolvedores possam colaborar é preciso ter um controle de versões, para garantir que seja registrado todas as aterações realizadas no arquivo do código-fonte. Essas mudanças são armazenadas em ferramentas de controle de versão, como o Git, que permite que o desenvolvedor rastrei todas as versãos do projeto, podendo ter acesso de versões mais antigas facilmente.

___

## Git 

O Git é a ferramenta mais conhecida para controle de versões, ele disponibiliza funcionalidades como **branches** e **merges** que ajudam a gerenciar e organizar o desenvolvimento de software. 

1. Branches (Ramificações):
- São diferentes linhas de desenvolvimento que permitem que você trabalhe em diferentes partes de um projeto simultaneamente. Eles são essencialmente cópias independentes do código base que você pode modificar sem afetar o código principal.
  
2. Merges (Mesclagens):
- são o processo de integrar as mudanças de uma branch em outra. Normalmente, isso significa trazer as alterações de uma branch de funcionalidade para a branch principal (main ou master) depois que o desenvolvimento na branch de funcionalidade está concluído e testado.

___

## Github 

O GitHub é um serviço baseado em nuvem que hospeda os repositórios remontamente, os usuários do GitHub podem acompanhar e gerenciar as mudanças feitas para o código-fonte em tempo real, enquanto têm acesso a todos os outros recursos do Git disponíveis, podendo contribuir em projetos com acesso ou open source.

#### Para criar o repositório remoto é so criar a conta no Github, e seguir esses passos:

1. Clique em Create a repository (criar um repositório) para começar um novo projeto. 

![print criar repositório](https://www.hostinger.com.br/tutoriais/wp-content/uploads/sites/12/2019/01/create-repository-step-1-github.webp)

2. Escolha um nome de repositório. Confira se ele está definido para Public (público) para que ele tenha código aberto, e então marque a caixa Add a README file (adicionar um arquivo LEIA-ME). Finalmente, clique em Criar repositório.

![adicionar informações do repositório](https://www.hostinger.com.br/tutoriais/wp-content/uploads/sites/12/2019/01/criar-repositorio-github-readme.webp)

___

## README.md

O README.md é um arquivo com extensão .md (Markdown). Que contém informações necessárias para entender o objetivo do projeto. Podemos considerar o README como um cartão de visita do  projeto. Com um arquivo bem descrito — às vezes com imagens, vídeos ou gifs — o projeto tem mais relevância e deixa as pessoas mais aguçadas e curiosas para ler o código.

## Markdown 

O Markdown é uma ferramenta de conversão de texto em HTML. Você escreve usando texto simples de fácil leitura e fácil escrita e depois é transformado em um HTML válido.

___

### Comandos para subir o repositório local para o remoto: 

![print comandos](https://www.purin-it.com/wp-content/uploads/2021/09/add_main_sub_3.png)

___

### Comandos Git importantes

- git init : inicia um repositório git oculto na pasta criada
- git status: ver arquivos criados ou modificados
- git add .: para adicionar todos os arquivos que estão na sua pasta de uma vez
- git commit -m "mensagem": é usado para identificar  a alteração feita
- git push origin master: enviar as alterações feitas par a branch 


