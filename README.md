# Caixa Baixa

Controle financeiro pessoal minimalista — feito para uso diário no celular, sem fricção.

## O que o app faz

- **Saldo disponível** — valor atual com visibilidade toggleável
- **Meta diária** — quanto você pode gastar por dia com base no que sobra
- **Gasto hoje** — total do dia em tempo real
- **A pagar / Já pago** — clicáveis, com detalhamento completo
- **Despesas fixas** — com vencimento, categorias e cofres (grupos nomeados)
- **Gastos do dia a dia** — registro rápido com categoria
- **Dívidas** — controle informal entre contas, com opção de contar no total
- **Ajustes de saldo** — soma, subtrai, corrige, com histórico e data
- **Sync com Google Drive** — backup automático a cada alteração
- **Export/Import JSON** — backup manual disponível
- **Tema claro/escuro** — amanhecer e entardecer

## Como usar no dia a dia

### Celular (uso principal)
1. Abra o app pelo ícone na tela inicial
2. Registre gastos na seção **Gastos do dia a dia**
3. Marque despesas como pagas quando pagar
4. O sync com Drive acontece automaticamente

### Desktop (consulta)
1. Abra `https://Oruam77.github.io/caixabaixa/caixa-baixa_v2_5_3.html` no Chrome
2. Clique no botão **↔** segurando **Shift** para puxar os dados do Drive
3. Os valores ficam iguais ao celular

## Sync com Google Drive

- **Automático:** a cada alteração no celular, os dados são salvos no Drive
- **Manual salvar:** clique no botão ↔ na topbar
- **Restaurar do Drive:** Shift + clique no botão ↔

Na primeira vez, o app pede autorização para acessar o Drive. Autorize com a mesma conta Google do celular.

## Arquivos no repositório

| Arquivo | Função |
|---------|--------|
| `caixa-baixa_v2_5_3.html` | App principal |
| `manifest.json` | Configuração PWA |
| `sw.js` | Service Worker (cache offline) |
| `icon-192.png` | Ícone 192×192px |
| `icon-512.png` | Ícone 512×512px |

## Atualizar o app

1. Baixe o novo HTML
2. Suba no repositório junto com `manifest.json` e `sw.js` atualizados
3. Os dados do localStorage são preservados entre versões

## Versão atual

v2.5.3 PWA
