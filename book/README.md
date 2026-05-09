# 📖 Lex Divina

> *"Mas tem o seu prazer na lei do Senhor, e na sua lei medita de dia e de noite."*
> — Salmo 1.2

**Lex Divina** é um livro colaborativo e de domínio público com meditações
práticas sobre a Lei do Senhor, organizado por temas da vida cristã.

---

## O que é este livro?

O Lex Divina não é um catecismo, nem um manual teológico, nem um substituto
para a pregação ou o aconselhamento pastoral. É um **recurso de apoio à
meditação** — uma coleção viva de textos bíblicos, reflexões dos Pais da
Igreja e meditações contemporâneas, organizados por temas, para que cada
pessoa possa meditar com mais profundidade sobre como a Palavra de Deus
ilumina o seu cotidiano.

Cada tema é composto por três camadas:

1. **Textos Bíblicos** — Passagens das Escrituras diretamente relacionadas ao tema.
2. **Pais da Igreja** — Excertos de grandes teólogos da tradição cristã histórica.
3. **Meditações Modernas** — Reflexões práticas e pastorais para o cristão de hoje.

---

## ⚠️ Aviso importante

**Este livro é um auxílio para a meditação, não um guia de vida autônomo.**

Nada aqui deve ser aplicado à sua vida sem o discernimento de um pastor,
presbítero, diácono ou outro líder espiritual maduro de sua confiança.
O livro não tem denominação específica e não faz afirmações pastorais
definitivas para situações individuais.

**Use este livro debaixo de orientação pastoral. Sempre.**

---

## Estrutura do repositório

```
lex-divina/
├── _config.yml              # Configurações do TeachBook
├── _toc.yml                 # Sumário
├── intro.md                 # Página inicial / introdução
├── como-usar.md             # Como usar o livro
├── como-contribuir.md       # Guia de contribuições
├── aviso-pastoral.md        # Aviso pastoral detalhado
├── glossario.md             # Glossário de termos
├── referencias.md           # Fontes e licenças
└── chapters/
    ├── obediencia-autoridades/
    │   ├── index.md
    │   ├── textos-biblicos.md
    │   ├── pais-da-igreja.md
    │   └── meditacoes-modernas.md
    ├── amor-proximo/
    │   ├── index.md
    │   ├── textos-biblicos.md
    │   ├── pais-da-igreja.md
    │   └── meditacoes-modernas.md
    └── humildade/
        ├── index.md
        ├── textos-biblicos.md
        ├── pais-da-igreja.md
        └── meditacoes-modernas.md
```

---

## Como contribuir

Qualquer pessoa pode contribuir com:

✅ **Aceito:**
- Textos bíblicos com referência e versão
- Citações dos Pais da Igreja com fonte verificável
- Meditações pastorais em domínio público ou revisadas pastoralmente
- Novos temas com ao menos uma contribuição inicial nas três camadas
- Correções de referências ou erros tipográficos

❌ **Não aceito:**
- Textos sectários ou que neguem doutrinas cristãs históricas fundamentais
- Autoajuda ou espiritualidade genérica sem ancoragem bíblica
- Conteúdo com direitos autorais sem autorização
- Afirmações pastorais definitivas para situações individuais
- Textos gerados por IA sem revisão pastoral

### Para contribuir via GitHub

1. Faça um **fork** do repositório
2. Edite ou crie o arquivo `.md` correspondente ao tema
3. Abra um **Pull Request** com descrição da contribuição e indicação
   de quem fez a revisão pastoral

### Para contribuir sem GitHub

Envie sua contribuição por e-mail (ver página do projeto) com:
- O tema e a camada (Bíblica / Pais da Igreja / Meditação moderna)
- O texto completo com fontes
- O nome de quem revisou pastoralmente

---

## Como publicar (build)

Este livro usa [TeachBooks](https://teachbooks.io) / Jupyter Book.

```bash
pip install jupyter-book
cd lex-divina
jupyter-book build .
```

O livro compilado estará em `_build/html/`.

Para publicar no GitHub Pages, configure o workflow de CI incluído no repositório.

---

## Licença

**Domínio Público — CC0 1.0 Universal**

Este livro e todo o seu conteúdo original são de domínio público.
Você pode copiar, modificar, distribuir e usar este trabalho, mesmo
para fins comerciais, sem pedir permissão.

https://creativecommons.org/publicdomain/zero/1.0/deed.pt_BR

Citações de obras de terceiros seguem as indicações de domínio público
ou uso permitido descritas em cada texto.

---

## Contato e mantenedores

*[Adicione aqui o e-mail ou canal de contato da comunidade mantenedora]*

---

*Que o Senhor abra os olhos do seu entendimento para contemplar
as maravilhas da sua Lei. — Salmo 119.18*
