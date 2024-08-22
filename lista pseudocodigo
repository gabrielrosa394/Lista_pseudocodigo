# Solicita a letra ao usuário
letra = input("Digite uma letra: ").lower()

# Verifica se a entrada é uma letra válida
if letra.isalpha() and len(letra) == 1:
    # Verifica se a letra é uma vogal
    if letra in 'aeiou':
        print("A letra é uma vogal.")
    else:
        print("A letra é uma consoante.")
else:
    print("Entrada inválida. Por favor, digite apenas uma letra.")

# Solicita ao usuário o salário mensal e o tempo de serviço
salario = float(input("Digite o salário mensal do funcionário: "))
tempo_servico = int(input("Digite o tempo de serviço em anos: "))

# Verifica se o tempo de serviço é maior ou igual a 5 anos
if tempo_servico >= 5:
    # Calcula o bônus de 10% sobre o salário
    bonus = salario * 0.10
    novo_salario = salario + bonus
    print(f"Tempo de serviço: {tempo_servico} anos")
    print(f"Salário original: R${salario:.2f}")
    print(f"Bônus concedido: R${bonus:.2f}")
    print(f"Novo salário: R${novo_salario:.2f}")
else:
    print(f"Tempo de serviço: {tempo_servico} anos")
    print(f"Salário original: R${salario:.2f}")
    print("Nenhum bônus concedido.")

# Solicita ao usuário os três lados do triângulo
lado1 = float(input("Digite o comprimento do primeiro lado: "))
lado2 = float(input("Digite o comprimento do segundo lado: "))
lado3 = float(input("Digite o comprimento do terceiro lado: "))

# Verifica se os lados fornecidos formam um triângulo válido
if (lado1 + lado2 > lado3) and (lado1 + lado3 > lado2) and (lado2 + lado3 > lado1):
    # Verifica o tipo de triângulo
    if lado1 == lado2 == lado3:
        print("O triângulo é Equilátero.")
    elif lado1 == lado2 or lado1 == lado3 or lado2 == lado3:
        print("O triângulo é Isósceles.")
    else:
        print("O triângulo é Escaleno.")
else:
    print("Os valores fornecidos não formam um triângulo válido.")


# Solicita o email e a senha ao usuário
email = input("Digite o email: ")
senha = input("Digite a senha: ")

# Verifica se o email e a senha estão corretos
if email == "admin" and senha == "123":
    print("Usuário logado.")
else:
    if email != "admin":
        print("O email está incorreto.")
    if senha != "123":
        print("A senha está incorreta.")
    if email != "admin" and senha != "123":
        print("O email e a senha estão incorretos.")


# Solicita ao usuário que selecione uma jogada de futebol
jogada = input("Escolha uma jogada (touchdown, conversão, field goal, punt, kickoff): ").lower()

# Define a pontuação para cada jogada
pontuacoes = {
    "touchdown": 6,
    "conversão": 1,
    "field goal": 3,
    "punt": 0,
    "kickoff": 0
}

# Verifica se a jogada selecionada é válida e exibe a pontuação correspondente
if jogada in pontuacoes:
    print(f"A pontuação para {jogada} é {pontuacoes[jogada]} pontos.")
else:
    print("Jogada inválida. Por favor, escolha uma das opções válidas.")


# Solicita ao usuário a quantidade de números e os números em si
n = int(input("Digite o número de elementos (máximo 10): "))

# Verifica se o número de elementos está dentro do limite permitido
if 1 <= n <= 10:
    numeros = []
    
    # Coleta os números do usuário
    for i in range(n):
        numero = int(input(f"Digite o {i+1}º número: "))
        numeros.append(numero)
    
    # Imprime o intervalo na ordem inversa
    print("Ordem inversa:")
    for numero in reversed(numeros):
        print(numero)
    
    # Imprime o intervalo na ordem correta
    print("Ordem correta:")
    for numero in numeros:
        print(numero)
else:
    print("Número de elementos fora do intervalo permitido. Digite um número entre 1 e 10.")


# Inicializa o booleano e o contador
executando = True
contador = 0

# Loop while que executa enquanto o booleano for True
while executando:
    # Imprime o valor atual do booleano
    print(f"Valor do booleano: {executando}")
    
    # Incrementa o contador
    contador += 1
    
    # Verifica se o contador atingiu 15
    if contador >= 15:
        # Define o booleano como False para parar o loop
        executando = False

# Mensagem final após o término do loop
print("O loop foi encerrado.")


# Solicita ao usuário o número inicial e o número final
numero_inicial = int(input("Digite o número inicial: "))
numero_final = int(input("Digite o número final: "))

# Calcula o tamanho do intervalo
tamanho_intervalo = numero_final - numero_inicial + 1

# Verifica se o intervalo está dentro do limite permitido
if 1 <= tamanho_intervalo <= 100:
    print("Intervalo entre os números:")
    for numero in range(numero_inicial, numero_final + 1):
        print(numero, end=' ')
    print()  # Pular linha após a impressão do intervalo
else:
    print("O intervalo é muito grande. Por favor, escolha um intervalo de no máximo 100 números.")


num_inicial = int(input("Digite o número inicial: "))
num_final = int(input("Digite o número final: "))
if abs(num_final - num_inicial) > 100:
    print("O intervalo deve ter no máximo 100 números.")
else:
    print("Intervalo:", list(range(num_inicial, num_final + 1)))

num = int(input("Digite um número: "))
if num > 1:
    for i in range(2, int(num**0.5) + 1):
        if num % i == 0:
            print("Não é um número primo.")
            break
    else:
        print("É um número primo.")
else:
    print("Não é um número primo.")

inicial = int(input("Digite o número inicial: "))
final = int(input("Digite o número final: "))
if abs(final - inicial) > 100:
    print("O intervalo deve ter no máximo 100 números.")
else:
    soma = sum(range(inicial, final + 1))
    print("Soma dos números:", soma)
    for i in range(inicial + 100, inicial + 200):
        print(i, end=' ')
        if (i - inicial + 1) % 10 == 0:
            print()

velocidade1 = 10
velocidade2 = 20
voltas = 0
while velocidade1 <= velocidade2:
    velocidade1 += 3
    velocidade2 += 1.5
    voltas += 1
    print(f"Volta {voltas}: Carro 1 = {velocidade1} km/h, Carro 2 = {velocidade2} km/h")
print("Carro 1 ultrapassou o Carro 2 em", voltas, "voltas.")
