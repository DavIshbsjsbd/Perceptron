# Perceptron

1. Conceito:
Percepiton e um primeiro neuronio artficial,que é um classificador linear. Ele tenta encontrar uma linha reta (ou um plano, em mais dimensões) que separe perfeitamente duas classes diferentes. Se os dados forem linearmente separáveis, ele consegue aprender essa separação.
Para a IA o que a descoberta do átomo é para a física moderna ou a primeira célula é para a biologia. Ele era uma unidade fundamental simples, com limitações óbvias, mas que carregava em si o potencial conceitual para toda a complexidade que viria depois. Sua história de otimismo, followed by ceticismo e eventual renascimento, é a própria história do campo da Inteligência Artificial.

2 Funcionamento:
Perceptron só consegue separar classes desenhando uma linha reta (ou um plano/hiperplano). Ele faz uma divisão do espaço de dados com uma única fronteira reta.
As suas limitações são: Não resolve problemas não-lineares: Ele falha completamente com problemas onde os dados não podem ser separados por uma linha reta.
Exemplo clássico: O problema do XOR (ou exclusivo) é o maior exemplo de sua falha. É impossível traçar uma única linha reta para separar as respostas verdadeiras das falsas nesse caso.

3 Código:Primeiro foi começar com pesos e bias aleatórios (ou zero). Depois foi calcular: a saída prevista (y_previsto) usando os pesos atuais. Alem disso foi necessário Comparar: a previsão com a resposta real (y_real). E por fim foi necessário Ajustar os pesos: SOMENTE se houver erro. A regra de atualização é:
Novo Peso = Peso Antigo + Taxa de Aprendizado * (Resposta Real - Resposta Prevista) * Entrada

4 Aplicação prática:
Exemplo: Filtro de Spam.
Justificativa: A separação entre "spam" e "não-spam" muitas vezes é baseada em palavras-chaves lineares (como "oferta", "grátis", "ganhe"). O Perceptron é perfeito para aprender essa fronteira simples e direta com base na presença ou ausência dessas palavras.



