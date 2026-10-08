# Olá, eu sou Daniel Lourenço

Estudante de Engenharia de Computação na UFC | Desenvolvedor Full-stack | Builder de sistemas com IA

Construo ferramentas desktop e de automação com foco em aprendizado de idiomas, exportação de dados e integração de LLMs em fluxos reais.

---

## Áreas de foco

- Aplicações desktop com Rust + Tauri
- Ferramentas de aprendizado de idiomas com LLMs e Anki
- Engenharia reversa e integração com APIs internas
- Exportação e conversão de dados (JSON, Markdown)
- Automação e tooling em Node.js

---

## Projetos principais

### SentenceMiner

Aplicativo desktop (Rust + Tauri) para mineração de frases e aprendizado de idiomas.

Fluxo atual: captura a frase selecionada com atalho global, gera o verso do flashcard via API compatível com OpenAI (modos beginner, intermediate, advanced) e envia a nota para o Anki via AnkiConnect.

- Captura via seleção PRIMARY no Linux/X11 e OCR de screenshots
- Preview ao vivo do frente do cartão com presets de formatação
- Integração com AnkiConnect (decks, note types, envio)
- Configuração em `~/.config/sentenceminer/config.toml`

Repositório: https://github.com/DanielLourencoJr/SentenceMiner

---

### SubstackKit

Downloader/exportador unificado para dados públicos do Substack (posts, notes, replies) usando a API interna da plataforma.

Gera um formato padrão de exportação em JSON (`substack-export@1`) e converte para Markdown padrão (um arquivo por post + notes mensais).

- Download completo de posts com paginação automática e enriquecimento de corpo
- Download completo de notes com paginação direta, retry em 429 e replies recursivas
- Conversão para Markdown com frontmatter YAML e arquivos mensais
- Núcleo importável como biblioteca + CLI unificada (`export | convert | fetch-new | lookup`)
- Documentação de API reversa em `docs/` (auth, endpoints, formatos, limites)

Repositório: https://github.com/DanielLourencoJr/SubstackKit

---

## Contato

- Email: daniel.lourencojr@proton.me
- GitHub: github.com/DanielLourencoJr

---

> Construindo ferramentas que conectam IA, engenharia de software e automação real.
