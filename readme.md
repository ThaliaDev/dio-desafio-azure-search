## Introdução à Azure AI Search
Nesse repositório será demonstrado o passo a passo para a utilização do Azure AI Search, com o objetivo de entender como funciona a busca em documentos.

#### Pré-requisitos
Temos como pré-requisito a criação uma conta gratuita na Azure ou disponibilidade de créditos para uso.

### Tutorial
#### Criando o recurso
Para criar um recurso, utilizei o marketplace, localizado no  portal do [Azure](https://portal.azure.com/learn.docs.microsoft.com?azure-portal=true) e fiz uma busca por AI Search, AI Services e Storage Accounts. Criei em cada uma delas.

![Recursos](https://i.imgur.com/C4fD1RR.png)

#### Configurando Storage Account
Foi feito a configuração do Storage Account, ativando o acesso anônimo, criando o container

![Container](https://i.imgur.com/zQjGLqd.png)
![Arquivos](https://i.imgur.com/F0iU1oN.png)

#### Usando o IA Search 
Primeiramente criei a conexão com o Storage, selecionando o container criado. Depois segui para o Search Explorer.

![Search](https://i.imgur.com/18sT4rg.png)

Os resultados foram os seguintes:

![Resultados](https://i.imgur.com/Zsvrqyf.png)

#### Conclusão
Com essa ferramenta é possível fazer uma análise de vários documentos, no caso foram avaliações de um estabelecimento. Essas análises nos permitem fazer filtros, seja por localização, se foi uma avaliação positiva ou negativa, entre outros.