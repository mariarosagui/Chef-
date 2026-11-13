# Como usar os agentes da Chef+ no Claude (claude.ai)

Crie um projeto para cada agente.

| Projeto | Instruções do projeto | Conhecimento do projeto |
|---|---|---|
| Chef+ Tráfego | Cole o conteúdo de `instrucoes-trafego.md` | Suba `../base-de-conhecimento.md` |
| Chef+ Copy de Vídeo | Cole o conteúdo de `instrucoes-copy-video.md` | Suba `../base-de-conhecimento.md` |

Passo a passo:

1. No claude.ai, abra **Projetos** e crie um projeto novo.
2. Em **Instruções**, cole o texto inteiro do arquivo de instruções.
3. Em **Conhecimento**, suba o arquivo `base-de-conhecimento.md`.
4. Abra uma conversa dentro do projeto e peça o que precisa.

Observações:

- Para o projeto de tráfego buscar números atuais, ative o conector do Supermetrics no claude.ai. Sem ele, o agente usa só o histórico da base.
- Quando a base de conhecimento mudar no repositório, suba o arquivo de novo nos dois projetos.
- Estes arquivos são gerados a partir de `.claude/agents/`. Se mudar um agente, atualize a instrução correspondente aqui.
