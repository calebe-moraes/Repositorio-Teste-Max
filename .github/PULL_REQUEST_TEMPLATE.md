# [Pull Request] Adiciona função de saudação ao projeto

# [Descrição]
Este Pull Request adiciona uma função simples de saudação.
Objetivo: demonstrar criação de branch e abertura de PR.

# [Branch]
feature/add-saudacao

# [Alterações]
- Criação da função saudacao(nome)
- Atualização do arquivo main.py
- Teste manual realizado

# [Código Adicionado]

def saudacao(nome):
    return f"Olá, {nome}! Bem-vindo ao projeto."

if __name__ == "__main__":
    nome = input("Digite seu nome: ")
    print(saudacao(nome))

# [Como Testar]
1. git checkout feature/add-saudacao
2. python main.py
3. Digitar um nome quando solicitado

# [Objetivo da Aula]
- Entender o fluxo de Pull Request
- Praticar organização de mudanças
- Simular processo de revisão

