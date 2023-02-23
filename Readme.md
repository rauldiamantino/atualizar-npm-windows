O <i>Node.js</i> já vem com o <i>npm</i> ao ser instalado. Para atualizar só o <i>npm</i>, rode o comando: `npm2 install -g npm@X.XX.X`

Pode ser que retorne a mensagem:
  ```
  npm ERR! path C:\Program Files\nodejs\npm.cmd
  npm ERR! code EEXIST
  npm ERR! Refusing to delete C:\Program Files\nodejs\npm.cmd: is outside
  C:\Program Files\nodejs\node_modules\npm and not a link
  npm ERR! File exists: C:\Program Files\nodejs\npm.cmd
  npm ERR! Move it away, and try again.
  ```

Para resolver acesse o diretório `C:\Users\yourUser\AppData\Roaming\nvm\vXX.XX.X)` e renomeie os arquivos:

- `npm` -> `npm2`
- `npm.cmd` -> `npm2.cmd`
- `npx` -> `npx2`
- `npx.cmd` -> `npx2.cmd`

Depois de renomear, execute o comando `npm2 install -g npm@X.XX.X`

Volte no diretório `C:\Users\yourUser\AppData\Roaming\nvm\vXX.XX.X)` e exclua os arquivos `npm2`
