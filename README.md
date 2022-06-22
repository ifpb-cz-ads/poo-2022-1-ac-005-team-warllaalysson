# BM01

Lampada

Dados:
ligada: boolean
potencia: double

Operações:
ligar: void
desligar: void
estaLigada: boolean

# BM02

TimeDeEsporte

Dados:
nome: string
numeroJogadores: int
jogadores: string[]
treinador: string

Operações:
mudarNome(string): void
substituirTreinador(string): void
adicionarJogadorNaPosicao(String, int): void

# BM03

Classe ContaBancariaSimples

# BM04

Classe Lampada

# BM05

Classe TimeDeEsporte

# BM06

Classe ContaBancariaSimples

# BM07

Nome da classe não deve possuir espaços. Deveria ser:

class RegistroDeEleitor

# BM08

O método maior apesar de não dar erro de compilação, deveria retornar boolean ao invés de item, já que seus retornos são apenas true or false. Correção:

boolean maior()
{
if (num1 > num2)
return true;
else return false;
}

O método menor dará erro de compilação, pois está assinado para não possuir retorno e está retornando int. Correção:

int menor()
{
if (num1 < num2)
return num1;
else return num2;
}

# BM09

Assinatura método main está errada. Correção:

public static void main(String[] args)

E o método main não deve possuir retorno, afinal possui assinatura void.
