# Teste Técnico Desenvolvedor(a) Frontend Júnior Vue.js [REMOTO]

Neste repositório você encontra o enunciado do teste técnico para a vaga de
_Desenvolvedor(a) Frontend Júnior Vue.js [REMOTO]_ da 
[Instruct](https://instruct.com.br/)! Você provavelmente chegou aqui através da 
indicação de alguma pessoa da empresa após passar pelas 
[outras etapas](https://instruct.com.br/trabalhe-com-a-gente/processo-de-selecao/)
do processo seletivo. Se este não for o seu caso e mesmo assim você implementar
alguma solução para este exercício ele **não** será avaliado.

> Você _pode_ usar o problema descrito aqui para exercitar suas habilidades de
> desenvolvimento, mas a sua solução será avaliada por alguém da Instruct
> **apenas se** você estiver no processo seletivo da vaga de _Desenvolvedor(a) 
> Frontend Júnior Vue.js [REMOTO]_.
Para saber mais sobre a empresa, leia o [FAQ](#FAQ)

## O problema

A empresa _Habitue_ desenvolveu um app (com o mesmo nome) que ajuda pessoas a
criar ou reforçar hábitos (ex: ler diariamente, caminhar 3 vezes por semana)
através de lembretes, notificações e algumas técnicas de gamificação.

O serviço foi muito bem recebido pelo mercado brasileiro, e, como nada do app é 
particular do mercado nacional, a _Habitue_ agora planeja extender suas
operações para outros países.

Internacionalizar uma aplicação pode ser um processo trabalhoso, portanto os
próximos passos serão feitos com ajuda de uma ferramenta para visualizar
algumas informações de países.

## Solução

Para auxiliar o planejamento da internacionalização do aplicativo você deve
desenvolver uma interface que liste alguns dados de países. Essa listagem deve
possuir alguns filtros para facilitar a tomada de decisão.

Os dados para listar os países devem ser consultados da
[Countries GraphQL API](https://countries.trevorblades.com/graphql) e o projeto
deve ser desenvolvido usando Vue 3. Este repositório contem um ponto de partida.

Para fazer a análise necessária, a listagem precisa ter 3 filtros:
- Um filtro de continente, obrigatório, que determina quais países são listados.
- Um filtro de países com mais de um idioma, opcional
- Um filtro por idioma, também opcional

Exemplo: se o usuário estiver visualizando países do continente _South America_ 
e usar o filtro para listar países com mais de um idioma, os seguintes países
devem estar visíveis: _Argentina_, _Bolivia_ e _Paraguay_.

| ⚠️ | Sua solução deve usar a [Countries GraphQL API](https://countries.trevorblades.com/graphql). Não use outro caminho pra buscar as informações necessárias |
| --- | --- |

## Avaliação

Você deve escrever sua solução usando Vue 3, subir o código fonte num
repositório privado do GitHub e fazer deploy no _Hobby Tier_ da
[Vercel](https://vercel.com/).

Quando finalizar a implementação, adicione o usuário `instruct-selecao` como
colaborador no seu repositório do GitHub até o fim do prazo estipulado.

A UX e UI do projeto serão levadas em consideração, atente-se não apenas para o
código escrito.

**Boa sorte!**

---

## FAQ

### Como me candidatar para trabalhar na Instruct?

As inscrições são feitas através das vagas publicadas no site: https://instruct.com.br/trabalhe-com-a-gente/

Nessa página estão listadas as vagas abertas e todos os detalhes de nosso
processo seletivo.

### Como ser avisado de novas vagas?

[Siga a Instruct no Linkedin](https://www.linkedin.com/company/instructbr).

Sempre publicamos quando novas vagas são abertas.

### Como é trabalhar na Instruct?

Você pode ler nosso [Handbook](https://github.com/instruct-br/handbook). Ele é a referência completa sobre como a Instruct funciona.

Destaque especial para as atribuições do papel de [Analista de Desenvolvimento Júnior](https://github.com/instruct-br/handbook/blob/main/papeis.md#analista-de-desenvolvimento-j%C3%BAnior)
