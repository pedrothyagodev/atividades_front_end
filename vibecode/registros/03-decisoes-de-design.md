# Decisões de design

## Tema e objetivo

- **Tema:** Biela, uma oficina de bicicletas de bairro na Vila Madalena, em São Paulo. É uma marca fictícia.
- **Quem escolheu:** a IA. O enunciado deixa o tema livre e o aluno não indicou preferência. Pode ser trocado.
- **Para quem:** quem usa a bike no dia a dia e quer saber quanto vai pagar e quanto tempo vai ficar sem ela.
- **O que a página precisa fazer:** levar a pessoa a agendar uma revisão.

## Estrutura da página

1. **Topo:** nome da oficina e três links (Serviços, Como funciona, Contato).
2. **Hero:** título com a promessa principal ("Sua bike de volta na rua em até 24 horas"), um texto curto, o botão "Agendar revisão" e uma caixa amarela com a revisão completa e o preço.
3. **Serviços e preços:** quatro serviços, cada um com descrição, preço e prazo.
4. **Como funciona:** três passos, que são uma sequência de verdade (trazer a bike, diagnóstico, retirar).
5. **Depoimento:** uma frase de uma cliente.
6. **Contato:** endereço, horário, e-mail e o botão "Chamar a oficina".
7. **Rodapé:** avisa que a marca é fictícia.

## Por que essas escolhas

- **Preço e prazo à vista.** Quem chega numa oficina quer saber quanto custa e quanto tempo demora, então isso aparece no começo da página.
- **Uma ação só.** Todo botão leva ao contato. A pesquisa apontou isso para página de negócio local (veja `02-pesquisa.md`).
- **Cores de oficina de rua.** Amarelo de sinalização, grafite e um tom de giz (veja `04-paleta-e-tipografia.md`).
- **Títulos em fonte estreita**, como letreiro, para dar personalidade sem precisar de imagens.
- **Sem imagens.** Não há fotos disponíveis nem direitos para usar, então a página se apoia em tipografia e cor.

## O que foi cortado

A primeira versão tinha uma ficha interativa que calculava o preço, uma animação, uma engrenagem no fundo, um plano de assinatura e um formulário simulado. Tudo isso foi retirado a pedido do aluno, porque o enunciado pede uma landing page simples. A história está em `01-prompts.md`.

## O que foi testado e o que não foi

- **Testado:** a página foi aberta no navegador em tela larga e em um quadro de 400px de largura, que simula o celular. Em ambos as seções aparecem em ordem e nada vaza para o lado.
- **Não testado:** teclado, leitor de tela e outros navegadores além do Chrome.
