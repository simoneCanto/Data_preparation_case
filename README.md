# Data_preparation_case
## Rotatividade de clientes de telecomunicações: conjunto de dados IBM

Prepare um dataset que será utilizado para classificação de Churn.

O dataset utilizado é proveniente de uma empresa fictícia de telefonia, criado e disponibilizado pela IBM para fins didáticos.

Conjunto de dados de amostras base do IBM Cognos Analytics 11.1.3+

Sobre o conjunto de dados
Contexto
Uma empresa de telecomunicações fictícia que forneceu serviços de telefone residencial e Internet para 7.043 clientes na Califórnia no terceiro trimestre.

descrição de dados
7.043 observações com 33 variáveis

CustomerID : um ID exclusivo que identifica cada cliente.

Contagem : um valor usado em relatórios/painel para somar o número de clientes em um conjunto filtrado.

País : O país de residência principal do cliente.

Estado : O estado da residência principal do cliente.

Cidade : A cidade da residência principal do cliente.

CEP : O CEP da residência principal do cliente.

Lat Long : A latitude e longitude combinadas da residência principal do cliente.

Latitude : A latitude da residência principal do cliente.

Longitude : A longitude da residência principal do cliente.

Gênero : O gênero do cliente: Masculino, Feminino

Idoso : Indica se o cliente tem 65 anos ou mais: Sim, Não

Parceiro : Indique se o cliente possui parceiro: Sim, Não

Dependentes : Indica se o cliente mora com algum dependente: Sim, Não. Os dependentes podem ser filhos, pais, avós, etc.

Meses de Posse : Indica o total de meses que o cliente esteve na empresa até o final do trimestre especificado acima.

Atendimento Telefônico : Indica se o cliente assina serviço telefônico residencial da empresa: Sim, Não

Múltiplas Linhas : Indica se o cliente assina múltiplas linhas telefônicas com a empresa: Sim, Não

Serviço de Internet : Indica se o cliente assina serviço de Internet com a empresa: Não, DSL, Fibra Óptica, Cabo.

Segurança Online : Indica se o cliente assina algum serviço adicional de segurança online fornecido pela empresa: Sim, Não

Backup Online : Indica se o cliente assina algum serviço adicional de backup online fornecido pela empresa: Sim, Não

Proteção de dispositivos : Indica se o cliente assina um plano adicional de proteção de dispositivos para seus equipamentos de Internet fornecido pela empresa: Sim, Não

Suporte Técnico : Indica se o cliente assina algum plano de suporte técnico adicional da empresa com tempos de espera reduzidos: Sim, Não

Streaming de TV : Indica se o cliente utiliza seu serviço de Internet para transmitir programação de televisão de um provedor terceirizado: Sim, Não. A empresa não cobra taxa adicional por este serviço.

Streaming de Filmes : Indica se o cliente utiliza seu serviço de Internet para transmitir filmes de um provedor terceirizado: Sim, Não. A empresa não cobra taxa adicional por este serviço.

Contrato : Indica o tipo de contrato atual do cliente: Mês a Mês, Um Ano, Dois Anos.

Faturamento sem papel : Indica se o cliente optou pelo faturamento sem papel: Sim, Não

Forma de Pagamento : Indica como o cliente paga sua fatura: Saque Bancário, Cartão de Crédito, Cheque Enviado

Cobrança Mensal : Indica a cobrança mensal total atual do cliente por todos os serviços da empresa.

Encargos Totais : Indica os encargos totais do cliente, calculados até o final do trimestre especificado acima.

Rótulo de rotatividade : Sim = o cliente saiu da empresa neste trimestre. Não = o cliente permaneceu na empresa. Diretamente relacionado ao valor de churn.

Valor de rotatividade : 1 = o cliente saiu da empresa neste trimestre. 0 = o cliente permaneceu na empresa. Diretamente relacionado ao rótulo Churn.

Pontuação de Churn : um valor de 0 a 100 que é calculado usando a ferramenta preditiva IBM SPSS Modeler. O modelo incorpora vários fatores conhecidos por causar rotatividade. Quanto maior a pontuação, maior a probabilidade de o cliente se desligar.

CLTV : Valor de vida do cliente. Um CLTV previsto é calculado usando fórmulas corporativas e dados existentes. Quanto maior o valor, mais valioso é o cliente. Clientes de alto valor devem ser monitorados quanto à rotatividade.

Motivo de rotatividade : motivo específico de um cliente para deixar a empresa. Diretamente relacionado à categoria Churn.

Fonte
Este conjunto de dados está detalhado em:
https://community.ibm.com/community/user/businessanalytics/blogs/steven-macko/2019/07/11/telco-customer-churn-1113

Transferido de:
https://community.ibm.com/accelerators/?context=analytics&query=telco%20churn&type=Data&product=Cognos%20Analytics

Existem vários conjuntos de dados relacionados, conforme documentado em:
https://community.ibm.com/community/user/businessanalytics/blogs/steven-macko/2018/09/12/base-samples-for-ibm-cognos-analytics
