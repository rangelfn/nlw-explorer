1. HTML
   - Hipertext Markup Language
   - Hiper texto?
     - Marcações
     - Tags
    - Linguagem
    - Maneira de escrever

3. CSS
  - Declaração
    - Seletor
    - Propriedades e Valor

  3. Conceitos
    - Cascatas
    - Especificidade
    - Box Model
    - Display block vs inline

  3. JS
     - Variáveis
       - let (posso alterar o valor a qualquer momento)
       - const (não osso alterar o valor) Case sensitive.
  
  #Tipos de dados
    - String (textos) sempre entre aspas duplas "Exemplo" ou simples 'Exemplo'.
    - Number (numeros) integer (12), float (12.3)
    - Boolean true false (verdadeiro ou falso)
    - undefined (indefinido)

  #Operadores
  - Atribuição de valor (ex: =)
    - let n1 = 12
    - let n2 = 3
    - console.log (n1 + n2)
    
  - Aritiméticos (ex: * / + -) Utilizado para cálculos matemáticos simples.
      - console.log (12*4)
  
  - Concatenação de string (*)
    - console.log ("23"+ 4)

  - Operador de comparação (true or false)
    - const maiorQue = 1 > 2 (false)
    - const igualA = 1 == 1 (true)

  - Condicional (if/else)
    - const idade = 17
    - const maiorIdade >= 18
    
    if (maiorIdade) {
        alert("Pode prosseguir")
    } else {
        alert("Não pode prosseguir")
    }

   - Estrutura de dados
    Array - Vetor - Lista
        const temperatura [23, 17, 30, 31.2, 2]
    
   #Object
      const pessoa = {
         nome: "Rangel",
         idade: 41,
         filhos: ["Pietra", "Paola", "Pilar", "Theodoro","Thomaz"]
      }
      console.log(pessoa.filho[3])

  #Função
      - Criação da função(){
         console.log ('codigo dentro da função!')
         }
      - Execução da função
         function nomeDaFuncao ()
      - Parametros da função
         function soma (a, b) {
         console.log (a + b)
         }
         soma (34, 89)
   
   #Retorno
      function soma (a, b) {
        return a + b
      }
      const multiplica = soma (2, 2) * 4
      console.log multiplica
      console.log(soma(2,2))
   
   #Extensões da linguagem (Math, Date)
      - Math.random()
      - Math.floor(1.2)
      - Math.ceil()
      - Math.PI
   
   #DOM (Document Object Model)
      - window
      - window.alert("alerta")
      - document
      - document.write("textos")
      - manipular elementos
          document.documentElement.style.background = "black"
