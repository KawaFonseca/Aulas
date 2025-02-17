# Aulas
Destinado para trabalhos da faculdade.

F = float(input("Digite o valor em Graus Farenheit: "))
C = (5/9)*(F-32)
print(f"O valor de {F}°f corresponde ao valor {C}°c")
     
Digite o valor em Graus Farenheit: 20
O valor de 20.0°f corresponde ao valor -6.666666666666667°c

P = float(input("Digite o valor em Polegadas: "))
mm = P*25-4
print(f"o valor de {P}pol correponde ao valor de {mm}mm")

     
Digite o valor em Polegadas: 2000
o valor de 2000.0pol correponde ao valor de 49996.0mm

I = int(input("Digite sua Idade: "))
if I >= 16:
   print("pode votar")
else:
   print("não pode votar")
     
Digite sua Idade: 17
pode votar

idade = int(input("Digite a sua idade: "))
if 16<= idade < 70:
  print("Você está na faixa etária entre 16 e 70.")
else:
  print("Você está fora da faixa etária entre 16 e 70.")
     
Digite a sua idade: 15
Você está fora da faixa etária entre 16 e 70.

while True:
    resposta = input("Deseja realizar uma soma? (sim/não): ").lower()
    if resposta == "sim":
        num1 = float(input("Digite o primeiro número: "))
        num2 = float(input("Digite o segundo número: " ))
        soma = num1 + num2 # calculo
        print ("A soma é:" , soma)
    else:
        print("Encerrando o programa. ")
        break
     
Deseja realizar uma soma? (sim/não): sim
Digite o primeiro número: 1
Digite o segundo número: 3
A soma é: 4.0
Deseja realizar uma soma? (sim/não): não
Encerrando o programa. 
