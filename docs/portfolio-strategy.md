# Estratégia do portfólio

## Objetivo

Apresentar a experiência consolidada em Quality Engineering desde 2010 e mostrar, com exemplos públicos verificáveis, a aplicação dessa base a estratégia de testes, automação e qualidade de software. AI Engineering aplicada à qualidade é uma frente de expansão em andamento; o portfólio deve descrevê-la como exploração até que existam entregas públicas que demonstrem essa atuação.

A página principal deve permitir que recrutadores e pares identifiquem rapidamente a especialidade, vejam evidências e distingam experiência estabelecida de trabalho em exploração.

## Posicionamento editorial

- **Identidade principal:** Quality Engineering, estratégia de testes e automação; QA desde 2010.
- **Extensão em desenvolvimento:** AI Engineering aplicada à qualidade, com avaliação de LLMs, RAG, context engineering e supervisão humana.
- **Projeto em destaque:** escolher pelo que os testes realmente demonstram e pela evidência de execução, não pela quantidade de áreas listadas no repositório.
- **Estudos de caso:** publicar somente com autorização e sanitização; exemplos sintéticos podem demonstrar métodos sem expor material de clientes ou empregadores.

## Estrutura editorial

- `README.md`: português primeiro, posicionamento, especialidades, projetos em destaque e evidências recentes.
- `README.en.md`: versão independente em inglês.
- `projects/`: catálogo de repositórios públicos, contribuições, PRs e checks verificáveis.
- `case-studies/`: estudos de caso somente quando sanitizados e autorizados.
- `architecture/`: diagramas e decisões baseados em exemplos sintéticos ou conteúdo autorizado.
- `roadmap/`: temas de exploração futura ou em andamento.

## Critérios de seleção

1. O repositório é público e pertence à conta indicada.
2. A descrição é sustentada pelo README, código e estrutura observáveis.
3. Um check verde comprova a execução do workflow, mas não deve ser usado como sinônimo de cobertura ou maturidade.
4. Projetos de curso e exemplos são identificados com contexto quando isso é conhecido.
5. O perfil aponta para repositórios originais e PRs; não replica seu código.
6. Resultados, cobertura, certificações e competências não são afirmados sem evidência.

## Auditoria do candidato anterior

Revisão estática de `robot_framework_qa_starter`, atualizada em 2026-11-10, com base apenas no conteúdo público:

- O repositório contém áreas e workflows para API, UI, mobile, acessibilidade e performance.
- Os arquivos atuais de teste de API e UI contêm apenas casos `Hello World` que registram mensagens; não exercitam serviço nem interface.
- A auditoria anterior encontrou identificador fictício de app mobile (`DUMMY_APP_ID`) e dependência declarada de credenciais BrowserStack. Um job verde não demonstra integração real com um dispositivo externo.
- Acessibilidade usa páginas locais sintéticas e verificações heurísticas básicas; isso não equivale a auditoria completa de conformidade WCAG.
- O job de performance executa um teste básico do k6 com carga pequena e duração curta; isso comprova a execução do script, não comportamento de produção.
- O workflow [`ci_completo.yml`](https://github.com/AnaCarolinaSantos-qa/robot_framework_qa_starter/blob/main/.github/workflows/ci_completo.yml) contém jobs de API, UI, mobile, acessibilidade, performance e resumo. A execução [#14 passou em todos esses jobs](https://github.com/AnaCarolinaSantos-qa/robot_framework_qa_starter/actions/runs/42866157339).
- O PR #37 corrigiu badge e caminhos no README, mas não ampliou a cobertura dos testes. O status verde agora é real e verificável; o alcance funcional continua limitado pelos casos de demonstração.

**Conclusão editorial:** o repositório continua sendo um laboratório amplo em evolução, mas não é o melhor destaque para provar profundidade de automação. O portfólio passou a destacar `testes-e2e-com-cypress`, que contém fluxos de cadastro, login, sessão e CRUD e teve CI aprovado no [PR #1](https://github.com/AnaCarolinaSantos-qa/testes-e2e-com-cypress/pull/1). O cenário de cadastro substitui o serviço de e-mail por uma simulação local; os demais cenários usam a aplicação de demonstração do projeto. Essa limitação está descrita no catálogo.

## Evidência de manutenção pública

Em novembro de 2026, dez PRs de manutenção foram mesclados em repositórios públicos. Sete checks associados a mudanças de CI, configuração ou documentação de workflow passaram. Três PRs alteraram somente documentação em projetos sem suíte executável local ou com dependências externas não seguras para CI autônoma.

O [catálogo de projetos](../projects/README.md#manutencao-publica-recente) mantém os links dos PRs e das execuções para que essas afirmações possam ser conferidas.

## Próximos passos editoriais

- Criar um estudo de caso sintético que mostre decisões, estratégia e resultados verificáveis sem dados corporativos.
- Desenvolver um projeto público específico de avaliação de LLMs ou RAG antes de apresentar AI Engineering como competência demonstrada.
- Rever a seleção principal quando os projetos de automação tiverem testes mais profundos e independentes de serviços de demonstração.
