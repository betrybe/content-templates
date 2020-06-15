# Boas vindas ao repositório do projeto de [PROJECT NAME]!

Você já usa o GitHub diariamente para desenvolver os exercícios, certo? Agora, para desenvolver os projetos, você deverá seguir as instruções a seguir. Fique atento a cada passo, e se tiver qualquer dúvida, nos envie por _Slack_! #vqv 🚀

Aqui você vai encontrar os detalhes de como estruturar o desenvolvimento do seu projeto a partir desse repositório, utilizando uma branch específica e um _Pull Request_ para colocar seus códigos.

---

## Instruções para entregar seu projeto:

### ANTES DE COMEÇAR A DESENVOLVER:

1. Clone o repositório
  * `git clone git@github.com:tryber/sd-0x-blockx-[project-name].git`.
  * Entre na pasta do repositório que você acabou de clonar:
    * `sd-0x-blockx-[project-name]`

2. Instale as dependências [**Caso existam**]
  * `npm install` [**exemplo**]

3. Crie uma branch a partir da branch `master`
  * Verifique que você está na branch `master`
    * Exemplo: `git branch`
  * Se não estiver, mude para a branch `master`
    * Exemplo: `git checkout master`
  * Agora crie uma branch à qual você vai submeter os `commits` do seu projeto
    * Você deve criar uma branch no seguinte formato: `nome-de-usuario-nome-do-projeto`
    * Exemplo: `git checkout -b joaozinho-[**project-name**]`

4. Adicione as mudanças ao _stage_ do Git e faça um `commit`
  * Verifique que as mudanças ainda não estão no _stage_
    * Exemplo: `git status` (deve aparecer listada a pasta _joaozinho_ em vermelho)
  * Adicione o novo arquivo ao _stage_ do Git
      * Exemplo:
        * `git add .` (adicionando todas as mudanças - _que estavam em vermelho_ - ao stage do Git)
        * `git status` (deve aparecer listado o arquivo _joaozinho/README.md_ em verde)
  * Faça o `commit` inicial
      * Exemplo:
        * `git commit -m 'iniciando o projeto x'` (fazendo o primeiro commit)
        * `git status` (deve aparecer uma mensagem tipo _nothing to commit_ )

5. Adicione a sua branch com o novo `commit` ao repositório remoto
  * Usando o exemplo anterior: `git push -u origin joaozinho-project-name`

6. Crie um novo `Pull Request` _(PR)_
  * Vá até a página de _Pull Requests_ do [repositório no GitHub](https://github.com/tryber/sd-0x-blockx-[project-name]/pulls)
  * Clique no botão verde _"New pull request"_
  * Clique na caixa de seleção _"Compare"_ e escolha a sua branch **com atenção**
  * Clique no botão verde _"Create pull request"_
  * Adicione uma descrição para o _Pull Request_ e clique no botão verde _"Create pull request"_
  * **Não se preocupe em preencher mais nada por enquanto!**
  * Volte até a [página de _Pull Requests_ do repositório](https://github.com/tryber/sd-0x-blockx-[project-name]/pulls) e confira que o seu _Pull Request_ está criado

---

# Entregáveis

Para entregar o seu projeto você deverá criar um Pull Request neste repositório. Este Pull Request deverá conter os arquivos `[Arquivos obrigatórios para concluri entrega]`, que conterão seu código `[Exemplo: HTML, CSS e JavaScript]`, respectivamente. Você pode adicionar outros arquivos se julgar necessário. ⚠️ É importante que seus arquivos tenham exatamente estes nomes! ⚠️

Você pode adicionar outros arquivos se julgar necessário. Qualquer dúvida, procure a monitoria. Lembre-se que você pode consultar nosso conteúdo sobre Git & GitHub sempre que quiser!

## ⚠️ É importante que seus arquivos tenham exatamente estes nomes! ⚠️ [Caso haja uma regra do tipo colocar especifique a desta forma]

Você pode adicionar outros arquivos se julgar necessário. Qualquer dúvida, procure a monitoria.

Lembre-se que você pode consultar nosso conteúdo sobre [Git & GitHub](https://course.betrybe.com/intro/git/) sempre que precisar!

---

### Data de Entrega

O projeto tem até a seguinte data: `DD/MM/YYYY - 14:00h`. Para ser entregue a avaliação final.


## Requisitos do projeto

### 💡Veja o exemplo a seguir de como o projeto pode se parecer depois de pronto. Lembre-se que você pode ~~e deve~~ ir além para deixar o projeto com a sua cara e impressionar à todos!

![exemplo do resultado](./resultadoFinal.gif)

## ⚠️ Leia-os atentamente e siga à risca o que for pedido. Em particular, **atente-se para os nomes de _ids_ que alguns elementos de seu projeto devem possuir**. ⚠️

O não cumprimento de um requisito, total ou parcialmente, impactará em sua avaliação.

---

### 👀Observações importantes:

  * [Caso necessario introdução de por onde estudante deve começar]

  * [Ou pontos de atenção sobre possiveis erros comuns ao tentar desenvolver] 

  * [Especifiques aqui desta forma]

## Requisitos Obrigatórios:

* Você vai ... [Descricão | Overview do que sera feito no projeto]

 **Em outras palavras, uma [aplicaçao de montar foguetes do Elon Musk].** 😜

### n - [Descrição do Requisito]

##### As seguintes verificações serão feitas:
- [**Pontos a serem validados neste requisito**]

- [**Pontos a serem validados neste requisito**]

- [**Pontos a serem validados neste requisito**]

### n + 1 - [Descrição do Requisito]

##### As seguintes verificações serão feitas:
- [**Pontos a serem validados neste requisito**]

- [**Pontos a serem validados neste requisito**]

- [**Pontos a serem validados neste requisito**]

### n + n - [Descrição do Requisito]

##### As seguintes verificações serão feitas:
- [**Pontos a serem validados neste requisito**]

- [**Pontos a serem validados neste requisito**]

- [**Pontos a serem validados neste requisito**]

## Requisitos Bônus:

### n - [Descrição do Requisito]

##### As seguintes verificações serão feitas:
- [**Pontos a serem validados neste requisito**]

- [**Pontos a serem validados neste requisito**]

- [**Pontos a serem validados neste requisito**]

---

## Dicas

- [Caso haja alguma dica de desenvolvimento]

- [Ou pontos para o estudante dar uma revisada para realizar este projeto]

- [Coloque os aqui]

---
### DURANTE O DESENVOLVIMENTO

* Faça `commits` das alterações que você fizer no código regularmente

* Lembre-se de sempre após um (ou alguns) `commits` atualizar o repositório remoto

* Os comandos que você utilizará com mais frequência são:
  1. `git status` _(para verificar o que está em vermelho - fora do stage - e o que está em verde - no stage)_
  2. `git add` _(para adicionar arquivos ao stage do Git)_
  3. `git commit` _(para criar um commit com os arquivos que estão no stage do Git)_
  4. `git push -u nome-da-branch` _(para enviar o commit para o repositório remoto na primeira vez que fizer o `push` de uma nova branch)_
  5. `git push` _(para enviar o commit para o repositório remoto após o passo anterior)_

---

### DEPOIS DE TERMINAR O DESENVOLVIMENTO (OPCIONAL)

Para sinalizar que o seu projeto está pronto para o _"Code Review"_ dos seus colegas, faça o seguinte:

* Vá até a página **DO SEU** _Pull Request_, adicione a label de _"code-review"_ e marque seus colegas:

  * No menu à direita, clique no _link_ **"Labels"** e escolha a _label_ **code-review**;

  * No menu à direita, clique no _link_ **"Assignees"** e escolha **o seu usuário**;

  * No menu à direita, clique no _link_ **"Reviewers"** e digite `students`, selecione o time `tryber/students-sd-0x`.

Caso tenha alguma dúvida, [aqui tem um video explicativo](https://vimeo.com/362189205).


---

### REVISANDO UM PULL REQUEST

Use o conteúdo sobre [Code Review](https://course.betrybe.com/real-life-engineer/code-review/) para te ajudar a revisar os _Pull Requests_.

#VQV 🚀
