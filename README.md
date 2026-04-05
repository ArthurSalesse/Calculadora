# Calculadora Web

Uma calculadora simples e funcional desenvolvida com HTML, CSS e JavaScript puro, com interface estilizada usando Bootstrap 4.

---

## Preview

> Interface escura com botões responsivos, display de resultado e suporte a operações básicas.

---

## Funcionalidades

- Operações básicas: adição (`+`), subtração (`-`), multiplicação (`x`) e divisão (`/`)
- Suporte a números decimais (`.`)
- Botão de limpar (`C`) para resetar o display
- Layout responsivo com Bootstrap 4
- Interface dark com design clean e sombras suaves

---

## Tecnologias Utilizadas

| Tecnologia | Versão |
|------------|--------|
| HTML5 | - |
| CSS3 | - |
| JavaScript | ES6+ |
| Bootstrap | 4.0.0-beta.2 |

---

## Estrutura do Projeto

```
calculadora/
└── index.html   # Arquivo principal com HTML, CSS e JS
```

---

## ▶Como Usar

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/calculadora.git
   ```

2. Acesse a pasta do projeto:
   ```bash
   cd calculadora
   ```

3. Abra o arquivo `index.html` diretamente no navegador — nenhuma instalação necessária.

---

## Como Funciona

A lógica da calculadora é baseada em uma única função `calcular(tipo, valor)`:

- **`tipo = 'valor'`** → adiciona o dígito ao display
- **`tipo = 'acao'`** → executa operações como `+`, `-`, `*`, `/`, `.`, `C` e `=`

O resultado é calculado com `eval()` aplicado sobre o conteúdo do campo de texto.

---

## Observações

- O projeto utiliza `eval()` para processar expressões matemáticas. Para ambientes de produção, recomenda-se substituir por uma solução mais segura (ex: biblioteca [math.js](https://mathjs.org/)).
- Compatível com navegadores modernos (Chrome, Firefox, Edge, Safari).

---

## Licença

Este projeto está sob a licença MIT. Consulte o arquivo [LICENSE](LICENSE) para mais detalhes.

---

## Autor

Feito com  por **Arthur Salesse Gonzaga**
