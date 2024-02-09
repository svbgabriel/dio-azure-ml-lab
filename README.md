# dio-azure-ml-lab
## Repositório para o Lab - Trabalhando com Machine Learning na Prática no Azure ML

### Passo a passo

Esse passo a passo é baseado no tutorial no seguinte link: https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/01-machine-learning.html

Observações: O idioma usando para interface foi o inglês

#### 1 - Criação do Azure Machine Learning

- Faça o login no [Azure Portal](https://portal.azure.com)
- Selecione **+ Create a resource**, pesquise por **Azure Machine Learning** e crie um resource
- Após preencher com os dados de criação, clique em **Review + create**, confira os dados e clique em **Create**
  - O processo pode demorar um pouco (5 - 15 minutos)
-  Clique em **Launch studio**

#### 2 - Usando o Automated ML

- Em **Azure Machine Learning studio**, clique em **Automated ML page**
- Crie um **Automated ML job** inserindo as informações solicitadas
- Após inserir as informações, aguarde o processamento

#### 3 - Encontre o melhor modelo

- Nos trabalhos, encontre e selecione o melhor trabalho
- Selecione **Deploy** e use a opção **Web service**
- Preencha as informações e clique em **Deploy**
- Aguarde o processamento, acompanhando em **Deploy status**

#### 4 - Testando o serviço

- Selecione o endpoint criado
- Na aba **Test** insira os dados
  - Há exemplos de requisição e resposta no repositório
- Clique em **Test**
