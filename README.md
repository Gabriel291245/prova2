# prova2
def media(num1, num2, num3):
    resultado = (num1 + num2 + num3) / 3
    return resultado

n1 = float(input("Digite o primeiro número: "))
n2 = float(input("Digite o segundo número: "))
n3 = float(input("Digite o terceiro número: "))

media_calculada = media(n1, n2, n3)

print(f"A média aritmética é: {media_calculada}")
