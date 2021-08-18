ATIVIDADE ORIENTADA: GIT E GIT HUB
Realize as atividades como se pede
1. Criando os arquivos
Crie uma pasta com o nome do projeto (a sua escolha) e um arquivo chamado index.html
Adicione o seguinte conteúdo ao arquivo:
<!DOCTYPE html>
<html lang="pt-br">
  <head>
    <title>Título da página</title>
    <meta charset="utf-8">
  </head>
  <body>
    <h1>Aqui vai um título</h1>
  </body>
</html>

2. Subindo seu projeto para o GitHub
Crie um repositório em seu GitHub
Abra o seu terminal de comando e adicione a origem remota e conecte seu projeto local com o GitHub
Verifique as alterações do seu projeto e adicione ao fluxo de versionamento
Faça um commit com uma mensagem útil e na sequência, um push para o repositório remoto (GitHub)

3. Tratando alterações 
Abra a pasta do seu projeto, crie uma pasta chamada imagens, procure no Google por uma imagem de gato e salve dentro dessa nova pasta. Feito isso, abra seu arquivo index.html e adicione as seguintes modificações e salve o arquivo:


 
<!DOCTYPE html>
<html lang="pt-br">
  <head>
    <title>Fanpage de Gatinhos</title>
    <meta charset="utf-8">
  </head>
  <body>
    <h1>Perfil #catsoninstagram</h1>
    <img src="images/nome_da_sua_imagem.jpg" />
  </body>
</html>

Repita os passos 2 e 3 do item 2.

4. Criando um arquivo não rastreável
Acesse a pasta do projeto que você criou no exercício 1 e crie um arquivo chamado minhas_senhas_secretas.txt
Abra o terminal e veja se o arquivo está aparecendo como não rastreado e que pode ser adicionado (dica)
Gerando o .gitignore
Crie o arquivo .gitignore e salve-o na raiz do projeto (ele deverá aparecer no mesmo nível dos arquivos index.html e da pasta imagens)
Abra o arquivo .gitignore, digite minhas_senhas_secretas.txt e salve-o
No terminal, digite novamente o comando para verificar o status dos arquivos e note que o minhas_senhas_secretas.txt não aparece mais.

5. Publicando .gitignore
No terminal, rode os comandos:
git add para adicionar o arquivo
git commit para commitar o novo arquivo, sem esquecer de adicionar uma mensagem útil e informativa sobre o que será publicado
git push para enviar para o repositório no GitHub

6. Repositório
Crie um novo repositório no GitHub com nome que desejar e marque para criar o arquivo README.md
Faça um clone deste repositório em sua máquina
Abra o arquivo README.md com o editor de código de sua preferência e faça algumas alterações no texto
Em seu terminal, rode os comandos:
git add para adicionar o arquivo
git commit para commitar o novo arquivo, sem esquecer de adicionar uma mensagem útil e informativa sobre o que será publicado
git push para enviar para o repositório no GitHub
7. Branchs
Crie uma nova branch , chamada versao01 e faça algumas alterações no README.md
Em seu terminal, rode os comandos:
git add para adicionar o arquivo
git commit para commitar o novo arquivo, sem esquecer de adicionar uma mensagem útil e informativa sobre o que será publicado
git push para enviar para o repositório no GitHub
Repita este passo para criar mais duas branchs, chamadas versao02 e versao03, respectivamente.

Data da atividade: 17.08.21

01 - VERSÃO 01 - TESTE
02 - VERSÃO 02 - TESTE
03 - VERSÃO 03 - TESTE