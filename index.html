import random

# Banco de dados simulado organizado por nível de dificuldade
QUESTOES = {
    1: [  # Nível 1 - Fácil (ex: 1.º Ano)
        {"pergunta": "Quanto é 2 + 3?", "resposta": "5"},
        {"pergunta": "Qual é a primeira letra da palavra 'Gato'?", "resposta": "g"},
        {"pergunta": "Quanto é 5 - 1?", "resposta": "4"}
    ],
    2: [  # Nível 2 - Médio (ex: 2.º/3.º Ano)
        {"pergunta": "Quanto é 4 x 3?", "resposta": "12"},
        {"pergunta": "Qual é o oposto de 'Quente'?", "resposta": "frio"},
        {"pergunta": "Quanto é 15 + 15?", "resposta": "30"}
    ],
    3: [  # Nível 3 - Avançado (ex: 4.º Ano)
        {"pergunta": "Quanto é 20 a dividir por 4?", "resposta": "5"},
        {"pergunta": "Qual é o plural de 'Caracol'?", "resposta": "caracois"},
        {"pergunta": "Quanto é 12 x 5?", "resposta": "60"}
    ]
}

def testar_ia_adaptativa():
    nivel = 2  # Começa num nível intermédio
    nivel_min, nivel_max = 1, 3
    acertos_consecutivos = 0
    erros_consecutivos = 0

    print("=== SISTEMA ADAPTATIVO DA IA (TESTE INICIAL) ===")
    print("Digita 'sair' a qualquer momento para terminar.\n")

    while True:
        # Seleciona uma pergunta aleatória do nível atual
        pergunta_atual = random.choice(QUESTOES[nivel])

        print(f"[Nível Atual: {nivel}] {pergunta_atual['pergunta']}")
        resposta = input("Resposta: ").strip().lower()

        if resposta == 'sair':
            print("Teste finalizado.")
            break

        # Lógica de validação e adaptação de dificuldade
        if resposta == pergunta_atual['resposta']:
            print("-> Correto!\n")
            acertos_consecutivos += 1
            erros_consecutivos = 0
            
            # Sobe de nível se acertar 2 seguidas
            if acertos_consecutivos >= 2 e nivel < nivel_max:
                nivel += 1
                acertos_consecutivos = 0
                print(f"*** Parabéns! Subiste para o Nível {nivel} ***\n")
        else:
            print(f"-> Incorreto (Resposta certa: {pergunta_atual['resposta']})\n")
            erros_consecutivos += 1
            acertos_consecutivos = 0

            # Desce de nível se errar
            if nivel > nivel_min:
                nivel -= 1
                erros_consecutivos = 0
                print(f"*** Ajustando dificuldade: Desceste para o Nível {nivel} ***\n")

if __name__ == "__main__":
    testar_ia_adaptativa()
