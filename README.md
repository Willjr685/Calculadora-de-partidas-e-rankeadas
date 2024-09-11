# Calculadora-de-partidas-e-rankeadas
def ranking():
    vitorias = 180 
    derrotas = 80
    reultado = vitorias - derrotas
    print("Classificação:", reultado)
ranking()


nivel = 100
vitorias = 180


if nivel >=100:
    print("Ranking Lendário")

print("O herói tem um saldo de {vitorias} vitórias e está no nivel: {nivel}".format(vitorias=vitorias , nivel=nivel))
