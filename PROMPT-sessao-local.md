Você vai continuar um planejamento de compras em Ciudad del Este (CDE), no Paraguai. A pesquisa começou numa sessão na nuvem que **não conseguia abrir o ComprasParaguai nem os sites das lojas** (a rede bloqueava). Aqui você tem acesso livre à internet e ao navegador. Use isso para trocar estimativas por preços reais.

## Contexto

- **Grupo:** 5 pessoas: João, mãe do João, Letícia, Bruno e Bruna.
- **Como vamos:** a pé, atravessando a Ponte da Amizade a partir de Foz do Iguaçu. Tudo precisa ser alcançável a pé no microcentro de CDE.
- **Lojas:** só lojas grandes, com boa reputação e que emitem nota (*factura*).
- **Repositório:** `github.com/BrunoMediador/Paraguai`, branch `claude/paraguay-shopping-itinerary-ft8wgu`. Faça `git pull` antes de começar.
  - `roteiro-paraguai.html`: página interativa para celular, com as abas Roteiro, Opções, Lista, Lojas, Antes de ir e Fontes. Os dados ficam em arrays JS dentro do próprio arquivo:
    - `STOPS`: paradas do roteiro;
    - `OPTIONS`: opções por produto, no formato `[loja, endereço, preço, link, nota, éLinkDoUsuário]`;
    - `PEOPLE`: lista por pessoa, no formato `[nome, preçoUSD, onde, éEstimativa, éOpcional]`;
    - `STORES`: fichas das lojas;
    - `PREP`: checklist da véspera.
  - `README.md`: a mesma informação em Markdown.

## Decisões já tomadas (não mude)

1. **Não fale de cota, imposto, e-DBV nem Receita Federal** em lugar nenhum. O usuário pediu para tirar tudo isso.
2. **A fonte principal de preço é o ComprasParaguai.** Use `comprasparaguai.com.br` ou `mobile.comprasparaguai.com.br`. Os preços estão em US$. Use os sites das lojas só para confirmar.
3. **Só aparelho novo e lacrado.** Descarte anúncios de swap, recondicionado, "Vitrina", "caixa danificada" e "somente aparelho". A única exceção é o iPhone 15 Pro Max do Bruno, que é opcional.
4. **Só lojas de Ciudad del Este.** Ignore anúncios de Pedro Juan Caballero, Salto del Guairá e Assunção.
5. **Mantenha a ordem do roteiro:** travessia → 1. Nissei (Shopping Hijazi) → 2. Jebai Center + Lai Lai Center → 3. Monalisa + Cellshop → 4. Mega Eletrônicos → 5. Shopping China (almoço) → 6. Shopping Paris → volta pela ponte até 14h30.
6. **iPhone:** na Nissei, só anotar o preço. A compra é no Jebai (Atacado Connect, Mestre Atacado, Mobile Zone). Só compre na Nissei se a diferença for menor que ~US$ 30.
7. **Atacado Connect:** tem "não recomendada" no Reclame Aqui e existe um site falso copiando a loja. Só confie em `atacadoconnect.com`.

## Lista de compras (com o que já foi definido)

**João**
- iPhone 17 Pro Max 512GB Deep Blue (MFXM4LL/A). Link que ele achou: https://www.comprasparaguai.com.br/celular-apple-iphone-17-pro-max-a3257-mfxm4lla-512gb-deep-blue__5016711/ . Já visto no Shopping China por US$ 1.520.
- **iPad Air 5 M1 64GB Space Gray (MM9C3LL/A).** É esse modelo específico. Links:
  - https://www.comprasparaguai.com.br/apple-ipad-air-5-2022-mm9c3lla-109-wifi-chip-m1-64gb-space-gray__4693094/
  - Tellecon Cell (Hijazi Center, 4º andar, loja 406; sábado fecha 12h): https://telleconcell.com.py/item/ipad-air-5th-mm9c3lla-109-64gb-spgray-13833
  - O usuário gostou destas 3 alternativas e quer que elas continuem no documento, com endereço, preço e link: **Nissei**, **Visão VIP** (Lai Lai, 4º andar) e **Prime Shop** (Lai Lai, 2º–3º andar).
- Ray-Ban Meta Wayfarer **Gen 2** (RW4012). Link: https://www.comprasparaguai.com.br/oculos-de-sol-smart-ray-ban-meta-wayfarer-gen-2-rw4012-large-shiny-blackg-15-green__5039842/ . **O usuário achou por "400 e poucos dólares"**: encontre essa oferta e confirme que é o Gen 2, não o Gen 1.
- Notebook Asus Vivobook Pro 15 OLED Q533MJ-U73050. Link: https://www.comprasparaguai.com.br/notebook-asus-vivobook-pro-15-q533mj-u73050-intel-core-ultra-7-14ghz-memoria-16gb-ssd-1tb-156-windows-11-rtx-3050-6gb_56020/ . O "a partir de US$ 458" parece erro, e o preço realista visto foi US$ 899. Candidatos: Alborada, Topdek, Visão VIP (todos no Lai Lai Center), Atacado Connect e Nissei.
- Apple Watch **Series 9 41mm**. Link: https://comparaguay.com.py/reloj-apple-watch-series-9-41mm_48980/ . Se não tiver estoque, mostre o Series 10 e o Series 11 como plano B.
- Itens menores:
  - pijama kigurumi;
  - mouse pad gamer de 1 m;
  - fone in-ear;
  - power bank 50.000 mAh;
  - mouse Bluetooth;
  - capinha e película para iPhone 17 Pro Max e para iPad Air 5.

**Mãe do João:** iPhone 17 Pro Max 256GB, perfume, skincare, produtos de cabelo e óculos Ray-Ban feminino.

**Letícia:** skincare e produtos de beleza, tênis de primeira linha (opcional). A loja "My Shoes" que ela citou não foi encontrada em CDE: tente de novo. Hoje as alternativas são Casa Angela e TL Sports, no Shopping Paris.

**Bruno:** óculos Oakley Meta HSTN, lanterna de cabeça, smartwatch custo-benefício, iPhone 15 Pro Max (opcional, só se sair por menos de R$ 3 mil; swap é aceitável aqui).

**Bruna:** iPhone 16 Pro ou 17 Pro, até R$ 6 mil, e skincare.

## O que fazer

1. **Pesquisar preços:** para cada item de cada pessoa, abra o ComprasParaguai, ordene por menor preço e anote as **3 melhores opções** que obedeçam às decisões acima. Para cada opção registre loja, endereço em CDE, preço em US$, data em que viu e link do anúncio.
2. **Validar os links do usuário:** confirme se cada link dele é o melhor preço. Se não for, diga qual é melhor e quanto se economiza.
3. **Atualizar `OPTIONS`:** hoje só tem os 5 itens caros do João. Inclua todos os itens de todas as pessoas, marcando os links do usuário com `éLinkDoUsuário = true`.
4. **Atualizar `PEOPLE`:** coloque o menor preço real de cada item e mude `éEstimativa` para `false` quando achar o preço. Atualize o câmbio padrão (`#fx`) com o dólar comercial do dia.
5. **Conferir o mapa:** no Google Maps, confirme os endereços e os tempos a pé a partir da Aduana paraguaia. Se alguma loja escolhida ficar fora do roteiro, encaixe-a na parada mais próxima. Não crie paradas longe.
6. **Conferir horários:** confirme o horário de cada loja e avise sobre as que fecham cedo no sábado.
7. **Atualizar os arquivos:** atualize o `README.md` com as mesmas informações. Mantenha o visual e a estrutura da página.
8. **Testar a página:** abra `roteiro-paraguai.html` no navegador em 400 px de largura, nos temas claro e escuro. Ela não pode ter rolagem horizontal nem erro no console.
9. **Enviar:** faça commit e push na mesma branch.

## Resposta final

Termine com:
- uma tabela curta por pessoa, com item, melhor loja, preço em US$ e link;
- o total por pessoa e o total do grupo, em US$ e em R$;
- o que não foi possível confirmar.

Escreva em português, direto, sem enrolação.
