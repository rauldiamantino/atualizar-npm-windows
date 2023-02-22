O Node já vem com o NPM ao ser instalado. 

Mas caso precise atualizar a versão do NPM no Windows, pode ser que retorne a mensagem `npm ERR! code EEXIST`

Para resolver acesse o diretório `C:\Users\yourUser\AppData\Roaming\nvm\vXX.XX.X)` e renomeie os arquivos:

- `npm -> npm2`
- `npm.cmd -> npm2.cmd`
- `npx -> npx2`
- `npx.cmd -> npx2.cmd`

Depois de renomear, execute o comando `npm2 install -g npm@X.XX.X`
