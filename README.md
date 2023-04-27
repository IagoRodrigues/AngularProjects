# AngularProjects
## Projetos de estudo e desenvolvimento em Angular
Curso de Angular da Cod3r disponível em: https://www.cod3r.com.br/courses/angular-9-essencial

### Rodar o Backend
<strong>O que:</strong> npm start </br>
<strong>Onde:</strong> crud/backend </br>
<strong>Para que:</strong> iniciar nossa api e permitir fazer requisições </br>
(Precisa ficar rodando em um console) </br>

### Rodar o Frontend
<strong>O que:</strong> npm start </br>
<strong>Onde:</strong> crud/frontend </br>
<strong>Para que:</strong> iniciar o frontend </br>
(Precisa ficar rodando em um console) </br>

### Angular
<strong>O que:</strong> npm i -g @angular/cli </br>
<strong>Onde:</strong> Qualquer lugar </br>
<strong>Para que:</strong> instalar a dependência e poder usar o angular e o angular cli </br>

<strong>O que:</strong> ng </br>
<strong>Onde:</strong> Qualquer lugar </br>
<strong>Para que:</strong> abrir um help, ou seja, lista de comandos possíveis usando ng </br>

<strong>O que:</strong> ng new (ver parâmetros) </br>
<strong>Onde:</strong> Qualquer lugar </br>
<strong>Para que:</strong> Começar um projeto usando angular </br>

### EndPoints
<strong>O que:</strong> Endpoints da API</br>
<strong>Onde:</strong> Navegador </br>
<strong>Para que:</strong> Modificar/Visualizar os dados salvos</br>

<strong>Exemplos:</strong>
Trazer todos os produtos:
http://localhost:3001/products

Trazer um produto específico:
http://localhost:3001/products/1

Outras requisições também são possíveis via Insomnia

### Diretivas
<strong>O que:</strong> Altera aparência e comportamento de um ou mais elementos</br>
<strong>Onde:</strong> Dentro das '<''>' após o nome de um componente</br>
<strong>Para que:</strong> Com diretivas podemos adicionar comportamentos variados a um componente.</br> Diretivas de atributo mudam aparência e comportamento, diretiva estruturais mudam estruturalmente o DOM, um exemplo é *ngIf e *ngFor.</br>

### Property Binding/ []
<strong>O que:</strong> Comunicação de dados do TS para o HTML</br>
<strong>Onde:</strong> Dentro das '<''>' após o nome de um componente usando colchetes</br>
<strong>Para que:</strong> Com data binding é possível comunicar TS e HTML passando dados de um para outro.</br>
É o que permite pegar algo digitado no HTML dentro do TS ou exibir algo do TS no HTML.</br>

### Event Binding/ ()
<strong>O que:</strong> Comunicação de eventos do HTML para o TS</br>
<strong>Onde:</strong> Dentro das '<''>' após o nome de um componente usando parênteses</br>
<strong>Para que:</strong> Com event binding é possível comunicar TS e HTML disparando um evento no HTML e executando um método correspondente no TS.</br>

### One way data binding/ []
<strong>O que:</strong> Uma linha de comunicação sempre do TS para o HTML</br>
<strong>Onde:</strong> Dentro das '<''>' após o nome de um componente usando colchetes</br>
<strong>Para que:</strong> One way data binding puxa o dado presente no TS e joga para o HTML, nunca o contário.</br>
Sendo assim é possível exibir dados do TS no HTML desde que eles não possam ser modificados no HTML.</br>

### Two way data binding/ [()]
<strong>O que:</strong> Uma linha de comunicação bilateral entre TS e HTML</br>
<strong>Onde:</strong> Dentro das '<''>' após o nome de um componente usando colchetes e parênteses: [(ngModel)]</br>
<strong>Para que:</strong> Two way data binding puxa o dado presente no TS e joga para o HTML, ou o contário.</br>
Sendo assim é possível exibir dados do TS no HTML e caso eles seja modificados no HTML essa modificação também acontece no TS.</br>

### Router
<strong>O que:</strong> Rotas entre links e componentes na aplicação</br>
<strong>Onde:</strong> Barra do navegador</br>
<strong>Para que:</strong> É necessário mapear a relação entre URL e componente exibido, para quando o cliente clicar em home ou utilizar /home no endereço do site seja exibido o componente home corretamente.</br>

### Pipes
<strong>O que:</strong> Processamento sobre variáveis</br>
<strong>Onde:</strong> Onde for necessário</br>
<strong>Para que:</strong> Podemos utilizar chaves (double mustache) para exibir variáveis, então podemos utilizar pipes para formatar ou fazer alguma operação/personalização na exibição dessa variável, por exemplo: {{ dataNiver | date }}</br>

### Chaining
<strong>O que:</strong> Encadeamento de pipes</br>
<strong>Onde:</strong> Onde for necessário</br>
<strong>Para que:</strong> Podemos encadear pipes para formatar ou fazer alguma operação/personalização na exibição dessa variável, por exemplo: {{ produto.vencimento | date:'fullDate' | uppercase }} ou seja: </br> formatar a variável produto.vencimento usando date:'fullDate' e após isso aplicar uppercase. </br>

### Modelo
<strong>O que:</strong></br>
<strong>Onde:</strong></br>
<strong>Para que:</strong></br>