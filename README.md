# Est-gio---Ribeir-o-Preto
print("-" * 30)
print("Sequência de Fibonacci")
print("-" * 30)

n = int(input("Digite um número: "))
t1 = 0
t2 = 1
print("{}->{}".format(t1, t2), end='')
cont = 3
while cont <= n:
    t3 = t1 + t2
    print("->{}".format(t3), end='')
    t1 = t2
    t2 = t3

    cont += 1
if n == t1 or n == t2 or n == t3:
    print('\n'"Esse número FAZ parte da sequência de Fibonacci.")
else:
    print("\n""Esse número NÃO faz parte da sequência de Fibonacci.")

