# Requisitos Elicitados

## Introdução

Esta página apresenta os requisitos que vão dar forma ao nosso projeto, levantados a partir das técnicas de **Observação** e **Introspecção.** Durante esse processo, nossa prioridade foi identificar as funcionalidades que realmente não podem faltar e as características de qualidade que o sistema precisa ter. O objetivo é que este documento sirva como um guia claro para as equipes de desenvolvimento e teste, garantindo que o trabalho esteja sempre alinhado às necessidades dos usuários e aos padrões do mercado.

Resumo das Técnicas de Elicitação

- **Observação:** Técnica em que o analista observa o usuário final interagindo com um sistema similar ou executando as tarefas que o novo sistema irá suportar. Ajuda a identificar necessidades implícitas e problemas práticos que o usuário pode não verbalizar.

- **Introspecção:** Técnica subjetiva onde o próprio analista, com base em sua experiência, imagina-se como um usuário do sistema para definir os requisitos. Embora seja útil para gerar uma base inicial de funcionalidades, deve ser validada posteriormente, pois pode introduzir vieses pessoais.


## Requisitos

Os requisitos foram organizados em duas tabelas: a Tabela 1 apresenta os Requisitos Funcionais, enquanto a Tabela 2 lista os Requisitos Não Funcionais.

### Requisitos Funcionais

| ID   | Descrição | Técnicas | Implementado |
|------|-----------|----------|--------------|
| <a id="RF01"></a>RF01 | O sistema deve permitir o cadastro de usuário (vendedores e compradores) | Observação | Sim |
| RF02 | O usuário deve poder filtrar produtos por preço, avaliação e entrega | Introspecção | Sim |
| RF03 | O sistema deve permitir a pesquisa de produtos por nome ou categoria | Introspecção | Sim |
| RF04 | O sistema deve permitir ao usuário cadastrar múltiplos métodos de pagamento | Observação | Sim |
| RF05 | O sistema deve permitir que o usuário recupere sua senha de acesso através de um link enviado para seu e-mail cadastrado | Observação | Sim |
| RF06 | O sistema deve exibir um histórico de todos os pedidos anteriores do usuário em sua área de perfil | Observação | Sim |
| RF07 | O sistema deve permitir ao usuário avaliar produtos e vendedores | Introspecção | Sim |
| RF08 | O sistema deve mostrar resultados relevantes em uma lista clara e objetiva | Observação | Sim |
| RF09 | O sistema deve permitir a adição de produtos ao carrinho | Introspecção | Sim |
| RF10 | O sistema deve permitir que o usuário adicione produtos a uma "Lista de Desejos" para consulta futura | Observação | Sim |
| RF11 | O sistema deve permitir acompanhar o status do pedido | Introspecção | Sim |
| RF12 | O sistema deve sugerir produtos com base em buscas anteriores | Observação | Sim |
| RF13 | O sistema deve permitir que o usuário cadastre e gerencie múltiplos endereços de entrega em sua conta | Observação | Sim |
| RF14 | O sistema deve mostrar avaliações e comentários de outros compradores | Observação | Sim |
| RF15 | O sistema deve possuir termos e políticas de privacidade claras e acessíveis | Observação | Sim |

Tabela 1 – Conjunto de requisitos funcionais elicitados.<br>
Elaboração por [Anna Clara](https://github.com/AnnaClarafg), [Gabriel](https://github.com/Dev-Gabriel-Lima), [João Igor](https://github.com/JoaoPC10), [Luisa de Souza](https://github.com/luisa12ll) e [Moisés](https://github.com/edumoisessilva)



### Requisitos Não Funcionais

| ID    | Descrição | Técnicas | Implementado |
|-------|-----------|----------|--------------|
| RNF01 | O usuário deve conseguir buscar produtos em menos de 5 segundos após digitar | Introspecção | Sim |
| RNF02 | O sistema deve ser acessível a pessoas com deficiência visual conforme as normas de acessibilidade | Observação | Não |
| RNF03 | O sistema deve suportar um grande número de usuários simultâneos | Introspecção | Sim |
| RNF04 | O sistema deve funcionar corretamente em desktops e dispositivos móveis | Observação | Sim |
| RNF05 | O sistema deve manter a integridade e segurança dos dados do usuário conforme a LGPD | Introspecção | Sim |
| RNF06 | O tempo de carregamento das páginas não deve ultrapassar 5 segundos | Observação | Sim |
| RNF07 | O sistema deve suportar múltiplos idiomas para usuários de diferentes regiões | Introspecção | Não |
| RNF08 | O usuário deve receber confirmação imediata da compra em até 10 segundos | Observação | Sim |
| RNF09 | O usuário deve finalizar a compra em menos de 5 minutos | Introspecção | Sim |
| RNF10 | O sistema deve validar os dados do cartão ou pagamento em menos de 15 segundos | Introspecção | Sim |
| RNF11 | O usuário deve conseguir ler descrições detalhadas dos produtos, com texto legível e claro | Observação | Sim |

Tabela 2 – Conjunto de requisitos não funcionais elicitados.<br>
Elaboração por [Anna Clara](https://github.com/AnnaClarafg), [Gabriel](https://github.com/Dev-Gabriel-Lima), [João Igor](https://github.com/JoaoPC10), [Luisa de Souza](https://github.com/luisa12ll) e [Moisés](https://github.com/edumoisessilva)


| Versão | Data | Descrição | Autor(es) 
|--------|------|-----------|-----------
| 1.0    | 27/09/2025 | Criação da pagina | [Anna Clara](https://github.com/AnnaClarafg), [Gabriel](https://github.com/Dev-Gabriel-Lima), [João Igor](https://github.com/JoaoPC10), [Luisa de Souza](https://github.com/luisa12ll) e [Moisés](https://github.com/edumoisessilva) |

