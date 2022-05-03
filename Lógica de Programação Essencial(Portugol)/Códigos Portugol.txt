# Alguns Códigos feitos em Portugol:key:

##### Segue abaixo:

- Média de vendas + Abono

  	funcao inicio()
  	{
  		real janeiro,fevereiro,marco,abril,media
  		cadeia funcionaria


  		escreva("Digite o seu nome: ")
  		leia(funcionaria)
  		escreva("Vendas de Janeiro: ")
  		leia(janeiro)
  		escreva("Vendas de Fevereiro: ")
  		leia(fevereiro)
  		escreva("Vendas de Março: ")
  		leia(marco)
  		escreva("Vendas de Abril: ")
  		leia(abril)
  		media = (janeiro+fevereiro+marco+abril)/4
  		escreva("O funcionario(a): " + funcionaria + " obteve a média final de vendas: R$" + media)
  		se (media>=5000)
  			escreva("\n" + "Parabéns! Vc receberá abono de 10%.")
  		senao 
  			escreva(".Vc só recebera abono de 3%!")
  		
  	}

- Matriz	

  	funcao inicio()  //Matriz
  	{
  		inteiro contador= 0
  		cadeia cesta [][] = {{"João | ","São Paulo | ","(11)9999-5241"},{"Maria | ","Ribeirão Preto | ","(16)9999-8596"},{"Ana | ","Manaus | ","(92)9999-8574"}}
  	
  		faca{  
  	
  			escreva("Nome: " + cesta[contador][0] + "Cidade: " + cesta[contador][1] + "Numero: " + cesta[contador][2] + "\n" )
  			contador ++
  		}enquanto(contador<=2)
  	}

- Tabuada

  	funcao inicio()
  	{
  		inteiro numero,contador,limite,resultado
  		escreva("Qual a tabuada vc quer saber: ")
  		leia(numero)
  		escreva("\n" + "Até que número vc quer multiplicar: ")
  		leia(limite)
  		contador = 0
  	
  		escreva("Tabuada do " + numero + ":")
  		escreva("\n" + "------------")
  		faca{
  	
  			resultado = numero * contador
  			escreva("\n" + numero + " x " + contador + " = " + resultado)
  			contador ++

  		}enquanto(contador<=limite)
  		escreva("\n" + "------------")
  	}

