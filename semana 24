# Listas ampliadas para 5 perguntas com tema de ciências (na mesma ordem das respostas)
perguntas = [
    "Qual é o planeta mais próximo do Sol?",
    "Qual gás os seres humanos precisam respirar para sobreviver?",
    "Qual é a fórmula química da água?",
    "Qual órgão é responsável por bombear o sangue no corpo humano?",
    "Em qual estado físico a água fica quando congela (abaixo de 0°C)?",
]

respostas = ["Mercurio", "Oxigenio", "H2O", "Coracao", "Solido"]

# Variável pontos criada antes do loop
pontos = 0

print("=== QUIZ DA FEIRA DE CIÊNCIAS ===")

# Loop for percorrendo as 5 perguntas
for i in range(5):
    resposta_usuario = input(f"\nPergunta {i + 1}: {perguntas[i]} ").strip()

    # Verifica se a resposta está certa (ignorando letras maiúsculas/minúsculas)
    if resposta_usuario.lower() == respostas[i].lower():
        print("Você acertou!")
        pontos += 1
    else:
        print(f"Você errou! A resposta correta era: {respostas[i]}")

# Exibição da pontuação final e mensagem personalizada após o loop
print("\n=== RESULTADO FINAL ===")
print(f"Você acertou {pontos} de 5 perguntas.")

if pontos == 5:
    print("Parabéns! Você gabaritou o quiz de ciências!")
elif pontos >= 3:
    print("Muito bem! Você mandou bem nos conhecimentos científicos.")
elif pontos >= 1:
    print("Bom esforço! Continue estudando para a feira de ciências.")
else:
    print("Não desanime! Revise os conteúdos e tente novamente.")
