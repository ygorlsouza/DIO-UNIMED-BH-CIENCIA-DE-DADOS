# Introdução ao Git 



##### Primeiros Comandos no windows usando cmd

- dir - lista de diretórios da pasta de onde você está.
- cd - change directory - navegar entre pastas usando a barra /
- cd ..  - volta para a pasta anterior, acima da que está
- cls - clear screen - limpa a tela retirando as informações
- tecla tab - autocompletar.
- mkdir - make directory - cria uma pasta
- echo - cria um arquivo / deve-se colocar a extensão - exemplo hello.txt
- del +nome da pasta - limpa os arquivos dentro da pasta
- rmdir +nome da pasta  /s /q - remove tudo, inclusive a pasta



##### Objetos internos do Git - Sistema distribuído Seguro

- Bloobs :arrow_down:
- Trees :arrow_down:
- Commits :arrow_down:

##### Primeiros comandos no git bash :nerd_face:

- git config --global user.email "*******@email.com" ➡️adiciona um email global
- git config --global user.name "*******" ➡️adiciona um usuario global


##### Criando um commit :nerd_face:
- git init
- git status
- git add * = adiciona tudo 
- git commit -m "mensagem/string motivo alteracao" 
- git remote add origin "https:// link do seu repositorio"

##### Passo a passo para enviar o arquivo commitado ao git hub :nerd_face:

  - abra a pasta/arquivo que você quiser enviar com o git bash
  - git status = para saber o status dos arquivos
  - git add arquivo = mudar o estado do arquivo para staged  ou git add . =para incluir tudo
  - git commit -m "mensagem"
  - git push origin main =para enviar seus commits 









