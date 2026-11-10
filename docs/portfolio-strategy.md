# Estratégia do portfólio

## Objetivo

Apresentar a trajetória de Quality Engineering iniciada em 2010 e a aplicação dessa experiência à AI Engineering para qualidade de software. O portfólio deve permitir que recrutadores e pares entendam rapidamente o foco profissional, encontrem exemplos públicos e distingam evidências existentes de iniciativas em andamento.

## Estrutura editorial

- `README.md`: português primeiro, seguido da versão em inglês; visão geral, tecnologias e projetos selecionados.
- `README.en.md`: versão independente em inglês.
- `projects/`: catálogo de projetos públicos existentes, com contexto e limitações observadas.
- `case-studies/`: estudos de caso somente quando sanitizados e autorizados.
- `architecture/`: diagramas e decisões baseados em exemplos sintéticos ou conteúdo autorizado.
- `roadmap/`: temas de exploração claramente marcados como futuros ou em andamento.

## Critérios de seleção

1. O repositório é público e pertence à conta indicada.
2. A descrição é sustentada pelo README e pela estrutura/código observáveis.
3. O destaque não sugere maturidade, cobertura ou sucesso de CI sem evidência verificável.
4. Projetos de curso e exemplos são identificados com contexto quando isso é conhecido.
5. O portfólio aponta para os repositórios originais; não replica seu código.

## Auditoria do candidato principal

Auditoria estática de `robot_framework_qa_starter`, realizada em 2026-11-10, somente sobre conteúdo público:

- O repositório reúne diretórios para API, UI, mobile, acessibilidade e performance, bibliotecas Python auxiliares, scripts k6 e workflow GitHub Actions.
- Os testes de API e UI verificados são casos `Hello World` que apenas registram mensagens. Eles não exercitam um serviço ou uma interface.
- A suíte mobile contém um identificador de app fictício (`DUMMY_APP_ID`) e depende de credenciais BrowserStack externas; a CI observada não fornece esses segredos.
- Os testes de acessibilidade incluem páginas HTML locais sintéticas e verificações heurísticas básicas; isso não equivale a uma auditoria completa de conformidade WCAG.
- O workflow executa somente o script k6 `basic_load_test.js` e o resumo final baixa especificamente o artefato de acessibilidade; essa dependência deve ser validada em execução.
- A API pública de GitHub retornou zero execuções do workflow no momento da consulta. Portanto, não há evidência de CI recente para sustentar badges de aprovação.
- O README do projeto declara badges de sucesso/falha e lista de pastas que não correspondem integralmente ao código presente. Eles não foram reproduzidos neste perfil.

**Conclusão:** é o melhor candidato de destaque pela amplitude e organização do escopo, mas deve ser apresentado como estrutura experimental em evolução, sem alegar cobertura funcional abrangente ou CI verde. Esta auditoria foi estática; não executou testes nem revisou cada arquivo do repositório.

## Próximos passos editoriais

- Aprofundar a revisão técnica de cada projeto antes de escrever estudos de caso.
- Criar exemplos sintéticos para mostrar abordagens de AI-powered Quality Engineering sem usar dados ou artefatos corporativos.
- Atualizar o perfil à medida que novas evidências públicas forem publicadas.
