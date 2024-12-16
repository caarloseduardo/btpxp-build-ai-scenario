# Exercício 4 - Prompt Editor

Neste exercício, você usará o Prompt Editor com as configurações que acabamos de criar.

👉 Selecione a aba de **_"Generative AI Hub"_**, e a opção **_"Prompt Editor"_**.

![Select Prompt Editor](assets/select-prompt.png)

👉 Clique em **_"Selected Model"_**, para selecionarmos o modelo que criamos no exercício anterior.

![Select Model](assets/select-model.png)

👉 Selecione o modelo criado no exercício anterior. Você pode confirmar pelo **_"Deployment ID"_**.

![Select Model](assets/select-model-2.png)

👉 Agora, você pode testar seu modelo escrevendo algo na sessão **_"Message"_**, e clicando em **_"Run"_**

![Run Model](assets/run-model.png)

👉 Teste também alterar os parâmetros disponíveis, e ver a diferença nas respostas. 

![Change Parameters](assets/parameters.png)

Os parâmetros são os seguintes:

  | Nome | Valor |
  |:-----------|:-----------|
  | Frequency Penalty | Reduz a probabilidade de repetição de tokens já usados com frequência. |
  | Presence Penalty | Diminui a probabilidade de repetição de ideias já mencionadas. |
  | Max Tokens | Define o limite máximo de tokens na resposta. |
  | Temperature | Ajusta o grau de aleatoriedade na escolha dos próximos tokens. |

Agora, como próximos passos, você pode criar uma aplicação back-end em Node.js usando o SAP CAP (Cloud Application Programming Model). Continue para o [Desafio Pro-code](../challenge/README.md), para fazer uma implementação prática de sua instância AI Core.