# Amigo Secreto

Este projeto é uma aplicação simples de sorteio de Amigo Secreto, desenvolvida com HTML, CSS e JavaScript. Permite adicionar nomes de amigos a uma lista, realizar o sorteio e definir quem tirou quem, além de reiniciar o processo, limpando a lista de amigos e os resultados do sorteio.

## Funcionalidades

- **Adicionar Amigos**: Permite ao usuário adicionar novos nomes à lista de amigos para o sorteio.
- **Realizar Sorteio**: Ao clicar em "Sortear", o sistema gera um pareamento aleatório entre os amigos da lista, indicando quem tirou quem.
- **Reiniciar Sorteio**: É possível reiniciar todo o processo, limpando a lista de amigos e os resultados do sorteio.

## Estrutura do Projeto

```bash
amigo-secreto/
│
├── assets/
│   └── imagem-presente.png  # Imagem decorativa de um presente
│
├── js/
│   └── app.js               # Lógica para adicionar amigos, realizar o sorteio e reiniciar
│
├── index.html               # Página principal da aplicação
├── styles.css               # Estilos principais da página
└── README.md                # Documentação do projeto
```

## Como Usar

1. Clone o repositório:
    ```bash
    git clone https://github.com/glelisv/amigo-secreto.git
    ```
2. Abra o arquivo `index.html` em qualquer navegador para acessar a aplicação do sorteio de Amigo Secreto.

## Tecnologias Utilizadas

- **HTML5**: Estrutura do conteúdo e dos elementos da aplicação.
- **CSS3**: Estilização e layout visual da interface.
- **JavaScript (ES6)**: Lógica para manipular a lista de amigos, realizar o sorteio aleatório e reiniciar o processo.

## Detalhes do Projeto

### Página Principal (`index.html`)

A página oferece a interface para o usuário:
- **Adicionar Amigos**: Campo de texto para digitar o nome e um botão para adicionar o nome à lista de amigos.
- **Lista de Amigos**: Exibe os amigos que foram adicionados para o sorteio.
- **Botão de Sorteio**: Ao clicar, realiza o sorteio e mostra quem tirou quem.
- **Botão de Reiniciar**: Limpa a lista de amigos e os resultados, permitindo que o usuário comece um novo sorteio.

### Estilos (`styles.css`)

O arquivo `styles.css` define o design da aplicação:
- Layout simples e intuitivo para adicionar amigos e visualizar o resultado do sorteio.
- Inclui uma imagem decorativa de um presente (localizada na pasta `assets`) para dar um toque visual ao tema do Amigo Secreto.

### Lógica do Sorteio (`app.js`)

O arquivo `app.js` contém toda a lógica da aplicação:
- **Adicionar Amigos**: Função que permite adicionar novos nomes à lista e os exibe na interface.
- **Realizar Sorteio**: Função que sorteia os amigos de forma aleatória, garantindo que ninguém tire a si mesmo.
- **Reiniciar Sorteio**: Função que limpa a lista de amigos e os resultados, permitindo que um novo sorteio seja realizado.