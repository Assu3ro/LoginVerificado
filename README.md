# LoginVerificado
senha1 = 'abc'
senha2 = input("Digite sua senha: ")
cont=1

if (senha2 != 'abc'):

    while cont<=3:

        senha2 = input("Tente novamente: ")
        cont=cont+1

        if senha2 == senha1:
            print("Bem vindo!")
            break
        if cont >3 :
            print("Acesso Neg")
else:
    print("\nBem vindos!")
