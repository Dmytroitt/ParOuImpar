from random import randint
from os import system
comp = randint(1,10)
jogada = 0
contadorGanhos = 0
parOuImpar = ''
terminar = False
while terminar == False:
    system('clear') 
    print('=+'*10)
    print('  PAR OU ÍMPAR  ')
    print('=+'*10)
    jogada = int(input('Insira um número de 1 a 10: '))
    parOuImpar = str(input('Par ou ímpar? [P/I]: ')).upper()
    somaNums = jogada + comp
    if parOuImpar == 'P' or parOuImpar == 'I':
        if jogada <= 10 and jogada >= 1:
            if somaNums % 2 == 0 and parOuImpar == 'P':
                print(f'Você ganhou! o computador jogou {comp}, e a soma dos números é {somaNums}')
                contadorGanhos = contadorGanhos + 1
            elif somaNums % 2 != 0 and parOuImpar == 'I':
                print(f'Você ganhou! o computador jogou {comp}, e a soma dos números é {somaNums}')
                contadorGanhos = contadorGanhos + 1
            else:
                print(f'Você perdeu, o computador jogou {comp}, e a soma dos números é {somaNums}')
        else:
            print('Só pode até o número 10!')
    else:
        print('Opção inválida! escolha entre [P/I]!')
    print(f'Você tem {contadorGanhos} rodadas ganhas!')    
    terminarQuestao = str(input('Deseja continuar? [S/N]: ')).upper()
    if terminarQuestao == 'N':
        terminar = True
