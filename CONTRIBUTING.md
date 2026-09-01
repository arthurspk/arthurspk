# Como contribuir com o perfil do Guia Dev Brasil

Obrigado por querer ajudar! Este repositório é o **README de perfil** de [@arthurspk](https://github.com/arthurspk), a vitrine oficial da rede [Guia Dev Brasil](https://github.com/arthurspk/guiadevbrasil). Ele segue o **Padrão de Qualidade GDB v2** e toda contribuição passa por revisão.

## Antes de tudo: onde a sua contribuição entra?

- **Sugerir um curso, livro, canal, ferramenta ou comunidade:** isso vai no **guia do tema**, não aqui. Abra a issue *Sugestão de recurso* no repositório do guia (ex.: um curso de React vai no `guiadereact`).
- **Link quebrado dentro de um guia:** abra a issue *Link quebrado* naquele guia.
- **Algo errado neste perfil** (link quebrado na vitrine, estrela desatualizada, erro de texto, tradução): é aqui mesmo — leia abaixo.

## O que você pode sugerir neste repositório

- **Link quebrado ou desatualizado** na vitrine, nas estatísticas ou nas redes: abra uma issue com o template *Link quebrado*, de preferência já com o substituto.
- **Guia faltando na vitrine:** a tabela lista os guias mais estrelados da rede. Se um guia ultrapassou os que estão listados, abra um pull request atualizando a tabela com a contagem real de estrelas e a data.
- **Correção de texto** (ortografia, descrição imprecisa) ou **tradução**: pull request direto.

## Critérios de aceitação

1. **Link funcionando** — resposta HTTP 200 no momento da revisão (verificamos com [lychee](https://github.com/lycheeverse/lychee)).
2. **Dados reais** — contagem de estrelas e estatísticas sempre com a data em que foram medidas; nada estimado.
3. **Conteúdo legal** — nada de material pago redistribuído ou links de terceiros não autorizados.
4. **Vitrine enxuta** — a tabela é uma curadoria dos guias mais procurados, não o catálogo inteiro (ele já existe na aba de repositórios).

## Fluxo de pull request

1. Faça um fork e crie uma branch a partir da `main` (ex.: `fix/vitrine-estrelas`).
2. Edite o `README.md` **e** a tradução `translations/README.en.md` (veja abaixo).
3. Rode a verificação de links antes de abrir o PR:
   ```bash
   lychee --no-progress './**/*.md'
   ```
4. Abra o PR preenchendo o checklist do template. Descreva o que mudou e por quê.
5. Um mantenedor revisa; ajustes podem ser pedidos antes do merge.

## Política de tradução

- O `README.md` em **português é a fonte**. A versão em inglês (`translations/README.en.md`) é uma tradução fiel dele.
- Todo PR que altera o README principal deve alterar também a tradução, na mesma seção. Se não puder traduzir, diga isso no PR para que alguém complete.
- Nomes próprios dos guias e das tecnologias permanecem como estão.

## Código de conduta

Ao participar, você concorda com o nosso [Código de Conduta](./CODE_OF_CONDUCT.md).
