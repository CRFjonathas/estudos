# Estudos

Repositório da minha trilha de estudos em programação, com foco em uma vaga de estágio em **backend Python com IA**.

Todo o código aqui é escrito por mim. O objetivo é aprender, não terminar rápido.

## Estrutura

| Pasta     | Assunto                                  |
|-----------|------------------------------------------|
| `python/` | Fundamentos e boas práticas de Python    |
| `ia/`     | Conceitos e aplicações de IA             |
| `claude/` | Uso da API e das ferramentas do Claude   |

Cada tópico fica em uma pasta com o nome do tópico. Exemplo: `python/solid`.

## Como eu estudo

1. Abro uma issue com o template **Tópico de estudo**.
2. Crio uma branch com o nome da pasta do tópico. Exemplo: `python/solid`.
3. Faço os exercícios e as anotações (as notas ficam no Obsidian).
4. Abro um pull request que fecha a issue do tópico.
5. Atualizo o progresso abaixo antes do merge.

## Progresso

| Tópico | Assunto | Status |
|--------|---------|--------|
| _nenhum ainda_ | | |

Legenda: ✅ concluído · 🚧 em andamento · ⏳ a fazer

## Como rodar os exercícios

```bash
python -m venv .venv
# Windows
.venv\Scripts\activate
# Linux/macOS
source .venv/bin/activate

python python/solid/exercicio.py
```

Chaves e senhas ficam em um arquivo `.env`, que não vai para o repositório.
