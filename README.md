# compras
frutas = [ 'maça', 'banana']
comidas = ['arroz', 'feijão']
bebidas = ['suco', 'água']

categorias = ['frutas', 'comidas', 'bebidas']
compras = [frutas, comidas, bebidas]

for índice, categoria in enumerate(categorias):
    print('você precisa comprar', len(compras[índice]), categoria+':')
    for compra in compras[índice]:
        print('-', compra)
