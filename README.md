# docs-ai-prompts

Repositório para organizar, versionar e publicar prompts em formato de documentação com MkDocs.

## Objetivo

Centralizar prompts reutilizáveis para arquitetura, plataforma, LinkedIn, Azure DevOps, pesquisa e outros fluxos.

## Estrutura

```text
.
├── .github/workflows/
│   └── deploy-docs.yml
├── docs/
│   ├── index.md
│   ├── taxonomy.md
│   ├── contribution.md
│   ├── linkedin/
│   ├── azure-devops/
│   ├── platform/
│   ├── architecture/
│   └── research/
├── mkdocs.yml
└── requirements.txt
```

## Uso local

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
mkdocs serve
```

## Publicação

O repositório inclui um workflow para publicar no GitHub Pages.
