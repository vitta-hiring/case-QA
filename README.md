[![](https://vitta.com.br/wp-content/uploads/2019/09/Azul-Horizontal-3.png)](https://vitta.com.br/)

# Sobre a Vitta
A Vitta nasceu com a missão de transformar a saúde do Brasil. Em poucos anos se tornou uma das maiores startups de health tech no mercado, e mesmo com o crescimento, mantemos em nosso DNA a inovação, a experiência, a praticidade e a segurança. Desde então temos trabalhado para construir nossa marca e cultura a fim de desenvolver um produto altamente eficiente, capaz de revolucionar a saúde no nosso país. Além das melhores soluções de tecnologia e atendimento excepcional voltadas ao mercado de saúde, contamos também com as melhores pessoas, os nossos ✨**Vittanos**✨.

Nossos valores:
> **Guerreiros por natureza**;
> **Vencemos em time**;
> **O cliente é a nossa vida**;
> **Excelência inegociável**.
 
[#vemMudarASaudeDoBrasil](https://vitta.gupy.io/)

---
#  Sobre o desafio
Para desenvolver este desafio, você deverá utilizar o site [Automation Practice](http://automationpractice.com/index.php) e as histórias de usuário apresentadas abaixo.

### História de usuário
O seu time desenvolveu as seguintes histórias:

**001 - Como um cliente da loja, gostaria de visualizar as roupas disponíveis no site:**
1. Deve ser possível visualizar as roupas mais vendidas (_Best Sellers_) e também as roupas mais populares na home page;
2. Deve ser possível ter uma visualização rápida (_Quick view_) de cada roupa na lista de roupas:
    - não devo ser redirecionado a outra página para ver mais informações do produto;
3. Deve ser possível visualizar ítens na promoção com uma etiqueta de desconto na cor amarela, mostrando a porcentagem descontada;
4. Deve ser possível pesquisar pelo nome de uma determinada roupa;
5. Deve ser possível ter uma visualização completa de cada roupa na lista de roupas:
    - devo ser redirecionado para uma página dedicada ao produto selecionado.

**002 - Como um cliente da loja, gostaria de adicionar roupas ao meu carrinho de compras:**
1. Não deve ser possível adicionar ao carrinho menos de 1 ítem:
    * ao escolher uma quantidade menor que 1, devo ser notificado que não é possível essa ação.
2. Deve ser possível adicionar uma roupa ao carrinho pela:
    * listagem de roupas;
    * visualização rápida;
    * visualização completa.
3. Deve ser possível visualizar os ítens adicionados no carrinho em formato de tabela, onde:
    * cada linha mostra um ítem adicionado ao carrinho com as colunas:
        * Produto - uma foto do produto adicionado;
        * Descrição - mostra o nome do produto, cor e tamanho escolhido;
        * Disponibilidade - se há produtos disponíveis no estoque;
        * Preço unitário;
        * Quantidade do produto a ser comprada;
        * Total - multiplicação entre o preço unitário vezes a quantidade;
        * Embalar para presente? - opção para embrulhar o produto;
        * Excluir - remove o produto do carrinho.
4. Deve ser possível calcular e visualizar o valor do frete;
5. Deve ser possível visualizar o valor total de todos os produtos adicionados ao carrinho.

**003 - Como um cliente da loja, gostaria de entrar em contato com o serviço ao consumidor:**
1. Deve ser possível enviar uma mensagem para a equipe de serviço ao consumidor pelo site através de um formulário com os campos:
    * 2 opções de cabeçalho - **campo obrigatório**:
        * Serviço ao consumidor (_Customer service_) - para qualquer questão sobre um produto ou compra realizada;
        * Suporte técnico (_Webmaster_) - para qualquer problema técnico com o site.
    * Endereço de Email - **campo obrigatório**:
        * ao inserir endereço inválido, devo ser notificado.
    * Referência de uma compra - **campo não obrigatório**;
    * Anexar arquivo - **campo não obrigatório**:
        * deve ser possível anexar qualquer tipo de arquivo;
        * ao anexar arquivos maiores que 5mb, devo ser notificado que o limite é esse valor.
    * Mensagem - **campo obrigatório**:
        * limite de até 255 caracteres.
2. Cliente deve ser notificado que sua mensagem foi enviada com sucesso.
---
### Artefatos a serem desenvolvidos 
##### Pré-requisitos e critérios de aceite:
* Realizar o fork desse repositório;
* Contabilizar quantas horas foram investidas no desenvolvimento do desafio inteiro;
* Documentar no final desse arquivo como rodamos a automação;
* Enviar todos artefatos desenvolvidos para o seu repositório.

##### Desafio:
1. Desenvolver cenários de testes manuais para as histórias acima descritas, utilizando técnicas e estratégias de teste. Escolha no mínimo dois requisitos de cada uma das três histórias. Fique livre para usar planilhas ou um documento de texto;
2. Caso encontre um bug, descreva-o como se você estivesse reportando para sua equipe;
3. Escrever no mínimo um cenário BDD para cada história;
4. Fazer a automação de um cenário de teste manual de cada história que você achou mais importante:
    * Deverá utilizar um framework de testes a sua escolha, desde que não seja um framework de reprodução/gravação (Selenium IDE, Katalon...).
5. Avisar a equipe Vitta com o link para o seu repositório. Não é necessário abrir um _Pull request_.

### Diferenciais/Extras
* Descrever e justificar quais técnicas e estratégias foram utilizadas durantes os testes;
* Uso do Cucumber;
* Uso de Page Object;
* Uso da linguagem Javascript.

> Gostaríamos muito que você nos enviasse o resultado em até 5 dias, mas se você precisar de mais tempo, basta nos avisar!
---