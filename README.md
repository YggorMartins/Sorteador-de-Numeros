<img width="1709" height="855" alt="image" src="https://github.com/user-attachments/assets/1363a106-3831-4237-bb73-b08809e414ad" />

🎰 Sorteador de Números — HTML, CSS e JavaScript

Um projeto simples e visualmente atrativo que sorteia números em sequência, exibindo cada resultado com uma animação tipo “flip card”.
Totalmente responsivo e com lógica otimizada para evitar repetição de números quando o usuário desejar.

📌 Funcionalidades

Sorteio de números com ou sem repetição

Animação individual para cada item sorteado

Exibição de apenas um item por vez durante a animação

Botão de reiniciar que só aparece após o fim da lista

Layout responsivo para desktop e mobile

Algoritmo Fisher-Yates para embaralhamento real e seguro

🧠 Técnica de Embaralhamento — Fisher-Yates

Para evitar repetições e garantir aleatoriedade verdadeira, o projeto utiliza o algoritmo Fisher-Yates Shuffle, que é amplamente usado em jogos, estatística e sorteios digitais.

Como funciona:

Começa do último índice do array.

Em cada passo, escolhe um índice aleatório que ainda não foi usado.

Troca os dois elementos.

Repete até chegar ao início do array.

Isso garante que todas as possíveis ordens têm exatamente a mesma probabilidade, diferente de métodos comuns como sort(() => Math.random() - 0.5).

Vantagens:

Não repete valores

Extremamente rápido

Aleatoriedade justa e comprovada

Ideal para sorteios e randomizações reais

🧩 Estrutura do Projeto
/index.html     → Estrutura base  
/style.css      → Estilos e animações  
/scripts.js     → Toda a lógica do sorteio, animações e controle de fluxo

🎨 Animações incluídas

Animação do “quadrado” girando

Transição suave entre números

Delay controlado para exibir itens um por vez

Ocultação automática do botão de reiniciar

📱 Responsividade

O layout se adapta completamente ao mobile.
Foram feitos ajustes para que:

O botão de reiniciar apareça centralizado

A animação não quebre o fluxo vertical

Os números mantenham legibilidade em telas pequenas

🔄 Reinício inteligente

O botão “Again” só aparece após todos os números serem exibidos, garantindo que o usuário veja o sorteio até o final antes de reiniciar.

📥 Como usar

Basta abrir o index.html no navegador e configurar:

Número inicial

Número final

Permitir repetição (ou não)

Pressionar Sortear

🚀 Tecnologias utilizadas

HTML5

CSS3 (Flexbox, animações e transições)

JavaScript puro

Algoritmo Fisher-Yates Shuffle
