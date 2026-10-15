# Atividade prática — Landing Page EducaCão

**Objetivo:** reproduzir, com HTML e CSS, a imagem do site apresentada no PDF da aula. O projeto original é fictício e destinado a fins educacionais.

## Organização dos arquivos

```text
educacao_alunos/
├── index.html
├── css/
│   └── style.css
└── img/               ← copiar esta pasta do projeto original
    ├── golden.avif
    ├── adestrador1.avif
    ├── adestrador2.avif
    ├── adestrador 3.avif
    └── sobre.jpg
```

**Importante:** as imagens não acompanham este ZIP porque não foram enviadas nesta conversa. Use os arquivos de imagem originais com **exatamente os mesmos nomes**, incluindo o espaço no arquivo `adestrador 3.avif`. Caso os caminhos das imagens estejam diferentes na pasta original, ajuste-os apenas conforme necessário.

## Parte 1 — HTML

1. Abra o `index.html` no VS Code.
2. Procure cada `___` (três traços baixos). Substitua pelos textos que aparecem na imagem de referência do PDF.
3. Em cima de cada local há um comentário `<!-- ... -->` explicando que texto pertence ali, com até dois exemplos.
4. Conserve as tags HTML, classes (`class`), IDs (`id`), links internos (`href`), caminhos das fotos (`src`) e atributos de formulário (`name`, `type`).
5. Alguns símbolos decorativos, como `🐾`, `✓`, `→` e ícones de rede social, foram mantidos propositalmente para preservar o desenho.

## Parte 2 — CSS

1. Abra `css/style.css`. As declarações de estilo estão no formato `propriedade: ;` para você completar.
2. Acima **de cada propriedade** há uma explicação e três opções (**A, B, C**). **Uma delas é o valor utilizado no gabarito**; as demais são alternativas para comparar.
3. Escolha o valor que reproduz o efeito visual do PDF. Escreva-o entre `:` e `;`.
4. Exemplo: `position: ;` pode ser transformado em `position: sticky;` caso essa seja a sua escolha.
5. Comece por `:root` (cores e medidas), depois configurações gerais, cabeçalho, banner, serviços e demais seções. Por fim, ajuste as regras `@media` (responsividade).
6. A página estará visualmente **sem a formatação desejada** até que os valores CSS sejam preenchidos. Isso faz parte da atividade.

## Conferência da atividade

- Textos escritos no lugar dos `___`, seguindo a imagem.
- Visual semelhante ao PDF: cores, colunas, cartões, espaçamentos e botões.
- Menu com links para cada seção.
- Formulário com rótulos, entradas e seleção de serviço.
- Página utilizável no computador e no celular.

**Atenção:** o formulário é uma estrutura demonstrativa e ainda **não envia dados** ao servidor. Sua implementação com JavaScript e/ou back-end pode ser realizada em outra aula.
