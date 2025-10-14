# Requisitos Elicitados

## Introdução

Esta página consolida os requisitos identificados para o projeto, eliciados por meio das técnicas Análise de documento,Entrevista e Brainstorming. O processo de levantamento priorizou a compreensão das necessidades dos usuários e a conformidade com normas técnicas, garantindo clareza e alinhamento aos objetivos propostos.

## Requisitos

Os requisitos foram organizados em duas tabelas: a Tabela 1 apresenta os Requisitos Funcionais, enquanto a Tabela 2 lista os Requisitos Não Funcionais.

Legenda das Tabelas:

- RFx: Requisito Funcional número x;
- RNFx: Requisito Não Funcional número x;

### Funcionais

## Gabriel
Prioridade | Requisito Funcional
--- | ---
Essencial | O sistema deve permitir o cadastro de usuários (compradores e vendedores).
Essencial | O sistema deve permitir o cadastro de produtos pelos vendedores.
Essencial | O sistema deve permitir a pesquisa de produtos por nome ou categoria.
Essencial | O sistema deve permitir aplicar filtros de preço, localização, avaliação, etc.
Essencial | O sistema deve permitir a adição de produtos ao carrinho.
Essencial | O sistema deve permitir a realização de pagamentos via Shopee Pay ou cartão.
Importante | O sistema deve permitir a aplicação de cupons de desconto.
Importante | O sistema deve permitir acompanhar o status do pedido.
Importante | O sistema deve permitir ao usuário avaliar produtos e vendedores.
Desejável | O sistema deve sugerir produtos com base em buscas anteriores.
Desejável | O sistema deve exibir promoções e campanhas sazonais.

---

Categoria | Requisito Não Funcional
--- | ---
Desempenho | O sistema deve suportar um grande número de usuários simultâneos.
Usabilidade | O sistema deve ter uma interface intuitiva e fácil de usar.
Responsividade | O sistema deve funcionar corretamente em dispositivos móveis e desktops.
Confiabilidade | O sistema deve manter a integridade e segurança dos dados do usuário.
Eficiência | O tempo de carregamento das páginas não deve ultrapassar 5 segundos.
Segurança | O sistema deve proteger informações sensíveis, como dados de pagamento.

## Luisa

| Identificação | Descrição | Categoria | Implementado | Versão |
| :---- | :---- | :---- | :---- | :---- |
| UC01 | O usuário deve conseguir criar conta em no máximo 55 segundos. | Funcional  | Sim | 1.0 |
| UC02 | O sistema deve confirmar o cadastro com um e-mail em até 30 segundos. | Funcional | Sim | 1.0 |
| UC03 | O usuário deve conseguir buscar produtos em menos de 3 segundos após digitar. | Não Funcional | Sim | 1.0 |
| UC04 | O sistema deve mostrar resultados relevantes em uma lista clara e objetiva. | Funcional | Sim | 1.0 |
| UC05 | O usuário deve poder filtrar produtos por preço, avaliação e entrega em até 5 segundos. | Funcional | Sim | 1.0 |
| UC06 | O sistema deve permitir que o usuário veja até 5 imagens por produto em menos de 10 segundos. | Funcional | Sim | 1.0 |
| UC07 | O usuário deve conseguir ler descrições detalhadas dos produtos, com texto legível e claro. | Funcional | Sim | 1.0 |
| UC08 | O sistema deve mostrar avaliações e comentários de outros compradores em menos de 3 segundos. | Funcional | Sim | 1.0 |
| UC09 | O carrinho deve atualizar o total em até 2 segundos após a adição ou remoção de produto. | Funcional | Sim | 1.0 |
| UC10 | O usuário deve escolher opções de pagamento com clareza e segurança em até 10 segundos. | Funcional | Sim | 1.0 |
| UC11 | O sistema deve validar os dados do cartão ou pagamento em menos de 15 segundos. | Funcional | Sim | 1.0 |
| UC12 | O usuário deve receber confirmação imediata da compra em até 10 segundos. | Funcional | Sim | 1.0 |
| UC13 | O sistema deve enviar e-mail de confirmação da compra em até 30 segundos. | Funcional | Sim | 1.0 |
| UC14 | O sistema deve notificar o usuário imediatamente sobre mudanças no status do pedido, em até 10 segundos. | Funcional | Sim | 1.0 |
| UC15 | O usuário deve poder avaliar produto em até 20 segundos após o recebimento. | Funcional | Sim | 1.0 |
| UC16 | O sistema deve permitir que o usuário restaure a senha pelo e-mail cadastrado.. | Funcional | Sim | 1.0 |
| UC17 | A interface deve ser acessível para pessoas com deficiências, conforme normas de acessibilidade. | Não Funcional | Sim | 1.0 |
| UC18 | O sistema deve possuir termos e políticas de privacidade claros e acessíveis.. | Funcional | Sim | 1.0 |
| UC19 | O sistema deve permitir que o usuário avalie produtos e vendedores. | Funcional | Sim | 1.0 |
| UC20 | O sistema deve permitir ao usuário cadastrar múltiplos métodos de pagamento (cartão, boleto, PayPal).. | Funcional | Sim | 1.0 |
| UC21 | O sistema deve suportar múltiplos idiomas. | Não funcional | Sim | 1.0 |
| UC25 | O sistema deve proteger os dados pessoais do usuário conforme a LGPD, solicitando consentimento claro. | não funcional | Sim | 1.0 |
| UC30 | O usuário deve conseguir finalizar a compra rapidamente, com o processo total levando menos de 2 minutos. | Funcional | Sim | 1.0 |

## Anna Clara

# Elicitação de Requisitos - Shopee

## Requisitos Funcionais

| Código | Descrição |
|:-------|:-----------|
| **RF01** | O sistema precisa cadastrar os usuários por meio de:<br> - E-mail<br> - Facebook<br> - Apple<br> - Google<br> - Números de telefone com senha |
| **RF02** | Cadastro de produtos, permitindo as operações de: <br> - Inserir <br> - Editar <br> - Remover |
| **RF03** | Busca e filtro de produtos |
| **RF04** | Carrinho de compras |
| **RF05** | Configurações |
| **RF06** | Carrinho de compras com pagamento online |
| **RF07** | Pagamento online |
| **RF08** | Notificações |

---

📄 **Observação:** Os requisitos acima descrevem as principais funcionalidades esperadas do sistema Shopee, conforme levantamento inicial de requisitos.


## Moisés

## João Igor


| Versão | Data | Descrição | Autor(es) | Revisor |
|--------|------|-----------|-----------|---------|
| 1.0    | 27/09/2025 | Criação da pagina | [Felipe Guimaraes](https://github.com/felipegf1)  |  [Vilmar José](https://github.com/VilmarFagundes) |
