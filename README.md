palavras_modernas = ["GearHead", "Lasanha", "Labubu", "Cringe", "Stalkear"]

significados = {"GearHead": "Uma pessoa que gosta ou entende muito de carros.", 
                "Lasanha": "um carro que alguém comprou e que ela nunca vai mexer.", 
                "Labubu": "um bicho de pelúcia demônio.", 
                "Cringe": "Algo vergonhoso ou constrangedor.", 
                "Stalkear": "Investigar a vida de alguém online."}

pergunta = input("Digite uma palavra moderna que você não entende: ")

if pergunta in palavras_modernas:
    print("significado:", significados[pergunta])

else:
    print("Palavra não encontrada.")
