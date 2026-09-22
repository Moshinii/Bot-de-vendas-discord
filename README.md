# ⚙️ Moshiini_ Automações

Bot Discord completo para lojas virtuais com sistema de pagamentos via PIX, tickets, painéis de produtos, cupons de desconto, sistema de convites com recompensa, moderação anti-hack e muito mais.

Multi-servidor: cada servidor configura sua própria loja com produtos, preços, chave PIX, painéis e regras — de forma 100% independente.

> 💰 **Freemium**: gratuito com limites (5 produtos e 2 painéis por servidor, vendas ilimitadas), sem taxa e sem comissão. Quer mais? A licença Premium destrava tudo.
>
> 🆕 **Novo na v5.2 — a era dos painéis**: a gestão inteira do bot agora vive em **dois painéis com botões** (a Central `/painel_admin` para a equipe e o `/painel_dono` exclusivo do dono do bot). Dos 95 comandos antigos restaram **27** — o que era comando virou botão. Configurou uma vez, nunca mais digita.

---

## 🧭 Comece por aqui — escolha seu caminho

| Você é... | Caminho |
|---|---|
| 📱 **Usuário de celular** | Seção **"Guia do Usuário de Celular"** — tudo pelo painel, sem digitar nada |
| 💻 **Usuário de PC** | Seção **"Guia do Usuário de PC"** — comandos, painéis e exemplos |
| 🛍️ **Só quero comprar** | Seção **"Comprando pelo painel da loja"** — funciona igual no celular e no PC |
| 👑 **Dono de servidor, 1ª vez** | Seção **"Passo a Passo"** — configure sua loja em 10 minutos |

> 💡 **Dica**: todos os comandos exibem uma **tag de permissão** na descrição (ex.: `[ADMINS]`, `[TODOS]`) — ao digitar o comando no Discord você já vê quem pode usá-lo. E os comandos de gestão só aparecem no seletor de quem pode usá-los.

---

## 🚀 Adicione o Bot ao seu Servidor

```
https://discord.com/oauth2/authorize?client_id=1360681926318624908&permissions=8&scope=bot
```

> ⚠️ O bot precisa da permissão **Administrador** para funcionar corretamente (criar canais, cargos, gerenciar mensagens, bans, etc).

**Permissões essenciais:**
- ✅ Criar Convite (sistema de convites)
- ✅ Gerenciar Servidor (tracking de invites)
- ✅ Banir Membros (honeypot)
- ✅ Gerenciar Canais (tickets)
- ✅ Gerenciar Cargos (verificação, recompensas)
- ✅ Ler Histórico de Mensagens (transcripts)
- ✅ Gerenciar Mensagens (moderação)

---

## 💰 Planos

| | **Gratuito** 🆓 | **Premium** 💎 |
|---|---|---|
| Custo | R$ 0 — sem taxa, sem comissão | R$ 0,50/dia |
| Produtos | criar até **5** | **ilimitado** |
| Painéis | criar até **2** | **ilimitado** |
| Vendas, tickets, cupons, entrega | ✅ ilimitado | ✅ ilimitado |

- **Ativação instantânea**: `/loja vincular` — a loja já nasce no plano Gratuito, sem burocracia
- **Downgrade gracioso**: sua loja passou do limite quando a licença expirou? **Nada é removido nem bloqueado** — tudo continua vendendo; você só não cria itens novos até renovar ou excluir algo
- Produtos **inativos/desativados não contam** no limite
- Veja seu uso a qualquer momento: `/loja plano` (ex: "3/5 produtos, 1/2 painéis")
- Aumente o limite: `/loja mudardeplano`

---

## ⚡ Passo a Passo — Configure sua Loja em 10 Minutos

> Configuração feita **uma única vez** pelo dono do servidor (ou admins). Funciona no celular e no PC — tudo acontece **na Central de Administração** (`/painel_admin`), por botões e menus.

| # | O que fazer | Como fazer | Tag |
|---|---|---|---|
| 1️⃣ | **Adicionar o bot** | Use o link de convite acima (permissão Administrador) | — |
| 2️⃣ | **Ativar a loja grátis** | Digite `/loja vincular` → a loja nasce no plano Gratuito na hora | `[DONO DO SERV]` |
| 3️⃣ | **Abrir a Central** | `/painel_admin abrir` → menu 🗂️ → **⚙️ Configuração da Loja** → botão 💰 **PIX** (cola a chave — o bot criptografa antes de salvar) | `[GERENTE+]` |
| 4️⃣ | **Definir os canais** | Na mesma seção: 📡 **Canais** → log, provas, carrinho e categoria dos tickets | `[GERENTE+]` |
| 5️⃣ | **Cadastrar produtos** | Menu 🗂️ → **🛍️ Produtos** → 🆕 **Adicionar** → nome, preço (R$), estoque e descrição (até 5 no grátis) | `[GERENTE+]` |
| 6️⃣ | **Montar o painel da loja** | Menu 🗂️ → **🖼️ Painéis** → 🆕 criar → ➕ **ligar o produto** → 📮 **postar** no canal da loja | `[GERENTE+]` |
| 7️⃣ | **Fixar a Central no canal de gestão** | `/painel_admin fixo` → escolhe o canal → painel permanente com todas as seções em botões | `[GERENTE+]` |
| 8️⃣ | **Extras (opcional)** | Pelo menu 🗂️ da Central: ✅ Verificação (captcha por DM) · 🧑‍🤝‍🧑 Cargos & Auxiliares · 🎟️ Cupons · 🎁 Sorteios & Convites · 🛡️ Segurança & Honeypot · 💾 Backup de Imagens | `[GERENTE+]` |
| 9️⃣ | **Precisa de mais espaço?** | `/loja mudardeplano` → licença Premium (R$ 0,50/dia, criação ilimitada) | `[DONO DO SERV]` |

**Pronto!** Com o painel postado (passo 6) o servidor já pode vender. A Central fixa (passo 7) deixa a gestão 100% por botões — perfeita para quem administra pelo celular — e ela **nunca expira**: sobrevive a restarts e funciona para sempre.

---

## 📱 Guia do Usuário de Celular — Tudo pelo Painel

> No celular, digitar comando é trabalho braçal. Por isso o bot trabalha com **painéis fixos e botões**: você configura uma vez e depois é só tocar na tela.

### 🏪 A Central de Administração (para quem gerencia)

1. Alguém da equipe (gerente, admin ou o dono do servidor) digita `/painel_admin fixo` **uma única vez**, no canal de gestão da loja
2. O bot posta a **Central fixa** — um menu 🗂️ no topo lista todas as seções, e ela continua funcionando mesmo depois do bot reiniciar (nunca expira)
3. A partir daí, a gestão inteira é no toque, dentro da própria mensagem do painel:
   - 🛍️ **Produtos**: adicionar, editar, ativar/desativar, estoque e excluir
   - 🖼️ **Painéis**: criar, ligar produtos, editar e postar
   - ⚙️ **Configuração da Loja**: PIX, canais, campo de entrega, cliente, termos e carrinho
   - ✅ **Verificação** · 🧑‍🤝‍🧑 **Cargos & Auxiliares** · 🎟️ **Cupons** · 🎁 **Sorteios & Convites**
   - 🛡️ **Segurança & Honeypot** (armadilha anti-hack e desbanimentos)
   - 💾 **Backup de Imagens** (destino das imagens das transcrições — decide a equipe da loja)
   - 🧰 **Manutenção & Relatórios**: estatísticas, CSV de vendas, diagnóstico, **backup/restauração da loja** (validação anti-adulteração)
4. Toda resposta aparece **na própria mensagem do painel** (nada de chat poluído) e toda sub-tela tem **⬅️ Voltar**

### 🛍️ Comprando pelo celular (clientes)

1. Abra o canal com o **painel da loja** (postado na configuração)
2. Toque no **menu suspenso** e escolha o produto
3. Use os botões da tela: **Comprar**, **Calcular R$→Qtd** ou **Calcular Qtd→R$**
4. No carrinho: ajuste quantidades, remova itens e aplique cupom (menu ou botão **"Aplicar Código"**)
5. Toque em **Finalizar Compra** → abre um ticket privado com o **QR Code PIX**
6. Anexe o **comprovante** no ticket → a staff confirma → entrega do produto
7. Avalie o atendimento com **estrelas** ⭐

### 👤 Sua área pessoal (botões, sem digitar)

- `/minha_loja` → hub pessoal com botões: **Ver Sacola**, **Histórico**, **Gasto Total** e **Cupons**
- **Suporte**: mande uma DM no bot — o modmail abre um ticket privado com a staff (dono de servidor/loja)
- **Trocas com segurança**: `/trocar enviar` convida alguém para uma troca com middleman e recibo anti-fraude — o convite chega na DM da pessoa

> ✅ **Resumo do celular**: 1 comando para fixar a Central (uma vez) + `/minha_loja` quando quiser. Todo o resto é botão.

---

## 🛍️ Comprando pelo painel da loja (celular e PC)

O fluxo de compra é o mesmo nas duas plataformas — tudo por menu e botões:

1. **Abra o painel da loja** no canal de compras
2. **Selecione o produto** no menu suspenso
3. Escolha na tela: **Comprar** · **Calcular R$→Qtd** · **Calcular Qtd→R$** (a calculadora mostra o valor antes de você se comprometer)
4. Confirme a quantidade → o item vai para a **sacola**
5. Aplique um **cupom** (se tiver) e clique em **Finalizar Compra**
6. Um **ticket privado** é aberto com o QR Code PIX
7. Envie o **comprovante** → a staff confirma → **entrega** do produto
8. Avalie com **estrelas** — e consulte tudo depois em `/minha_loja`

---

## 💻 Guia do Usuário de PC — Comandos e Painéis

A gestão da loja é toda pela **Central de Administração** (`/painel_admin`) e pelo **Painel do Dono** (`/painel_dono`) — restaram na árvore apenas **27 comandos**, organizados por quem pode usar. Cada comando também mostra a tag na descrição, dentro do Discord.

**Legenda das tags:**

| Tag | Quem pode usar |
|---|---|
| `[TODOS]` | Qualquer membro |
| `[GERENTE+]` | Dono do servidor, admins **ou gerentes da loja** (nível ≥ 1) |
| `[DONO DO SERV]` | Somente o dono do servidor |
| `[DONO DO BOT]` | Somente o dono do bot |

### 🗂️ Antes de tudo: os dois painéis

| Comando | O que faz | Exemplo de uso |
|---|---|---|
| `/painel_admin abrir` `[GERENTE+]` | Abre a **Central de Administração** (efêmero) — menu com 10 seções de gestão | `/painel_admin abrir` → toca em "🛍️ Produtos" |
| `/painel_admin fixo` `[GERENTE+]` | Posta a Central **fixa** num canal — sobrevive a restarts e nunca expira | `/painel_admin fixo` → escolhe `#gestão` |
| `/painel_dono abrir` `[DONO DO BOT]` | Abre o **Painel Exclusivo do dono do bot** (efêmero) | `/painel_dono abrir` |

**O que tem dentro da Central (`/painel_admin`)** — tudo por botões, na mesma mensagem, com ⬅️ Voltar:

| Seção | O que você faz ali |
|---|---|
| 🛍️ **Produtos** | Adicionar (modal), editar, ativar/desativar, excluir, limiar de estoque com aviso automático |
| 🖼️ **Painéis** | Criar, ligar/desligar produtos, editar textos/banner/cor e postar ou atualizar o painel da loja |
| ⚙️ **Configuração da Loja** | PIX (criptografado), canais de log/provas/carrinho/tickets, campo de entrega (Nick/ID), cargo de cliente, termos e auto-close do carrinho |
| ✅ **Verificação** | Canal + cargo da verificação (captcha por DM) e postagem do painel de verificar |
| 🧑‍🤝‍🧑 **Cargos & Auxiliares** | Cargo de suporte, canais ignorados na contagem e recompensas por gasto |
| 💾 **Backup de Imagens** | Destino das imagens das transcrições/provas (Site FreeImage.host / Canal do Discord / Ambos), canal que recebe, teste de envio e resetar — **uso da equipe da loja** |
| 🎟️ **Cupons** | Criar cupom público (com código) ou de sorteio, listar, excluir e desativar tipos — com vínculo a produto, quantidade mínima, "leva tudo", mostrar no painel e auto-aplicar |
| 🎁 **Sorteios & Convites** | Criar/gerenciar sorteios (com requisito de cargo/mensagens) e configurar/desativar o sistema de convites |
| 🛡️ **Segurança & Honeypot** | Ativar/desativar a armadilha, ver status e bans, desbanir usuário |
| 🧰 **Manutenção & Relatórios** | Estatísticas de vendas, exportar CSV, diagnóstico da loja, **backup JSON da loja** e restauração (validação anti-adulteração) |

**O que tem no Painel do Dono (`/painel_dono`)** — só o dono do bot abre; gerentes e admins de loja nem veem que existe:

| Seção | O que você faz ali |
|---|---|
| 🔑 **Licenças & Equipe** | Cobrança de licença via PIX, adicionar/remover gerentes de loja, bloquear/desbloquear lojas, definir/verificar licenças e avisar geral (todos/donos/logistas) |
| 🛡️ **Modmail** | Bloquear/desbloquear usuário de abrir tickets e definir a categoria dos tickets de suporte |
| 🌐 **Ações Globais** | Limpar lojas inativas (30+ dias), remover um cargo de todos os membros, DM para todos (com confirmação) e status global do bot |
| 🔄 **Sincronizar Comandos** | Força o reenvio da lista de comandos ao Discord (útil se algo novo demorar a aparecer) |

### 👥 Comandos de cliente `[TODOS]`

| Comando | O que faz | Exemplo de uso |
|---|---|---|
| `/ajuda` | Central de Ajuda interativa: botões por categoria com todos os comandos e tags | `/ajuda` → toca em "🛒 Comprar" |
| `/minha_loja` | Hub pessoal com botões: sacola, histórico, gasto e cupons | `/minha_loja` → toca em "Ver Sacola" |
| `/loja top` | Ranking dos maiores compradores do servidor | `/loja top` |
| `/loja meugasto` | Quanto você já gastou e o próximo cargo de recompensa | `/loja meugasto` → "faltam R$ 50 pro cargo Comprador" |
| `/loja robux calcular_robux` | Conversão R$ ↔ Robux (com ou sem a taxa de 30%) | informe `100` R$ e escolha "com taxa" |
| `/cupom resgatar` | Roleta de cupons: gasta mensagens acumuladas para tentar a sorte | `/cupom resgatar` → gira com o saldo de mensagens |
| `/cupom meuscupons` | Lista seus cupons disponíveis | `/cupom meuscupons` |
| `/convite criar` | Gera seu link de convite rastreado (1 ciclo por vez) | `/convite criar` → compartilha o link |
| `/convite status` | Recupera o link do seu convite ativo + progresso do ciclo | `/convite status` → "3/5 convites" |
| `/convite resgatar` | Abre ticket para receber a recompensa ao bater a meta | `/convite resgatar` |
| `/convite ranking` | Top 10 convidadores do servidor | `/convite ranking` |
| `/sorteio minhasmensagens` | Seu saldo de mensagens para sorteios com requisito | `/sorteio minhasmensagens` |
| `/trocar enviar` | Convida alguém para uma troca com middleman (MM) | `/trocar enviar` → escolhe a pessoa → convite na DM dela (expira em 15 min) |
| `/trocar aceitar` | Aceita a troca — abre o ticket privado dos dois lados | `/trocar aceitar` após receber o convite |
| `/trocar verificar` | Valida a assinatura digital de um recibo | anexe o recibo no comando → bot confirma autenticidade |
| `/status_publico` | Resumo público do bot (servidores, membros, vendas) | `/status_publico` |
| `/sugestao` | Envia sugestão direto pro dono do bot (1 a cada 24h) | `/sugestao` → "adiciona pagamento via card" |

**Fluxo do sistema de convites:**
1. `/convite criar` → recebe um link personalizado
2. Compartilhe → cada entrada pelo link soma +1 no seu contador
3. Bateu a meta (ex: 5)? Chega uma **DM avisando**
4. `/convite resgatar` → ticket com a staff + prêmio (+ cargo automático, se configurado)
5. O ciclo encerra → pode criar outro convite e continuar ganhando

### 👑 Comandos do dono do servidor `[DONO DO SERV]`

| Comando | O que faz | Exemplo de uso |
|---|---|---|
| `/loja vincular` | Ativa a loja grátis (plano Gratuito, sem taxa) | `/loja vincular` — só o dono do servidor consegue |
| `/loja plano` | Plano atual, uso dos limites e dívidas antigas | `/loja plano` → "3/5 produtos, 1/2 painéis" |
| `/loja mudardeplano` | Compra/renova a licença Premium (R$ 0,50/dia) | `/loja mudardeplano` → paga o PIX → destrava |

### 🤖 Comandos do dono do bot `[DONO DO BOT]`

| Comando | O que faz |
|---|---|
| `/painel_dono abrir` | Abre o Painel Exclusivo (licenças, modmail e ações globais — detalhes acima) |
| `/modmail_admin bloquear` | Impede um usuário de abrir tickets de Modmail (atalho para a seção 🛡️ do painel do dono) |
| `/modmail_admin desbloquear` | Libera os tickets do usuário |
| `/sugestao_admin bloquear` | Impede um usuário de enviar sugestões |
| `/sugestao_admin desbloquear` | Libera as sugestões do usuário |

> 🧭 **Onde foi parar o resto?** Todas as funções dos antigos `/produto`, `/painel`, `/gerenciar_loja`, `/configurar`, `/recompensa`, `/verificacao`, `/honeypot`, `/backup`, `/botadmin`, `/revalidar`, `/status`, `/limpar_lojas_inativas` e `/setup` continuam lá — viraram **botões nas seções da Central** (`/painel_admin`) e do **Painel do Dono** (`/painel_dono`). Menus para tocar, modais com campos na tela — mais rápido que digitar comando.

---

## ✨ Funcionalidades

### 🛒 Loja e Compras
- **Planos freemium** — grátis com limites, licença destrava (veja tabela de planos)
- **Painéis dinâmicos** com produtos, preços, estoque e emojis personalizados
- **Carrinho** com edição de quantidades, remoção e cupons
- **Pagamento via PIX** com QR Code gerado automaticamente
- **Tickets de compra** privados, com comprovante e entrega dentro do canal
- **Calculadora integrada** (R$ → Quantidade / Quantidade → R$) na tela de compra
- **Avaliação por estrelas** após entrega · **histórico** e **ranking de compradores**
- **Trocas com middleman (MM)** — convite por DM, ticket dos dois lados e **recibo anti-fraude assinado digitalmente** (`/trocar`)

### 🎟️ Cupons de Desconto
- Cupons **públicos** (código) e **de sorteio** (resgatados com mensagens)
- **Vinculação a produto**, quantidade mínima, modo "leva tudo", exibição no painel e aplicação automática
- Limite de usos e validação em tempo real (desconto só no produto vinculado)

### 🎁 Convites com Recompensa
- Modelo **1 convite = 1 ciclo**, tracking automático de quem convidou quem
- Notificação por DM ao bater a meta · resgate via ticket · cargo automático opcional
- Ranking de convidadores e recuperação do link do convite

### 🧹 Moderação e Segurança
- **Honeypot anti-hack** com ban temporário e desbanimento automático
- Log de membros (entrada, saída, kick, ban) e **transcripts HTML** dos tickets — com **backup de imagens configurável pela própria loja** (site, Discord ou ambos)
- Verificação com **captcha por DM** · modmail · contador de mensagens
- **Sorteios** com requisito de cargo e de mensagens

### 📊 Painéis de Controle (v5.2)
- **Central de Administração** (`/painel_admin`) com **10 seções** de gestão — tudo por botões, menus e modais, na mesma mensagem, com ⬅️ Voltar
- **Painel Exclusivo do Dono** (`/painel_dono`) — licenças, modmail e ações globais separados da equipe
- **Painel fixo que nunca expira** — sobrevive a restarts e os botões funcionam para sempre
- Estatísticas de vendas, relatórios (CSV) e backup/restauração por servidor

### 🔔 Automações
- **Presença rotativa** mostrando estatísticas do bot
- Limpeza automática de lojas inativas (carência de 30 dias)
- Lembretes de licença (1, 3 e 7 dias antes) e backup automático semanal
- Sincronização de painéis ao editar produtos · verificação de integridade do banco a cada inicialização

---

## 🆘 Suporte

- **Celular ou PC**: mande uma **DM no bot** para abrir um modmail com a staff (dono de servidor/loja)
- Abra um **ticket de suporte** pelo painel
- Use `/sugestao` para enviar sugestões direto pro dono do bot
- Dúvidas sobre permissões? Digite o comando no Discord e olhe a **tag** na descrição — ou comece pelo `/ajuda`

---
