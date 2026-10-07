# Hello World — Cultura e Práticas DevOps

Projeto inicial da disciplina Cultura e Práticas DevOps (UNIPÊ). É uma página HTML simples que exibe "Hello, World!", criada para praticar o fluxo básico de versionamento com Git e a publicação de um repositório no GitHub.

## Pré-requisitos

Antes de começar, você precisa ter instalado:

* **Git:** para clonar o repositório.
* **Navegador web:** Google Chrome, Firefox, Edge ou Safari atualizados.
* **Editor de código (opcional):** Visual Studio Code com a extensão *Live Server*.

## Passo a passo de instalação

1. Clone este repositório para a sua máquina:

```bash
git clone https://github.com/PlinioFdev/hello-world-devops.git
```

2. Acesse a pasta do projeto:

```bash
cd hello-world-devops
```

3. Abra o arquivo `HelloWorld.html` no navegador, ou abra a pasta no VS Code e clique em **Go Live**:

```bash
code .
```

## Exemplos de uso

* **Visualização:** ao abrir a página, o título "Hello, World!" é exibido no centro da tela.
* **Interação:** clique no botão **Dizer olá** para exibir uma mensagem abaixo dele.

Trecho de JavaScript responsável pela interação:

```javascript
const botao = document.querySelector('#btn-ola');
const mensagem = document.querySelector('#mensagem');

botao.addEventListener('click', () => {
  mensagem.textContent = 'Olá! Este é o meu primeiro repositório da disciplina.';
});
```

## Estrutura do projeto

```
hello-world-devops/
├── HelloWorld.html   # página principal
└── README.md         # documentação do projeto
```

## Autor

Plinio — Ciência da Computação, UNIPÊ
[github.com/PlinioFdev](https://github.com/PlinioFdev)
