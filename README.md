# Aula_15-09
---
# Código VSCode
### Usar código por meio do modo edição!!


programa {
	funcao inicio() {
		real peso, altura, imc
		escreva("Informe o peso: ")
		leia(peso)
		escreva("Informe a altura: ")
		leia(altura)
		imc = peso / altura * altura
		se(imc < 18.5) {
		    escreva("O IMC é classificado como Magreza")
		} senao se (imc < = 24.9) {
		    escreva("O IMC é classificado como Saúdavel")
		} senao se (imc < = 29.9) {
		    escreva("O IMC é classificado como Sobrepeso")
		} senao se(imc < = 34.9) {
		}   escreva("O IMC é classificado como Obesidade grau I")
		
		}
	}
}
-------------------------------------------------------------------------------
