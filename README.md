# Atividade-SENAI-2
atividade 1 
programa {
  funcao inicio() {
    inteiro x
    x = 18
    escreva("Digite sua idade: ")
    leia(x)
    se (x<18)
    escreva(" Menor de idade")
    senao
    escreva(" Maior de idade")
    }
   } 

atividade 2

programa {
  funcao inicio() {
    inteiro x
    x = 0
    escreva(" Digite um número ")
    leia(x)
    se(x>=0)
    escreva(" Número positivo ")
    senao
    escreva(" Número negativo ")
    
  }
}

atividade 3

programa {
  funcao inicio() {
    inteiro numero
    escreva(" Digite um número: ")
    leia(numero)
    se ( numero % 2 == 0 ) {
      escreva(numero, " é par")
      }
      senao {
        escreva(numero, " é ímpar")
        }
    
  }
}

atividade 4

programa {
  funcao inicio() {
    inteiro a, b 
    escreva(" Digite um número:")
    leia(a)

    escreva(" Digite um número: ")
    leia(b)

    se(a>b)
    escreva(a, " é maior que ", b)

    senao
    escreva(a, " é menor que ", b)

    
  }
}

atividade 5 

programa {
  funcao inicio() {
    inteiro a, b 
    escreva(" Digite um número:")
    leia(a)

    escreva(" Digite um número: ")
    leia(b)

    se(a==b)
    escreva(a, " é igual a ", b)

    senao
    escreva(a, " é diferente de ", b)

    
  }
}

atividade 6

programa {
  funcao inicio() {
    inteiro x
      escreva("Digite um número ")
      leia(x)
      se((x >=10) e (x <=20))
      escreva("Está entre o intervalo")
      senao
      escreva("Não está entre o intervalo") 
    
  }
}


atividade 7

programa {
  funcao inicio() {
    inteiro numero
    escreva("Digite um número: ")
   leia(numero)
   se (numero > 0 e numero % 2 == 0)
      escreva("O número é positivo e par.")
   senao
      escreva("O número NÃO é positivo e par.")
    
  }
}

atividade 8

programa {
  funcao inicio() {
    inteiro numero
    escreva("Digite um número: ")
   leia(numero)
   se ((numero < 0) ou (numero % 2 != 0))
      escreva("O número é negativo ou ímpar.")
   senao
      escreva("O número NÃO é negativo nem ímpar.")
    
  }
}


atividade 9 

programa {
  funcao inicio() {
    inteiro numero

    escreva("Digite um número: ")
    leia(numero)

    se ((numero % 5 == 0) e (numero % 3 == 0))
        escreva("O número ", numero, " é múltiplo de 5 e 3.")
    senao
        escreva("O número ", numero, " não é múltiplo de 5 e 3.")
    
  }
}


atividade 10

programa {
  funcao inicio() {
     inteiro numero
      escreva("Digite um número: ")
    leia(numero)
     se (numero % 4 ?- 0)
        escreva("O número não é múltiplo de 4.")
    senao
        escreva("O número é múltiplo de 4.")
        }
      }  

    atividade 11
    
programa {
  funcao inicio() {
    inteiro idade

    
    escreva("Digite sua idade: ")
    leia(idade)

    
    se (idade >= 16) 
        escreva("Você pode votar!")
    senao
        escreva("Você não pode votar ainda.")
    
  }
}

atividade 12 

programa {
  funcao inicio() {
      real nota

    escreva("Digite a nota do aluno: ")
    leia(nota)

    se (nota >= 7)
        escreva("Aluno aprovado.")
    senao
        escreva("Aluno reprovado.")
    
  }
}


atividade 13 

programa {
  funcao inicio() {
    inteiro numero

    escreva("Digite um número: ")
    leia(numero)

    se ((numero % 2 == 0) e (numero < 100))
        escreva("O número ", numero, " é par e menor que 100.")
    senao
        escreva("O número ", numero, " não é par ou não é menor que 100.")
    
    
  }
}

atividade 14

programa {
  funcao inicio() {
    cadeia senha

    escreva("Digite a senha: ")
    leia(senha)

    se (senha == "1234")
        escreva("Senha correta.")
    senao
        escreva("Senha incorreta.")
    
  }
}

atividade 15

programa {
  funcao inicio() {
    caractere letra

    escreva("Digite uma letra: ")
    leia(letra)

    se (letra == "a" ou letra == "e" ou letra == "i" ou letra == "o" ou letra == "u")
        escreva("A letra ", letra, " é uma vogal.")
    senao
        escreva("A letra ", letra, " não é uma vogal.")
    
  }
}


atividade 16

programa {
  funcao inicio() {
      inteiro ano

    escreva("Digite um ano: ")
    leia(ano)

    se ((ano % 4 == 0) e (ano % 100 != 0) ou (ano % 400 == 0))
        escreva("O ano ", ano, " é bissexto.")
    senao
        escreva("O ano ", ano, " não é bissexto.")
    
  }
}

atividade 17

programa {
  funcao inicio() {
      logico valor1, valor2

    escreva("Digite o primeiro valor (verdadeiro ou falso): ")
    leia(valor1)

    escreva("Digite o segundo valor (verdadeiro ou falso): ")
    leia(valor2)

    se ((valor1 == verdadeiro e valor2 == verdadeiro))
        escreva("Ambos os valores são verdadeiros.")
    senao
        escreva("Pelo menos um dos valores não é verdadeiro.")
    
  }
}

atividade 18

programa {
  funcao inicio() {
      logico valor1, valor2

    escreva("Digite o primeiro valor (verdadeiro ou falso): ")
    leia(valor1)

    escreva("Digite o segundo valor (verdadeiro ou falso): ")
    leia(valor2)

    se ((valor1 == verdadeiro e valor2 == verdadeiro))
        escreva("Ambos os valores são verdadeiros.")
    senao
        escreva("Pelo menos um dos valores não é verdadeiro.")
    
  }
}

atividade 19

programa {
  funcao inicio() {
      logico valor1, valor2

    escreva("Digite o primeiro valor (verdadeiro ou falso): ")
    leia(valor1)

    escreva("Digite o segundo valor (verdadeiro ou falso): ")
    leia(valor2)

    se ((valor1 == verdadeiro e valor2 == verdadeiro))
        escreva("Ambos os valores são verdadeiros.")
    senao
        escreva("Pelo menos um dos valores não é verdadeiro.")
    
  }
}

atividade 20

programa {
  funcao inicio() {
    inteiro numero

    escreva("Digite um número: ")
    leia(numero)

    se (numero < 0 ou numero > 1000)
        escreva("O número ", numero, " é negativo ou maior que 1000.")
    senao
        escreva("O número ", numero, " não é negativo nem maior que 1000.")
    
  }
}



atividade 21
programa {
  
  funcao inicio() 
  {
    real soma, sub, mult, div
    real n1, n2
    real op

    escreva("escreva a op desejada: \n")
    escreva(" digite: \n")
    escreva("1 para somar \n")
    escreva("2 para subtrair \n")
    escreva("3 para multiplicar \n")
    escreva("4 para dividir \n")
    leia(op)

    limpa()

    escreva("informe o primeiro numero: ")
    leia(n1)
    escreva(" informe o segundo numero")
    leia(n2)

    se(op == 1){
      soma = n1+n2
        escreva("o resultado é: ", soma)
     }
      senao se (op == 2){
        sub = n1-n2
        escreva("o resultado é: ", sub)
        }
        senao se(op == 3){
          mult = n1*n2
          escreva("o resultado é: ", mult)
          }
          senao se (op == 4){
            div = n1/n2
            escreva("o resultado é: ", div)
            }
            senao{
              escreva(" operação invalida ")
              }



  }
}



atividade 22

programa {
  
  funcao inicio() 
  {
    real dom,seg, ter, qua, qui, sex, sab
    real n1, n2
    real op


    escreva("digite um numero de 1 a 7: \n")
    leia(op)

    limpa()

    escreva("informe o dia da semana desejado: \n")
    
    se (op == 1){
    dom = 1
    escreva("O dia da semana é domingo: \n")
    }
    senao se (op == 2){
      seg = 2
      escreva("O dia da semana é segunda: \n")
      }
      senao se (op == 3){
        ter = 3
        escreva("O dia da semana é terça: \n")
        }
        senao se (op == 4){
          qua = 4
          escreva("O dia da semana é quarta: \n")
          }
          senao se (op == 5){
          qui = 5
          escreva("O dia da semana é quinta: \n")
        }
        senao se (op == 6){
          sex = 6
          escreva("O dia da semana é sexta: \n")
          }
          senao se (op == 7){
          sab = 7
          escreva("O dia da semana é sabádo: \n")
          }
          senao{
            escreva("nao e possivel dizer qual o dia: ")
            }
  }
}

atividade 23 
programa {
  
  funcao inicio() 
  {
    inteiro idade


    escreva("digite sua idade: ")
    leia(idade)

    se(idade >=0 e idade <=12){
      escreva(" Ainda é uma criança: \n")
      }
      senao se (idade >=13 e idade <=17){
        escreva("Ainda é um adolescente: \n")
        }
        senao se (idade >=18 e idade <=59){
          escreva("Ainda é um adulto: \n")
          }
          senao se (idade >= 60){
            escreva("É um idoso: \n")
            }
            





  }
}

atividade 24 

programa {  
  funcao inicio() 
  {
    real valor, resultado
    real op

    
    escreva("1. Quilômetros para Milhas: \n")
    escreva("2. Quilogramas para Libras: \n")
    escreva("3. Celsius para Fahrenheit: \n")
    escreva("Escolha uma opção: \n")
    leia(op)

    escreva("Digite o valor a ser convertido: ")
    leia(valor)

      se (op == 1){
        resultado = valor * 0.621371
        escreva(valor, " km equivalem a ", resultado, " milhas.\n")
        }
      senao se (op == 2){
        resultado = valor * 2.20462
        escreva(valor, " kg equivalem a ", resultado, " libras.\n")
        }
        senao se (op == 3){
          resultado = (valor * 9/5) + 32
          escreva(valor, "°C equivalem a ", resultado, "°F.\n")
          }




  }
}

atividade 25

programa 
{
	funcao inicio()
	{
		inteiro lado_a, lado_b, lado_c
		
		escreva ("Informe o primeiro lado do triângulo: ")
		leia (lado_a)

		escreva ("Informe o segundo lado do triângulo: ")
		leia (lado_b)

		escreva ("Informe o terceiro lado do triângulo: ")
		leia (lado_c)

		se (lado_a == lado_b e lado_a == lado_c)
		{	
			escreva ("\nEste triângulo é Equilátero\n")
		}
		senao 
		{	
			se (lado_a == lado_b ou lado_b == lado_c ou lado_c == lado_a)
			{
				escreva ("\nEste triângulo é Isósceles\n")
			}
			senao
			{
				escreva ("\nEste triângulo é Escaleno\n")
			}
		}
	}
}
