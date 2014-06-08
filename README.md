Videolog-embed
=====================

Web Component para incorporar vídeos do [Videolog](http://videolog.tv).

## Instalação ##

```sh
$ bower install videolog-embed --save
```

## Utilização ##

1. Importe o Platform, polyfill para Web Components:

    ```html
    <script src="bower_components/platform/platform.js"></script>
    ```

2. Importe o Videolog-embed no `<head>`:

    ```html
    <link rel="import" href="bower_components/videolog-embed/elements/videolog-embed.html" />
    ```

3. Comece a usar!

    ```html
    <videolog-embed url="http://videolog.tv/348985"></videolog-embed>
    ```

## Opções ##

| Parâmetro | Tipo | Padrão | Descrição |
| --------- | ---- | ------ | --------- |
| url | string | null | URL do vídeo |
| vid | string | 671092 | ID do vídeo (pode ser substituído pela URL) |
| width | float | 500 | Largura do player (em pixels) |
| height | float | 281.25 | Altura do player (em pixels) |
| preload | boolean | false | Define se o vídeo deve ser pré-carregado logo que a página for exibida |

## Licença ##

Este projeto está disponível sob a licença [MIT](http://choosealicense.com/licenses/mit/). 
