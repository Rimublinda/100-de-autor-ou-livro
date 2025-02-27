# 📚 Repositório de Frases de Autores Famosos

Bem-vindo ao repositório que reúne frases inspiradoras, reflexivas e marcantes de autores famosos! O objetivo deste projeto é coletar **100 frases** de cada autor, criando um acervo rico para consulta, estudo ou inspiração. Todas as frases estão organizadas em um arquivo JSON para facilitar o acesso e a manipulação dos dados.

---

## 🎯 Objetivo

Este projeto visa:
- Compilar frases significativas de autores consagrados.
- Facilitar o acesso a pensamentos e ideias de grandes mentes.
- Criar um repositório colaborativo e aberto para entusiastas de literatura, filosofia e cultura.

---

## 📂 Estrutura do Repositório

As frases estão armazenadas em uma pasta com seu nome e nela vai ter um arquivo JSON (`frases.json`), onde cada autor é um objeto com as seguintes propriedades:
- `nome`: Nome do autor.
- `biografia`: Breve descrição sobre o autor.
- `frases`: Lista de frases (a meta é 100 frases por autor).

Exemplo de estrutura do JSON:
```json
{
  "autores": [
    {
      "nome": "Machado de Assis",
      "biografia": "Machado de Assis foi um escritor brasileiro, considerado um dos maiores nomes da literatura nacional.",
      "frases": [
        "A vida não é mais que um sonho; mas nesse sonho não há nem riso nem prazer.",
        "A ocasião faz não só o ladrão, mas o herói."
      ]
    },
    {
      "nome": "Clarice Lispector",
      "biografia": "Clarice Lispector foi uma escritora e jornalista brasileira, conhecida por sua prosa introspectiva e inovadora.",
      "frases": [
        "Liberdade é pouco. O que eu desejo ainda não tem nome.",
        "Renda-se, como eu me rendi. Mergulhe no que você não conhece como eu mergulhei."
      ]
    }
  ]
}
