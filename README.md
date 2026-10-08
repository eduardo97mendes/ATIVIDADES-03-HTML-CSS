# Atividade prática — Landing Page EducaCão

## 1. Desafio

Você foi contratado(a) para criar uma página inicial para a **EducaCão**, uma empresa fictícia de adestramento de cães.

Seu objetivo é construir uma landing page usando **HTML5 e CSS3**, praticando a estruturação de conteúdo, a escolha de imagens, a organização visual e a adaptação da página para diferentes tamanhos de tela.

> **Atenção:** os arquivos `index.html` e `css/style.css` são apenas pontos de partida. Há espaços e valores que você deverá completar. Não basta abrir a página: você precisa entender o que cada elemento e propriedade faz.

## 2. O que você deverá entregar

- [ ] Uma página com cabeçalho e navegação.
- [ ] Uma área principal de destaque (hero/banner).
- [ ] Uma seção com três serviços.
- [ ] Uma seção “Sobre a EducaCão”.
- [ ] Uma seção de diferenciais.
- [ ] Uma seção de depoimentos fictícios, identificados como conteúdo criado para a atividade.
- [ ] Uma seção de contato com formulário visual.
- [ ] Um rodapé.
- [ ] Imagens salvas na pasta `img/`.
- [ ] CSS organizado por seções.
- [ ] Layout adaptado para celular e computador.
- [ ] Arquivos salvos com os nomes e pastas indicados.

**Importante:** o formulário será apenas visual. Sem programação de servidor ou serviço externo, ele não enviará mensagens de verdade.

## 3. Estrutura de pastas

Organize seu trabalho desta forma:

```text
02-landing-page-educacao/
├── README.md
├── index.html
├── css/
│   └── style.css
└── img/
    ├── banner.jpg
    ├── sobre.jpg
    ├── servico-obediencia.jpg
    └── filhotes.jpg
```

Os nomes das imagens acima são sugestões. Se você escolher nomes diferentes, lembre-se de usar exatamente os mesmos nomes no HTML. Maiúsculas, minúsculas e extensões diferentes podem causar erros.

## 4. Antes de programar: planeje a página

A página deverá transmitir confiança, cuidado e acolhimento. Use os valores abaixo como **referência**, não como respostas obrigatórias.

| Elemento visual | Ideia de valor |
|---|---|
| Cor principal | Verde `#4CAF50` |
| Cor escura | Verde-escuro `#2E7D32` |
| Cor de destaque | Laranja `#FF9800` |
| Fundo suave | Creme `#FFF8E7` |
| Texto | Cinza bem escuro |
| Estilo | Cards com cantos arredondados e espaços confortáveis |
| Tipografia | Uma fonte para títulos e outra para textos |

Você pode usar essas sugestões ou pesquisar outras combinações. Mantenha contraste suficiente entre o texto e o fundo.

## 5. Pesquise e escolha as imagens

Você pode procurar imagens gratuitas em:

- [Unsplash](https://unsplash.com/)
- [Pexels](https://www.pexels.com/)
- [Pixabay](https://pixabay.com/)

Experimente pesquisar também em inglês:

| Uso na página | Termos para pesquisar |
|---|---|
| Banner principal | `golden retriever portrait`, `dog with owner` |
| Seção sobre | `dog trainer with dog` |
| Serviço de obediência | `dog obedience training` |
| Filhotes | `puppy in grass` |

### Como fazer

1. Pesquise uma imagem que combine com a seção.
2. Confira a licença e as condições de uso do site.
3. Prefira uma imagem nítida, sem marca-d'água e com enquadramento adequado.
4. Baixe a imagem para a pasta `img/`.
5. Se necessário, renomeie o arquivo com um nome curto e descritivo.
6. No HTML, indique o caminho relativo correto para a imagem.
7. Teste a página no navegador para confirmar que a imagem aparece.

Não use o endereço temporário de uma imagem encontrada no buscador se a proposta for manter o arquivo dentro do projeto. Salve a imagem localmente e utilize o caminho da pasta `img/`.

## 6. HTML: o que você precisa entender

O HTML define a **estrutura e o significado** do conteúdo. O CSS controla a **aparência e o posicionamento**.

### Elementos importantes

| Elemento | Para que serve |
|---|---|
| `<!DOCTYPE html>` | Informa ao navegador que o documento usa HTML5. |
| `<html>` | Elemento raiz da página. |
| `<head>` | Guarda metadados, título da aba e ligação com o CSS. |
| `<body>` | Contém o conteúdo visível da página. |
| `<header>` | Cabeçalho da página ou de uma seção. |
| `<nav>` | Área de navegação com links. |
| `<main>` | Conteúdo principal da página. |
| `<section>` | Agrupa conteúdo relacionado. |
| `<article>` | Conteúdo independente, como um card ou depoimento. |
| `<h1>` a `<h6>` | Títulos organizados por nível de importância. |
| `<p>` | Parágrafo. |
| `<a>` | Link para outra página ou para uma seção. |
| `<img>` | Exibe uma imagem. |
| `<form>` | Agrupa campos de formulário. |
| `<label>` e `<input>` | Identificam e recebem dados em campos. |
| `<button>` | Cria um botão. |
| `<footer>` | Rodapé da página ou de uma seção. |

### Tarefas de HTML

1. Abra `index.html` no VS Code.
2. Complete os espaços indicados no arquivo inicial.
3. Confira se a página possui um título na aba do navegador.
4. Crie textos próprios para cada seção. Não deixe textos de exemplo sem revisar.
5. Use títulos em uma ordem lógica: normalmente um `<h1>` principal e títulos `<h2>` para as grandes seções.
6. Adicione textos alternativos descritivos nas imagens usando `alt`.
7. Verifique se cada link tem um destino coerente.
8. Associe cada campo do formulário a um `<label>`.

### Ideias de conteúdo

- **Título principal:** “Mais que adestramento: uma relação melhor entre você e seu cão.”
- **Texto de apoio:** explique que o serviço oferece treinamento positivo e personalizado.
- **Serviços:** Adestramento Básico, Obediência e Comportamento, Educação de Filhotes.
- **Sobre:** explique a proposta da empresa fictícia.
- **Diferenciais:** métodos positivos, atendimento personalizado e cuidado com os animais.
- **Depoimentos:** invente exemplos para o exercício e identifique-os como fictícios.
- **Contato:** nome, e-mail, serviço de interesse e mensagem.

## 7. CSS: como preencher as propriedades

O CSS é composto, normalmente, por um **seletor**, seguido de chaves e declarações. Cada declaração contém uma propriedade e um valor.

Exemplo conceitual:

```css
seletor {
    propriedade: valor;
}
```

No arquivo inicial, os seletores e as propriedades já estão organizados. Sua tarefa é pesquisar, escolher e inserir valores adequados nos espaços em branco.

### 7.1 Cores — `color` e `background-color`

- `color` altera a cor do texto.
- `background-color` altera a cor de fundo.
- Você pode usar nomes (`white`), hexadecimal (`#FFFFFF`), RGB (`rgb(255, 255, 255)`) ou RGBA, que permite transparência.

Ideias para testar:
- `#4CAF50`
- `#2E7D32`
- `#FF9800`
- `#FFF8E7`
- `white`
- `rgb(40, 40, 40)`

Escolha cores que mantenham boa leitura. Não use a mesma cor para texto e fundo quando isso tornar o conteúdo ilegível.

### 7.2 Largura e altura — `width`, `max-width`, `min-height`

Essas propriedades controlam dimensões, mas não são equivalentes.

| Valor/unidade | Significado e exemplo de uso |
|---|---|
| `100%` | Ocupa toda a largura disponível do elemento pai. |
| `50%` | Ocupa metade da largura disponível do elemento pai. |
| `1200px` | Largura fixa de 1200 pixels CSS. Pode não caber em telas pequenas. |
| `20rem` | Dimensão baseada no tamanho da fonte raiz; útil para medidas escaláveis. |
| `80vw` | 80% da largura da janela do navegador. |
| `auto` | O navegador calcula o valor conforme as regras daquela propriedade. |
| `min-height` | Define uma altura mínima; o conteúdo ainda pode aumentar o elemento. |
| `max-width` | Limita a largura máxima para o conteúdo não ficar excessivamente largo. |

**Dica:** para conteúdo centralizado, uma combinação comum é usar uma largura relativa, uma largura máxima e margens automáticas. Pesquise como essas propriedades funcionam em conjunto e aplique no contêiner principal.

### 7.3 Espaçamento — `margin` e `padding`

- `margin`: espaço **fora** da borda do elemento.
- `padding`: espaço **entre o conteúdo e a borda**.
- `gap`: espaço entre itens de um layout flexível ou grid.

Unidades comuns:
- `px`: pixels CSS.
- `rem`: múltiplos do tamanho da fonte raiz.
- `%`: percentual relativo ao contexto definido pela propriedade.
- `em`: unidade relativa ao tamanho da fonte do elemento.

Experimente valores pequenos, médios e grandes. Por exemplo, compare `8px`, `16px`, `24px`, `1rem` e `2rem`, observando o resultado. Não existe um único valor correto para todas as situações.

### 7.4 Texto — `font-family`, `font-size`, `font-weight`, `line-height`

- `font-family`: escolhe a família tipográfica.
- `font-size`: define o tamanho do texto.
- `font-weight`: controla o peso, como normal ou negrito.
- `line-height`: controla a altura da linha e influencia a legibilidade.
- `text-align`: alinha o texto, por exemplo à esquerda ou ao centro.
- `text-decoration`: controla decorações, como o sublinhado de links.

Você pode experimentar tamanhos como `16px`, `1rem`, `1.25rem` e `2rem`. Para `font-weight`, teste `400`, `600` e `700`, lembrando que a fonte escolhida precisa oferecer esses pesos.

### 7.5 Bordas e cantos — `border`, `border-radius`, `box-shadow`

- `border`: define espessura, estilo e cor da borda.
- `border-radius`: arredonda os cantos. Teste `8px`, `16px`, `24px` ou `50%`, conforme o efeito desejado.
- `box-shadow`: cria sombra. Pesquise a ordem dos valores para deslocamento horizontal, deslocamento vertical, desfoque e cor.

Use sombras discretas e mantenha um estilo consistente entre os cards.

### 7.6 Layout com Flexbox

As propriedades de Flexbox ajudam a organizar itens em linha ou coluna.

- `display: flex`: ativa o layout flexível.
- `flex-direction`: define a direção, como linha ou coluna.
- `justify-content`: distribui os itens no eixo principal.
- `align-items`: alinha os itens no eixo transversal.
- `flex-wrap`: permite que os itens quebrem para outra linha.
- `gap`: define o espaço entre os itens.

Para estudar, teste valores como `row`, `column`, `center`, `space-between`, `stretch` e `wrap` nas propriedades em que fazem sentido. Observe como o layout muda.

### 7.7 Layout com Grid

CSS Grid é útil para organizar cards em colunas e linhas.

- `display: grid`: ativa o Grid.
- `grid-template-columns`: define a estrutura das colunas.
- `gap`: cria espaço entre linhas e colunas.

Pesquise como usar `repeat()`, `minmax()` e `auto-fit` para criar colunas flexíveis. Compare o resultado em uma tela larga e em uma tela estreita.

### 7.8 Imagens — `object-fit` e dimensões

- `width` e `height`: definem as dimensões da imagem.
- `object-fit: cover`: preenche a área definida, podendo cortar partes da imagem.
- `object-fit: contain`: mostra a imagem inteira dentro da área, podendo deixar espaços vazios.

Escolha a opção de acordo com a imagem e a seção. Confira se rostos ou partes importantes dos cães não foram cortados.

### 7.9 Botões e estados — `:hover` e `transition`

- `:hover` aplica estilos quando o ponteiro passa sobre o elemento.
- `transition` suaviza a mudança entre estados.

Crie um estado visual para o botão quando o ponteiro estiver sobre ele. Não dependa apenas da cor: mantenha contraste e indique claramente que o elemento é interativo.

### 7.10 Responsividade com media queries

Uma página responsiva se adapta a diferentes larguras de tela.

- `@media` permite aplicar regras quando uma condição de tela é atendida.
- Você pode reorganizar cards, reduzir espaçamentos, alterar tamanhos de texto e empilhar o conteúdo no celular.
- Não escolha um ponto de quebra sem testar. Redimensione a janela e observe quando o layout começa a ficar apertado.

Pesquise a sintaxe de `@media (max-width: ...)` e complete o bloco responsivo no arquivo CSS.

## 8. Roteiro de desenvolvimento

### Etapa 1 — Preparar o projeto
- [ ] Abra a pasta do projeto no VS Code.
- [ ] Confira a estrutura de pastas.
- [ ] Baixe e organize as imagens.

### Etapa 2 — Completar o HTML
- [ ] Preencha os metadados.
- [ ] Complete cabeçalho, navegação e banner.
- [ ] Complete os cards de serviços.
- [ ] Complete as seções sobre, diferenciais e depoimentos.
- [ ] Complete o formulário visual e o rodapé.
- [ ] Confira os caminhos das imagens e os destinos dos links.

### Etapa 3 — Completar o CSS
- [ ] Defina cores e tipografia.
- [ ] Ajuste o contêiner principal.
- [ ] Estilize cabeçalho, banner e botões.
- [ ] Organize os serviços com Flexbox ou Grid.
- [ ] Estilize as outras seções.
- [ ] Ajuste imagens, bordas e sombras.
- [ ] Crie regras responsivas.

### Etapa 4 — Testar e revisar
- [ ] Abra `index.html` no navegador.
- [ ] Confira se todas as imagens aparecem.
- [ ] Clique nos links e teste os estados dos botões.
- [ ] Verifique se não há rolagem horizontal indesejada no celular.
- [ ] Corrija erros e salve todos os arquivos.

## 9. Como investigar um problema

Se algo não funcionar, siga esta ordem:

1. Leia o nome da propriedade ou do elemento com atenção.
2. Confira se faltam `:`, `;`, aspas, parênteses ou chaves.
3. Confirme se o caminho da imagem está correto.
4. Confira se o HTML está ligado ao arquivo CSS.
5. Salve os arquivos e atualize o navegador.
6. Pesquise a propriedade pelo nome e consulte documentação confiável, como [MDN Web Docs](https://developer.mozilla.org/pt-BR/).

## 10. Desafio extra

Depois de concluir a página, escolha uma melhoria:
- Criar um menu que se reorganize em telas pequenas.
- Acrescentar uma seção de perguntas frequentes.
- Criar um efeito visual suave nos cards.
- Ajustar o contraste e a acessibilidade.
- Experimentar outra combinação de cores e justificar sua escolha.

## 11. Critérios de avaliação

| Critério | O que será observado |
|---|---|
| Estrutura HTML | Uso coerente de elementos semânticos e organização do conteúdo. |
| CSS | Propriedades preenchidas de forma adequada e código organizado. |
| Imagens e conteúdo | Imagens apropriadas, caminhos corretos e textos revisados. |
| Responsividade | Página utilizável em computador e celular. |
| Autonomia | Capacidade de testar, pesquisar, explicar escolhas e corrigir erros. |
| Organização | Arquivos e pastas nomeados corretamente. |

**Entrega:** salve o projeto completo na pasta indicada pelo professor e siga as orientações da turma para enviar ou publicar seu trabalho.
