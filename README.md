# clone-tabnews
Implementação do tabnews como parte do estudo curso.dev

## configurando ambiente

Instalando a versão presente no `.nvmrc` que é a recomendada no curso.

```bash
nvm install
```

Trocar para a versão específica.

```bash
nvm use
```

Definir como versão padrão no ambiente.

```bash
nvm alias default $(cat .nvmrc)
nvm use default
```

Checando a versão do node

```bash
node -v
```

Instalando as dependências indicadas no `package-lock.json`

```bash
npm ci
```

Checando a versão das dependencias (devem ser as mesmas presentes no campo `dependencies` do arquivo `package.json`)

```bash
npm ls
```