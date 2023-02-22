Ao atualizar a versão do npm para `8.12.1` no Windows, pode ser que retorne a mensagem `npm ERR! code EEXIST`

Para resolver acesse o diretório `C:\Users\yourUser\AppData\Roaming\nvm\v14.17.0)` e renomeie os arquivos:

`npm -> npm2`
`npm.cmd -> npm2.cmd`
`npx -> npx2`
`npx.cmd -> npx2.cmd`

Depois de renomear, execute o comando `npm2 install -g npm@8.12.1` para atualizar o NPM
