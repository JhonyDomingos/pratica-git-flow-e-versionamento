# Estrutura de Branches

Este é um guia para a estrutura de branches comuns em um projeto Git:

- **master (ou main):** Este é o branch principal do seu projeto, onde o código estável e pronto para produção deve residir. Geralmente, você deseja manter este branch protegido.

- **develop:** Este é um branch de desenvolvimento intermediário, onde as novas funcionalidades são mescladas antes de serem integradas no branch "master" ou "main". Isso ajuda a isolar o trabalho em progresso.

- **feature/[nome-da-funcionalidade]:** Branches de recursos são usados para desenvolver novas funcionalidades ou componentes do seu projeto. Cada funcionalidade específica deve ter seu próprio branch. Exemplo: `feature/login`, `feature/dashboard`, etc.

- **bugfix/[nome-do-bug]:** Branches de correção de bugs são usados para corrigir problemas específicos. Cada correção de bug deve ter seu próprio branch. Exemplo: `bugfix/bug-na-pagina-de-login`.

- **hotfix/[nome-do-hotfix]:** Branches de hotfix são usados para correções de bugs críticos em produção. Eles são criados para corrigir problemas urgentes e são mesclados diretamente no branch "master" ou "main" após a correção.

- **release/[versão]:** Branches de lançamento são usados para preparar uma nova versão do software. Eles permitem a realização de testes finais e correções antes de mesclar no branch "master" ou "main". Exemplo: `release/
