# list_comprehensions

[x for x in range(10) if x % 3 == 0] # gera os valores

(x for x in range(10) if x % 3 == 0) #protocolo de acesso

for y in (x for x in range(10) if x % 3 == 0):
  print(y)
