# CT003 — Favoritos

**Status:** Executado  
**Data:** 21/05/2026  
**Testado por:** Gabrielle Sca  

---

## Descrição
Verificar o comportamento completo da funcionalidade de favoritos,
incluindo adição, remoção, persistência e estado vazio.

---

## Casos de Teste

### CT003.1 — Adicionar filme aos favoritos
**Passos:**
1. Acessar gabriellesca.github.io/buscador-filmes
2. Aguardar carregamento dos filmes
3. Clicar no ícone de coração de qualquer filme

**Resultado esperado:** Ícone fica marcado/colorido e filme aparece na seção Meus Favoritos  
**Resultado obtido:** ✅ Conforme esperado

---

### CT003.2 — Persistência após fechar o navegador
**Passos:**
1. Favoritar um filme
2. Fechar a aba
3. Reabrir o site

**Resultado esperado:** Filme continua marcado como favorito  
**Resultado obtido:** ✅ Conforme esperado

---

### CT003.3 — Remover filme dos favoritos
**Passos:**
1. Com um filme favoritado, clicar novamente no coração
2. Verificar seção Meus Favoritos

**Resultado esperado:** Filme removido da seção  
**Resultado obtido:** ✅ Conforme esperado

---

### CT003.4 — Comportamento de toggle no coração
**Passos:**
1. Clicar no coração de um filme (favoritar)
2. Clicar novamente no mesmo coração (desfavoritar)

**Resultado esperado:** Alterna entre favoritado e não favoritado  
**Resultado obtido:** ✅ Conforme esperado

---

### CT003.5 — Seção de favoritos sem itens
**Passos:**
1. Remover todos os filmes favoritados
2. Acessar a seção Favoritos

**Resultado esperado:** Mensagem orientando o usuário a adicionar favoritos  
**Resultado obtido:** ✅ Conforme esperado