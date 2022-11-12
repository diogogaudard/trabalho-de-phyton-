Questão 1:
B = float(input('Entre com o valor da Base Maior: '))
b = float(input('Entre com o valor da Base Menor: '))
h = float(input('Entre com o valor da altura: '))
a = 2

formula = ((B + b) * h) / a

print('A Área do Trapézio é: ', formula)

Questão 2:
def somaImposto(taxaImposto, Custo):
    return (1 + taxaImposto/100)*Custo
t = float(input('Digite a taxa de imposto: '))
c = float(input('Digite o custo: '))
print('Valor com imposto:', somaImposto(t,c))

Questão 3:
def  converter_hora ( hora ):
	se  hora  >  12  e  hora  !=  24 :
		contador  =  0
		para  x  no  intervalo ( hora ):
			se  x  >=  12 :
				contador += 1
		voltar  contador
	elif  hora  ==  24 :
		retornar  0
	mais :
		volta  hora
controle  =  1
enquanto  controle  !=  0 :
	hora  =  input ( "Digite a hora a ser convertida: " )
	minuto  =  input ( "Digite ou minuto: " )
	print  "Convertido: %i:%i" % ( converter_hora ( hora ), minuto )
	controle  =  input ( "Continuar? 1(sim)/0(nao): " )
print ( "Obrigado até mais" )
