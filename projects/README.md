# Catálogo de projetos

Este catálogo aponta para repositórios públicos originais e evidencia o tipo de trabalho observável em cada um. A seleção representa variedade; não é uma classificação de qualidade ou maturidade.

## Projetos em destaque

- [testes-e2e-com-cypress](https://github.com/AnaCarolinaSantos-qa/testes-e2e-com-cypress) — cenários Cypress de cadastro, login, sessão e CRUD. O fluxo de cadastro usa uma simulação local da API no lugar do Mailosaur; o [CI do PR #1 passou](https://github.com/AnaCarolinaSantos-qa/testes-e2e-com-cypress/actions/runs/42867357417). Os cenários restantes usam a aplicação de demonstração do projeto.
- [Testes_API_NodeJS](https://github.com/AnaCarolinaSantos-qa/Testes_API_NodeJS) — exercícios de API com Node.js, Mocha, Chai e Supertest; [CI do PR #2 passou](https://github.com/AnaCarolinaSantos-qa/Testes_API_NodeJS/actions/runs/42862795387).
- [zapLink](https://github.com/AnaCarolinaSantos-qa/zapLink) — aplicação de agenda virtual em Vue.js/Node.js/MongoDB com testes da API executados em CI contra um MongoDB efêmero; [CI do PR #1 passou](https://github.com/AnaCarolinaSantos-qa/zapLink/actions/runs/42864983095).

## Outros exemplos públicos

- [CypressCucumber](https://github.com/AnaCarolinaSantos-qa/CypressCucumber) — cenário Cypress/Cucumber para um formulário local; [CI do PR #1 passou](https://github.com/AnaCarolinaSantos-qa/CypressCucumber/actions/runs/42867393049).
- [cypress_boilerplate](https://github.com/AnaCarolinaSantos-qa/cypress_boilerplate) — boilerplate de Cypress com workflow atualizado; [CI do PR #1 passou](https://github.com/AnaCarolinaSantos-qa/cypress_boilerplate/actions/runs/42861994146).
- [API_Restful_Sinatra](https://github.com/AnaCarolinaSantos-qa/API_Restful_Sinatra) — API Sinatra/RSpec testada com serviço MongoDB efêmero; [CI do PR #1 passou](https://github.com/AnaCarolinaSantos-qa/API_Restful_Sinatra/actions/runs/42869479563).
- [robot_framework_qa_starter](https://github.com/AnaCarolinaSantos-qa/robot_framework_qa_starter) — laboratório experimental de automação. O workflow tem jobs para API, UI, mobile, acessibilidade e performance, e o [CI do PR #37 passou](https://github.com/AnaCarolinaSantos-qa/robot_framework_qa_starter/actions/runs/42866157339). Isso não equivale a cobertura funcional abrangente: os testes atuais de API e UI são demonstrações que apenas registram mensagens. Veja a [auditoria atualizada](../docs/portfolio-strategy.md#auditoria-do-candidato-anterior).
- [rocklov](https://github.com/AnaCarolinaSantos-qa/rocklov) — projeto de curso com cenários de API e web em Ruby/RSpec e Cucumber; execução depende de serviços Docker e Jenkins externos.

## Manutenção pública recente

Em novembro de 2026, dez PRs de manutenção foram mesclados em repositórios públicos. Sete checks de CI associados a esses PRs passaram. Os outros três PRs atualizaram somente documentação e não têm uma suíte executável no GitHub Actions.

### CI, automação e configuração

- [cypress_boilerplate — PR #1](https://github.com/AnaCarolinaSantos-qa/cypress_boilerplate/pull/1) · [CI aprovado](https://github.com/AnaCarolinaSantos-qa/cypress_boilerplate/actions/runs/42861994146): Actions atuais, Node.js 20, instalação reproduzível e execução em pull requests.
- [Testes_API_NodeJS — PR #2](https://github.com/AnaCarolinaSantos-qa/Testes_API_NodeJS/pull/2) · [CI aprovado](https://github.com/AnaCarolinaSantos-qa/Testes_API_NodeJS/actions/runs/42862795387): instalação por lockfile, Node.js 20 e asserção menos sujeita a mudanças da API de demonstração.
- [CypressCucumber — PR #1](https://github.com/AnaCarolinaSantos-qa/CypressCucumber/pull/1) · [CI aprovado](https://github.com/AnaCarolinaSantos-qa/CypressCucumber/actions/runs/42867393049): formulário e servidor locais para evitar dependência de um site remoto indisponível.
- [testes-e2e-com-cypress — PR #1](https://github.com/AnaCarolinaSantos-qa/testes-e2e-com-cypress/pull/1) · [CI aprovado](https://github.com/AnaCarolinaSantos-qa/testes-e2e-com-cypress/actions/runs/42867357417): cadastro sem Mailosaur, por simulação local da resposta da API, e remoção de variáveis de segredo que deixaram de ser necessárias.
- [zapLink — PR #1](https://github.com/AnaCarolinaSantos-qa/zapLink/pull/1) · [CI aprovado](https://github.com/AnaCarolinaSantos-qa/zapLink/actions/runs/42864983095): URI MongoDB configurável por ambiente e testes da API com banco efêmero.
- [API_Restful_Sinatra — PR #1](https://github.com/AnaCarolinaSantos-qa/API_Restful_Sinatra/pull/1) · [CI RSpec aprovado](https://github.com/AnaCarolinaSantos-qa/API_Restful_Sinatra/actions/runs/42869479563): execução da API por Rack e testes contra MongoDB efêmero.
- [robot_framework_qa_starter — PR #37](https://github.com/AnaCarolinaSantos-qa/robot_framework_qa_starter/pull/37) · [workflow aprovado](https://github.com/AnaCarolinaSantos-qa/robot_framework_qa_starter/actions/runs/42866157339): badge ligado ao workflow real e caminhos do README alinhados ao projeto.

### Documentação e limites de execução

- [NinjaWeek — PR #1](https://github.com/AnaCarolinaSantos-qa/NinjaWeek/pull/1): README alinhado ao conteúdo versionado; o repositório não contém suíte executável.
- [RobotFrameworkWeek — PR #1](https://github.com/AnaCarolinaSantos-qa/RobotFrameworkWeek/pull/1): README alinhado aos arquivos existentes; o repositório não contém suíte executável.
- [rocklov — PR #1](https://github.com/AnaCarolinaSantos-qa/rocklov/pull/1): pré-requisitos dos serviços Jenkins documentados, incluindo o aviso de que a preparação da suíte de API apaga o banco configurado. Não há CI autônomo seguro no GitHub para essa configuração.

## Repositórios públicos adicionais revisados

[NinjaWeek](https://github.com/AnaCarolinaSantos-qa/NinjaWeek) e [RobotFrameworkWeek](https://github.com/AnaCarolinaSantos-qa/RobotFrameworkWeek) são exemplos de curso compostos apenas por documentação. Continuam disponíveis nos repositórios originais.
