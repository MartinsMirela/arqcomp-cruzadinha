# Palavras Cruzadas: Arquitetura de Computadores

Jogo de palavras cruzadas feito com HTML, CSS e JavaScript puros, com 12 termos de arquitetura de computadores.

## Como jogar

1. Abra o arquivo `index.html` no navegador.
2. Leia as pistas das listas **Horizontais** e **Verticais**. O número de cada pista aparece na casa onde a palavra começa.
3. Clique numa casa do tabuleiro e digite a letra.
4. Clique em **Conferir** para ver quais palavras estão certas (verde) e quais estão erradas (vermelho).
5. Clique em **Reiniciar** para limpar o tabuleiro e tentar de novo.

## Funcionalidades

- Tabuleiro com 12 palavras que se cruzam entre si
- Pistas numeradas, separadas em Horizontais e Verticais
- Digitação direto nas casas do tabuleiro
- Botão **Conferir**, que mostra as palavras certas e erradas
- Contador de acertos (exemplo: "8 de 12 palavras")
- Botão **Reiniciar**, que limpa o tabuleiro

## Palavras do jogo

CPU, ULA, UC, REGISTRADORES, RAM, ROM, EEPROM, FLASH, CACHE, MEMORIADEMASSA, DMA e ADDRESSBUS.

As respostas são escritas em letras maiúsculas, sem acento e sem espaço.

## Tecnologias

- HTML
- CSS
- JavaScript 

## Estrutura do projeto

```
/
├── index.html   # página e código JavaScript do jogo
├── style.css    # estilos da página
└── README.md    # este arquivo
```

## Como o código funciona

- O vetor `palavras` guarda a resposta, a posição inicial, a direção e a pista de cada palavra.
- Uma matriz (`grade`) marca onde ficam as casas do tabuleiro.
- A função `conferir()` junta as letras digitadas em cada palavra, compara com a resposta e conta os acertos.
- A função `reiniciar()` apaga as letras, as cores e zera o contador.

## Como executar

Não precisa instalar nada. Baixe ou clone o repositório e abra o `index.html` no navegador.

```
git clone [https://github.com/MartinsMirela/arqcomp-cruzadinha.git]
```

## Autor
https://github.com/MartinsMirela 