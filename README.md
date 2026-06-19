# Olá, eu sou Daniel Lourenço 👋

Estudante de Engenharia de Computação na UFC | Desenvolvedor Full-stack | Builder de sistemas com IA

Construo sistemas de software complexos com foco em automação, IA aplicada e engenharia de backend.

---

## 🧠 Áreas de foco

- Sistemas com LLMs (pipelines, automação, agentes)
- Engenharia de backend e APIs
- Aplicações desktop com Rust + Tauri
- Engenharia de dados e scraping
- Sistemas de análise e pesquisa de grandes volumes de informação
- Integração de IA em ferramentas reais

---

## 🚀 Projetos principais

### 📚 SubstackAPI (projeto de pesquisa e engenharia de API)
Projeto de engenharia reversa e documentação da API interna do Substack.

Trabalho autoral baseado em testes reais contra a plataforma.

**Escopo do projeto:**
- Engenharia reversa de endpoints não documentados (`/api/v1`)
- Mapeamento de 24+ endpoints em diferentes escopos (plataforma e publicação)
- Análise do formato de autenticação via cookie `substack.sid`
- Modelagem de limites reais de uso (rate limits e constraints de payload)
- Comparação de formatos internos de conteúdo (Tiptap vs ProseMirror)
- Identificação de comportamentos não documentados via testes empíricos

**Contribuição pessoal (o que foi feito por mim):**
- Escrita completa da documentação técnica
- Construção dos testes automatizados contra a API real
- Validação empírica de limites e formatos
- Organização e estruturação do conhecimento em módulos independentes

**Principais arquivos (todos escritos por mim):**
- `API_REFERENCE.md` — referência completa de endpoints
- `AUTH.md` — modelo de autenticação e sessão
- `CONTENT_FORMATS.md` — estrutura de documentos internos
- `LIMITS.md` — rate limits e restrições reais
- `tests/` — suíte de testes contra API real

---

### 🧩 FrankSherlock *(fork de projeto externo — não sou autor original)*
Fork de um sistema de catalogação de mídia com IA multimodal.

Este projeto mantém a base original do repositório upstream, mas contém minhas modificações.

**Minhas contribuições:**
- Abstração de múltiplos providers de LLM (Ollama, Groq, OpenRouter)
- Sistema unificado de geração (`generate()` com dispatch por provider)
- Integração com APIs cloud além de modelos locais
- Melhorias no pipeline de classificação com fallback multi-estágio
- Adaptação do sistema para execução sem dependência obrigatória de modelos locais
- Modificações no fluxo de setup e configuração do usuário

---

### 🧠 Extreme_Translator
Pipeline de tradução de longo contexto (500k–10M tokens)
- Segmentação inteligente de texto
- Memória estruturada para consistência global
- Arquitetura multi-pass para revisão incremental
- Foco em livros e textos longos

---

### 📊 BubbleAnalyser
Sistema de análise de redes baseado em dados do Substack
- Crawling com checkpoint em SQLite
- Construção de grafos interativos
- API + visualização web

---

### 🎓 SentenceMiner
Ferramenta de aprendizado de idiomas baseada em extração de frases
- Captura de texto via OCR ou seleção
- Geração de flashcards com LLM
- Integração com Anki

---

### ♟️ NexusChessMaster
Engine de xadrez em Rust
- Alpha-beta pruning + iterative deepening
- Tabelas de transposição
- Sistema de torneios entre versões

---

## 📫 Contato

- Email: daniel.lourencojr@proton.me
- GitHub: github.com/DanielLourencoJr

---

> Construindo sistemas que conectam IA, engenharia de software e automação real.
