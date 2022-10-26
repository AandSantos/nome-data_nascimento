# nome-data_nascimento
desenvolver um programa com o nome e a data de nascimento do usuário

nome = str(input("digite seu nome completo: "))
data_nascimento = int(input("digite o ano em que você nasceu: "))
if (data_nascimento<1922 or data_nascimento>2021):
    print("erro")
elif(data_nascimento>=1922 and data_nascimento<=2021):
    data_nascimento = (2022 - data_nascimento)
    print(f"{nome}) tem ou completará {data_nascimento} anos.")
