# 1. FrameLayout
Descrição: Um layout simples que empilha os elementos um sobre o outro.

Cenário ideal: Quando você quer mostrar apenas um item por vez (como uma imagem de fundo com um botão por cima).

Características:

Os elementos são posicionados no canto superior esquerdo por padrão.

Útil para sobreposição de elementos.


2. LinearLayout
Descrição: Organiza os elementos em linha vertical ou horizontal.

Cenário ideal: Quando você quer uma lista simples de elementos (como botões empilhados).

Características:

Usa orientation="vertical" ou horizontal.

Pode usar weight para dividir espaço proporcionalmente.

3. RelativeLayout
Descrição: Permite posicionar elementos relativamente uns aos outros.

Cenário ideal: Quando você precisa de um layout mais flexível sem usar ConstraintLayout.

Características:

Pode alinhar elementos à direita, esquerda, abaixo ou acima de outros.

4. ConstraintLayout
Descrição: O layout mais poderoso e recomendado atualmente. Permite posicionar elementos com restrições.

Cenário ideal: Layouts complexos e responsivos.

Características:

Reduz a profundidade da hierarquia.

Permite alinhamentos precisos e responsivos.

5. RecyclerView
Descrição: Um componente para listas eficientes e dinâmicas.

Cenário ideal: Quando você precisa exibir uma lista grande de itens (como contatos, mensagens, produtos).

Características:

Usa um Adapter para popular os dados.

Muito mais eficiente que ListView.
