# Contexto do Projeto — Handoff entre IAs

> **Última atualização:** `<AAAA-MM-DD HH:MM>`
> **Atualizado por:** `<nome/modelo da IA>`
> **Sessão nº:** `<número>`
> **Status geral:** `<não iniciado | em andamento | bloqueado | concluído>`

---

## 📌 Instruções para a IA (leia primeiro)

Este arquivo é o **cérebro compartilhado** entre sessões. Ele existe para que outra IA continue seu trabalho sem reler tudo.

**Ao INICIAR uma sessão:**
1. Leia este arquivo inteiro antes de qualquer ação.
2. Confira a seção **9. Próximos passos** e **8. Em andamento** para saber de onde continuar.
3. Verifique se o estado real do projeto bate com o que está descrito aqui (arquivos podem ter mudado).

**Durante o trabalho:**
- Atualize as seções 7, 8 e 10 a cada marco concluído, não só no fim.

**Quando os tokens estiverem acabando (~10–15% restantes):**
1. PARE de iniciar novas tarefas.
2. Preencha/atualize TODAS as seções abaixo.
3. Seja específico: caminhos de arquivo, nomes de função, comandos exatos, mensagens de erro.
4. Escreva a seção 9 como se o leitor não tivesse nenhuma memória da conversa.

**Regras de preenchimento:**
- ✅ Seja objetivo e factual. Prefira listas e tabelas.
- ✅ Registre o **porquê** das decisões, não só o quê.
- ❌ **NUNCA grave segredos aqui:** senhas, tokens, chaves de API, `JWT_SECRET`, IDs de cliente OAuth, IDs de pastas privadas, CPFs, dados reais de clientes, e-mails pessoais, caminhos que revelem o nome de usuário. Use `<placeholder>` e diga **onde** o valor real fica (ex.: "no `.env.local`").
- ❌ Não apague histórico útil; mova itens concluídos para a seção 7.

---

## 1. Objetivo do projeto

**O que é:**
`<descrição em 2–3 linhas>`

**Usuário-alvo:**
`<quem usa>`

**Objetivo da sessão/tarefa atual:**
`<o que se está tentando alcançar agora>`

---

## 2. Stack e ambiente

| Camada | Tecnologia / versão |
|--------|---------------------|
| `<ex.: Frontend>` | `<...>` |
| `<...>` | `<...>` |

**Sistema operacional / shell:** `<...>`
**Restrições de ambiente:** `<ex.: PowerShell bloqueia .ps1, usar cmd.exe>`

**Como rodar:**
```
<comando 1>
<comando 2>
```

**Como verificar (testes / typecheck / lint):**
```
<comandos>
```

---

## 3. Estrutura de arquivos

```
<árvore resumida com comentário de uma linha por item relevante>
```

**Arquivos sensíveis (nunca versionar nem copiar o conteúdo aqui):**
| Arquivo | Para que serve | Onde obter |
|---------|----------------|------------|
| `<...>` | `<...>` | `<...>` |

---

## 4. Arquitetura e decisões-chave

| # | Decisão | Motivo | Data |
|---|---------|--------|------|
| 1 | `<...>` | `<...>` | `<...>` |

**Padrões de código adotados:**
- `<ex.: valores monetários em centavos inteiros>`

---

## 5. Modelo de dados / API

**Entidades principais:**
| Entidade | Campos relevantes | Observações |
|----------|-------------------|-------------|
| `<...>` | `<...>` | `<...>` |

**Endpoints / interfaces principais:**
```
<MÉTODO /rota — descrição>
```

---

## 6. Regras de negócio implementadas

1. `<regra>`
2. `<regra>`

---

## 7. ✅ Concluído

| Data | O que foi feito | Arquivos tocados |
|------|-----------------|------------------|
| `<AAAA-MM-DD>` | `<...>` | `<caminho/arquivo>` |

---

## 8. 🔧 Em andamento

**Tarefa atual:** `<descrição>`

**Estado exato em que parou:**
`<ex.: função X criada em arquivo Y, falta ligar na rota Z>`

**Arquivos modificados e ainda não validados:**
- `<caminho>` — `<o que mudou>`

**Última coisa que rodei e o resultado:**
```
<comando>
<saída/erro relevante>
```

---

## 9. ➡️ Próximos passos (ordem de prioridade)

1. [ ] `<passo concreto, com arquivo e ação>`
2. [ ] `<...>`
3. [ ] `<...>`

**Pendências conhecidas / ainda não implementado:**
- `<...>`

---

## 10. ⚠️ Problemas, bloqueios e armadilhas

| Problema | Sintoma / erro | Causa conhecida | Solução ou status |
|----------|----------------|-----------------|-------------------|
| `<...>` | `<...>` | `<...>` | `<...>` |

**O que NÃO funcionou (não repetir):**
- `<tentativa> → <por que falhou>`

---

## 11. Perguntas em aberto para o usuário

- [ ] `<pergunta que precisa de decisão humana>`

---

## 12. Notas livres

`<qualquer contexto adicional que não coube acima>`

---

## 13. Log de sessões

| Sessão | Data | IA | Resumo em uma linha |
|--------|------|----|---------------------|
| 1 | `<...>` | `<...>` | `<...>` |
