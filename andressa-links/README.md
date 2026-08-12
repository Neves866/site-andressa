# Landing page — Andressa de Souza

Projeto estático criado com HTML e CSS puro.

## Como abrir

1. Abra a pasta no VS Code.
2. Clique duas vezes em `index.html`, ou use a extensão Live Server.
3. Para usar o Live Server:
   - instale a extensão **Live Server**;
   - clique com o botão direito em `index.html`;
   - escolha **Open with Live Server**.

## Como trocar as fotos

Salve as imagens dentro de:

`assets/images/`

Depois altere o `src` correspondente dentro do arquivo `index.html`.

Exemplo:

```html
<img src="assets/images/andressa-principal.webp" alt="Foto de Andressa de Souza">
```

Preferência de formato:

- `.webp` para melhor desempenho;
- foto principal na proporção aproximada de 4:5;
- largura entre 900 e 1400 pixels.

## Como trocar os links

No arquivo `index.html`, procure por:

```html
href="#"
```

Substitua `#` pelo endereço verdadeiro.

Exemplo para WhatsApp:

```html
href="https://wa.me/55DDDNUMERO"
```

Não coloque espaços, parênteses ou traços no número.

## Publicação

O projeto pode ser publicado gratuitamente no Cloudflare Pages usando o repositório do GitHub.
