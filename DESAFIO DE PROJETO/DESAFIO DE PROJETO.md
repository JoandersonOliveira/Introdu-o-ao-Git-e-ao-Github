# Introdu-o-ao-Git-e-ao-Github
Anotações do curso de introdução ao Git e Github da Dio.

##CRIANDO REPOSITÓRIO ON GITHUB

No canto superior direito da página tem um botão representado por um símbolo "+", após clicar nele pode clicar em "new repository".
Em seguida coloque um nome para o seu repositório e mais abaixo adicione uma descrição, esta fica gravada no arquivo readme.md posteriormente.
Defina se seu projeto vai ser público ou não. Ter em mente que uma vez público outros usuários da plataforma terão acesso ao repostório.
Em seguida marque a caixa "Add a README file" (opcional). Se marcar o github irá criar um arquivo .md no repositório com algumas informações do repositório.
Agora só clicar em "create repository."

###clonando para repositório local

Uma vez criado o repositório podemos clicar no botão "code" de cor verde no lado superior direito, escolher qual protocolo iremos utilizar para fazer a clonagem do repositório (HTTPS, SSH ou pelo GitHub cli). Selecione algum dos protocolos e copie o link.

Feito esse passo e com o terminal do Git instalado na sua máquina abra o mesmo dentro da pasta onde iremos importar o repositório. Digite no terminal o comando "git clone" e na frente desse comando digite um espaço e cole o link, pressione enter em segida. Feito.


##Principais comandos:

###Git Status
  permite inspecionar quais alterações foram despreparadas, quais não foram e quais arquivos não estão sendo monitorados pelo Git.

###Git clone
   baixar o código-fonte existente de um repositório remoto (como o Github, por exemplo).

###Git add
  Com este comando todas as alterações feitas no ambiente local são incluídas no próximo commit.

###Git diff
  Este comando permite saber exatamente o que você alterou (e não apenas quais arquivos foram alterados).

###Git commit
  Esse comando defini um ponto de verificação no processo de desenvolvimento, para o qual você pode voltar mais tarde, caso necessário.

###Git push
  Após confirmar as alterações, a próxima coisa que você deseja fazer é enviar as alterações para o servidor remoto usando o comando git push.

###Git pull
  O git pull é usado para obter atualizações do repositório remoto. 

Trata-se de um comando que depende do referencial de onde ele foi feito, ou seja, um git pull feito da sua máquina vai puxar informações do repositório original para ela. Mas um git pull feito a partir do repositório original vai puxar as informações da sua máquina. 




