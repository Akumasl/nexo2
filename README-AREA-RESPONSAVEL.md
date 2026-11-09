# NEXO — primeira versão da área do responsável

## Como abrir
- Abra `responsavel.html` no navegador para visualizar a nova área.
- Para testar a partir do servidor local existente, sirva a pasta raiz do projeto com um servidor estático.
- A página inicial, login e cadastro originais foram preservados.

## O que foi implementado nesta etapa
- Dashboard responsivo inspirado na referência enviada.
- Tema claro/escuro com preferência persistida em `localStorage`.
- Seleção de perfis de filhos e cadastro/edição de perfis demonstrativos.
- Cadastro e edição de tarefas, pontos, tipo/frequência e adolescente.
- Filtros Hoje/Semana/Todas e por adolescente.
- Registro demonstrativo de conclusão, crédito de pontos e histórico.
- Cadastro/edição/arquivamento de metas e barras de progresso.

## Limitações importantes
Este ZIP original contém somente páginas HTML/CSS/JS de entrada, login e cadastro demonstrativos, além de `express` listado como dependência. Não contém área do adolescente, autenticação funcional, API, banco de dados, modelos ou vínculos familiares. Por isso, esta entrega é uma **primeira versão de interface funcional com dados locais de demonstração** (`localStorage`). Ela não sincroniza entre dispositivos nem com uma conta de adolescente. Não use dados reais de crianças nesta versão.

## Próxima etapa necessária para produção
Definir e implementar backend/API, autenticação e autorização familiar; persistência em banco; regras de recorrência e idempotência no servidor; e contrato de integração para a futura área do adolescente. A conclusão e a pontuação devem ser validadas no servidor em transação, com chave única por tarefa/ocorrência, para impedir crédito duplicado.
