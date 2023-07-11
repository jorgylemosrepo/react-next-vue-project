<h1>Projetos: React Vite, Vue e NextJS 💻</h1>
<p>📌 Cada projeto é independente, um não condiz com o outro.</p>
<p>📌 Cada projeto é um framework único!</p>

<section id="framework_docs">
    <h2>Documentação de cada framework: </h2>
    <ul>
        <li><a href="https://vitejs.dev/guide/" target="_blank">Vite</a></li>
        <li><a href="https://vuejs.org/guide/quick-start.html#creating-a-vue-application" target="_blank">Vue</a></li>
        <li><a href="https://nextjs.org/docs/getting-started/installation" target="_blank">Next</a></li>
        <li><a href="https://nuxt.com/docs/getting-started/installation" target="_blank">Opcional: Nuxt</a></li>
    </ul>
</section>

<h2>O que é necessário? 🔧</h2>
<h3>1. Primeiramente, é necessário instalar o NodeJS: (é recomendável instalar o LTS)</h3>

<a href="https://nodejs.org/en">Link para NodeJS</a>

<h3>2. Agora, é necessário instalar algum editor de código: (VSCode, SublimeText, Atom - Foi finalizado, mas tem seu repositório no github)</h3>

<ul>
    <li><a href="https://code.visualstudio.com/download" target="_blank">Link para VSCode</a></li>
    <li><a href="https://www.sublimetext.com/" target="_blank">Link para SublimeText</a></li>
    <li><a href="https://github.com/atom/atom" target="_blank">🔴 Link para o repositório oficial do Atom (Finalizado pelo desenvolvedor)</a></li>
</ul>


<h4><strong>Após seguir os passos anteriores, vamos entender os gerenciadores de pacotes.</strong></h4>
<h4>Lembre-se de estudar a documentação de cada gerenciador:</h4>
<section id="gerenciadores_docs">
    <ul>
        <li><a href="https://docs.npmjs.com/cli/v9" target="_blank">Documentação do npm</a></li>
        <li><a href="https://yarnpkg.com/getting-started/usage" target="_blank">Documentação do yarn</a></li>
        <li><a href="https://pnpm.io/pnpm-cli" target="_blank">Documentação do pnpm</a></li>
    </ul>
</section>
<p>
    Os principais gerenciadores de pacotes do Node.js são o npm (Node Package Manager), Yarn e Pnpm.
</p>
<p>
<strong>npm (Node Package Manager)</strong>: O npm é o gerenciador de pacotes padrão do Node.js e é amplamente utilizado na comunidade. Ele vem instalado por padrão junto com a instalação do Node.js.

Para verificar se o npm está instalado em seu sistema, abra o terminal e execute o seguinte comando:
```bash
npm --version
```
Se o npm estiver instalado, você verá a versão do npm sendo exibida.

<strong>Yarn</strong>: O Yarn é outro gerenciador de pacotes popular para projetos Node.js. Ele oferece recursos adicionais em relação ao npm, como instalações mais rápidas e eficientes, caching de pacotes e resolução de dependências mais confiável.

Para instalar o Yarn, você precisa ter o npm instalado em seu sistema. Abra o terminal e execute o seguinte comando para instalar o Yarn globalmente:
```bash
npm install -g yarn
```
Após a instalação, você pode verificar se o Yarn está instalado executando o seguinte comando:
```bash
yarn --version
```

<strong>pnpm</strong>: O pnpm é outro gerenciador de pacotes popular para projetos Node.js. Ele oferece uma abordagem alternativa para gerenciamento de pacotes, com foco em eficiência de espaço em disco e tempo de instalação.

O pnpm usa um mecanismo de links simbólicos para compartilhar pacotes instalados entre projetos. Isso significa que, em vez de duplicar pacotes em cada projeto, o pnpm cria links para uma única instância dos pacotes no sistema de arquivos. Isso resulta em economia de espaço em disco e redução no tempo de instalação.

Para instalar o pnpm, você precisa ter o npm instalado em seu sistema. Abra o terminal e execute o seguinte comando para instalar o pnpm globalmente:

```bash
npm install -g pnpm
```

Após a instalação, você pode verificar se o pnpm está instalado executando o seguinte comando:

```bash
pnpm --version
```
</p>

<h2>Como criar cada projeto?</h2>
<h3>1. React Vite:</h3>
<div>
<p>
Para criar um projeto React Vite, utilize o seguinte comando:

Com npm:
```bash
npm create vite@latest
```

Com Yarn:
```bash
yarn create vite
```

Com pnpm:
```bash
pnpm create vite
```

Logo após, siga as instruções dadas pelo próprio vite:
```bash
Project-name: "Aqui você coloca o nome do seu projeto"
Select a framework: "Opte por React"
Select a variant: "Opte por JavaScript, caso seja iniciante (recomendável)."
```

Logo após, seu projeto será criado.
E,após seu projeto ser criado, abra-o no VSCode.

Há duas possíveis maneiras de abrir:
<ul>
<li>1: Dentro da pasta do projeto criado, caso esteja no Windows, clique na barra de endereços/caminho e digite <strong>"cmd ."</strong> sem as aspas.
No cmd aberto, digite <strong>"code ."</strong> sem as aspas</li>
<li>2: Abra o VSCode, vá na aba <strong>Arquivo</strong>, depois <strong>Abrir Pasta</strong>, selecione a pasta do projeto no diretório à qual você criou.
</li>
</ul>
<section id="commands_install">
Instalar as dependências e iniciar o projeto: (Obs: o node_modules é deletado por padrão quando o projeto é enviado ao Github e, então, todas as vezes que baixar o projeto do repositório, é preciso instalar as dependências.)
    <ul>
        <li>1. Dentro do VSCode, vá na aba <strong>Terminal</strong>, depois clique em <strong>New Terminal</strong></li>
        <li>2. Utilize o gerenciador de pacotes de sua preferência para instalar as dependências. 
            <p>Para npm, yarn ou pnpm: <strong> npm | yarn | pnpm install</strong></p>
            <h4>Utilize apenas o gerenciador que você usa, por exemplo: <strong>yarn install</strong>! Lembrando, os gerenciadores possuem comandos específicos, leia a <a href="#gerenciadores_docs">documentação</a> de cada um para entender como funciona!</h4>
        </li>
        <li>
            3. Para iniciar o projeto utilize o comando: caso utilize npm: <strong>npm run dev</strong>, caso seja Yarn: <strong>yarn dev</strong> ou caso seja pnpm: <strong>pnpm run dev</strong>. Logo após, aparecerá o host e porta em que está rodando a sua aplicação. Vá no navegador, coloque o host e porta dado na url. 
            <p>
                Leia a <a href="https://vitejs.dev/guide/" target="_blank">documentação do framework</a> para entender como funciona o package.json, seus scripts e pacotes.
            </p>
        </li>
    </ul>
</section>
</div>

<h3>2. NextJS:</h3>
<div>
<p>
Para criar um projeto Next, utilize o seguinte comando:

```bash
npx create-next-app@latest
```

O npx é padrão do npm, não é preciso intalá-lo.

Logo após, siga as instruções dadas pelo próprio Next:
```bash
What is your project named? "Aqui você coloca o nome do seu projeto"
Would you like to use TypeScript? "Coloque No para utilizar Javascript"
Would you like to use ESLint? "Inicialmente, opte por No. Mas é bom aprender sobre o ESlint"
Would you like to use Tailwind CSS? "Opte por Yes, caso queira utilizar Tailwind para estilização. Pode optar por No caso queira CSS, SASS ou Styled-Components."
Would you like to use `src/` directory? "Inicialmente, opte por No. É bom aprender para que serve o src."
Would you like to use App Router? (recommended) "Opte por Yes, veja na documentação do Next o que é e para que serve."
Would you like to customize the default import alias? "Opte por No, inicialmente."
```

Logo após, seu projeto será criado.
E,após seu projeto ser criado, abra-o no VSCode.

Há duas possíveis maneiras de abrir:
<ul>
<li>1: Dentro da pasta do projeto criado, caso esteja no Windows, clique na barra de endereços/caminho e digite <strong>"cmd ."</strong> sem as aspas.
No cmd aberto, digite <strong>"code ."</strong> sem as aspas</li>
<li>2: Abra o VSCode, vá na aba <strong>Arquivo</strong>, depois <strong>Abrir Pasta</strong>, selecione a pasta do projeto no diretório à qual você criou.
</li>
</ul>

As dependências são instaladas por padrão pelo próprio Next. Caso tenha baixado o projeto do repositório Github, então sim, é preciso instalar as dependências seguindo o que foi dado no projeto anterior e, após instalar, volte aqui para iniciar o projeto com os comandos do próprio Next. <a href="#commands_install">Clique aqui</a> para ver os comandos para instalar as dependências.

Para iniciar o projeto utilize o comando: caso utilize npm: <strong>npm run dev</strong>, caso seja Yarn: <strong>yarn dev</strong> ou caso seja pnpm: <strong>pnpm run dev</strong>. Logo após, aparecerá o host e porta em que está rodando a sua aplicação. Vá no navegador, coloque o host e porta dado na url. 
<p>
    Leia a <a href="https://nextjs.org/docs/getting-started/installation" target="_blank">documentação do framework</a> para entender como funciona o package.json, seus scripts e pacotes.
</p>

</ul>
</div>

<h3>3. Vue:</h3>
<div>
<p>
Para criar um projeto Vue, utilize o seguinte comando:

```bash
npm init vue@latest
```

O npx é padrão do npm, não é preciso intalá-lo.

Logo após, siga as instruções dadas pelo próprio Next:
```bash
Project name: "Aqui você coloca o nome do seu projeto"
Add TypeScript? "Opte por No, se você quer usar Javascript"
Add JSX Support? "Opte por Yes"
Add Vue Router for Single Page Application development? "Opte por No, inicialmente. Olhe a documentação para entender o que é e como funciona."
Add Pinia for state management? "Opte por No, inicialmente. Olhe a documentação para entender o que é e como funciona."
Add Vitest for Unit testing? "Opte por No, inicialmente. Olhe a documentação para entender o que é e como funciona."
Add an End-to-End Testing Solution? "Opte por No, inicialmente. Olhe a documentação para entender o que é e como funciona."
Add ESLint for code quality? "Opte por No, inicialmente. Olhe a documentação para entender o que é e como funciona."
Add Prettier for code formatting? "Opte por Yes. Olhe a documentação para entender o que é e como funciona."
```

Logo após, seu projeto será criado.
E,após seu projeto ser criado, abra-o no VSCode.

Há duas possíveis maneiras de abrir:
<ul>
<li>1: Dentro da pasta do projeto criado, caso esteja no Windows, clique na barra de endereços/caminho e digite <strong>"cmd ."</strong> sem as aspas.
No cmd aberto, digite <strong>"code ."</strong> sem as aspas</li>
<li>2: Abra o VSCode, vá na aba <strong>Arquivo</strong>, depois <strong>Abrir Pasta</strong>, selecione a pasta do projeto no diretório à qual você criou.
</li>
</ul>

Instalar as dependências e iniciar o projeto: (Obs: o node_modules é deletado por padrão quando o projeto é enviado ao Github e, então, todas as vezes que baixar o projeto do repositório, é preciso instalar as dependências.). Após instalar, volte aqui para iniciar o projeto com os comandos do próprio Next. <a href="#commands_install">Clique aqui</a> para ver os comandos para instalar as dependências.

Para iniciar o projeto utilize o comando: caso utilize npm: <strong>npm run dev</strong>, caso seja Yarn: <strong>yarn dev</strong> ou caso seja pnpm: <strong>pnpm run dev</strong>. Logo após, aparecerá o host e porta em que está rodando a sua aplicação. Vá no navegador, coloque o host e porta dado na url. 
<p>
    Leia a <a href="https://vuejs.org/guide/quick-start.html#using-vue-from-cdn" target="_blank">documentação do framework</a> para entender como funciona o package.json, seus scripts e pacotes.
</p>

</ul>
</div>