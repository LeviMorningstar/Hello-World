import os
import munip as mp

print('-=-' *20)
print('              Este programa Cria Etiquetas.')
print('-=-' *20)

x = ('sim')
y = ('sim')
s = ('sim','s')

valid_destino = False
valid_vara1 = False
lista_tipo = [1,2,3]
lista_vara = ['1','2','3','4','5','6','c']

while x in s:
    while valid_destino == False:
        tipo = input('Digite (1) para Vara Judicial (2) para Vara Cível ou (3) para Juizado Especial Cível: ')
        try:
            tipo = int(tipo)
            if tipo not in lista_tipo:
                print()
                print('Erro, Por favor use somente uma das opções informadas.')
                print()
            else:
                valid_destino = True
        except:
            print()
            print('Erro, Por favor use somente uma das opções informadas.')
            print()

    if tipo == (1):
        parte1 = "Vara Judicial da Comarca de"
        while valid_vara1 == False:
            vara = input("Especifique o numero da Vara ou digite 'c' caso nao necessite de uma vara especifica.")
            try:
                vara = str(vara)
                if vara not in lista_vara:
                    print('Erro na entrada de dados.')
                else:
                    valid_vara1 = True
            except:
                print('Erro na entrada de dados.')
        municipio = str(input('Digite a Comarca: ')).lower()
        enderecamento = mp.enderecos.get(municipio, 'Este município não costa no Banco de dados.')
        cepf = mp.cep.get(municipio, 'Este município não costa no Banco de dados')
        comarcaf = mp.comarca.get(municipio,'Este município não costa no Banco de dados')
        if vara == ('c'):
            primeiralinha = ('Aos Cuidados da {} {} - RS'.format(parte1, comarcaf))
        else:
            primeiralinha = ('Aos Cuidados da {}º {} {} - RS'.format(vara, parte1, comarcaf))

    elif tipo == (2):
        parte1 = "Vara Cível da Comarca de"
        vara = input("Especifique o numero da Vara ou digite 'c' caso nao necessite de uma vara especifica.")
        try:
            vara = str(vara)
            if vara not in lista_vara:
                print('Erro na entrada de dados.')
            else:
                valid_vara1 = True
        except:
            print('Erro na entrada de dados.')
        municipio = str(input('Digite a Comarca: ')).lower()
        enderecamento = mp.enderecos.get(municipio, 'Este município não costa no Banco de dados.')
        cepf = mp.cep.get(municipio, 'Este município não costa no Banco de dados')
        comarcaf = mp.comarca.get(municipio,'Este município não costa no Banco de dados')
        if vara == ('c'):
            primeiralinha = ('Aos Cuidados da {} {} - RS'.format(parte1, comarcaf))
        else:
            primeiralinha = ('Aos Cuidados da {}º {} {} - RS'.format(vara, parte1, comarcaf))
    elif tipo == (3):
        parte1 = "Juizado especial Cível da comarca de"
        municipio = str(input('Digite a Comarca: ')).lower()
        enderecamento = mp.enderecos.get(municipio, 'Este município não costa no Banco de dados.')
        cepf = mp.cep.get(municipio, 'Este município não costa no Banco de dados')
        comarcaf = mp.comarca.get(municipio, 'Este município não costa no Banco de dados')
        primeiralinha = ('Ao {} {} - RS'.format(parte1, comarcaf))
    else:
        print('Erro, entre em contato com o Administrador.')

    print()
    print('-=-' * 30)
    print()
    print(primeiralinha)
    print('Endereço:',enderecamento)
    print('CEP:',cepf)
    print()
    print('-=-' * 30)
    print()

    y = input('Está correto?')
    print()

    if y in s:
        def escreverarquivo():
            arquivo = open('Final.rtf','a')
            arquivo.write('\n')
            arquivo.write('\n')
            arquivo.write('\n')
            arquivo.write(primeiralinha)
            arquivo.write('\nEndereço: ')
            arquivo.write(enderecamento)
            arquivo.write('\nCEP:')
            arquivo.write(cepf)
            arquivo.write('\n')
            arquivo.write('\n')
            arquivo.write('\n')
            arquivo.close()

        escreverarquivo()
    x = input('Deseja continuar? ').lower()

    valid_vara1 = False
    valid_destino = False

def abrirArquivo():
    os.startfile('Final.rtf')

abrirArquivo()
