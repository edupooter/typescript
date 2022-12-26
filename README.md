### TypeScript

Small example to show how TypeScript works.

Para criar um projeto TypeScript, você pode seguir os seguintes passos:

Instale o TypeScript usando o npm (gerenciador de pacotes do Node.js). Abra o terminal e execute o comando:

`npm install -g typescript`

Crie um novo diretório para o projeto e acesse-o.

Inicialize o projeto com o npm, executando o comando:

`npm init -y`

Isso criará um arquivo package.json com as configurações básicas do projeto.

Crie um arquivo tsconfig.json para configurar o compilador TypeScript. Você pode fazer isso executando o comando:

`tsc --init`

Isso criará um arquivo tsconfig.json com as configurações padrão para o projeto. Você pode personalizar essas configurações de acordo com suas necessidades.

Crie um arquivo de script TypeScript. Por exemplo, crie um arquivo chamado index.ts com o seguinte conteúdo:

```
function hello(name: string) {
  console.log(`Hello, ${name}!`);
}

hello('TypeScript');
```

Compile o arquivo TypeScript para JavaScript executando o comando:

```tsc```

Isso irá gerar um arquivo index.js com o código JavaScript equivalente.

Execute o script JavaScript usando o Node.js com o comando:

```node index.js```

Isso deve exibir a mensagem "Hello, TypeScript!" no console.

Esses são os passos básicos para criar um projeto TypeScript. Você pode adicionar mais arquivos TypeScript e configurar o projeto de acordo com suas necessidades. Além disso, é possível usar ferramentas como o create-react-app para criar projetos TypeScript com um conjunto de configurações já pré-definidas.
