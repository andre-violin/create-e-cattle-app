<!-- ![Logo Create e-Cattle](assets/logo.png){style="display: block; margin: auto"} -->
<a href="https://www.npmjs.com/package/create-e-cattle-app">
    <img src="/assets/logo.png" alt="Create e-Cattle logo" title="Create e-Cattle" style="display: block; margin: auto" />
</a>

---

## Sobre o Create e-Cattle

Create e-Cattle é uma aplicação web que simplifica o processo de criação e configuração de aplicações micro-frontend integradas com Progressive Web App (PWA)  para a Plataforma e-Cattle.

Com ela é possível criar aplicações base, *host* e *remote*, utilizando a arquitetura de *module-federation* e *Progressive Web App* (PWA), para a Plataforma e-Cattle.

Os módulos foram desenvolvidos utilizando os principais conceitos arquiteturais de micro-frontend e tecnoplogias atuais para criação de aplicações como Vite, Vue.js, *module-federation* e PWA.

---

## Como usar

Antes de utilizar esta ferramente, o usuário deverá verificar se tem os seguintes recursos instalados em seu equipamento:
- Node.js
- Git

##### Os seguintes passsos deverão ser seguidos para utilizar adequadamente este gerador de projetos:

1. Abra o terminal/prompt de comando de sua preferência. Selecione um local em seu computador em que deseja criar o projeto e digite o seguinte comando:

    ```bash
    npx create-e-cattle-app
    ```

2. Em seguida, defina um nome para o projeto.

    ![Imagem mostrando o usuário definido o nome no terminal ou prompt de comando](assets/logo.png){style="display: block; margin: auto"}

3. O prõximo passo ~e escolher qual o tipo de projeto serã criado. São três opções para escolher: Base, Host e Remote.

    ![Imagem mostrando o usuário escolhendo o tipo do projeto no terminal ou prompt de comando](assets/logo.png){style="display: block; margin: auto"}

    - **Base:** Esta opção define uma base mínima para executar de forma integrada o *host* e o(s) *remote(s)*. O projeto Base conta apenas com um `package.json` com toda a estrutura e scripts para rodar os demais projetos (*host* e *remote(s)*) contidos nele um por um.
    - **Host:** Cria um projeto base com as configurações necessárias para que seja um micro-frontend integrando com tecnicas de aplicação *web* progressiva (pwa) que servirá como hospedeiro do(s) *remote(s)*. Já vem com alguns componentes internos (formulário de cadastro de usuário, formulário de *login*, menu de navegação e registro de aplicação) que poderão ser alterados a gosto do desenvolvedor.
    - **Remote:** Assim como a opção anterior, escolhendo essa opção será definido um projeto base com as configurações necessárias para que seja um micro-frontend integrado com tecnicas de aplicação *web* progressiva (pwa) para uma aplicação *remote*. Entretando essa aplicação não conta com componentes internos.

4. Por último, o usuário deverá escolher se quer que os módulos sejam instados imediatamente ou se ele fará isso em um momento posterior:

    ![Imagem mostrando o usuário escolhendo no terminal ou prompt de comando se os módulos serão intalados imediatamente ou não](assets/logo.png){style="display: block; margin: auto"}

  