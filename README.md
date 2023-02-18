programa
{
	
	funcao inicio()
	{

		real nota1, nota2, nota3, nota4, media

		escreva ("Primeira Nota: ")
		leia (nota1)

		escreva ("Segunda Nota: ")
		leia (nota2)

		escreva ("Terceira Nota: ")
		leia (nota3)

		escreva ("Quarta Nota: ")
		leia (nota4)

		limpa ()

		media = (nota1 + nota2 + nota3 + nota4)/4

		
		
		se (media >= 7) escreva ("Sua nota é: "+ media +"\nAprovado!")
		senao escreva ("Sua nota é: "+ media +"\nReprovado!")
		
	}
}
