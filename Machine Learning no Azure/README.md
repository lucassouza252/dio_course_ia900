# Machine Learning no Azure

## Passos para o machine learning automatizado

<ol>
    <li>Devemos criar um ambiente de trabalho no resource: Azure Machine Learning;</li>
    <li>Acessar o Azure Machine Learnign Studio;</li>
    <li>Selecionar a opção de ML Automatizado;</li>
    <li>Entrar com as configurações de nome do job e descrição;</li>
    <li>Selecionar o tipo de modelo, que neste caso é regressão;</li>
    <li>Criar a base de dados que sera utilizada;</li>
    <li>A base de dados é feita proveniente da web pelo link: https://aka.ms/bike-rentals</li>
    <li>A forma dos dados é CSV e a primeira linha são os headers;</li>
    <li>Devemos configurar os limites de tentativas e os modelos permitidos para a tarefa;</li>
    <li>O tipo de validação é Train test split;</li>
    <li>A computação é dedicada em cpu com apenas uma instancia de uma vm standard;</li>
    <li>Após as configurações, o job irá iniciar;</li>
    <li>Com o job finalizado, será disponibilizado os melhores modelos;</li>
    <li>A partir da escolha do melhor modelo, é feito o deploy deste modelo;</li>
    <li>Com o deploy do modelo pronto, é criado um endpoint através de uma vm;</li>
    <li>Com o endpoint criado, é possivel realizar testes e chamadas rest ao modelo em produção.</li>
</ol>