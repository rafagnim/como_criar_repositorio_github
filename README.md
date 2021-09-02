# Como criar um repositório no Github

<h3>1) Instalar o GIT na máquina:</h3>

   [Faça o download e instalação](https://git-scm.com/downloads)

<h3>2) No GitHub:</h3>

**Create a new repository**

- Repository name
  Description
  Public / Private (Public para que outras pessoas possam acessar)
  
  Add a README file (para orientar quem acessar o repositório)
  
  pode ser editado no próprio GitHub
      
  Para mais informações sobre arquivo .md:
      
  [clique aqui](markdownguide.org/basic-syntax/)
           
   Ao alterar: commit changes
   
   Add .gitignore (para ignorar arquivos não essenciais ao versionamento)
   
   **-> Create a Repository**
   
  Code / clone (copiar para clonar na máquina)    

<h3>3) Na Máquina:</h3>

Obs.: GIT já deve estar instalado

Selecione uma pasta na máquina:

clique com o botão direito -> selecione *Git bash here*

ou via *"Prompt de Comando"*

digite: 

**git clone "link copiado acima"**


**git status**

Se incluir novos arquivos:

**git add .** (não esqueça de incluir o '.' (ponto)

**git commit -m "mensagem"**

**git push origin main** (para enviar para a nuvem)


Toda vez que acrescentar ou alterar arquivos,  faça os comandos a partir de git status
