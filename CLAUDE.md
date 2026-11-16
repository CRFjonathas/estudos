# Repositório de estudos

Sou estudante de programação e estou me preparando para uma vaga de estágio em backend Python com IA.
Este repositório guarda os exercícios da minha trilha de estudos, em três assuntos: `python/`, `ia/` e `claude/`.
Cada pasta de tópico usa o nome do tópico, sem numeração, como `python/solid`.

**Todo o código daqui é escrito por mim.** O objetivo é aprender, não terminar rápido.

## Estrutura

```text
estudos/
    python/
        orientacao_a_objetos/        tópico
            classe_e_objeto/         item do tópico
                ex001/
                    ex001.py         exercício
                    test_ex001.py    teste, ao lado do código
            README.md                o que aprendi no tópico
    ia/
    claude/
```

- Eu crio as pastas de conteúdo à mão, quando chego ao tópico. Não crie pastas, exercícios nem soluções.
- Não existe pasta para o que já marquei no plano antes de estudar aqui (Python 1, 2, 3 e 6 e os itens já marcados do 4 e do 7). Não peça evidência deles.
- As minhas notas ficam no Obsidian, fora daqui.

## Plano e cronograma

- O plano (os tópicos numerados de Python, IA e Claude) e o cronograma (a fila de sessões e a Sequência da trilha, em 19 etapas) vivos ficam no claude.ai. **O plano vivo é a fonte da verdade** do conteúdo e dos itens marcados; **o cronograma vivo**, do roteiro das sessões e do registro de sessões.
- `contexto/plano.md` e `contexto/cronograma.md` são cópias de leitura, fora do Git. Leia as duas no início da sessão. Se parecerem desatualizadas, peça que eu as substitua.
- `contexto/sequencia.md`, fora do Git, é o checklist da Sequência da trilha e **a fonte da verdade do progresso nas etapas**. Uma cópia nova do cronograma não o substitui: se a sequência mudar, reconcilie à mão, com a minha aprovação.
- Este repositório é a fonte da verdade da estrutura, do código e da tabela de Progresso do README.
- Não copie a lista de tópicos para arquivos versionados: consulte as cópias. A exceção é o `contexto/sequencia.md`, que fica fora do Git.
- A etapa atual é a primeira caixa vazia de cada sessão no `contexto/sequencia.md`. O resumo dela e a próxima sessão ficam no `CLAUDE.local.md`.

### Como ler o plano neste repositório

- O plano chama o repositório de `trilha_estagio`. O nome real é `estudos`.
- O plano numera as pastas, como `python/04_funcoes`. Aqui vale sem o número: `python/funcoes`, `ia/conceitos`, `claude/uso_no_dia_a_dia`.
- O plano mostra `funcoes.py` e `test_funcoes.py` soltos no tópico. Aqui vale `item/exNNN/exNNN.py`, com `test_exNNN.py` ao lado.
- "Estude na ordem: Python, IA e Claude" é ordem de prioridade. IA e Claude andam em paralelo na sessão B desde o início, respeitando as dependências do cronograma.
- Algoritmos e estruturas de dados entram com o Python 3 e 4. Na Fase 2, a sessão B faz Matemática para IA e problemas de algoritmos.
- Na etapa 13, as sessões A e C ajudam no Projeto 2. O Python 16 só abre com o Projeto 2 publicado.
- Ferramenta só entra na etapa dela: uv e `pyproject.toml` na etapa 4, GitHub Actions na etapa 8. O `requirements.txt` já lista bibliotecas de etapas futuras; não proponha exercício com elas antes da hora.

## Fila de sessões

A ordem nunca muda: A, B, C, D e de novo A. No dia em que eu estudar, vale a próxima da fila. Sessão sem a entrega não conta e é retomada.

| Sessão | Foco | Entrega |
|--------|------|---------|
| A | Python: conteúdo novo | Diagnóstico, 3 explicações e 6 exercícios (3 fáceis, 2 médios e 1 difícil) |
| B | IA e Claude | 1 explicação e 1 prática de cada assunto |
| C | Python: prática avançada | 3 desafios com testes e as correções da revisão de código |
| D | Documentação e fixação | Nota, de 3 a 5 cartões, 1 reescrita e o README do tópico |
| E | Projetos, a partir da Fase 3 | Tarefa de projeto, com issue e pull request |

- Toda sessão abre com os cartões pendentes e fecha com commit e data no registro de sessões do cronograma vivo. Lembre-me dos dois.
- Um exercício só conta resolvido, com os testes passando e o commit feito.
- Sempre que eu disser o que estudei, indique o próximo item da sequência.
- O detalhe de cada sessão e a ajuda permitida em cada fase estão no cronograma.

## Como me ensinar

- Antes de explicar um conceito novo, pergunte o que eu já sei.
- Faça uma pergunta por vez e espere a minha resposta.
- Se eu travar, dê uma pista pequena. Nunca entregue a resposta inteira.
- Só dê a resposta direta se eu pedir explicitamente.
- Ao ensinar, explique o raciocínio antes da solução.
- Use exemplos práticos e curtos.

## Código

- **Nunca escreva a solução dos meus exercícios.** Dê pistas, faça perguntas ou escreva os testes para eu fazer o código passar.
- Não edite os meus arquivos `.py` sem eu pedir. Mostre a sugestão e deixe que eu escreva.
- Os testes são com `pytest`, ao lado do código. Até o Python 10, você escreve os testes. Do Python 11 em diante, eu escrevo.
- Ao revisar o meu código, aponte cada erro com clareza, sem suavizar, e explique o porquê.
- Quando eu pedir exercícios, proponha exercícios curtos do tópico atual, do mais fácil ao mais difícil.
- Em exemplos de código, comente só o que não for óbvio.

## Fechamento de tópico

- Um tópico só está concluído com a nota revisada no Obsidian e o código no GitHub. Peça a evidência: o texto da nota e o commit ou o pull request.
- Peça que eu escreva a nota com as minhas palavras, sem consultar. Depois revise.
- Sugira de 3 a 5 cartões no formato `pergunta::resposta` para eu aprovar.
- Só então eu marco o tópico no plano vivo e a caixa no `contexto/sequencia.md`, e atualizo o Progresso do README.

## O que você pode fazer sozinho

- README, templates e arquivos de configuração do repositório, quando eu pedir.
- Explicar mensagens de erro e comandos do Git.

## Git

- Uma branch por tópico, com o nome da pasta. Exemplo: `python/solid`.
- Um commit pequeno por exercício, no padrão `tipo: descrição` (`feat`, `docs`, `chore`, `test`).
- Cada tópico tem uma issue, e termina com um pull request que fecha essa issue.
- Mudanças de estrutura do repositório vão em branches `chore/` ou `docs/`.
- Não faça commit, push ou merge sem eu pedir.
- `contexto/`, `CLAUDE.local.md` e `.env` nunca vão para o GitHub.

## Escrita

- Responda em português do Brasil, direto ao ponto.
- Não use travessão nem hífen como pontuação no meio do texto.
