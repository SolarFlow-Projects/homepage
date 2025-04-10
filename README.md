## Instalação

Para instalar as dependências necessárias, execute:

```bash
npm install
```

Este comando instalará o Tailwind CSS v4.1.3 e o CLI necessário para compilação.

## Compilação do Tailwind CSS

Para compilar o CSS do Tailwind e iniciar o modo de observação (watch mode), execute:

```bash
npx @tailwindcss/cli -i ./src/assets/css/input.css -o ./src/assets/css/output.css --watch --minify
```

ou

```bash
npm run compile:TW
```

Este comando:
- Usa o `@tailwindcss/cli` instalado
- Pega o arquivo de entrada `./src/assets/css/input.css`
- Gera um arquivo de saída em `./src/assets/css/output.css`
- Ativa o modo de observação para atualizar automaticamente quando houver mudanças
- Minifica o arquivo de saída para melhor performance