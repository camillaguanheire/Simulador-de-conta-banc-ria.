# Simulador de Conta Bancária - Focado em estudos de Engenharia de Software
saldo = 1000.0

print("--- Bem-vindo ao Simulador de Conta Digital ---")

while True:
    print("\n1. Ver Saldo")
    print("2. Depositar Dinheiro")
    print("3. Sacar Dinheiro")
    print("4. Sair")
    
    opcao = input("Escolha uma opção (1-4): ")
    
    if opcao == "1":
        print(f"Seu saldo atual é: R$ {saldo:.2f}")
    elif opcao == "2":
        valor_deposito = float(input("Digite o valor para depósito: R$ "))
        if valor_deposito > 0:
            saldo += valor_deposito
            print(f"Depósito de R$ {valor_deposito:.2f} realizado com sucesso!")
        else:
            print("Valor inválido.")
    elif opcao == "3":
        valor_saque = float(input("Digite o valor para saque: R$ "))
        if 0 < valor_saque <= saldo:
            saldo -= valor_saque
            print(f"Saque de R$ {valor_saque:.2f} realizado com sucesso!")
        else:
            print("Saldo insuficiente ou valor inválido.")
    elif opcao == "4":
        print("Obrigado por usar nosso sistema bancário!")
        break
    else:
        print("Opção inválida. Tente novamente.")
