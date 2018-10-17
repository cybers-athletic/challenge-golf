# <img src="https://avatars1.githubusercontent.com/u/42723118?s=200&v=4" alt="CA" width="24" /> Desafio Golf

## Introdução

A nossa Product Owner pensou em um produto fantástico para ser desenvolvido, e um dos desafios é criação de um jogo de Tarot.
<br>

**Então, essa é a sua missão!**

Criar um jogo de Tarot, permitindo o sorteio de uma carta.

E as especificações são:

- Tela de apresentação exibindo todas as cartas com seu conteúdo visível, e com um botão para iniciar o jogo.
- Ao clicar no botão, as cartas deverão ser viradas - escondendo o conteúdo - e embaralhadas.
- Permitir que o usuário selecione apenas uma carta, clicando na mesma.
- Apresentar a carta selecionada, o nome da carta e uma descrição. (a descrição pode ser um lorem ipsum)

OBS: As imagens e nomes das cartas estão listadas no arquivo [`tarot.json`](tarot.json), esse arquivo deve ser consumido via _http request_. A propriedade `image` de cada carta deve ser concatenada com a propriedade `imagesUrl`, para obter o endereço final da imagem. Utilize o valor da propriedade `imageBackCard` para obter a imagem do fundo da carta.


Você pode usar qualquer linguagem de programação para o desafio. Abaixo a lista de linguagens que nós aqui da CA temos mais afinidade:
- JavaScript
- Python
- Go
- Ruby
- C++
- PHP

Você pode usar qualquer _framework_. Se a sua escolha for por um _framework_ que resulte em _boilerplate code_, por favor assinale no README qual pedaço de código foi escrito por você. Quanto mais código feito por você, mais conteúdo teremos para avaliar.

## Requisitos
- Forkar esse desafio e criar o seu projeto (ou workspace) usando a sua versão desse repositório, tão logo acabe o desafio, submeta um *pull request* usando a branch resolucoes.
- O código precisa rodar em Windows, macOS ou Ubuntu
- Para executar seu código, deve ser preciso apenas rodar os seguintes comandos:
  - git clone $seu-fork
  - cd $seu-fork
  - comando para instalar dependências
  - comando para executar a aplicação



## Critério de avaliação

- **Organização do código**: Separação de módulos, view e model, back-end e front-end
- **Clareza**: O README explica de forma resumida qual é o problema e como pode rodar a aplicação?
- **Assertividade**: A aplicação está fazendo o que é esperado? Se tem algo faltando, o README explica o porquê?
- **Legibilidade do código** (incluindo comentários)
- **Histórico de commits** (estrutura e qualidade)
- **UX**: A interface é de fácil uso e auto-explicativa?

## Dúvidas

Quaisquer dúvidas que você venha a ter, consulte as [_issues_](https://github.com/cybers-athletic/challenge-golf/issues) para ver se alguém já não a fez e caso você não ache sua resposta, abra você mesmo uma nova issue!

Boa sorte! ;)

<p align="center">
  <img src="https://github.com/cybers-athletic/challenge-alpha/blob/master/ca.jpg?raw=true" alt="Challange accepted" />
</p>

## Créditos
Esse repositório foi baseado no [front-end-challenge](https://github.com/Personare/front-end-challenge) criado pela [Personare](https://github.com/Personare).
