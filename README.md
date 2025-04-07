# Alpine.js Tests

Este projeto contém exemplos práticos de uso do Alpine.js, uma biblioteca JavaScript leve para manipulação de componentes reativos e interativos no front-end.

## Demonstração

Você pode acessar a demonstração ao vivo deste projeto no GitHub Pages:  
[https://unit-cesar.github.io/alpinejs-tests/](https://unit-cesar.github.io/alpinejs-tests/)

## Repositório

O código-fonte deste projeto está disponível no GitHub:  
[https://github.com/unit-cesar/alpinejs-tests](https://github.com/unit-cesar/alpinejs-tests)

## Funcionalidades

O projeto demonstra o uso das principais diretivas e propriedades mágicas do Alpine.js, incluindo:

### Diretivas

- **x-data**: Define o escopo de dados para componentes.
- **x-init**: Executa código ao inicializar o componente.
- **x-show**: Controla a visibilidade de elementos.
- **x-bind**: Vincula atributos HTML a expressões.
- **x-on**: Adiciona manipuladores de eventos.
- **x-text**: Insere texto dinâmico.
- **x-html**: Insere HTML dinâmico (com cuidado para evitar XSS).
- **x-model**: Vincula dados a elementos de formulário.
- **x-modelable**: Exposição de estado interno como modelo.
- **x-for**: Renderiza listas dinamicamente.
- **x-transition**: Adiciona transições animadas.
- **x-effect**: Executa código reativo baseado em dependências.
- **x-ignore**: Ignora elementos no escopo do Alpine.js.
- **x-ref e $refs**: Referencia elementos DOM.
- **x-cloak**: Evita flash de conteúdo não processado.
- **x-teleport**: Move elementos para fora do escopo atual.
- **x-if**: Adiciona ou remove elementos do DOM.
- **x-id e $id**: Gera IDs únicos para acessibilidade.

### Propriedades Mágicas

- **$el**: Referencia o elemento DOM atual.
- **$refs**: Acessa elementos marcados com `x-ref`.
- **$store**: Gerencia dados globais.
- **$watch**: Observa mudanças em propriedades específicas.
- **$dispatch**: Dispara eventos personalizados.
- **$nextTick**: Executa código após a atualização do DOM.
- **$root**: Acessa o elemento raiz do componente.
- **$data**: Retorna todos os dados do componente.
- **$id**: Gera IDs únicos.

## Como Usar

1. Clone o repositório:
   ```bash
   git clone https://github.com/unit-cesar/alpinejs-tests.gits
   ```
