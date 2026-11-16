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
Dentro dela, cada exercício tem a própria pasta, com o teste ao lado do código:

```text
python/orientacao_a_objetos/
    classe_e_objeto/
        ex001/
            ex001.py
            test_ex001.py
```

## Como eu estudo

1. Abro uma issue com o template **Tópico de estudo**.
2. Crio uma branch com o nome da pasta do tópico. Exemplo: `python/solid`.
3. Faço os exercícios, com um commit pequeno para cada um (as notas ficam no Obsidian).
4. Escrevo o README do tópico: o que aprendi e as dúvidas que resolvi.
5. Abro um pull request que fecha a issue do tópico.
6. Atualizo o progresso abaixo antes do merge.

## Progresso

Os tópicos seguem a ordem da trilha. Os que eu já dominava antes deste repositório não têm pasta.

| Tópico | Assunto | Status |
|--------|---------|--------|
| Primeiros passos | Python | ✅ sem pasta |
| Fundamentos | Python | ✅ sem pasta |
| Estruturas de dados | Python | ✅ sem pasta |
| Funções | Python | 🚧 |
| Arquivos e erros | Python | ⏳ |
| Terminal, Git e GitHub | Python | ✅ sem pasta |
| Módulos e pacotes | Python | 🚧 |
| Orientação a objetos | Python | 🚧 |
| SOLID | Python | ⏳ |
| Qualidade de código | Python | ⏳ |
| Testes | Python | ⏳ |
| Conceitos de IA | IA | ⏳ |
| Estatística básica | IA | ⏳ |
| Uso desde o primeiro dia | Claude | ⏳ |
| Prompts | Claude | ⏳ |

Os tópicos seguintes entram na tabela quando a fase deles começar.

Legenda: ✅ concluído · 🚧 em andamento · ⏳ a fazer

## Como rodar os exercícios

```bash
python -m venv .venv
# Windows
.venv\Scripts\activate
# Linux/macOS
source .venv/bin/activate

pip install -r requirements.txt

# Um exercício
python python/orientacao_a_objetos/classe_e_objeto/ex001/ex001.py

# Os testes
pytest
```

Chaves e senhas ficam em um arquivo `.env`, que não vai para o repositório.
