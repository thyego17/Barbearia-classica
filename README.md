# Barbearia Clássica

Site de uma barbearia fictícia, criado como projeto de portfólio por **Thyego**. O visitante conhece a barbearia, escolhe um serviço, seleciona dia e horário e envia o pedido de agendamento direto pelo WhatsApp.

**Acesse:** [thyego17.github.io/Projeto-1](https://thyego17.github.io/Projeto-1/)

## Funcionalidades

- **Agendamento pelo WhatsApp:** o visitante escolhe o serviço, o dia e o horário, e o botão abre a conversa com a mensagem já pronta.
- **Serviços e preços:** Corte masculino (R$ 35), Barba (R$ 20) e Corte + barba (R$ 50).
- **Datas inteligentes:** a lista mostra os próximos 7 dias de atendimento, sem domingos.
- **Horários atualizados:** de 9h às 19h, e no dia de hoje os horários que já passaram são escondidos.
- **Status em tempo real:** uma etiqueta informa se a barbearia está aberta ou fechada agora.
- **Contato rápido:** botões de telefone, e-mail e mapa.

## Tecnologias

- HTML5 semântico
- CSS3 (Grid, variáveis CSS e animações)
- JavaScript puro, sem bibliotecas
- Fontes [Cormorant Garamond](https://fonts.google.com/specimen/Cormorant+Garamond) e [Jost](https://fonts.google.com/specimen/Jost), via Google Fonts

## Design

- Visual elegante e sóbrio, com fundo verde-garrafa escuro e acento em verde-sálvia.
- Tipografia serifada em destaque e rótulos em caixa-alta espaçada.
- Layout responsivo, pensado primeiro para o celular.
- Foco visível, HTML semântico e respeito à preferência de movimento reduzido.

## Estrutura

```
Projeto-1/
├── index.html
└── README.md
```

O site inteiro está em um único arquivo, com CSS e JavaScript incorporados.

## Como executar localmente

1. Clone o repositório:
   ```bash
   git clone https://github.com/thyego17/Projeto-1.git
   ```
2. Abra o `index.html` no navegador.

Não é necessário instalar nada.

## Como personalizar

Tudo fica no `index.html`:

- **Serviços e preços:** altere a lista `S` no início do script e os três blocos de serviço na seção "Escolha e agende".
- **Número do WhatsApp:** troque `5511999999999` nos links, usando código do país e DDD, sem espaços.
- **Horário de funcionamento:** ajuste o intervalo no laço de horários e o texto na seção de contato.
- **Cores:** edite as variáveis em `:root`, no início do `<style>`.

## Observações

Este é um projeto de demonstração. Nome, endereço, telefone e e-mail são fictícios.

## Autor

**Thyego**

- Portfólio: [thyego17.github.io/Portif-lio](https://thyego17.github.io/Portif-lio/)
- GitHub: [@thyego17](https://github.com/thyego17)
