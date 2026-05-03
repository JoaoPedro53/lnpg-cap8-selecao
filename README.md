<h2>João Pedro Santos Vieira</h2>
<p>LLM: ChatGPT - v5.3</p>

<h3>Análise Q1: </h3>
<li>1° Melhor facilidade de escrita -> Python. Por ser uma linguagem menos verbosa, se sobressai nesse ponto, em relação a outras como Java e Swift. </li>
<li>2° Melhor legibilidade -> Java. Devido aos blocos de código e sua tipagem estática que deixa explícito quais os tipos das variáveis que você está lindando.</li>
<li>3° Melhor em ambos -> Java. Mesmo sendo mais verboso, recursos como LLMs e auto-complete, em parte resolvem o problema. Blocos de 
código tiram a preocupação de ter que reparando em espaçamento de linhas, é bem mais simples entender que o que está dentro dos '{}' é o que sera executado, e por último, 
a fato de estar sempre definindo estaticamente o tipo de cada variável diminui a chances de erros.</li>

<h3>Análise Q2: </h3>
<li>1° Switch: C -> Boa escrita, boa legibilidade e Uso de bloco de código.</li>
<li>2° Case: Ruby -> Ótima escrita, Ótima legibilidade.</li>
<li>3° Case ... of: Erlang -> Leitura aceitável, bom no sentido de que, entre as três é a única que não repete a variável que vai receber a atribuição.</li>

<h3>Análise Q3: </h3>
<li>No geral, as mudanças que houveram foi: Ao invés de Switch agora é if/else/else-if | o for continua sendo executado enquanto o j <= 0. Porque, se j > 0 ele para, então ele continua se j <= 0. | j + 2 saiu dos parâmetros do switch e foi para a variável expr, que agora é comparada dentro dos IFs.</li>
<li>Houveram algumas mudanças específicas como: em Python, o iterador 'i' tem que ser instanciado antes e fora do for, em Javascript usa 'let' ao invés de 'int' e usa o comparador '===' invés do '==', isso porque o '===' em javascript verifica o tipo e o valor da variável que está sendo comparada.</li>

<h3>Análise Q4: </h3>
<li>1° C, C++ e Javascript -> Suportam a mesma contrução for que Java, e também é feita inicialização da variável 'sum', que faltou no exemplo Java. </li>
<li>2° Go -> A declaração e atribuição é feita com ':=', as variáveis 'i' e 'j' são declaradas e atribuidas sequencialmente dentro do for 'i, j := 0, 17;'. Na parte de atualização do for, 'i, j = i+1, j-1' é usado o '=' por que só está sendo feito uma reatribuição.</li>
<li>3° Kotlin -> Não permite declarar duas ou + variáveis no for, logo elas foram declaradas e atribuídas antes. A variável 'n' é do tipo 'val', e não 'var' como as outras, logo 'n' é imultável, mas as outras do tipo 'var' são multáveis, portanto podem ter seus valores alterados.</li>
