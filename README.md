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

Aplicativo desktop standalone (Rust + Tauri, binário único sem dev server) para mineração de frases e aprendizado de idiomas.

Fluxo atual: invoca diálogo estilo spotlight com atalho global Super+J (configurável) ou tray, captura a seleção, sugere automaticamente o termo desconhecido, gera o verso via API compatível com OpenAI (beginner, intermediate, advanced) e envia para o Anki via AnkiConnect.

- Inferência de termo: sugere a palavra mais rara elegível (lista top-10k embarcada, ignora stopwords, nomes próprios, siglas, números e contrações), pré-preenche a etapa 2 sem sobrescrever digitação, com seleção e substituição em uma tecla
- Camada de vocabulário Anki: cache de palavras conhecidas construído do deck, refresh em background (24h, silencioso com Anki fechado), aprende palavras recém-mineradas no envio, com fallback para raridade pura sem cache
- Listas Anki sempre atualizadas: revalida deck e note type ao vivo no envio, refresh silencioso a cada invocação, erros acionáveis
- Preview ao vivo do frente do cartão com presets de formatação
- Captura via seleção PRIMARY no Linux/X11 e OCR de screenshots
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
