# Uma das funções mais procuradas por usuários de aplicativos de saúde é o de controle de calorias ingeridas em um dia.
# Por essa razão, você deve elaborar um algoritmo implementado em Python em que o usuário informe quantos alimentos consumiu 
# naquele dia e depois possa informar o número de calorias de cada um dos alimentos.

print("Controle de calorias ingeridas em um dia. \n")
qtde_alimentos = int(input("Quantos alimentos você consumiu hoje?\n"))
qtde_total_calorias = 0.0
print(f"Agora precisamos saber o número de calorias de cada alimento consumido. Hoje Você consumiu {qtde_alimentos} alimentos.\n")
for alimento in range(1,qtde_alimentos+1):
  qtde_calorias = input(f"Digite o numero de calorias consumidas para o alimento {alimento}.")
  if qtde_calorias == '':
    qtde_calorias = 0.0
  else:
    qtde_total_calorias = qtde_total_calorias + float(qtde_calorias)

print(f"Você consumiu o total de {qtde_total_calorias} calorias no dia.")