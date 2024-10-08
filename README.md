# Cronômetro de Proposta

Uma página web que exibe uma proposta com tempo limitado, com um cronômetro regressivo de 48 horas. Os usuários podem aceitar a oferta via WhatsApp antes que a proposta expire.

### Funcionalidades
* Cronômetro Regressivo: Mostra o tempo restante até que a proposta expire, começando em 48 horas.
* Integração com WhatsApp: Os usuários podem aceitar a proposta clicando em um link que já preenche automaticamente uma mensagem no WhatsApp.
* Suporte a Local Storage: O tempo restante é salvo no armazenamento local do navegador, permitindo que o cronômetro continue mesmo após a página ser atualizada.
* Design Responsivo: Otimizado para dispositivos desktop e móveis.

### Como Funciona
* Timer da Proposta: O cronômetro começa a contar quando o usuário acessa a página e a contagem é salva no local storage. Mesmo que a página seja atualizada ou reaberta, o cronômetro continua de onde parou.
* Link para WhatsApp: Ao clicar no botão, o usuário é redirecionado para o WhatsApp com uma mensagem pré-preenchida para confirmar a aceitação da proposta.
* Expiração: Quando o cronômetro chega a zero, a página exibe "Proposta expirada!" e o cronômetro para.
### Tecnologias Utilizadas
HTML5: Para a estrutura da página.
CSS3: Para o design, incluindo responsividade e efeitos de hover.
JavaScript: Para gerenciar o cronômetro regressivo e o local storage.

### Contribuições
Este projeto foi criado por mim, professor de programação e robótica na Ctrl+Play, para que o setor comercial possa enviar propostas com descontos aos clientes com a possibilidade do cliente acompanhar a duração da proposta e caso deseje aceitar apenas clique no botão de aceite, direcionando ao WhatsApp do setor comercial com a mensagem pronta, bastando apenas dar enter para aceitar. Sinta-se à vontade para contribuir!
