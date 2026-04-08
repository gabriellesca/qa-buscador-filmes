# CT002 — Filtro por gênero

**Funcionalidade:** Botões de filtro por gênero  
**Prioridade:** Alta  
**Ambiente:** gabriellesca.github.io/buscador-filmes

---

## Pré-condições
- Aplicação aberta no navegador
- Filmes populares carregados na tela

---

## Casos de teste

### CT002.1 — Filtro por gênero válido
| Campo | Detalhe |
|-------|---------|
| **Dado** | Usuário está na tela inicial com filmes populares |
| **Quando** | Clica no botão "Ação" |
| **Então** | A lista é atualizada |
| **Resultado esperado** | Somente filmes de Ação são exibidos |
| **Status** | ❌ Falhou |
| **Observação** | A lista de filmes não foi atualizada após clicar no filtro |

---

### CT002.2 — Alternância entre gêneros
| Campo | Detalhe |
|-------|---------|
| **Dado** | Usuário está com filtro "Ação" ativo |
| **Quando** | Clica no botão "Comédia" |
| **Então** | O filtro muda para Comédia |
| **Resultado esperado** | Filmes de Ação somem e filmes de Comédia aparecem |
| **Status** | ❌ Falhou |
| **Observação** | A alternância entre gêneros não atualizou a lista |

---

### CT002.3 — Voltar para "Todos"
| Campo | Detalhe |
|-------|---------|
| **Dado** | Usuário está com algum filtro de gênero ativo |
| **Quando** | Clica no botão "Todos" |
| **Então** | O filtro é removido |
| **Resultado esperado** | Todos os filmes populares voltam a ser exibidos |
| **Status** | ✅ Passou |

---

### CT002.4 — Filtro combinado com busca
| Campo | Detalhe |
|-------|---------|
| **Dado** | Usuário buscou por "Batman" |
| **Quando** | Clica no filtro "Ação" |
| **Então** | A lista é filtrada |
| **Resultado esperado** | Apenas filmes de Ação relacionados a "Batman" aparecem |
| **Status** | ⚠️ Comportamento inesperado |
| **Observação** | O filtro ignorou a busca e voltou para a lista padrão de filmes populares |