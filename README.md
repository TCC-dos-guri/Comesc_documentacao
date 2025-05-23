# Comesc

Projeto Integrador do Curso de Técnico em Desenvolvimento de Sistemas para a Internet Integrado ao Ensino Médio do IFC - Campus Araquari.

A Comesc Indústria e Comércio Eireli é uma empresa terceirizada do setor têxtil que atua na aquisição de fios, produção de malhas, tingimento e comercialização de tecidos acabados. Para garantir a qualidade de seus produtos e a eficiência na gestão de estoques e vendas, a empresa necessita de um sistema que automatize o controle de qualidade, a gestão de estoque e a interação com seus fornecedores e clientes. O objetivo é desenvolver um sistema integrado de gerenciamento de qualidade e estoque, permitindo o registro e acompanhamento da análise realizada por um funcionário nos lotes de rolos de tecido, a geração de relatórios de não conformidade, a cobrança de indenizações de fornecedores e o controle de vendas para clientes.

### IMPORTANTE: [link do projeto](https://github.com/TCC-dos-guri/)

Professor: [Marco André Lopes Mendes](https://github.com/marrcandre)

Equipe:

- [Gabriel Lucas de Miranda](https://github.com/Gabz047)
- [Luan Tiola Monteiro da Silva](https://github.com/luansilva25)
- [Renato Chagas de Morais](https://github.com/renas-cm)
- [Matheus Silveira de Oliveira](https://github.com/mattusilveira)

Links do Projeto:

- [Documentação](https://github.com/TCC-dos-guri/Comesc_documentacao/)
- Backend: [Repositório](https://github.com/TCC-dos-guri/Comesc_Backend)
- Frontend: [Repositório](https://github.com/TCC-dos-guri/Comesc_Frontend)

# 1. Desenvolvimento

### Ordem de Serviço(O.S.) e Ponto de Vendas(PDV)

A Comesc Indústria e Comércio Eireli é uma empresa terceirizada do setor têxtil que atua na comercialização de malhas. Sua operação consiste na compra de tecido cru, que é enviado para empresas terceirizadas 
responsáveis pelo processo de tecelagem e tingimento. Após o processamento, a Comesc recebe os rolos de tecido acabado, realiza a inspeção de qualidade e disponibiliza os produtos para venda. Para garantir a 
qualidade de seus produtos e a eficiência na gestão de estoques e vendas, a empresa necessita de um sistema que automatize o controle de qualidade, a gestão de estoque e a interação com seus fornecedores e 
clientes. O objetivo é desenvolver um sistema integrado de gerenciamento de qualidade e estoque, permitindo o registro e acompanhamento da análise realizada por um funcionário nos lotes de rolos de tecido, a 
geração de relatórios de não conformidade, a cobrança de indenizações de fornecedores e o controle de vendas para clientes. A Comesc precisa de um sistema que otimize seus processos de qualidade e estoque, 
garantindo maior controle e transparência em sua operação. A empresa recebe lotes de rolos de tecido de fornecedores terceirizados e precisa assegurar que esses materiais atendam aos padrões exigidos antes de 
serem disponibilizados para venda.

# 2. Situação do Problema

### **Introdução**

A Comesc Indústria e Comércio Eireli é uma empresa terceirizada do setor têxtil que atua na comercialização de malhas. Fundada há 10 anos, a empresa é de propriedade de Sergio Leomar dos Reis e Guilherme 
Guissoni conta com uma equipe de 18 funcionários responsáveis por diversas etapas do processo, como aquisição, controle de qualidade e vendas. Sua operação consiste na compra de tecido cru, que é enviado para 
empresas terceirizadas responsáveis pelo processo de tecelagem e tingimento. Após o processamento, a Comesc recebe os rolos de tecido acabado, realiza a inspeção de qualidade e disponibiliza os produtos para
venda.

### **Processo de Aquisição e Produção**

A Comesc inicia sua operação com a compra de tecidos crus de fornecedores específicos. Após a aquisição, esses tecidos são encaminhados para empresas terceirizadas que realizam o processo de tecelagem e 
posteriormente para tinturarias que fazem o tingimento de acordo com as especificações da empresa.

### **Controle de Qualidade**

Quando os tecidos retornam das empresas terceirizadas, eles passam por uma inspeção de qualidade interna, realizada por funcionários especializados. Cada lote de rolos de tecido é analisado para verificar se há 
defeitos como variação de cor, falhas na tecelagem ou outros problemas que comprometam a qualidade do produto final. Caso alguma irregularidade seja identificada, é necessário gerar um relatório de não 
conformidade e retornar o lote ao fornecedor responsável, havendo sempre uma cobrança de indenização. A análise da malha precisa ser realizada manualmente para garantir precisão, mas o sistema identificará o erro 
com base na descrição do funcionário, gerará automaticamente relatórios de não conformidade e calculará a indenização devida ao fornecedor, automatizando todo o restante do processo.

### **Gestão de Estoque**

Os tecidos aprovados são cadastrados no estoque da empresa, aguardando sua comercialização. O controle desses produtos é essencial para garantir que os clientes tenham acesso a um catálogo atualizado e evitar 
perdas por desorganização ou falta de rastreabilidade dos produtos armazenados. No entanto, o registro e gerenciamento do estoque ainda são feitos manualmente, tornando o processo mais suscetível a erros e 
dificuldades no acompanhamento do fluxo de produtos.

### **Comercialização**

A Comesc vende seus produtos para diversos clientes do setor têxtil, fornecendo malhas acabadas de diferentes tipos. O processo de vendas exige um acompanhamento eficiente do estoque para garantir que os pedidos 
sejam atendidos sem atrasos ou indisponibilidades inesperadas. Atualmente, a empresa enfrenta dificuldades na gestão das vendas, pois não há um sistema unificado que permita um controle preciso das transações, do 
faturamento e do envio de produtos.

### **Conclusão**

Embora o processo de controle de qualidade precise ser realizado manualmente para garantir precisão, a Comesc enfrenta desafios na gestão do estoque e na organização das vendas devido à falta de um sistema 
integrado. O gerenciamento manual dessas áreas aumenta o risco de inconsistências nos registros, atrasos na atualização do estoque e dificuldades no controle de pedidos e faturamento. Um sistema informatizado 
pode solucionar essas dificuldades ao fornecer uma plataforma integrada para o registro e monitoramento do estoque e a otimização das vendas. Com a implementação de um software, a Comesc 
poderá melhorar a rastreabilidade dos produtos, reduzir erros operacionais e aprimorar o relacionamento com clientes e fornecedores.

# 3. Proposta

Para atender às necessidades da Comesc, será desenvolvido um sistema de gestão integrado que automatizará os processos de controle de qualidade, gestão de estoque e vendas. O sistema contará com três tipos de usuários:

Cliente: Poderá visualizar o catálogo de produtos disponíveis e realizar compras de maneira simplificada.

Administrador: Terá acesso total ao sistema, podendo executar qualquer tipo de ação, como gerenciar usuários, acompanhar relatórios e modificar dados do estoque e das vendas.

Funcionário: Poderá realizar o cadastro, edição e exclusão de lotes, rolos, cores e materiais. Além disso, será responsável por registrar as análises de qualidade dos rolos de tecido, inserindo descrições sobre 
possíveis defeitos.

O funcionamento do sistema será baseado em um fluxo otimizado: Ao receber um novo lote de rolos de tecido, ele será cadastrado no sistema com o status "Pendente".

Um funcionário realizará a inspeção de um rolo do lote e registrará suas observações no sistema. Se o rolo analisado estiver dentro dos padrões de qualidade, o lote será aprovado e disponibilizado no estoque para 
comercialização. Caso haja alguma irregularidade, o sistema solicitará uma análise mais detalhada dos demais rolos do lote para quantificar a quantidade de tecido prejudicada. Com base nos dados inseridos pelo 
funcionário, o sistema gerará automaticamente um relatório de não conformidade e calculará a indenização que deverá ser paga pela tinturaria ou malharia responsável.

O administrador poderá acompanhar os relatórios e garantir que os fornecedores cumpram com as indenizações e correções necessárias. O módulo de vendas permitirá que os clientes acessem o catálogo de produtos 
disponíveis e realizem pedidos de forma automatizada, garantindo maior eficiência na comercialização das malhas. Com essa solução, a Comesc terá um sistema centralizado que agiliza o fluxo operacional, reduz 
erros manuais, melhora a gestão do estoque e otimiza a comunicação com fornecedores e clientes.

# 4. Modelo do Banco de Dados

![diagrama MER](images/MER.png)

# 5. Regras de Negócio

RN01 – Análise de Qualidade Manual
A inspeção de qualidade dos rolos de tecido deve ser feita obrigatoriamente por um funcionário qualificado. O sistema apenas registra e organiza as informações fornecidas pelo funcionário, não substituindo a 
análise humana.

RN02 – Acompanhamento de Lotes
Cada lote de tecido recebido da malharia ou tinturaria deve ser inspecionado e ter seu status atualizado no sistema antes de ser disponibilizado para venda ou enviado para indenização.

RN03 – Identificação de Defeitos
Se um rolo apresentar defeitos, o funcionário deve registrar o problema no sistema. O sistema, então, exigirá a verificação dos demais rolos do mesmo lote para determinar a extensão do problema.

RN04 – Geração Automática de Relatórios
Ao identificar defeitos em um lote, o sistema deve gerar automaticamente um relatório de não conformidade para ser enviado à malharia ou tinturaria responsável.

RN05 – Cálculo de Indenização
Sempre que um lote for identificado como defeituoso, o sistema calculará automaticamente o valor da indenização que a malharia ou tinturaria deve pagar, considerando a quantidade de tecido comprometida e o custo 
da matéria-prima.

RN06 – Registro Obrigatório no Estoque
Nenhum lote pode ser vendido antes de estar devidamente cadastrado e aprovado no sistema. Apenas lotes sem defeitos ou lotes defeituosos rejeitados pela malharia/tinturaria podem ser disponibilizados para venda.

RN07 – Venda de Lotes com Defeitos
Caso a tinturaria ou malharia não aceite receber um lote defeituoso de volta, esse lote poderá ser colocado à venda com a devida identificação do problema, podendo ser vendido a um preço reduzido conforme regras 
da empresa.

RN08 – Controle de Acesso
Diferentes usuários terão permissões específicas no sistema:

Administradores podem acessar e modificar qualquer informação.

Funcionários podem cadastrar lotes e registrar defeitos.

Clientes apenas consultam o estoque e realizam pedidos.

# 6. Requisitos Funcionais

RF001 - O sistema deve manter Usuário, contendo os seguintes dados: (
Nome, Data de nascimento, CPF, Telefone, Email, Endereço )

RF002 - O sistema deve manter Funcionário, contendo os seguintes dados: (
Identificação do funcionário, Chave estrangeira de usuário, Cargo )

RF003 - O sistema deve manter Administrador, contendo os seguintes dados: (Chave estrangeira de usuário )

RF004 - O sistema deve manter Lote, contendo os seguintes dados: (Número de nota fiscal, Itens, Peso, Preço total( cálculo do custo de fio, malharia e tinturaria de todos os rolos), tem Inconformidade, Quantidade de kg com problemas )

RF005 - O sistema deve manter Rolo de Malha, contendo os seguintes dados: (
Chave estrangeira de lote, Ordem de produção, Cor, Material, Nome, Tem inconformidade, Comprimeto, Gramatura )

RF006 - O sistema deve manter Material, contendo os seguintes dados: ( Custo de fio, Custo de produção de malharia, Custo de produção de tinturaria, Nome do artigo, Composição )

RF007 - O sistema deve manter Problemas da Malha, contendo os seguintes dados: ( Tipo de problema (malharia ou tinturaria), Descrição do problema, Funcionalidades do Sistema, Entradas )

RF008 - O sistema deve permitir o cadastro de tecidos adquiridos, informando fornecedor, tipo de tecido, quantidade e data da compra.

RF009 - O sistema deve permitir o registro do envio de tecidos para tecelagem e tinturaria, com informações de destino, prazos e quantidades enviadas.

RF010 - O sistema deve permitir que os funcionários registrem a análise dos tecidos recebidos, incluindo eventuais defeitos e conformidade do produto.

RF011 - O sistema deve permitir o cadastro dos tecidos aprovados e disponíveis para venda, incluindo suas características e localização no estoque.

RF012 - O sistema deve permitir o registro de pedidos realizados pelos clientes, informando produtos selecionados, quantidades e prazos de entrega.

RF013 - O sistema deve gerar automaticamente relatórios de não conformidade caso um lote de tecido apresente defeitos durante a inspeção de qualidade.

RF014 - O sistema deve calcular automaticamente a indenização devida pelo fornecedor caso um lote apresente inconformidades.

RF015 - O sistema deve verificar automaticamente se há produtos disponíveis antes da confirmação de um pedido de venda.

RF016 - O sistema deve reduzir automaticamente a quantidade correspondente no estoque a cada venda realizada.

RF017 - O sistema deve permitir o acompanhamento do status dos pedidos, desde a solicitação até a entrega ao cliente.

RF018 - O sistema deve gerar relatórios de estoque que permitam a visualização dos produtos disponíveis, suas quantidades e localização.

RF017 - O sistema deve gerar relatórios de qualidade sobre os lotes analisados, incluindo defeitos encontrados e status de aprovação.

RF018 - O sistema deve gerar relatórios de vendas com informações sobre pedidos realizados, faturamento e produtos mais vendidos.

RF019 - O sistema deve gerar um histórico de movimentação de estoque, registrando todas as alterações e permitindo rastrear entradas e saídas de produtos.

RF020 - O sistema deve gerar relatórios financeiros exibindo informações sobre faturamento e indenizações recebidas de fornecedores.

RF021 - O sistema deve manter fornecedores ( Nome, Endereço, CNPJ, Tipo)

# 7. Requisitos Não Funcionais

RNF001 - O sistema deve ser desenvolvido com HTML, CSS, Tailwind, JavaScript e Vue.js para o frontend.

RNF002 - O backend do sistema deve ser desenvolvido em Python, utilizando Django e Django REST Framework.

RNF003 - O sistema deve utilizar Streamlit para a geração de gráficos.

RNF004 - O sistema deve integrar a API do Mercado Pago para processamento de pagamentos.

RNF005 - O sistema deve ser responsivo, adaptando-se a diferentes tamanhos de tela.

RNF006 - O sistema deve estar disponível para dispositivos móveis via PWA e também como aplicativo e site para computadores.

RNF007 - O sistema deve garantir a segurança dos dados, criptografando senhas e demais informações sensíveis.

RNF008 - O acesso a informações restritas deve ser permitido apenas para administradores e funcionários autorizados.

RNF009 - O sistema deve utilizar PostgreSQL como banco de dados e o diagrama deve ser feito no MySQL Workbench.

RNF010 - O sistema deve estar disponível 24 horas por dia, apesar do funcionamento da empresa ser das 8h às 18h.

RNF011 - O sistema deve rodar em dispositivos com no mínimo um processador Intel i3 de 5ª geração ou similar, 8GB de RAM e um navegador atualizado.

RNF012 - O catálogo de vendas deve ser acessível sem autenticação, mas para adicionar itens ao carrinho ou realizar compras, é necessário autenticar-se.

RNF013 - O gerenciamento do sistema deve ser acessível apenas para usuários autenticados como administradores ou funcionários.

Com a implementação desses requisitos, o sistema garantirá maior controle e eficiência para a gestão da Comesc, reduzindo erros e otimizando processos essenciais da empresa.

# 8. Diagrama de Caso de Uso

## Identificação dos Atores

![image](https://github.com/user-attachments/assets/a6655c13-9078-455b-a425-277bc8493fee)

**1. Gerente (Administrador)**  
- **Função:** Administra o sistema como um todo.  
- **Atribuições:**
  - Controla o acesso ao sistema.
  - Cadastra e gerencia usuários (funcionários e clientes).
  - Visualiza relatórios financeiros, de vendas, de qualidade e de estoque.

**2. Funcionário**  
- **Função:** Interage com o estoque e realiza análises de qualidade dos rolos.  
- **Atribuições:**
  - Cadastra lotes e rolos de malha no sistema.
  - Registra os resultados das análises de qualidade.
  - Informa problemas detectados nos rolos.
  - Visualiza e atualiza o estoque.

**3. Cliente**  
- **Função:** Realiza a compra de rolos de malha.  
- **Atribuições:**
  - Visualiza o catálogo de produtos.
  - Adiciona produtos ao carrinho.
  - Realiza pedidos e pagamentos (mediante autenticação).
  - Acompanha o status de seu pedido.


