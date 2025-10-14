# Requisitos Elicitados

## Introdução

Esta página apresenta os requisitos que vão dar forma ao nosso projeto, levantados a partir das técnicas de **Observação** e **Introspecção.** Durante esse processo, nossa prioridade foi identificar as funcionalidades que realmente não podem faltar e as características de qualidade que o sistema precisa ter. O objetivo é que este documento sirva como um guia claro para as equipes de desenvolvimento e teste, garantindo que o trabalho esteja sempre alinhado às necessidades dos usuários e aos padrões do mercado.

Resumo das Técnicas de Elicitação

- **Observação:** Técnica em que o analista observa o usuário final interagindo com um sistema similar ou executando as tarefas que o novo sistema irá suportar. Ajuda a identificar necessidades implícitas e problemas práticos que o usuário pode não verbalizar.

- **Introspecção:** Técnica subjetiva onde o próprio analista, com base em sua experiência, imagina-se como um usuário do sistema para definir os requisitos. Embora seja útil para gerar uma base inicial de funcionalidades, deve ser validada posteriormente, pois pode introduzir vieses pessoais.


## Requisitos

Os requisitos foram organizados em duas tabelas: a Tabela 1 apresenta os Requisitos Funcionais, enquanto a Tabela 2 lista os Requisitos Não Funcionais.

### Requisitos Funcionais

| ID   | Descrição | Técnicas | 
|------|-----------|----------|
| RF01 | O sistema deve permitir o cadasto de usuário (vendedores e compradores)   | Observação|
| RF02 | O usuário deve poder filtrar produtos por preço, avaliação e entrega     | Instrospecção| 
| RF03 | O sistema deve permitir a pesquisa de produtos por nome ou categoria     | Introspecção| 
| RF04 | O sistema deve permitir ao usuário caadastrar múltiplos métodos de pagamento  | Observação|
| RF05 | O sistema deve permitir que o usuário recupere sua senha de acesso através de um link enviado para seu e-mail cadastrado.  |Observação|
| RF06 | O sistema deve exibir um histórico de todos os pedidos anteriores do usuário em sua área de perfil. | Observação|
| RF07 | O sistema deve permitir ao usuário avaliar produtos e vendedores  | Introspecção| 
| RF08 | O sistema deve mostrar resultados relevantes em uma lista clara e objetiva | Observação| 
| RF09 | O sistema deve permitir a adição de produtos ao carrinho.  | Introspecção|
| RF10 |  O sistema deve permitir que o usuário adicione produtos a uma "Lista de Desejos" para consulta futura. | Observação| 
| RF11 | O sistema deve permitir acompanhar o status do pedido    | Introspecção|
| RF12 | O sistema deve sugerir produtos com base em buscas anteriores   | Observação|
| RF13 | O sistema deve permitir que o usuário cadastre e gerencie múltiplos endereços de entrega em sua conta. | Observação|
| RF14 | O sistema deve mostrar avaliações e comentários de outros compradores  | Observação |
| RF15 | O sistema deve possuir termos e políticas de privacidades claras e acessíveis | Observação|


Tabela 1 – Conjunto de requisitos funcionais elicitados.<br>
Elaboração por [Anna Clara](https://github.com/AnnaClarafg), [Gabriel](https://github.com/Dev-Gabriel-Lima), [João Igor](https://github.com/JoaoPC10), [Luisa de Souza](https://github.com/luisa12ll) e [Moisés](https://github.com/edumoisessilva)


### Requisitos Não Funcionais 

| ID    | Descrição | Técnicas | 
|-------|-----------|----------|
| RNF01 | O usuário deve conseguir buscar produtos em menos de 5 segundos após digitar|Introspecção|
| RNF02 | O sistema deve ser acessível a pessoas com deficiência visual conforme as normas de acessibilidade  | Observação|
| RNF03 | O sistema deve suportar um grande número de usuários simultâneos | Introspecção |
| RNF04 | O sistema deve funcionar corretamente em desktops e dispositivos móveis | Observação |
| RNF05 | O sistema deve manter a integridade e segurança dos dados do usuários conforme a LGPD | Intospecção |
| RNF06 | O tempo de carregamento das páginas não deve ultrapassas 5 segundos | Observação |
| RNF07 | O sistema deve suportar múltiplos idiomas | Introspecção |
| RNF08 | O usuário deve receber confirmação imediata da compra em até 10 segundos. | Observação | 
| RNF09 | O usuário deve finalizar a compra em menos de 5 minutos | Introspecção | 
| RNF10 | O sistema deve validar os dados do cartão ou pagamento em menos de 15 segundos | Introspecção | 
| RNF11 | O usuário deve conseguir ler descrições detalhadas dos produtos, com texto legível e claro | Observação | 

Tabela 2 – Conjunto de requisitos não funcionais elicitados.<br>
Elaboração por [Anna Clara](https://github.com/AnnaClarafg), [Gabriel](https://github.com/Dev-Gabriel-Lima), [João Igor](https://github.com/JoaoPC10), [Luisa de Souza](https://github.com/luisa12ll) e [Moisés](https://github.com/edumoisessilva)


| Versão | Data | Descrição | Autor(es) 
|--------|------|-----------|-----------
| 1.0    | 27/09/2025 | Criação da pagina | [Anna Clara](https://github.com/AnnaClarafg), [Gabriel](https://github.com/Dev-Gabriel-Lima), [João Igor](https://github.com/JoaoPC10), [Luisa de Souza](https://github.com/luisa12ll) e [Moisés](https://github.com/edumoisessilva) |

