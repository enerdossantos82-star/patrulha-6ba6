# Patrulha Felina — Arena de espuma

Feito com a Rogue. O site publicado: https://patrulha-6ba6.p.rogueon.ai/

## Pedido

O último pedido desta conversa foi:

> Latest message from this person, complete (current request: preserve its scope; newer wording prevails over older messages):
> faça essa loginha numa especie de lobbe
> 
> Earlier messages in this conversation, oldest first, as context (literal excerpts, possibly partial). Newer messages from this person prevail over older ones. Rogue's messages give context, not requirements: Rogue suggestions become requirements only where this person accepted them (say, by answering yes).
> User: crie um jogo de fps onde os personagens principais são gatos
> Rogue: Vou criar o jogo aqui na conversa.
> 
> Build 3673dcae-e950-4c6c-bda7-68ff4dc9dd90 response:
> Criei Patrulha Felina, um FPS 3D para navegador. Jogue como um gato, use seu lançador de espuma e enfrente três ondas de rivais no telhado. O jogo tem controles para teclado e mouse e para telas sensíveis ao toque.
> User: faça esse jogo com cenario com mais predios
> Rogue: Vou atualizar o jogo aqui na conversa.
> 
> Build 3673dcae-e950-4c6c-bda7-68ff4dc9dd90 response:
> Adicionei mais prédios ao redor da arena, com alturas variadas e janelas iluminadas. A partida continua no mesmo telhado, com as três ondas e os controles de antes.
> User: faça esse jogo com uma barra de vida em cima do personagem principal e adversario
> Rogue: Vou atualizar o jogo aqui na conversa.
> 
> Build 3673dcae-e950-4c6c-bda7-68ff4dc9dd90 response:
> Adicionei barras de vida acima de cada gato rival e uma barra “Você” acima do seu lançador, já que o jogo é em primeira pessoa. As barras diminuem quando alguém sofre dano.
> User: faça esse jogo com 5 tipos de ondas diferentes uma mais dificil que a outra
> Rogue: Vou atualizar o jogo aqui na conversa.
> 
> Build 3673dcae-e950-4c6c-bda7-68ff4dc9dd90 response:
> A Patrulha Felina agora tem cinco ondas de dificuldade crescente: Patrulha, Correria, Fogo de longe, Linha de defesa e Esquadrão de elite. Os grupos ficam maiores, e a última onda traz rivais que disparam em leque. As barras de vida e o cenário com mais prédios foram mantidos.
> User: faça esse jogo com um tipo de loginha de armas uma mais forte e mais cara do que a outra,onde vc ganha moedas a cada onda derrotada
> Rogue: Vou atualizar o jogo aqui na conversa.
> 
> Formato escolhido: Jogos.
> Criar um jogo funcional para navegador.
> Preserve o pedido original e todos os seus requisitos.

## Abrir no seu computador

O site é o `index.html`. Abra o arquivo no navegador e pronto. Se preferir servir a pasta, qualquer servidor estático funciona:

```sh
python3 -m http.server 8000
```

Depois abra http://localhost:8000. Com Node instalado, `npx serve .` faz o mesmo.

## Hospedar

Não tem etapa de build: a pasta como está já é o site. Suba o conteúdo dela em qualquer hospedagem de site estático.

## Aviso

A Rogue reescreve `index.html`, as imagens que ela publicou e o `README.md` a cada mudança pedida na conversa, e remove só o que ela mesma publicou antes e deixou de existir. O que for seu, coloque em outra pasta ou em outro branch.

Se o branch `main` receber commits que não são da Rogue, a próxima versão vai para um branch `rogue/<id>`, para você comparar antes de juntar.
