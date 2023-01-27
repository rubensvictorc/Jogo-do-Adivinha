Aqui estamos usando a classe Random para gerar um número aleatório entre 1 e 100, que o usuário deve adivinhar. Dentro do loop, estamos lendo a entrada do usuário usando a classe Scanner e comparando-a com o número gerado aleatoriamente. Se o usuário acertar o número, o jogo é encerrado e o número de tentativas é exibido. Caso contrário, o usuário é informado se o número é maior ou menor do que a entrada.

Foram adicionadas as seguintes funcionalidades:

Sistema de dificuldade: o usuário pode escolher entre 3 níveis de dificuldade (Fácil, Médio e Difícil), cada um com um número diferente de tentativas. O número de tentativas é definido como 5 para o nível Fácil, 10 para o nível Médio e 20 para o nível Difícil.
Validação de entrada: foi adicionada uma validação para garantir que o usuário entre apenas com um nível de dificuldade válido (1-3). Se o usuário entrar com um nível inválido, o jogo define o nível de dificuldade como Fácil (1) e usa 5 tentativas.
Mensagem de saída: foram adicionadas mensagens de saída para informar ao usuário se ele adivinhou o número correto, quantas tentativas ele usou e, se ele não adivinhar o número, qual era o número correto.
Este código é uma versão mais complexa do jogo de adivinhação de números simples, pois adiciona recursos adicionais para tornar o jogo mais desafiador e interativo.
