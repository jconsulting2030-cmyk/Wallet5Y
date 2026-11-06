# De 1 a 100 — a tua app de carteira (sem App Store)

Uma web app que se instala no ecrã principal do iPhone. Os dados ficam **só no teu iPhone** (no Safari); as cotações vêm da internet.

## 1. Pôr a app online (grátis, ~10 min, uma vez)

1. Cria uma conta em **github.com** (grátis).
2. Carrega em **+ → New repository**. Nome: `carteira` · **Private** não funciona com Pages grátis → escolhe **Public** (o código é público, **os teus dados não**: ficam no iPhone, nunca vão para o GitHub).
3. No repositório: **Add file → Upload files** e arrasta os 6 ficheiros desta pasta (`index.html`, `manifest.json`, `sw.js`, `icon-180.png`, `icon-512.png`, `LEIA-ME.md`). **Commit changes**.
4. **Settings → Pages → Branch: main / (root) → Save.** Ao fim de 1–2 min aparece o endereço: `https://<o-teu-utilizador>.github.io/carteira/`.

## 2. Instalar no iPhone

1. Abre esse endereço no **Safari**.
2. **Partilhar (□↑) → Adicionar ao ecrã principal → Adicionar.**
3. Abre a app pelo ícone novo (abre em ecrã inteiro).

## 3. Cotações automáticas (2 min)

1. Em **alphavantage.co** → *Get free API key* → preenche e copia a chave.
2. Na app: **Definições → Chave Alpha Vantage → Guardar e atualizar.**
3. Símbolos por omissão: `VWCE.DEX`, `PPFB.DEX`, `SXRV.DEX` (Xetra). Se algum não atualizar, a app avisa; nesse caso diz-me qual e procuro o símbolo certo.
4. Limite grátis: 25 pedidos/dia. A app atualiza no máximo de 30 em 30 min (3 pedidos por atualização com os 3 ETFs). O Bitcoin vem do CoinGecko (sem chave).

## 4. Começar com os teus dados (semana de 23 nov)

1. **Definições → Apagar dados de exemplo e começar.**
2. **Movimentos → Novo movimento** para cada compra (data, ativo, quantidade, preço). O depósito de 200 € no pote de ações é "Depósito no pote".
3. Ou importa um CSV com o formato `data;tipo;ativo;quantidade;preço;custos;corretora` (há um botão para descarregar o modelo). Para importar diretamente os extratos da XTB e da Trade Republic, envia-me um exemplo de cada (podes apagar valores pessoais) e adapto a importação.
4. Transferência para a cold wallet: tipo **Bitcoin: Trade Republic → cold wallet**, com o BTC enviado, a taxa da rede (em BTC) e o TXID.

## 5. Cópias de segurança

Os dados vivem no Safari deste iPhone. Se apagares os dados do Safari ou mudares de telemóvel, perdes-os. **Definições → Exportar cópia de segurança** uma vez por mês (guarda o ficheiro no iCloud Drive). Para recuperar: **Restaurar cópia**.

## 6. Atualizar a app

Quando eu te enviar uma versão nova, substitui os ficheiros no GitHub (Upload files → Commit). Os teus dados não se perdem.

*Não é aconselhamento financeiro. Cotações de terceiros podem ter atraso.*
