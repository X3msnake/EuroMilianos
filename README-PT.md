# EuroMilianos
### Gerador simples de números aleatórios para o Euromilhões

![GPETAS - O Chico esperto de alfama](https://github.com/X3msnake/my-gists-files/blob/main/gpetas-euromillianos.gif)

#### A HISTÓRIA - GPETAS - O Chico-esperto de Alfama

Este código foi criado com a ajuda do GPT-CHAT, um exercício de programação do meu irmão que sabe muito pouco sobre programação.

Inicialmente, ele apenas pediu ao GPT para gerar um gerador de consola, mas como isto foi feito para ser utilizado por uma pessoa idosa, não era ideal.
Depois disso, a meu pedido, ele pediu ao GPT para fazer com uma GUI (Interface Gráfica de Utilizador), a "AI" optou por tkinter (uma escolha sensata uma vez que já vem pré-instalado no Python, sem necessidade de dependências).
O novo código foi executado, mas não produziu qualquer saída ou erros.

Neste relatório, pedi ao meu irmão que me enviasse o código e eu colei de volta o seu código do GPT-CHAT.

Ele leu-o e disse-me para que servia, mas não mencionou quaisquer problemas.
Pedi-lhe para explicar por que o código não funcionava, mas não conseguiu, mas sugeriu imprimir as instruções em cada segmento do código para ver o que estava a ser executado ou não.
Mesmo que eu tenha colado de volta os resultados, ele ainda não conseguiu identificar a falha, mas a essa altura eu já tinha uma ideia de que o código não estava a funcionar porque o Tkinter não estava a ser iniciado de alguma forma, então pesquisei no Google e eis que "AI" se esqueceu de iniciar a janela tkinter -> window.mainloop()

----
![GPETAS - O Chico esperto de alfama](https://github.com/X3msnake/my-gists-files/blob/main/gpt-chat-bs-itself-out-of-situation.png)
----

#### DEPOIS DO CHAT

Agora tínhamos um MVP (Produto Mínimo Viável) funcional, mas a fonte e a janela utilizadas eram demasiado pequenas.
A melhor coisa a fazer era controlar o design com algo preferencialmente com uma solução "O Que Vês É o Que Tens".
Foi aí que o PAGE (Python Automatic GUI Generator) entrou em ação.

![GPETAS - O Chico esperto de alfama](https://github.com/X3msnake/my-gists-files/blob/main/gpt-on-PAGE.png)

A UI foi construída com o PAGE e, em seguida, pedi ao GPT que a adaptasse para funcionar com os ficheiros gerados pelo PAGE. Foi necessário algum esforço extra para direcionar corretamente o script de código PAGE, nomeadamente como direcionar corretamente as etiquetas, foi uma questão de seguir o exemplo que o PAGE gera e adaptá-lo às suas convenções de nomenclatura.


Traduzido automáticamente pelo GPT-CHAT a partir do original em Inglês: [> AQUI <](/README.md)
