# Léxico

## Introdução

O **Léxico Ampliado da Linguagem (LAL)** é uma técnica tradicional de modelagem usada para **definir os principais termos do domínio do sistema**, ou seja, as palavras e expressões que descrevem o mundo do aplicativo (nesse caso, a Shopee).

### Objetivo

- Eliminar ambiguidades (cada termo tem um sentido único no projeto);
- Facilitar o entendimento do sistema;
- Poder servir como base para outras modelagens (como casos de uso e diagramas, por exemplo).

## Metodologia

Este léxico apresenta os principais termos identificados a partir dos **requisitos funcionais e não funcionais** do sistema, inspirado na plataforma **Shopee**.  
Cada termo é descrito pelos seguintes campos:

- **Símbolo:** o termo principal.  
- **Sinônimos:** outras palavras usadas para se referir ao mesmo conceito.  
- **Noção:** definição do termo no contexto do sistema.  
- **Impacto:** como o termo se relaciona com outros elementos do sistema.

---

## Léxicos


### 🧑‍💼 1. Usuário
**Sinônimos:** cliente, comprador, vendedor  
**Noção:** Pessoa que utiliza o sistema para comprar ou vender produtos.  
**Impacto:** Pode cadastrar-se, fazer login, comprar, vender, avaliar produtos e gerenciar sua conta.


---

### 🛍️ 2. Produto
**Sinônimos:** item, mercadoria  
**Noção:** Bem disponível para compra ou venda no sistema.  
**Impacto:** Pode ser pesquisado, filtrado, adicionado ao carrinho, avaliado ou incluído na lista de desejos.

---

### 🧾 3. Pedido
**Sinônimos:** compra, transação  
**Noção:** Registro gerado quando o usuário finaliza uma compra.  
**Impacto:** Fica disponível no histórico, pode ser acompanhado e seu status é atualizado pelo sistema.

---

### 💳 4. Pagamento
**Sinônimos:** método de pagamento, cartão, PIX  
**Noção:** Forma escolhida pelo usuário para efetuar uma compra.  
**Impacto:** É validado pelo sistema e pode ser gerenciado na conta do usuário.

---

### 📦 5. Entrega
**Sinônimos:** envio, transporte  
**Noção:** Processo de envio do produto ao comprador.  
**Impacto:** Está associada ao pedido e depende do endereço cadastrado. O status pode ser acompanhado pelo usuário.

---

### 📬 6. Endereço
**Sinônimos:** local de entrega ou partida  
**Noção:** Local definido pelo usuário para receber produtos.  
**Impacto:** Pode haver múltiplos endereços por conta e eles influenciam o cálculo do frete e o status de entrega.

---

### 🔐 7. Autenticação
**Sinônimos:** login, cadastro, recuperação de senha  
**Noção:** Processo de identificação do usuário para acesso ao sistema.  
**Impacto:** Permite o uso de funcionalidades como compras, avaliações e histórico de pedidos.

---

### ⭐ 8. Avaliação
**Sinônimos:** nota, comentário, feedback  
**Noção:** Opinião do usuário sobre um produto ou vendedor.  
**Impacto:** Influencia a reputação dos vendedores e as recomendações exibidas a outros usuários.

---

### ❤️ 9. Lista de Desejos
**Sinônimos:** favoritos  
**Noção:** Coleção de produtos que o usuário deseja comprar futuramente.  
**Impacto:** Permite fácil acesso a produtos de interesse e pode ser usada para sugestões de compra.

---

### 🛒 10. Carrinho
**Sinônimos:** cesta de compras  
**Noção:** Local onde o usuário armazena temporariamente produtos antes de concluir a compra.  
**Impacto:** Permite gerenciar quantidades, preços e formas de pagamento antes do pedido.

---

### 🔍 11. Pesquisa
**Sinônimos:** busca  
**Noção:** Função que permite encontrar produtos por nome, categoria ou filtro.  
**Impacto:** Afeta diretamente a experiência do usuário e a rapidez de resposta do sistema.

---

### 🧠 12. Recomendação
**Sinônimos:** sugestão  
**Noção:** Mecanismo que indica produtos com base em buscas anteriores.  
**Impacto:** Aumenta o engajamento e a personalização da experiência do usuário.

---

### ⚙️ 13. Sistema
**Sinônimos:** plataforma, site  
**Noção:** Conjunto de funcionalidades que permite a interação entre usuários, produtos e serviços.  
**Impacto:** Deve garantir desempenho, acessibilidade, segurança e conformidade com a LGPD.

---

### 🕒 14. Desempenho
**Sinônimos:** tempo de resposta, carregamento  
**Noção:** Tempo que o sistema leva para responder a uma ação do usuário.  
**Impacto:** Afeta diretamente a satisfação do usuário e está presente em vários requisitos não funcionais.

---

### 🧑‍🦯 15. Acessibilidade
**Sinônimos:** usabilidade inclusiva  
**Noção:** Capacidade do sistema de ser utilizado por pessoas com deficiência.  
**Impacto:** Define padrões visuais e estruturais, garantindo conformidade com normas de acessibilidade.

---

### 🧱 16. Segurança
**Sinônimos:** proteção de dados, LGPD  
**Noção:** Medidas que protegem informações e transações dos usuários.  
**Impacto:** Garante integridade, confidencialidade e conformidade legal dos dados.

---

### 🌎 17. Internacionalização
**Sinônimos:** idiomas, tradução  
**Noção:** Capacidade do sistema de funcionar em múltiplos idiomas.  
**Impacto:** Aumenta o alcance do sistema e influencia a interface e o conteúdo textual.

---

### 📜 18. Políticas de Privacidade
**Sinônimos:** termos de uso  
**Noção:** Documentos que descrevem as regras e condições de uso do sistema.  
**Impacto:** Devem ser acessíveis e claros, garantindo transparência e conformidade legal.

---

<div align="center"><strong>Autoria de <a href="https://github.com/Dev-Gabriel-Lima">Gabriel</a></strong></div>

## Referências
SERRANO, Milene; SERRANO, Maurício. Requisitos - Aula 10. Disponível em: [Requisitos_Aula 10](../arquivos/Cenarios_Aula10.pdf). Acesso em: 15 outubro 2025.

## Histórico de versão

| Versão | Data | Descrição | Autor(es) | Revisor |
|--------|------|-----------|-----------|---------|
| 1.0    | 15/10/2025 | Atualização do documento dos Léxicos e elaboração dos léxicos de 1 - 18 | [Gabriel](https://github.com/Dev-Gabriel-Lima) | [João Igor](https://github.com/JoaoPC10) |
