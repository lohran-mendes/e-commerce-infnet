# E-commerce Infnet

## Descrição

Este repositório contém o E-commerce Infnet. Ele é um projeto idealizado pelos alunos da Infnet com o objetivo de testar os seus conhecimentos sobre a area de TI simulando o ambiente de trabalho de uma equipe desenvolvedora.

Siga as instruções abaixo para clonar o projeto, criar uma nova branch(Ramo) e enviar suas alterações.

## Requisitos

Certifique-se de que você tem as seguintes ferramentas instaladas:

- [Git](https://git-scm.com/downloads)
- [VScode](https://code.visualstudio.com/)
- Conta no [GitHub](https://github.com/) com acesso a este repositório.

## Clonando o Repositório

Para clonar o repositório em sua máquina local:

1- Abra o terminal ou prompt de comando do seu VScode.
  
2- Execute o comando abaixo para clonar o repositório:
   ```bash
   git clone https://github.com/lohran-mendes/e-commerce-infnet.git
   ```

3- Entre no diretório do projeto:  
   ```bash
   cd e-commerce-infnet
   ```

## Mexendo com código!  

Para mexer com o código você sempre deve lembrar de criar a sua própria branch!

4- Criando uma Nova Branch  
    Antes de fazer qualquer modificação, crie uma nova branch para suas mudanças. Isso garante que o código principal se mantenha estável.  
    Crie uma branch com o nome da issue que você pegou, ou com o seu próprio nome caso não tenha pegado uma issue no quadro ainda.  
   ```bash
   git switch --create 'issue-0'
             ou
   git switch --create 'joao'
   ```

   5- Verifique que você está na branch correta  
    Execute esse comando para ir para a branch criada! 
   ```bash
   git switch 'issue-0'
   ```

## Terminei, quero mandar as atualizações

6- Enviando alterações  
    Depois que criar a sua branch você pode mexer no código como bem entender, mas depois que você terminar de fazer as suas tarefas você pode enviar as suas mudanças para o projeto.
   ```bash
   git add .
   git commit -m 'A sua mensagem explicando o que tem neste commit'
   git push origin nome-da-sua-branch
   ```

## Após fazer esse processo informe na sua Issue que você enviou atualizações que um responsável irá receber e atualizar o projeto com essas atualizações!
