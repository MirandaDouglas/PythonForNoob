#Declarando as variaveis de preco e quantidade

#preco dos produtos
cocaValor = 3.50
pepsiValor = 3.50
guaranaValor = 3.50
mateleaoValor = 2.50
aguaValor = 2
energeticoValor = 8
acaiValor = 5.20

#quantidade de produtos
cocaEstoque = 6
pepsiEstoque = 9
guaranaEstoque = 7
mateleaoEstoque = 5
aguaEstoque = 10
energeticoEstoque = 7
acaiEstoque = 7

#quantidade de dinheiro
dezPapel = 11
cincoPapel = 15
doisPapel = 22
umReal = 80
cinquentaCentavos = 55
vinteCincoCentavos = 52
dezCentavos = 32
cincoCentavos = 27

#variaveis para uso na hora da compra
dezPapelInseridos = 0
cincoPapelInseridos = 0
doisPapelInseridos = 0
umRealInseridos = 0
cinquentaCentavosInseridos = 0
vinteCincoCentavosInseridos = 0
dezCentavosInseridos = 0
cincoCentavosInseridos = 0

#senha do administrador
senhaADM = str(1)
errofatal = 0

#***********Codigo principal**************

while True:                                         #Repeticao para o usuario fazer varias operacoes
                                                    #Menu principal                             
    print ("\n" * 50) 
    print("/************ MENU *************\ ")
    print("|                               |")
    print("| 1: Comprar Bebida             |")
    print("| 2: Entrar como Administrador  |")
    print("|                               |")
    print("| 0: Encerrar                   |")
    print("|                               |")
    print("\*******************************/\n")
    menu = input("Escolha a operação: ")
                                                    #Escolha do menu
    if menu == "1":
        print("\n" * 50)
        print("  ---------------------------  ")
        print("| Código  -  Produto -  Valor |")
        print("|                             |")
        print("|  11          Coca  -  3.50  |")
        print("|  12          Água  -  2.00  |")
        print("|  13          Açaí  -  5.20  |")
        print("|  21         Pepsi  -  3.50  |")
        print("|  22       Guaraná  -  3.50  |")
        print("|  23     Mate Leão  -  2.50  |")
        print("|  31    Energético  -  8.00  |")
        print("  ---------------------------  \n")
        print("Atenção! Esta máquina só aceita cédulas de 2,5 e 10 reais.\n")
        opcao = input("Entre com o código do produto: ")
        
        if opcao == "11": #coca
            if cocaEstoque >= 1:
                dinheiroInserido = 0
                dezPapelInseridos = 0
                cincoPapelInseridos = 0
                doisPapelInseridos = 0
                umRealInseridos = 0
                cinquentaCentavosInseridos = 0
                vinteCincoCentavosInseridos = 0
                dezCentavosInseridos = 0
                cincoCentavosInseridos = 0
                if dinheiroInserido < cocaValor:
                    while dezPapelInseridos == 0:
                        print("\nFalta inserir R$", cocaValor - dinheiroInserido ,"na máquina.")
                        dezPapelInseridos = int(input("Quantas notas de 10 reais você irá inserir ? "))
                        if dezPapelInseridos < 2:
                            dinheiroInserido += dezPapelInseridos * 10
                            break
                        else:
                            print("Só é aceita 1 cédula de dez reais por vez.")
                    if dinheiroInserido < cocaValor:
                        while cincoPapelInseridos == 0:
                            print("\nFalta inserir R$", cocaValor - dinheiroInserido ,"na máquina.")
                            cincoPapelInseridos = int(input("Quantas notas de 5 reais você irá inserir ? "))
                            if cincoPapelInseridos < 3:
                                dinheiroInserido += cincoPapelInseridos * 5
                                break
                            else:
                                print("Só serão aceitas 2 cédulas de cinco reais por vez.")
                        if dinheiroInserido < cocaValor:
                            while doisPapelInseridos == 0:
                                print("\nFalta inserir R$", cocaValor - dinheiroInserido ,"na máquina.")
                                doisPapelInseridos = int(input("Quantas notas de 2 reais você irá inserir ? "))
                                if doisPapelInseridos < 6:
                                    dinheiroInserido += doisPapelInseridos * 2
                                    break
                                else:
                                    print("Só serão aceitas 5 cédulas de dois reais por vez.")
                            if dinheiroInserido < cocaValor:
                                while umRealInseridos == 0:
                                    print("\nFalta inserir R$", cocaValor - dinheiroInserido ,"na máquina.")
                                    umRealInseridos = int(input("Quantas moedas de 1 real você irá inserir ? "))
                                    if umRealInseridos < 11:
                                        dinheiroInserido += umRealInseridos
                                        break
                                    else:
                                        print("Só serão aceitas 10 moedas de um real por vez.")
                                if dinheiroInserido < cocaValor:
                                    while cinquentaCentavosInseridos == 0:
                                        print("\nFalta inserir R$", cocaValor - dinheiroInserido ,"na máquina.")
                                        cinquentaCentavosInseridos = int(input("Quantas moedas de 50 centavos você irá inserir ? "))
                                        if cinquentaCentavosInseridos < 21:
                                            dinheiroInserido += cinquentaCentavosInseridos * 0.5
                                            break
                                        else:
                                            print("Só serão aceitas 20 moedas de cinquenta centavos por vez.")
                                    if dinheiroInserido < cocaValor:
                                        while vinteCincoCentavosInseridos == 0:
                                            print("\nFalta inserir R$", cocaValor - dinheiroInserido ,"na máquina.")
                                            vinteCincoCentavosInseridos = int(input("Quantas moedas de 25 centavos você irá inserir ? "))
                                            if vinteCincoCentavosInseridos < 41:
                                                dinheiroInserido += vinteCincoCentavosInseridos * 0.25
                                                break
                                            else:
                                                print("Só serão aceitas 40 moedas de vinte e cinco centavos por vez.")
                                        if dinheiroInserido < cocaValor:
                                            while dezCentavosInseridos == 0:
                                                print("\nFalta inserir R$", cocaValor - dinheiroInserido ,"na máquina.")
                                                dezCentavosInseridos = int(input("Quantas moedas de 10 centavos você irá inserir ? "))
                                                if dezCentavosInseridos < 51:
                                                    dinheiroInserido += dezCentavosInseridos * 0.1
                                                    break
                                                else:
                                                    print("Só serão aceitas 50 moedas de dez centavos por vez.")
                                            if dinheiroInserido < cocaValor:
                                                while cincoCentavosInseridos == 0:
                                                    print("\nFalta inserir R$", cocaValor - dinheiroInserido ,"na máquina.")
                                                    cincoCentavosInseridos = int(input("Quantas moedas de 5 centavos você irá inserir ? "))
                                                    if cincoCentavosInseridos < 51:
                                                        dinheiroInserido += cincoCentavosInseridos * 0.05
                                                        break
                                                    else:
                                                        print("Só serão aceitas 50 moedas de cinco centavos por vez.")

                    dezPapel += dezPapelInseridos
                    cincoPapel += cincoPapelInseridos
                    doisPapel += doisPapelInseridos
                    umReal += umRealInseridos
                    cinquentaCentavos += cinquentaCentavosInseridos
                    vinteCincoCentavos += vinteCincoCentavosInseridos
                    dezCentavos += dezCentavosInseridos
                    cincoCentavos += cincoCentavosInseridos

                    if dinheiroInserido > cocaValor:
                        print()
                        troco = dinheiroInserido - cocaValor
                        print("Troco sendo ejetado: R$", troco ,"\n")
                        while troco >= 1:
                            if umReal >= 1:
                                troco -= 1
                                umReal -= 1
                                print("*Cai uma moeda de 1 real da máquina*")
                            else:
                                print("\nAcabou o troco da máquina favor contactar administrador.")
                                input("Desculpe pelo transtorno! Pressione Enter para continuar.\n")
                                errofatal = 1
                                break
                        if errofatal == 1:
                            break
                        while troco >= 0.5:
                            troco -= 0.5
                            cinquentaCentavos -= 1
                            print("*Cai uma moeda de 50 centavos da máquina*")
                        while troco >= 0.25:
                            troco -= 0.25
                            vinteCincoCentavos -= 1
                            print("*Cai uma moeda de 25 centavos da máquina*")
                        while troco >= 0.1:
                            troco -= 0.1
                            dezCentavos -= 1
                            print("*Cai uma moeda de 10 centavos da máquina*")
                        while troco >= 0.05:
                            troco -= 0.05
                            cincoCentavos -= 1
                            print("*Cai uma moeda de 5 centavos da máquina*")
                        cocaEstoque -= 1
                        input("\nPressione Enter para pegar suas moedas e sua bebida.")
                    elif dinheiroInserido < cocaValor:
                        print("\nFaltou dinheiro para finalizar a compra, devolvendo seu dinheiro em moedas...\n")
                        while dinheiroInserido >= 1:
                            dinheiroInserido -= 1
                            umReal -= 1
                            print("*Cai uma moeda de 1 real da máquina*")
                        while dinheiroInserido >= 0.5:
                            dinheiroInserido -= 0.5
                            cinquentaCentavos -= 1
                            print("*Cai uma moeda de 50 centavos da máquina*")
                        while dinheiroInserido >= 0.25:
                            dinheiroInserido -= 0.25
                            vinteCincoCentavos -= 1
                            print("*Cai uma moeda de 25 centavos da máquina*")
                        while dinheiroInserido >= 0.1:
                            dinheiroInserido -= 0.1
                            dezCentavos -= 1
                            print("*Cai uma moeda de 10 centavos da máquina*")
                        while dinheiroInserido >= 0.05:
                            dinheiroInserido -= 0.05
                            cincoCentavos -= 1
                            print("*Cai uma moeda de 5 centavos da máquina*")
                        input("\nPressione Enter para pegar suas moedas.")
                    else:
                        cocaEstoque -= 1
                        print("\nCompra efetuada com sucesso.")
                        input("\nPressione Enter para pegar sua bebida.")
            else:
                input("\nNão temos esta bebida em estoque no momento, desculpe pelo transtorno. Pressione Enter para continuar.")

        elif opcao == "12": #agua
            if aguaEstoque >= 1:
                dinheiroInserido = 0
                dezPapelInseridos = 0
                cincoPapelInseridos = 0
                doisPapelInseridos = 0
                umRealInseridos = 0
                cinquentaCentavosInseridos = 0
                vinteCincoCentavosInseridos = 0
                dezCentavosInseridos = 0
                cincoCentavosInseridos = 0
                if dinheiroInserido < aguaValor:
                    while dezPapelInseridos == 0:
                        print("\nFalta inserir R$", aguaValor - dinheiroInserido ,"na máquina.")
                        dezPapelInseridos = int(input("Quantas notas de 10 reais você irá inserir ? "))
                        if dezPapelInseridos < 2:
                            dinheiroInserido += dezPapelInseridos * 10
                            break
                        else:
                            print("Só é aceita 1 cédula de dez reais por vez.")
                    if dinheiroInserido < aguaValor:
                        while cincoPapelInseridos == 0:
                            print("\nFalta inserir R$", aguaValor - dinheiroInserido ,"na máquina.")
                            cincoPapelInseridos = int(input("Quantas notas de 5 reais você irá inserir ? "))
                            if cincoPapelInseridos < 3:
                                dinheiroInserido += cincoPapelInseridos * 5
                                break
                            else:
                                print("Só serão aceitas 2 cédulas de cinco reais por vez.")
                        if dinheiroInserido < aguaValor:
                            while doisPapelInseridos == 0:
                                print("\nFalta inserir R$", aguaValor - dinheiroInserido ,"na máquina.")
                                doisPapelInseridos = int(input("Quantas notas de 2 reais você irá inserir ? "))
                                if doisPapelInseridos < 6:
                                    dinheiroInserido += doisPapelInseridos * 2
                                    break
                                else:
                                    print("Só serão aceitas 5 cédulas de dois reais por vez.")
                            if dinheiroInserido < aguaValor:
                                while umRealInseridos == 0:
                                    print("\nFalta inserir R$", aguaValor - dinheiroInserido ,"na máquina.")
                                    umRealInseridos = int(input("Quantas moedas de 1 real você irá inserir ? "))
                                    if umRealInseridos < 11:
                                        dinheiroInserido += umRealInseridos
                                        break
                                    else:
                                        print("Só serão aceitas 10 moedas de um real por vez.")
                                if dinheiroInserido < aguaValor:
                                    while cinquentaCentavosInseridos == 0:
                                        print("\nFalta inserir R$", aguaValor - dinheiroInserido ,"na máquina.")
                                        cinquentaCentavosInseridos = int(input("Quantas moedas de 50 centavos você irá inserir ? "))
                                        if cinquentaCentavosInseridos < 21:
                                            dinheiroInserido += cinquentaCentavosInseridos * 0.5
                                            break
                                        else:
                                            print("Só serão aceitas 20 moedas de cinquenta centavos por vez.")
                                    if dinheiroInserido < aguaValor:
                                        while vinteCincoCentavosInseridos == 0:
                                            print("\nFalta inserir R$", aguaValor - dinheiroInserido ,"na máquina.")
                                            vinteCincoCentavosInseridos = int(input("Quantas moedas de 25 centavos você irá inserir ? "))
                                            if vinteCincoCentavosInseridos < 41:
                                                dinheiroInserido += vinteCincoCentavosInseridos * 0.25
                                                break
                                            else:
                                                print("Só serão aceitas 40 moedas de vinte e cinco centavos por vez.")
                                        if dinheiroInserido < aguaValor:
                                            while dezCentavosInseridos == 0:
                                                print("\nFalta inserir R$", aguaValor - dinheiroInserido ,"na máquina.")
                                                dezCentavosInseridos = int(input("Quantas moedas de 10 centavos você irá inserir ? "))
                                                if dezCentavosInseridos < 51:
                                                    dinheiroInserido += dezCentavosInseridos * 0.1
                                                    break
                                                else:
                                                    print("Só serão aceitas 50 moedas de dez centavos por vez.")
                                            if dinheiroInserido < aguaValor:
                                                while cincoCentavosInseridos == 0:
                                                    print("\nFalta inserir R$", aguaValor - dinheiroInserido ,"na máquina.")
                                                    cincoCentavosInseridos = int(input("Quantas moedas de 5 centavos você irá inserir ? "))
                                                    if cincoCentavosInseridos < 51:
                                                        dinheiroInserido += cincoCentavosInseridos * 0.05
                                                        break
                                                    else:
                                                        print("Só serão aceitas 50 moedas de cinco centavos por vez.")
                    dezPapel += dezPapelInseridos
                    cincoPapel += cincoPapelInseridos
                    doisPapel += doisPapelInseridos
                    umReal += umRealInseridos
                    cinquentaCentavos += cinquentaCentavosInseridos
                    vinteCincoCentavos += vinteCincoCentavosInseridos
                    dezCentavos += dezCentavosInseridos
                    cincoCentavos += cincoCentavosInseridos
                    if dinheiroInserido > aguaValor:
                        print()
                        troco = dinheiroInserido - aguaValor
                        print("Troco sendo ejetado: R$", troco ,"\n")
                        while troco >= 1:
                            if umReal >= 1:
                                troco -= 1
                                umReal -= 1
                                print("*Cai uma moeda de 1 real da máquina*")
                            else:
                                print("\nAcabou o troco da máquina favor contactar administrador.")
                                input("Desculpe pelo transtorno! Pressione Enter para continuar.\n")
                                errofatal = 1
                                break
                        if errofatal == 1:
                            break
                        while troco >= 0.5:
                            troco -= 0.5
                            cinquentaCentavos -= 1
                            print("*Cai uma moeda de 50 centavos da máquina*")
                        while troco >= 0.25:
                            troco -= 0.25
                            vinteCincoCentavos -= 1
                            print("*Cai uma moeda de 25 centavos da máquina*")
                        while troco >= 0.1:
                            troco -= 0.1
                            dezCentavos -= 1
                            print("*Cai uma moeda de 10 centavos da máquina*")
                        while troco >= 0.05:
                            troco -= 0.05
                            cincoCentavos -= 1
                            print("*Cai uma moeda de 5 centavos da máquina*")
                        aguaEstoque -= 1
                        input("\nPressione Enter para pegar suas moedas e sua bebida.")
                    elif dinheiroInserido < aguaValor:
                        print("\nFaltou dinheiro para finalizar a compra, devolvendo seu dinheiro em moedas...\n")
                        while dinheiroInserido >= 1:
                            dinheiroInserido -= 1
                            umReal -= 1
                            print("*Cai uma moeda de 1 real da máquina*")
                        while dinheiroInserido >= 0.5:
                            dinheiroInserido -= 0.5
                            cinquentaCentavos -= 1
                            print("*Cai uma moeda de 50 centavos da máquina*")
                        while dinheiroInserido >= 0.25:
                            dinheiroInserido -= 0.25
                            vinteCincoCentavos -= 1
                            print("*Cai uma moeda de 25 centavos da máquina*")
                        while dinheiroInserido >= 0.1:
                            dinheiroInserido -= 0.1
                            dezCentavos -= 1
                            print("*Cai uma moeda de 10 centavos da máquina*")
                        while dinheiroInserido >= 0.05:
                            dinheiroInserido -= 0.05
                            cincoCentavos -= 1
                            print("*Cai uma moeda de 5 centavos da máquina*")
                        input("\nPressione Enter para pegar suas moedas.")
                    else:
                        aguaEstoque -= 1
                        print("\nCompra efetuada com sucesso.")
                        input("\nPressione Enter para pegar sua bebida.")
            else:
                input("\nNão temos esta bebida em estoque no momento, desculpe pelo transtorno. Pressione Enter para continuar.")
        elif opcao == "13": #acai
            if acaiEstoque >= 1:
                dinheiroInserido = 0
                dezPapelInseridos = 0
                cincoPapelInseridos = 0
                doisPapelInseridos = 0
                umRealInseridos = 0
                cinquentaCentavosInseridos = 0
                vinteCincoCentavosInseridos = 0
                dezCentavosInseridos = 0
                cincoCentavosInseridos = 0
                if dinheiroInserido < acaiValor:
                    while dezPapelInseridos == 0:
                        print("\nFalta inserir R$", acaiValor - dinheiroInserido ,"na máquina.")
                        dezPapelInseridos = int(input("Quantas notas de 10 reais você irá inserir ? "))
                        if dezPapelInseridos < 2:
                            dinheiroInserido += dezPapelInseridos * 10
                            break
                        else:
                            print("Só é aceita 1 cédula de dez reais por vez.")
                    if dinheiroInserido < acaiValor:
                        while cincoPapelInseridos == 0:
                            print("\nFalta inserir R$", acaiValor - dinheiroInserido ,"na máquina.")
                            cincoPapelInseridos = int(input("Quantas notas de 5 reais você irá inserir ? "))
                            if cincoPapelInseridos < 3:
                                dinheiroInserido += cincoPapelInseridos * 5
                                break
                            else:
                                print("Só serão aceitas 2 cédulas de cinco reais por vez.")
                        if dinheiroInserido < acaiValor:
                            while doisPapelInseridos == 0:
                                print("\nFalta inserir R$", acaiValor - dinheiroInserido ,"na máquina.")
                                doisPapelInseridos = int(input("Quantas notas de 2 reais você irá inserir ? "))
                                if doisPapelInseridos < 6:
                                    dinheiroInserido += doisPapelInseridos * 2
                                    break
                                else:
                                    print("Só serão aceitas 5 cédulas de dois reais por vez.")
                            if dinheiroInserido < acaiValor:
                                while umRealInseridos == 0:
                                    print("\nFalta inserir R$", acaiValor - dinheiroInserido ,"na máquina.")
                                    umRealInseridos = int(input("Quantas moedas de 1 real você irá inserir ? "))
                                    if umRealInseridos < 11:
                                        dinheiroInserido += umRealInseridos
                                        break
                                    else:
                                        print("Só serão aceitas 10 moedas de um real por vez.")
                                if dinheiroInserido < acaiValor:
                                    while cinquentaCentavosInseridos == 0:
                                        print("\nFalta inserir R$", acaiValor - dinheiroInserido ,"na máquina.")
                                        cinquentaCentavosInseridos = int(input("Quantas moedas de 50 centavos você irá inserir ? "))
                                        if cinquentaCentavosInseridos < 21:
                                            dinheiroInserido += cinquentaCentavosInseridos * 0.5
                                            break
                                        else:
                                            print("Só serão aceitas 20 moedas de cinquenta centavos por vez.")
                                    if dinheiroInserido < acaiValor:
                                        while vinteCincoCentavosInseridos == 0:
                                            print("\nFalta inserir R$", acaiValor - dinheiroInserido ,"na máquina.")
                                            vinteCincoCentavosInseridos = int(input("Quantas moedas de 25 centavos você irá inserir ? "))
                                            if vinteCincoCentavosInseridos < 41:
                                                dinheiroInserido += vinteCincoCentavosInseridos * 0.25
                                                break
                                            else:
                                                print("Só serão aceitas 40 moedas de vinte e cinco centavos por vez.")
                                        if dinheiroInserido < acaiValor:
                                            while dezCentavosInseridos == 0:
                                                print("\nFalta inserir R$", acaiValor - dinheiroInserido ,"na máquina.")
                                                dezCentavosInseridos = int(input("Quantas moedas de 10 centavos você irá inserir ? "))
                                                if dezCentavosInseridos < 51:
                                                    dinheiroInserido += dezCentavosInseridos * 0.1
                                                    break
                                                else:
                                                    print("Só serão aceitas 50 moedas de dez centavos por vez.")
                                            if dinheiroInserido < acaiValor:
                                                while cincoCentavosInseridos == 0:
                                                    print("\nFalta inserir R$", acaiValor - dinheiroInserido ,"na máquina.")
                                                    cincoCentavosInseridos = int(input("Quantas moedas de 5 centavos você irá inserir ? "))
                                                    if cincoCentavosInseridos < 51:
                                                        dinheiroInserido += cincoCentavosInseridos * 0.05
                                                        break
                                                    else:
                                                        print("Só serão aceitas 50 moedas de cinco centavos por vez.")
                    dezPapel += dezPapelInseridos
                    cincoPapel += cincoPapelInseridos
                    doisPapel += doisPapelInseridos
                    umReal += umRealInseridos
                    cinquentaCentavos += cinquentaCentavosInseridos
                    vinteCincoCentavos += vinteCincoCentavosInseridos
                    dezCentavos += dezCentavosInseridos
                    cincoCentavos += cincoCentavosInseridos
                    if dinheiroInserido > acaiValor:
                        print()
                        troco = dinheiroInserido - acaiValor
                        print("Troco sendo ejetado: R$", troco ,"\n")
                        while troco >= 1:
                            if umReal >= 1:
                                troco -= 1
                                umReal -= 1
                                print("*Cai uma moeda de 1 real da máquina*")
                            else:
                                print("\nAcabou o troco da máquina favor contactar administrador.")
                                input("Desculpe pelo transtorno! Pressione Enter para continuar.\n")
                                errofatal = 1
                                break
                        if errofatal == 1:
                            break
                        while troco >= 0.5:
                            troco -= 0.5
                            cinquentaCentavos -= 1
                            print("*Cai uma moeda de 50 centavos da máquina*")
                        while troco >= 0.25:
                            troco -= 0.25
                            vinteCincoCentavos -= 1
                            print("*Cai uma moeda de 25 centavos da máquina*")
                        while troco >= 0.1:
                            troco -= 0.1
                            dezCentavos -= 1
                            print("*Cai uma moeda de 10 centavos da máquina*")
                        while troco >= 0.05:
                            troco -= 0.05
                            cincoCentavos -= 1
                            print("*Cai uma moeda de 5 centavos da máquina*")
                        acaiEstoque -= 1
                        input("\nPressione Enter para pegar suas moedas e sua bebida.")
                    elif dinheiroInserido < acaiValor:
                        print("\nFaltou dinheiro para finalizar a compra, devolvendo seu dinheiro em moedas...\n")
                        while dinheiroInserido >= 1:
                            dinheiroInserido -= 1
                            umReal -= 1
                            print("*Cai uma moeda de 1 real da máquina*")
                        while dinheiroInserido >= 0.5:
                            dinheiroInserido -= 0.5
                            cinquentaCentavos -= 1
                            print("*Cai uma moeda de 50 centavos da máquina*")
                        while dinheiroInserido >= 0.25:
                            dinheiroInserido -= 0.25
                            vinteCincoCentavos -= 1
                            print("*Cai uma moeda de 25 centavos da máquina*")
                        while dinheiroInserido >= 0.1:
                            dinheiroInserido -= 0.1
                            dezCentavos -= 1
                            print("*Cai uma moeda de 10 centavos da máquina*")
                        while dinheiroInserido >= 0.05:
                            dinheiroInserido -= 0.05
                            cincoCentavos -= 1
                            print("*Cai uma moeda de 5 centavos da máquina*")
                        input("\nPressione Enter para pegar suas moedas.")
                    else:
                        acaiEstoque -= 1
                        print("\nCompra efetuada com sucesso.")
                        input("\nPressione Enter para pegar sua bebida.")
            else:
                input("\nNão temos esta bebida em estoque no momento, desculpe pelo transtorno. Pressione Enter para continuar.")
        elif opcao == "21": #pepsi
            if pepsiEstoque >= 1:
                dinheiroInserido = 0
                dezPapelInseridos = 0
                cincoPapelInseridos = 0
                doisPapelInseridos = 0
                umRealInseridos = 0
                cinquentaCentavosInseridos = 0
                vinteCincoCentavosInseridos = 0
                dezCentavosInseridos = 0
                cincoCentavosInseridos = 0
                if dinheiroInserido < pepsiValor:
                    while dezPapelInseridos == 0:
                        print("\nFalta inserir R$", pepsiValor - dinheiroInserido ,"na máquina.")
                        dezPapelInseridos = int(input("Quantas notas de 10 reais você irá inserir ? "))
                        if dezPapelInseridos < 2:
                            dinheiroInserido += dezPapelInseridos * 10
                            break
                        else:
                            print("Só é aceita 1 cédula de dez reais por vez.")
                    if dinheiroInserido < pepsiValor:
                        while cincoPapelInseridos == 0:
                            print("\nFalta inserir R$", pepsiValor - dinheiroInserido ,"na máquina.")
                            cincoPapelInseridos = int(input("Quantas notas de 5 reais você irá inserir ? "))
                            if cincoPapelInseridos < 3:
                                dinheiroInserido += cincoPapelInseridos * 5
                                break
                            else:
                                print("Só serão aceitas 2 cédulas de cinco reais por vez.")
                        if dinheiroInserido < pepsiValor:
                            while doisPapelInseridos == 0:
                                print("\nFalta inserir R$", pepsiValor - dinheiroInserido ,"na máquina.")
                                doisPapelInseridos = int(input("Quantas notas de 2 reais você irá inserir ? "))
                                if doisPapelInseridos < 6:
                                    dinheiroInserido += doisPapelInseridos * 2
                                    break
                                else:
                                    print("Só serão aceitas 5 cédulas de dois reais por vez.")
                            if dinheiroInserido < pepsiValor:
                                while umRealInseridos == 0:
                                    print("\nFalta inserir R$", pepsiValor - dinheiroInserido ,"na máquina.")
                                    umRealInseridos = int(input("Quantas moedas de 1 real você irá inserir ? "))
                                    if umRealInseridos < 11:
                                        dinheiroInserido += umRealInseridos
                                        break
                                    else:
                                        print("Só serão aceitas 10 moedas de um real por vez.")
                                if dinheiroInserido < pepsiValor:
                                    while cinquentaCentavosInseridos == 0:
                                        print("\nFalta inserir R$", pepsiValor - dinheiroInserido ,"na máquina.")
                                        cinquentaCentavosInseridos = int(input("Quantas moedas de 50 centavos você irá inserir ? "))
                                        if cinquentaCentavosInseridos < 21:
                                            dinheiroInserido += cinquentaCentavosInseridos * 0.5
                                            break
                                        else:
                                            print("Só serão aceitas 20 moedas de cinquenta centavos por vez.")
                                    if dinheiroInserido < pepsiValor:
                                        while vinteCincoCentavosInseridos == 0:
                                            print("\nFalta inserir R$", pepsiValor - dinheiroInserido ,"na máquina.")
                                            vinteCincoCentavosInseridos = int(input("Quantas moedas de 25 centavos você irá inserir ? "))
                                            if vinteCincoCentavosInseridos < 41:
                                                dinheiroInserido += vinteCincoCentavosInseridos * 0.25
                                                break
                                            else:
                                                print("Só serão aceitas 40 moedas de vinte e cinco centavos por vez.")
                                        if dinheiroInserido < pepsiValor:
                                            while dezCentavosInseridos == 0:
                                                print("\nFalta inserir R$", pepsiValor - dinheiroInserido ,"na máquina.")
                                                dezCentavosInseridos = int(input("Quantas moedas de 10 centavos você irá inserir ? "))
                                                if dezCentavosInseridos < 51:
                                                    dinheiroInserido += dezCentavosInseridos * 0.1
                                                    break
                                                else:
                                                    print("Só serão aceitas 50 moedas de dez centavos por vez.")
                                            if dinheiroInserido < pepsiValor:
                                                while cincoCentavosInseridos == 0:
                                                    print("\nFalta inserir R$", pepsiValor - dinheiroInserido ,"na máquina.")
                                                    cincoCentavosInseridos = int(input("Quantas moedas de 5 centavos você irá inserir ? "))
                                                    if cincoCentavosInseridos < 51:
                                                        dinheiroInserido += cincoCentavosInseridos * 0.05
                                                        break
                                                    else:
                                                        print("Só serão aceitas 50 moedas de cinco centavos por vez.")
                    dezPapel += dezPapelInseridos
                    cincoPapel += cincoPapelInseridos
                    doisPapel += doisPapelInseridos
                    umReal += umRealInseridos
                    cinquentaCentavos += cinquentaCentavosInseridos
                    vinteCincoCentavos += vinteCincoCentavosInseridos
                    dezCentavos += dezCentavosInseridos
                    cincoCentavos += cincoCentavosInseridos
                    if dinheiroInserido > pepsiValor:
                        print()
                        troco = dinheiroInserido - pepsiValor
                        print("Troco sendo ejetado: R$", troco ,"\n")
                        while troco >= 1:
                            if umReal >= 1:
                                troco -= 1
                                umReal -= 1
                                print("*Cai uma moeda de 1 real da máquina*")
                            else:
                                print("\nAcabou o troco da máquina favor contactar administrador.")
                                input("Desculpe pelo transtorno! Pressione Enter para continuar.\n")
                                errofatal = 1
                                break
                        if errofatal == 1:
                            break
                        while troco >= 0.5:
                            troco -= 0.5
                            cinquentaCentavos -= 1
                            print("*Cai uma moeda de 50 centavos da máquina*")
                        while troco >= 0.25:
                            troco -= 0.25
                            vinteCincoCentavos -= 1
                            print("*Cai uma moeda de 25 centavos da máquina*")
                        while troco >= 0.1:
                            troco -= 0.1
                            dezCentavos -= 1
                            print("*Cai uma moeda de 10 centavos da máquina*")
                        while troco >= 0.05:
                            troco -= 0.05
                            cincoCentavos -= 1
                            print("*Cai uma moeda de 5 centavos da máquina*")
                        pepsiEstoque -= 1
                        input("\nPressione Enter para pegar suas moedas e sua bebida.")
                    elif dinheiroInserido < pepsiValor:
                        print("\nFaltou dinheiro para finalizar a compra, devolvendo seu dinheiro em moedas...\n")
                        while dinheiroInserido >= 1:
                            dinheiroInserido -= 1
                            umReal -= 1
                            print("*Cai uma moeda de 1 real da máquina*")
                        while dinheiroInserido >= 0.5:
                            dinheiroInserido -= 0.5
                            cinquentaCentavos -= 1
                            print("*Cai uma moeda de 50 centavos da máquina*")
                        while dinheiroInserido >= 0.25:
                            dinheiroInserido -= 0.25
                            vinteCincoCentavos -= 1
                            print("*Cai uma moeda de 25 centavos da máquina*")
                        while dinheiroInserido >= 0.1:
                            dinheiroInserido -= 0.1
                            dezCentavos -= 1
                            print("*Cai uma moeda de 10 centavos da máquina*")
                        while dinheiroInserido >= 0.05:
                            dinheiroInserido -= 0.05
                            cincoCentavos -= 1
                            print("*Cai uma moeda de 5 centavos da máquina*")
                        input("\nPressione Enter para pegar suas moedas.")
                    else:
                        pepsiEstoque -= 1
                        print("\nCompra efetuada com sucesso.")
                        input("\nPressione Enter para pegar sua bebida.")
            else:
                input("\nNão temos esta bebida em estoque no momento, desculpe pelo transtorno. Pressione Enter para continuar.")
        elif opcao == "22": #guarana
            if guaranaEstoque >= 1:
                dinheiroInserido = 0
                dezPapelInseridos = 0
                cincoPapelInseridos = 0
                doisPapelInseridos = 0
                umRealInseridos = 0
                cinquentaCentavosInseridos = 0
                vinteCincoCentavosInseridos = 0
                dezCentavosInseridos = 0
                cincoCentavosInseridos = 0
                if dinheiroInserido < guaranaValor:
                    while dezPapelInseridos == 0:
                        print("\nFalta inserir R$", guaranaValor - dinheiroInserido ,"na máquina.")
                        dezPapelInseridos = int(input("Quantas notas de 10 reais você irá inserir ? "))
                        if dezPapelInseridos < 2:
                            dinheiroInserido += dezPapelInseridos * 10
                            break
                        else:
                            print("Só é aceita 1 cédula de dez reais por vez.")
                    if dinheiroInserido < guaranaValor:
                        while cincoPapelInseridos == 0:
                            print("\nFalta inserir R$", guaranaValor - dinheiroInserido ,"na máquina.")
                            cincoPapelInseridos = int(input("Quantas notas de 5 reais você irá inserir ? "))
                            if cincoPapelInseridos < 3:
                                dinheiroInserido += cincoPapelInseridos * 5
                                break
                            else:
                                print("Só serão aceitas 2 cédulas de cinco reais por vez.")
                        if dinheiroInserido < guaranaValor:
                            while doisPapelInseridos == 0:
                                print("\nFalta inserir R$", guaranaValor - dinheiroInserido ,"na máquina.")
                                doisPapelInseridos = int(input("Quantas notas de 2 reais você irá inserir ? "))
                                if doisPapelInseridos < 6:
                                    dinheiroInserido += doisPapelInseridos * 2
                                    break
                                else:
                                    print("Só serão aceitas 5 cédulas de dois reais por vez.")
                            if dinheiroInserido < guaranaValor:
                                while umRealInseridos == 0:
                                    print("\nFalta inserir R$", guaranaValor - dinheiroInserido ,"na máquina.")
                                    umRealInseridos = int(input("Quantas moedas de 1 real você irá inserir ? "))
                                    if umRealInseridos < 11:
                                        dinheiroInserido += umRealInseridos
                                        break
                                    else:
                                        print("Só serão aceitas 10 moedas de um real por vez.")
                                if dinheiroInserido < guaranaValor:
                                    while cinquentaCentavosInseridos == 0:
                                        print("\nFalta inserir R$", guaranaValor - dinheiroInserido ,"na máquina.")
                                        cinquentaCentavosInseridos = int(input("Quantas moedas de 50 centavos você irá inserir ? "))
                                        if cinquentaCentavosInseridos < 21:
                                            dinheiroInserido += cinquentaCentavosInseridos * 0.5
                                            break
                                        else:
                                            print("Só serão aceitas 20 moedas de cinquenta centavos por vez.")
                                    if dinheiroInserido < guaranaValor:
                                        while vinteCincoCentavosInseridos == 0:
                                            print("\nFalta inserir R$", guaranaValor - dinheiroInserido ,"na máquina.")
                                            vinteCincoCentavosInseridos = int(input("Quantas moedas de 25 centavos você irá inserir ? "))
                                            if vinteCincoCentavosInseridos < 41:
                                                dinheiroInserido += vinteCincoCentavosInseridos * 0.25
                                                break
                                            else:
                                                print("Só serão aceitas 40 moedas de vinte e cinco centavos por vez.")
                                        if dinheiroInserido < guaranaValor:
                                            while dezCentavosInseridos == 0:
                                                print("\nFalta inserir R$", guaranaValor - dinheiroInserido ,"na máquina.")
                                                dezCentavosInseridos = int(input("Quantas moedas de 10 centavos você irá inserir ? "))
                                                if dezCentavosInseridos < 51:
                                                    dinheiroInserido += dezCentavosInseridos * 0.1
                                                    break
                                                else:
                                                    print("Só serão aceitas 50 moedas de dez centavos por vez.")
                                            if dinheiroInserido < guaranaValor:
                                                while cincoCentavosInseridos == 0:
                                                    print("\nFalta inserir R$", guaranaValor - dinheiroInserido ,"na máquina.")
                                                    cincoCentavosInseridos = int(input("Quantas moedas de 5 centavos você irá inserir ? "))
                                                    if cincoCentavosInseridos < 51:
                                                        dinheiroInserido += cincoCentavosInseridos * 0.05
                                                        break
                                                    else:
                                                        print("Só serão aceitas 50 moedas de cinco centavos por vez.")
                    dezPapel += dezPapelInseridos
                    cincoPapel += cincoPapelInseridos
                    doisPapel += doisPapelInseridos
                    umReal += umRealInseridos
                    cinquentaCentavos += cinquentaCentavosInseridos
                    vinteCincoCentavos += vinteCincoCentavosInseridos
                    dezCentavos += dezCentavosInseridos
                    cincoCentavos += cincoCentavosInseridos
                    if dinheiroInserido > guaranaValor:
                        print()
                        troco = dinheiroInserido - guaranaValor
                        print("Troco sendo ejetado: R$", troco ,"\n")
                        while troco >= 1:
                            if umReal >= 1:
                                troco -= 1
                                umReal -= 1
                                print("*Cai uma moeda de 1 real da máquina*")
                            else:
                                print("\nAcabou o troco da máquina favor contactar administrador.")
                                input("Desculpe pelo transtorno! Pressione Enter para continuar.\n")
                                errofatal = 1
                                break
                        if errofatal == 1:
                            break
                        while troco >= 0.5:
                            troco -= 0.5
                            cinquentaCentavos -= 1
                            print("*Cai uma moeda de 50 centavos da máquina*")
                        while troco >= 0.25:
                            troco -= 0.25
                            vinteCincoCentavos -= 1
                            print("*Cai uma moeda de 25 centavos da máquina*")
                        while troco >= 0.1:
                            troco -= 0.1
                            dezCentavos -= 1
                            print("*Cai uma moeda de 10 centavos da máquina*")
                        while troco >= 0.05:
                            troco -= 0.05
                            cincoCentavos -= 1
                            print("*Cai uma moeda de 5 centavos da máquina*")
                        guaranaEstoque -= 1
                        input("\nPressione Enter para pegar suas moedas e sua bebida.")
                    elif dinheiroInserido < guaranaValor:
                        print("\nFaltou dinheiro para finalizar a compra, devolvendo seu dinheiro em moedas...\n")
                        while dinheiroInserido >= 1:
                            dinheiroInserido -= 1
                            umReal -= 1
                            print("*Cai uma moeda de 1 real da máquina*")
                        while dinheiroInserido >= 0.5:
                            dinheiroInserido -= 0.5
                            cinquentaCentavos -= 1
                            print("*Cai uma moeda de 50 centavos da máquina*")
                        while dinheiroInserido >= 0.25:
                            dinheiroInserido -= 0.25
                            vinteCincoCentavos -= 1
                            print("*Cai uma moeda de 25 centavos da máquina*")
                        while dinheiroInserido >= 0.1:
                            dinheiroInserido -= 0.1
                            dezCentavos -= 1
                            print("*Cai uma moeda de 10 centavos da máquina*")
                        while dinheiroInserido >= 0.05:
                            dinheiroInserido -= 0.05
                            cincoCentavos -= 1
                            print("*Cai uma moeda de 5 centavos da máquina*")
                        input("\nPressione Enter para pegar suas moedas.")
                    else:
                        guaranaEstoque -= 1
                        print("\nCompra efetuada com sucesso.")
                        input("\nPressione Enter para pegar sua bebida.")
            else:
                input("\nNão temos esta bebida em estoque no momento, desculpe pelo transtorno. Pressione Enter para continuar.")
        elif opcao == "23": #mate leao
            if mateleaoEstoque >= 1:
                dinheiroInserido = 0
                dezPapelInseridos = 0
                cincoPapelInseridos = 0
                doisPapelInseridos = 0
                umRealInseridos = 0
                cinquentaCentavosInseridos = 0
                vinteCincoCentavosInseridos = 0
                dezCentavosInseridos = 0
                cincoCentavosInseridos = 0
                if dinheiroInserido < mateleaoValor:
                    while dezPapelInseridos == 0:
                        print("\nFalta inserir R$", mateleaoValor - dinheiroInserido ,"na máquina.")
                        dezPapelInseridos = int(input("Quantas notas de 10 reais você irá inserir ? "))
                        if dezPapelInseridos < 2:
                            dinheiroInserido += dezPapelInseridos * 10
                            break
                        else:
                            print("Só é aceita 1 cédula de dez reais por vez.")
                    if dinheiroInserido < mateleaoValor:
                        while cincoPapelInseridos == 0:
                            print("\nFalta inserir R$", mateleaoValor - dinheiroInserido ,"na máquina.")
                            cincoPapelInseridos = int(input("Quantas notas de 5 reais você irá inserir ? "))
                            if cincoPapelInseridos < 3:
                                dinheiroInserido += cincoPapelInseridos * 5
                                break
                            else:
                                print("Só serão aceitas 2 cédulas de cinco reais por vez.")
                        if dinheiroInserido < mateleaoValor:
                            while doisPapelInseridos == 0:
                                print("\nFalta inserir R$", mateleaoValor - dinheiroInserido ,"na máquina.")
                                doisPapelInseridos = int(input("Quantas notas de 2 reais você irá inserir ? "))
                                if doisPapelInseridos < 6:
                                    dinheiroInserido += doisPapelInseridos * 2
                                    break
                                else:
                                    print("Só serão aceitas 5 cédulas de dois reais por vez.")
                            if dinheiroInserido < mateleaoValor:
                                while umRealInseridos == 0:
                                    print("\nFalta inserir R$", mateleaoValor - dinheiroInserido ,"na máquina.")
                                    umRealInseridos = int(input("Quantas moedas de 1 real você irá inserir ? "))
                                    if umRealInseridos < 11:
                                        dinheiroInserido += umRealInseridos
                                        break
                                    else:
                                        print("Só serão aceitas 10 moedas de um real por vez.")
                                if dinheiroInserido < mateleaoValor:
                                    while cinquentaCentavosInseridos == 0:
                                        print("\nFalta inserir R$", mateleaoValor - dinheiroInserido ,"na máquina.")
                                        cinquentaCentavosInseridos = int(input("Quantas moedas de 50 centavos você irá inserir ? "))
                                        if cinquentaCentavosInseridos < 21:
                                            dinheiroInserido += cinquentaCentavosInseridos * 0.5
                                            break
                                        else:
                                            print("Só serão aceitas 20 moedas de cinquenta centavos por vez.")
                                    if dinheiroInserido < mateleaoValor:
                                        while vinteCincoCentavosInseridos == 0:
                                            print("\nFalta inserir R$", mateleaoValor - dinheiroInserido ,"na máquina.")
                                            vinteCincoCentavosInseridos = int(input("Quantas moedas de 25 centavos você irá inserir ? "))
                                            if vinteCincoCentavosInseridos < 41:
                                                dinheiroInserido += vinteCincoCentavosInseridos * 0.25
                                                break
                                            else:
                                                print("Só serão aceitas 40 moedas de vinte e cinco centavos por vez.")
                                        if dinheiroInserido < mateleaoValor:
                                            while dezCentavosInseridos == 0:
                                                print("\nFalta inserir R$", mateleaoValor - dinheiroInserido ,"na máquina.")
                                                dezCentavosInseridos = int(input("Quantas moedas de 10 centavos você irá inserir ? "))
                                                if dezCentavosInseridos < 51:
                                                    dinheiroInserido += dezCentavosInseridos * 0.1
                                                    break
                                                else:
                                                    print("Só serão aceitas 50 moedas de dez centavos por vez.")
                                            if dinheiroInserido < mateleaoValor:
                                                while cincoCentavosInseridos == 0:
                                                    print("\nFalta inserir R$", mateleaoValor - dinheiroInserido ,"na máquina.")
                                                    cincoCentavosInseridos = int(input("Quantas moedas de 5 centavos você irá inserir ? "))
                                                    if cincoCentavosInseridos < 51:
                                                        dinheiroInserido += cincoCentavosInseridos * 0.05
                                                        break
                                                    else:
                                                        print("Só serão aceitas 50 moedas de cinco centavos por vez.")
                    dezPapel += dezPapelInseridos
                    cincoPapel += cincoPapelInseridos
                    doisPapel += doisPapelInseridos
                    umReal += umRealInseridos
                    cinquentaCentavos += cinquentaCentavosInseridos
                    vinteCincoCentavos += vinteCincoCentavosInseridos
                    dezCentavos += dezCentavosInseridos
                    cincoCentavos += cincoCentavosInseridos
                    if dinheiroInserido > mateleaoValor:
                        print()
                        troco = dinheiroInserido - mateleaoValor
                        print("Troco sendo ejetado: R$", troco ,"\n")
                        while troco >= 1:
                            if umReal >= 1:
                                troco -= 1
                                umReal -= 1
                                print("*Cai uma moeda de 1 real da máquina*")
                            else:
                                print("\nAcabou o troco da máquina favor contactar administrador.")
                                input("Desculpe pelo transtorno! Pressione Enter para continuar.\n")
                                errofatal = 1
                                break
                        if errofatal == 1:
                            break
                        while troco >= 0.5:
                            troco -= 0.5
                            cinquentaCentavos -= 1
                            print("*Cai uma moeda de 50 centavos da máquina*")
                        while troco >= 0.25:
                            troco -= 0.25
                            vinteCincoCentavos -= 1
                            print("*Cai uma moeda de 25 centavos da máquina*")
                        while troco >= 0.1:
                            troco -= 0.1
                            dezCentavos -= 1
                            print("*Cai uma moeda de 10 centavos da máquina*")
                        while troco >= 0.05:
                            troco -= 0.05
                            cincoCentavos -= 1
                            print("*Cai uma moeda de 5 centavos da máquina*")
                        mateleaoEstoque -= 1
                        input("\nPressione Enter para pegar suas moedas e sua bebida.")
                    elif dinheiroInserido < mateleaoValor:
                        print("\nFaltou dinheiro para finalizar a compra, devolvendo seu dinheiro em moedas...\n")
                        while dinheiroInserido >= 1:
                            dinheiroInserido -= 1
                            umReal -= 1
                            print("*Cai uma moeda de 1 real da máquina*")
                        while dinheiroInserido >= 0.5:
                            dinheiroInserido -= 0.5
                            cinquentaCentavos -= 1
                            print("*Cai uma moeda de 50 centavos da máquina*")
                        while dinheiroInserido >= 0.25:
                            dinheiroInserido -= 0.25
                            vinteCincoCentavos -= 1
                            print("*Cai uma moeda de 25 centavos da máquina*")
                        while dinheiroInserido >= 0.1:
                            dinheiroInserido -= 0.1
                            dezCentavos -= 1
                            print("*Cai uma moeda de 10 centavos da máquina*")
                        while dinheiroInserido >= 0.05:
                            dinheiroInserido -= 0.05
                            cincoCentavos -= 1
                            print("*Cai uma moeda de 5 centavos da máquina*")
                        input("\nPressione Enter para pegar suas moedas.")
                    else:
                        mateleaoEstoque -= 1
                        print("\nCompra efetuada com sucesso.")
                        input("\nPressione Enter para pegar sua bebida.")
            else:
                input("\nNão temos esta bebida em estoque no momento, desculpe pelo transtorno. Pressione Enter para continuar.")
        elif opcao == "31": #energetico
            if energeticoEstoque >= 1:
                dinheiroInserido = 0
                dezPapelInseridos = 0
                cincoPapelInseridos = 0
                doisPapelInseridos = 0
                umRealInseridos = 0
                cinquentaCentavosInseridos = 0
                vinteCincoCentavosInseridos = 0
                dezCentavosInseridos = 0
                cincoCentavosInseridos = 0
                if dinheiroInserido < energeticoValor:
                    while dezPapelInseridos == 0:
                        print("\nFalta inserir R$", energeticoValor - dinheiroInserido ,"na máquina.")
                        dezPapelInseridos = int(input("Quantas notas de 10 reais você irá inserir ? "))
                        if dezPapelInseridos < 2:
                            dinheiroInserido += dezPapelInseridos * 10
                            break
                        else:
                            print("Só é aceita 1 cédula de dez reais por vez.")
                    if dinheiroInserido < energeticoValor:
                        while cincoPapelInseridos == 0:
                            print("\nFalta inserir R$", energeticoValor - dinheiroInserido ,"na máquina.")
                            cincoPapelInseridos = int(input("Quantas notas de 5 reais você irá inserir ? "))
                            if cincoPapelInseridos < 3:
                                dinheiroInserido += cincoPapelInseridos * 5
                                break
                            else:
                                print("Só serão aceitas 2 cédulas de cinco reais por vez.")
                        if dinheiroInserido < energeticoValor:
                            while doisPapelInseridos == 0:
                                print("\nFalta inserir R$", energeticoValor - dinheiroInserido ,"na máquina.")
                                doisPapelInseridos = int(input("Quantas notas de 2 reais você irá inserir ? "))
                                if doisPapelInseridos < 6:
                                    dinheiroInserido += doisPapelInseridos * 2
                                    break
                                else:
                                    print("Só serão aceitas 5 cédulas de dois reais por vez.")
                            if dinheiroInserido < energeticoValor:
                                while umRealInseridos == 0:
                                    print("\nFalta inserir R$", energeticoValor - dinheiroInserido ,"na máquina.")
                                    umRealInseridos = int(input("Quantas moedas de 1 real você irá inserir ? "))
                                    if umRealInseridos < 11:
                                        dinheiroInserido += umRealInseridos
                                        break
                                    else:
                                        print("Só serão aceitas 10 moedas de um real por vez.")
                                if dinheiroInserido < energeticoValor:
                                    while cinquentaCentavosInseridos == 0:
                                        print("\nFalta inserir R$", energeticoValor - dinheiroInserido ,"na máquina.")
                                        cinquentaCentavosInseridos = int(input("Quantas moedas de 50 centavos você irá inserir ? "))
                                        if cinquentaCentavosInseridos < 21:
                                            dinheiroInserido += cinquentaCentavosInseridos * 0.5
                                            break
                                        else:
                                            print("Só serão aceitas 20 moedas de cinquenta centavos por vez.")
                                    if dinheiroInserido < energeticoValor:
                                        while vinteCincoCentavosInseridos == 0:
                                            print("\nFalta inserir R$", energeticoValor - dinheiroInserido ,"na máquina.")
                                            vinteCincoCentavosInseridos = int(input("Quantas moedas de 25 centavos você irá inserir ? "))
                                            if vinteCincoCentavosInseridos < 41:
                                                dinheiroInserido += vinteCincoCentavosInseridos * 0.25
                                                break
                                            else:
                                                print("Só serão aceitas 40 moedas de vinte e cinco centavos por vez.")
                                        if dinheiroInserido < energeticoValor:
                                            while dezCentavosInseridos == 0:
                                                print("\nFalta inserir R$", energeticoValor - dinheiroInserido ,"na máquina.")
                                                dezCentavosInseridos = int(input("Quantas moedas de 10 centavos você irá inserir ? "))
                                                if dezCentavosInseridos < 51:
                                                    dinheiroInserido += dezCentavosInseridos * 0.1
                                                    break
                                                else:
                                                    print("Só serão aceitas 50 moedas de dez centavos por vez.")
                                            if dinheiroInserido < energeticoValor:
                                                while cincoCentavosInseridos == 0:
                                                    print("\nFalta inserir R$", energeticoValor - dinheiroInserido ,"na máquina.")
                                                    cincoCentavosInseridos = int(input("Quantas moedas de 5 centavos você irá inserir ? "))
                                                    if cincoCentavosInseridos < 51:
                                                        dinheiroInserido += cincoCentavosInseridos * 0.05
                                                        break
                                                    else:
                                                        print("Só serão aceitas 50 moedas de cinco centavos por vez.")
                    dezPapel += dezPapelInseridos
                    cincoPapel += cincoPapelInseridos
                    doisPapel += doisPapelInseridos
                    umReal += umRealInseridos
                    cinquentaCentavos += cinquentaCentavosInseridos
                    vinteCincoCentavos += vinteCincoCentavosInseridos
                    dezCentavos += dezCentavosInseridos
                    cincoCentavos += cincoCentavosInseridos
                    if dinheiroInserido > energeticoValor:
                        print()
                        troco = dinheiroInserido - energeticoValor
                        print("Troco sendo ejetado: R$", troco ,"\n")
                        while troco >= 1:
                            if umReal >= 1:
                                troco -= 1
                                umReal -= 1
                                print("*Cai uma moeda de 1 real da máquina*")
                            else:
                                print("\nAcabou o troco da máquina favor contactar administrador.")
                                input("Desculpe pelo transtorno! Pressione Enter para continuar.\n")
                                errofatal = 1
                                break
                        if errofatal == 1:
                            break
                        while troco >= 0.5:
                            troco -= 0.5
                            cinquentaCentavos -= 1
                            print("*Cai uma moeda de 50 centavos da máquina*")
                        while troco >= 0.25:
                            troco -= 0.25
                            vinteCincoCentavos -= 1
                            print("*Cai uma moeda de 25 centavos da máquina*")
                        while troco >= 0.1:
                            troco -= 0.1
                            dezCentavos -= 1
                            print("*Cai uma moeda de 10 centavos da máquina*")
                        while troco >= 0.05:
                            troco -= 0.05
                            cincoCentavos -= 1
                            print("*Cai uma moeda de 5 centavos da máquina*")
                        energeticoEstoque -= 1
                        input("\nPressione Enter para pegar suas moedas e sua bebida.")
                    elif dinheiroInserido < energeticoValor:
                        print("\nFaltou dinheiro para finalizar a compra, devolvendo seu dinheiro em moedas...\n")
                        while dinheiroInserido >= 1:
                            dinheiroInserido -= 1
                            umReal -= 1
                            print("*Cai uma moeda de 1 real da máquina*")
                        while dinheiroInserido >= 0.5:
                            dinheiroInserido -= 0.5
                            cinquentaCentavos -= 1
                            print("*Cai uma moeda de 50 centavos da máquina*")
                        while dinheiroInserido >= 0.25:
                            dinheiroInserido -= 0.25
                            vinteCincoCentavos -= 1
                            print("*Cai uma moeda de 25 centavos da máquina*")
                        while dinheiroInserido >= 0.1:
                            dinheiroInserido -= 0.1
                            dezCentavos -= 1
                            print("*Cai uma moeda de 10 centavos da máquina*")
                        while dinheiroInserido >= 0.05:
                            dinheiroInserido -= 0.05
                            cincoCentavos -= 1
                            print("*Cai uma moeda de 5 centavos da máquina*")
                        input("\nPressione Enter para pegar suas moedas.")
                    else:
                        energeticoEstoque -= 1
                        print("\nCompra efetuada com sucesso.")
                        input("\nPressione Enter para pegar sua bebida.")
            else:
                input("\nNão temos esta bebida em estoque no momento, desculpe pelo transtorno. Pressione Enter para continuar.")
        else:
            input("\nNão existe nenhum produto com este código. Pressione Enter para continuar.")

    elif menu == "2":
        senhaEntrada = input("Entre com a senha do administrador: ")
        if senhaEntrada == senhaADM:
            while True:

                print("\n" * 50)
                print("        _______________________")
                print("        \ 1 = alterar estoque /")
                print("         \  2 = mudar senha  /")
                print("          \   3 = dinheiro  /")
                print("           \    0 = sair   /")
                print("            \ ----------- /")
                print("             \     A     /")
                print("              \    D    /")
                print("               \   M   /")
                print("                \  I  /")
                print("                 \ N /")
                print("                  \_/\n")
                opcao = input("Entre com o código da operação desejada: ")
                if opcao == "1":
                    while True:
                        print("\n" * 50)
                        print("  ----------------------------")
                        print("| Código  -  Produto - Estoque")
                        print("|                             ")
                        print("|  11          Coca  - ", cocaEstoque ,"")
                        print("|  12          Água  - ", aguaEstoque ,"")
                        print("|  13          Açaí  - ", acaiEstoque ,"")
                        print("|  21         Pepsi  - ", pepsiEstoque ,"")
                        print("|  22       Guaraná  - ", guaranaEstoque ,"")
                        print("|  23     Mate Leão  - ", mateleaoEstoque ,"")
                        print("|  31    Energético  - ", energeticoEstoque ,"")
                        print("|                             ")
                        print("|  0 - para sair deste menu   ")
                        print("  ----------------------------\n")
                        if cocaEstoque > 20 or aguaEstoque > 20 or acaiEstoque > 20 or pepsiEstoque > 20 or guaranaEstoque > 20 or mateleaoEstoque > 20 or energeticoEstoque > 20:
                            print("\nUm ou mais dos valores do estoque parecem um pouco altos (maior que 20), talvez esteja incorreto ?\n")

                        opcaoEstoque = input("Entre com o código do produto: ")
                        if opcaoEstoque == "11":
                                cocaEstoque = int(input("\nVocê selecionou Coca-cola, entre com o novo valor de estoque do produto: "))
                        elif opcaoEstoque == "12":
                                aguaEstoque = int(input("\nVocê selecionou Água, entre com o novo valor de estoque do produto: "))
                        elif opcaoEstoque == "13":
                                acaiEstoque = int(input("\nVocê selecionou Açaí, entre com o novo valor de estoque do produto: "))
                        elif opcaoEstoque == "21":
                                pepsiEstoque = int(input("\nVocê selecionou Pepsi, entre com o novo valor de estoque do produto: "))
                        elif opcaoEstoque == "22":
                                guaranaEstoque = int(input("\nVocê selecionou Guaraná, entre com o novo valor de estoque do produto: "))
                        elif opcaoEstoque == "23":
                                mateleaoEstoque = int(input("\nVocê selecionou Mate Leão, entre com o novo valor de estoque do produto: "))
                        elif opcaoEstoque == "31":
                                energeticoEstoque = int(input("\nVocê selecionou Energético, entre com o novo valor de estoque do produto: "))
                        elif opcaoEstoque == "0":
                            break
                        else:
                            input("Código incorreto. Pressione Enter para continuar.")
                elif opcao == "2":
                    senhaADM = input("Entre com a nova senha do administrador: ")
                    input("Senha atualizada. Pressione Enter para continuar.")
                
                elif opcao == "3":
                    print("\n" * 50)
                    print("***************************************************")
                    print("|  Quantidade de cédulas de 10 reais:  ", dezPapel ,"       |")
                    print("|  Quantidade de cédulas de 5 reais:   ", cincoPapel ,"       |")
                    print("|  Quantidade de cédulas de 2 reais:   ", doisPapel ,"       |")
                    print("|  Quantidade de moedas de 1 real:     ", umReal ,"       |")
                    print("|  Quantidade de moedas de 50 centavos:", cinquentaCentavos ,"       |")
                    print("|  Quantidade de moedas de 25 centavos:", vinteCincoCentavos ,"       |")
                    print("|  Quantidade de moedas de 10 centavos:", dezCentavos ,"       |")
                    print("|  Quantidade de moedas de 5 centavos: ", cincoCentavos ,"       |")
                    print("|                                                 |")
                    print("|  Valor total de dinheiro na máquina:  R$", dezPapel*10+cincoPapel*5+doisPapel*2+umReal+cinquentaCentavos*0.5+vinteCincoCentavos*0.25+dezCentavos*0.1+cincoCentavos*0.05 ,"|")
                    print("***************************************************\n")
                    input("Pressione Enter para voltar para o menu.")

                elif opcao == "0":
                    break

                else:
                    input("Opção inválida. Pressione Enter para continuar.")
        else:
            input("Senha inválida. Pressione Enter para continuar.")

    elif menu == "0":
        break

    else:
        input("Opção incorreta. Pressione Enter para continuar.")
print("Obrigado por escolher a nossa máquina! A NewDrink lhe deseja um ótimo dia!")
