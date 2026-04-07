# CT001 — Busca por nome de filme

**Funcionalidade:** Campo de busca  
**Prioridade:** Alta  
**Ambiente:** gabriellesca.github.io/buscador-filmes

---

## Pré-condições
- Aplicação aberta no navegador
- Conexão com a internet ativa

---

## Casos de teste

### CT001.1 — Busca com termo válido
| Campo | Detalhe |
|-------|---------|
| **Dado** | Usuário acessa a aplicação |
| **Quando** | Digita "Inception" no campo de busca e pressiona Enter |
| **Então** | Filmes relacionados ao termo são exibidos na tela |
| **Resultado esperado** | Cards de filmes com "Inception" no título aparecem |
| **Status** | ✅ Passou |
| **Observação** | Termo exibido com aspas extras no cabeçalho de resultados. Investigar se é bug de formatação. |
---

### CT001.2 — Busca com termo inválido
| Campo | Detalhe |
|-------|---------|
| **Dado** | Usuário acessa a aplicação |
| **Quando** | Digita "xyzxyzxyz" no campo de busca e pressiona Enter |
| **Então** | Nenhum resultado é encontrado |
| **Resultado esperado** | Mensagem de "nenhum resultado" ou tela vazia sem erros |
| **Status** | ✅ Passou |

---

### CT001.3 — Busca com campo vazio
| Campo | Detalhe |
|-------|---------|
| **Dado** | Usuário acessa a aplicação |
| **Quando** | Deixa o campo vazio e pressiona Enter |
| **Então** | A aplicação não quebra |
| **Resultado esperado** | Filmes populares continuam exibidos ou nada muda |
| **Status** | ✅ Passou |