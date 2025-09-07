# Atividade-Perceptron

1. Conceito

O Perceptron é um modelo de rede neural criado por Frank Rosenblatt em 1957 e é considerado o marco inicial da Inteligência Artificial moderna. Ele foi a primeira tentativa de simular o processo de aprendizado do cérebro humano em um computador.
Sua importância histórica está no fato de ter introduzido a ideia de que máquinas poderiam aprender a partir de exemplos e reconhecer padrões nos dados. Esse conceito é a base do que hoje conhecemos como aprendizado de máquina e aprendizado profundo (deep learning).

2. Funcionamento

O Perceptron é considerado um classificador linear, o que significa que ele só consegue separar dados que podem ser divididos por uma linha reta ou, em dimensões maiores, por um hiperplano.
Isso quer dizer que ele consegue resolver problemas simples, mas não consegue lidar com padrões não lineares, como o clássico problema do XOR.
Essa limitação foi um dos fatores que levou ao chamado “inverno da IA”, quando o entusiasmo inicial diminuiu. Somente décadas depois, com redes neurais multicamadas e maior capacidade computacional, foi possível superar essas barreiras.

3. Código

O código mostra o funcionamento de um Perceptron, mas não implementa o processo de treinamento completo (ajuste automático de pesos).
As principais etapas que aparecem no código são:
	•	Entrada: Recebe valores de entrada (inputs), pesos (weights) e um viés (bias).
	•	Cálculo da soma ponderada: Multiplica cada entrada pelo respectivo peso e soma os resultados, adicionando o viés.
	•	Função de ativação: Aplica uma regra simples (se o valor ≥ 0, retorna 1; caso contrário, retorna 0) para definir a saída do Perceptron.

Ou seja, o código exemplifica a lógica de inferência de um Perceptron, mas não a parte de aprendizado via atualização de pesos, que é típica no treinamento real.

4. Aplicação prática

Um Perceptron simples pode ser útil é na detecção de spam em e-mails.
Mesmo sem redes neurais profundas, um Perceptron pode analisar características simples das mensagens, como presença de determinadas palavras-chave, quantidade de links ou tamanho do texto, e classificá-las em spam ou não spam.

Para esse tipo de problema inicial, um classificador linear pode oferecer uma solução rápida, eficiente e de baixo custo computacional, servindo como base para sistemas mais complexos.
