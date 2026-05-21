# CT004 — Modal de Detalhes do Filme

**Status:** Executado  
**Data:** 21/05/2026  
**Testado por:** Gabrielle Sca  

---

## Descrição
Verificar o comportamento do modal de detalhes exibido
ao clicar em um filme, incluindo exibição de informações,
abertura, fechamento e integração com favoritos.

---

## Casos de Teste

### CT004.1 — Abrir modal ao clicar no filme
**Passos:**
1. Acessar gabriellesca.github.io/buscador-filmes
2. Clicar em qualquer card de filme

**Resultado esperado:** Modal abre com detalhes do filme  
**Resultado obtido:** ✅ Conforme esperado

---

### CT004.2 — Fechar modal pelo botão X
**Passos:**
1. Abrir o modal de um filme
2. Clicar no botão X

**Resultado esperado:** Modal fecha e retorna à listagem  
**Resultado obtido:** ✅ Conforme esperado

---

### CT004.3 — Consistência de informações entre card e modal
**Passos:**
1. Observar título, ano e nota de um filme na listagem
2. Clicar no filme e comparar as informações no modal

**Resultado esperado:** Título, ano e nota idênticos nos dois lugares  
**Resultado obtido:** ✅ Conforme esperado

---

### CT004.4 — Adicionar favorito pelo modal
**Passos:**
1. Abrir modal de um filme não favoritado
2. Clicar em "Adicionar aos Favoritos"
3. Fechar modal e verificar seção Meus Favoritos

**Resultado esperado:** Filme aparece na seção de favoritos  
**Resultado obtido:** ✅ Conforme esperado

---

### CT004.5 — Botão alterna conforme estado do favorito
**Passos:**
1. Abrir modal de um filme já favoritado

**Resultado esperado:** Botão exibe "Remover dos Favoritos"  
**Resultado obtido:** ✅ Conforme esperado — botão altera texto
e remove o filme dos favoritos ao ser clicado