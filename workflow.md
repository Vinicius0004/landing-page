## Modelo Adotado
Usaremos o **GitHub Flow**, onde todo desenvolvimento é feito em branches a partir da `main`


## Estratégia de Branches
- `main`: branch estável.
- `feature/nome`: novas funcionalidades.
- `fix/nome`: correções de bugs.
- `docs/nome`: documentação.
#destino de merges: `main`


## Política de Commits
Formato:
tipo(escopo): descrição do commit

Tipos recomendados:
- feat: nova funcionalidade.
- fix: correção de bug.
- docs: alterações na documentação (inclui correção de links).
- style: formatação, lint, sem mudança de comportamento (espaços, ponto e vírgula).
- refactor: refatoração de código sem alterar comportamento.
- perf: melhorias de desempenho.
- test: adicionar/ajustar testes.
- chore: tarefas de manutenção (dependências, scripts, etc.).
- build: mudanças no processo de build.
- ci: mudanças em configuração de integração contínua.


Exemplos:
- feat(home): adicionar botão de login
- fix(css): corrigir cor do header
- docs(workflow): atualizar regras