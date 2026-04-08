# BUG001 — Filtro por gênero não filtra os resultados

**Severidade:** Alta  
**Prioridade:** Alta  
**Status:** Aberto  
**Encontrado em:** CT002.1, CT002.2, CT002.4  
**Data:** 08/04/2026  

---

## Descrição
Os botões de filtro por gênero não atualizam a lista de filmes exibida.

---

## Passos para reproduzir
1. Acessar gabriellesca.github.io/buscador-filmes
2. Aguardar carregamento dos filmes populares
3. Clicar em qualquer botão de gênero (ex: "Ação")

## Resultado obtido
A lista de filmes permanece inalterada após clicar no filtro.

## Resultado esperado
Somente filmes do gênero selecionado devem ser exibidos.

---

## Comportamento adicional (CT002.4)
Ao buscar "Batman" e clicar em "Ação", a lista de resultados da busca é substituída pela lista padrão de filmes populares — a busca é perdida.

## Resultado esperado (CT002.4)
O filtro deveria agir sobre os resultados da busca, ou manter o contexto atual.

---

## Ambiente
- Navegador: Chrome
- URL: gabriellesca.github.io/buscador-filmes
- Dispositivo: Desktop