# Especificação Suplementar 

## Introdução

Este documento apresenta a Especificação Suplementar do aplicativo Jornada do Estudante, com o objetivo de complementar os requisitos funcionais previamente definidos. A especificação suplementar é um documento utilizado para descrever os requisitos não funcionais e outras restrições ou características que não estão diretamente relacionadas às funcionalidades do sistema, mas que influenciam fortemente sua qualidade e comportamento.

Esse tipo de especificação é importante porque garante uma visão mais completa do sistema, permitindo que a equipe de desenvolvimento compreenda não apenas o que o sistema deve fazer, mas também como ele deve se comportar em diferentes contextos de uso.

O conteúdo foi estruturado com base no modelo FURPS+, que serve para organizar e classificar os requisitos de qualidade de software em categorias como Funcionalidade, Usabilidade, Confiabilidade, Desempenho e Suportabilidade, além de incluir outros aspectos complementares.

A técnica utilizada para elaboração desse documento foi feita conforme sugerido por Milena Serrano <a id="RP1" href="https://aprender3.unb.br/pluginfile.php/3210637/mod_resource/content/1/Requisitos%20-%20Aula%20013a.pdf">1.</a>, e os itens necessários abordados aqui incluem todos os aspectos não funcionais e complementares que devem ser considerados durante o desenvolvimento do sistema.

## Metodologia

A elaboração da especificação suplementar seguiu os seguintes passos <a id="RP1" href="https://aprender3.unb.br/pluginfile.php/3210637/mod_resource/content/1/Requisitos%20-%20Aula%20013a.pdf">1.</a>:

1. **Levantamento dos Requisitos Não Funcionais** por meio da análise dos objetivos do sistema e padrões de qualidade esperados.
2. **Classificação dos Requisitos** segundo o modelo FURPS+, que contempla: Funcionalidade, Usabilidade, Confiabilidade, Desempenho, Suporte e extensões (como restrições e interfaces).
3. **Preenchimento de Tabelas** com os requisitos descritos de forma clara, justificando sua inclusão e indicando prioridade e status.
4. **Consulta à bibliografia técnica**, garantindo conformidade com boas práticas de Engenharia de Software.

<br>


---

## Modelo

Este documento segue o modelo **FURPS+**, organizando os requisitos de software em categorias:

- **F (Functionality):** Funcionalidades e regras de negócio
- **U (Usability):** Usabilidade e acessibilidade
- **R (Reliability):** Confiabilidade e disponibilidade
- **P (Performance):** Desempenho e tempo de resposta
- **S (Supportability):** Manutenibilidade e portabilidade
- **+ (Extensões):** Interfaces, restrições técnicas e legais

---


## Requisitos Não Funcionais
A seguir, temos a Tabela 1, referente à Especificação Suplementar, na qual a equipe realizou a definição e o detalhamento dos requisitos não funcionais do sistema.

| Código | Categoria | Requisito Não Funcional | Descrição | Justificativa | Prioridade | Implementado |
|--------|------------|-------------------------|------------|----------------|-------------|-------------|
|RNF01 |Performance (P) | O usuário deve conseguir buscar produtos em menos de 5 segundos após digitar	 | O tempo de resposta das pesquisas realizadas no aplicativo deve ser inferior a 5 segundos, garantindo fluidez na navegação. |Tempos de resposta elevados comprometem a experiência do usuário, especialmente em dispositivos móveis. | Alta |Sim |
| RNF02	| Usabilidade (U) | O sistema deve ser acessível a pessoas com deficiência visual conforme as normas de acessibilidade. | O sistema deve ter suporte a leitores de tela, contraste adequado e navegação por teclado, conforme diretrizes WCAG 2.1. | A inclusão amplia o público-alvo e garante conformidade com a legislação de acessibilidade.  | Alta |Não| 
|RNF03	 | Confiabilidade (R) | O sistema deve suportar um grande número de usuários simultâneos. | Deve permanecer estável mesmo com milhões de acessos simultâneos | Essencial para evitar falhas durante grandes eventos de vendas e manter a confiança dos usuários. |Alta|Sim|
|RNF04	| Suportabilidade (S) | O sistema deve funcionar corretamente em desktops e dispositivos móveis. | A interface deve ser totalmente responsiva e compatível com os principais navegadores e sistemas operacionais (Android, iOS, Windows, macOS).| Garante acessibilidade universal e consistência na experiência do usuário. | Alta|Sim|
| RNF05	| Funcionalidade / Extensão (+) | O sistema deve manter a integridade e segurança dos dados dos usuários conforme a LGPD. | Os dados pessoais devem ser protegidos com criptografia, autenticação segura e coleta conforme consentimento do usuário. | A conformidade com a LGPD (Lei nº 13.709/2018) é obrigatória para proteger a privacidade dos usuários e a reputação da plataforma.| Alta | Sim|
| RNF06 | Performance (P) | O tempo de carregamento das páginas não deve ultrapassas 5 segundos. | O sistema deve assegurar uma navegação fluida e eficiente, reduzindo a taxa de rejeição e melhorando a experiência do usuário. | Tempos de resposta elevados podem causar frustração e abandono da plataforma, especialmente em dispositivos móveis. | Alta | Sim |
| RNF07 | Usabilidade (U) | O sistema deve suportar múltiplos idiomas. | O sistema deve ser acessível a diferentes públicos, permitindo uso internacional.  | A oferta de mais idiomas amplia o público e melhora a inclusão. | Média | Não |
| RNF08 | Perfomance(P) | O usuário deve receber confirmação imediata da compra em até 10 segundos. | O sistema deve confirmar a compra do usuário em um período de tempo rápido (até 10 segundos). | A falta de resposta imediata pode causar dúvidas, duplicação de pedidos e reclamações. | Alta | Sim |
| RNF09 | Perfomance(P) | O usuário deve finalizar a compra em menos de 5 minutos. | O sistema deve permitir que o usuário finalize o processo de compra completo (do carrinho ao pagamento) em menos de 5 minutos. | Processos longos ou confusos tendem a aumentar a taxa de abandono do carrinho. | Média | Não |
| RNF10 | Perfomance(P) | O sistema deve validar os dados do cartão ou pagamento em menos de 15 segundos. | O sistema deve realizar a validação dos dados do cartão ou método de pagamento em até 15 segundos, garantindo segurança e eficiência na transação. | Validações demoradas ou falhas podem causar frustração e perda de vendas. | Alta | Sim |
| RNF11 | Usabilidade (U) | O usuário deve conseguir ler descrições detalhadas dos produtos, com texto legível e claro. | As descrições dos produtos devem ser claras, detalhadas e visualmente legíveis, respeitando boas práticas de design e acessibilidade. | Textos de difícil leitura comprometem a confiança e a decisão de compra. | Média | Sim |

Tabela 1 – Requisitos Não Funcionais classificados de acordo com o modelo FURPS+. <br>
Elaboração por [Anna Clara](https://github.com/AnnaClarafg) e [Luisa de Souza](https://github.com/luisa12ll)


## Referência bibliográfica

<a id="RP1" href="#tec1">1.</a> SERRANO, Milene; SERRANO, Maurício. Requisitos – Aula 13. UnB, 2025. Disponível em: <[https://aprender3.unb.br/pluginfile.php/3210637/mod_resource/content/1/Requisitos%20-%20Aula%20013a.pdf](https://aprender3.unb.br/pluginfile.php/3210637/mod_resource/content/1/Requisitos%20-%20Aula%20013a.pdf)>. Acesso em: 14 de outubro de 2025. p. 27–30.


## Histórico de versão

| Versão | Data | Descrição | Autor(es) | Revisor |
|--------|------|-----------|-----------|---------|
| 1.0    | 14/10/2025 | Criação do documento da Especificação Suplementar | [Anna Clara](https://github.com/AnnaClarafg) e [Luisa de Souza](https://github.com/luisa12ll) |  [Moisés](https://github.com/edumoisessilva)|
