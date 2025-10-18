# Cenário

## Introdução
Os cenários são uma técnica de modelagem que descrevem instâncias específicas de uso do sistema, ilustrando atividades discretas e independentes que um ator pode realizar para alcançar um resultado de valor. Cada cenário reflete uma única ocorrência de interação, sendo parte de um caso de uso mais amplo.

## Metodologia

Os cenários que serão apresentados a seguir levarão em consideração [requisitos implementados e não implementados](https://joaopc10.github.io/Desafio1-TraineeEngNet-2025-Shopee/Elicitacao/requisitos_elicitados/), visto que na fase de elicitação não foram descobertos muitas funções inesistentes no sistema.

## Padrão de cenário utilizado

| **Cenário X**|**Título do Cenário** |
| ---- | ---- |
| **Nome do Cenário** | Nome descritivo e único do cenário que será testado/executado. |
| **Ator Principal** | Participante principal (usuário ou sistema) que inicia e executa o cenário. |
| **Contexto** | Descreve a situação ou necessidade do usuário que motiva o cenário, explicando o objetivo da ação no sistema. |
| **Pré-condições** | Lista as condições que devem ser verdadeiras ou satisfeitas (dados, estado do sistema, permissões) antes que o cenário possa ser executado. |
| **Fluxo Principal** | Enumera, passo a passo, a interação principal e esperada entre o usuário e o sistema para alcançar o objetivo do cenário. |
| **Pós-condições** | Descreve o estado do sistema ou o resultado final para o usuário após a conclusão bem-sucedida do cenário. |
| **Exceções** | Lista os possíveis erros, alternativas ou situações excepcionais que podem impedir a conclusão do fluxo principal. |                   |

<div align="center"><strong>Autoria de: <a href="https://github.com/JoaoPC10">João Igor</a></strong></div>

## Cenários

| **Cenário 01**|**Cadastro de Usuário** |
| ---- | ---- |
| **Nome do Cenário** | Cadastro de Usuário |
| **Ator Principal** | Novo usuário |
| **Contexto** | O cliente quer começar a usufruir dos serviços da plataforma. |
| **Pré-condições** | Acesso à internet. |
| **Fluxo Principal** | 1. O usuário acessa o aplicativo da Shopee; <br>2. Seleciona a opção 'Cadastrar'; <br>3.Ele preenche os dados pessoais pedidos; <br>4. O cliente preenche as informações sobre formas de pagamento possíveis; <br>5. O cliente preenche as informações sobre os múltiplos endereços para entrega.  |
| **Pós-condições** | Um email de confirmação é enviado para ratificar a criação da conta |
| **Exceções** | Algum dado do cliente pode ter sido preenchido errado. |  

| **Cenário 02**|**Seleção de Produto** |
| ---- | ---- |
| **Nome do Cenário** | Seleção de Produto |
| **Ator Principal** | Usuário cadastrado |
| **Contexto** | O cliente quer realizar uma compra na plataforma. |
| **Pré-condições** | O usuário tem que estar cadastrado na plataforma. |
| **Fluxo Principal** | 1. O usuário acessa o aplicativo da Shopee; <br>2. Utilizando o filtro de texto, ele procura por um produto; <br>3.O sistema mostra a lista de resultados claramente; <br>4. O cliente adiciona o produto ao carrinho.  |
| **Pós-condições** | Um email de confirmação é enviado para ratificar a espera do pagamento do produto selecionado. |
| **Exceções** | O cliente pode não achar o produto pelo nome e procurá-lo pela avaliação. |  

| **Cenário 03**|**Avaliação de Produto** |
| ---- | ---- |
| **Nome do Cenário** | Avaliação de Produto |
| **Ator Principal** | Usuário cadastrado |
| **Contexto** | O cliente quer avaliar o produto que ele comprou. |
| **Pré-condições** | O usuário tem que estar cadastrado na plataforma. |
| **Fluxo Principal** | 1. O usuário acessa o aplicativo da Shopee; <br>2. O cliente acessa a lista de todos os produtos que ele comprou; <br>3.Escolhe o produto desejado; <br>4. O cliente escolhe de 1 a 5 estrelas para avaliar o produto e o vendedor.  |
| **Pós-condições** | Uma mensagem aparece na tela confirmando a avaliação. |
| **Exceções** | O cliente pode não achar o produto, dependendo do tamanho da lista. |  


<div align="center"><strong>Autoria de: <a href="https://github.com/JoaoPC10">João Igor</a></strong></div>


### Tabela de Rastreabilidade

|Código do Cenário | Código(s) do(s) requisito(s)|
|---|---|
| C01 |[RF01](https://joaopc10.github.io/Desafio1-TraineeEngNet-2025-Shopee/Elicitacao/requisitos_elicitados/#RF01), [RF04](https://joaopc10.github.io/Desafio1-TraineeEngNet-2025-Shopee/Elicitacao/requisitos_elicitados/#RF04), [RF13](https://joaopc10.github.io/Desafio1-TraineeEngNet-2025-Shopee/Elicitacao/requisitos_elicitados/#RF13)|
| C02 |[RF02](https://joaopc10.github.io/Desafio1-TraineeEngNet-2025-Shopee/Elicitacao/requisitos_elicitados/#RF02), [RF03](https://joaopc10.github.io/Desafio1-TraineeEngNet-2025-Shopee/Elicitacao/requisitos_elicitados/#RF03), [RF08](https://joaopc10.github.io/Desafio1-TraineeEngNet-2025-Shopee/Elicitacao/requisitos_elicitados/#RF08), [RF09](https://joaopc10.github.io/Desafio1-TraineeEngNet-2025-Shopee/Elicitacao/requisitos_elicitados/#RF09), [RF14](https://joaopc10.github.io/Desafio1-TraineeEngNet-2025-Shopee/Elicitacao/requisitos_elicitados/#RF14)|
| C03 | [RF06](https://joaopc10.github.io/Desafio1-TraineeEngNet-2025-Shopee/Elicitacao/requisitos_elicitados/#RF06), [RF07](https://joaopc10.github.io/Desafio1-TraineeEngNet-2025-Shopee/Elicitacao/requisitos_elicitados/#RF07)|


## Referências
SERRANO, Milene; SERRANO, Maurício. Requisitos - Aula 10. Disponível em: [Requisitos_Aula 10](../arquivos/Cenarios_Aula10.pdf). Acesso em: 16 outubro 2025.

## Histórico de Versões

| Versão | Data   | Descrição  | Autor(es) |Revisor   |
|--------|--------|------------|-----------|----------|
| 1.0 | 16/10/2025 | Criação do documento e dos cenários | [João Igor](https://github.com/JoaoPC10) | [Luisa](https://github.com/luisa12ll)|
