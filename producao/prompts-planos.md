# Prompts dos 144 planos — prontos para disparar

Traço Humano · "Como sobreviver na floresta sem piorar tudo" · 8 min · 16:9 · 24 fps · **sem áudio**

Complemento de `producao/decupagem-floresta.md`. Uma entrada por clipe: prompt da
imagem-base + instrução de animação. Disparar **bloco a bloco**, só depois que as
7 referências (`producao/prompts-referencias.md`) estiverem aprovadas.

**Como usar os tokens:** cada prompt abaixo começa com `[ESTILO]` e usa os tokens
de personagem. Substituir pelo texto integral da tabela antes de disparar — os
tokens existem para o prompt não repetir 12 linhas de estilo 144 vezes.

---

## Tokens

`[ESTILO]` — bloco de estilo, idêntico ao de `prompts-referencias.md`:

```
2D hand-drawn cartoon illustration, stick-figure character style.
White rounded head with thin black outline, simple dot eyes and a small
simple mouth. Torso and limbs are plain thin black lines. Small simple
hands and feet, no realistic fingers. Flat muted colors, soft cream-beige
background, subtle paper texture, soft shadows.
NOT 3D, NOT photorealistic, NOT anime, NOT chibi, NOT volumetric human
anatomy. Exactly two arms and two legs.
```

| Token | Substituir por | Ref |
| --- | --- | --- |
| `[LÉO]` | a stick-figure boy with a RED baseball cap worn FORWARD and a MOSS-GREEN backpack | R-01 |
| `[LÉO+C]` | `[LÉO]`, wearing a flat TEAL-BLUE winter coat, zipped closed (flat and simple, NOT bulky) | R-04 |
| `[NINA]` | a stick-figure girl in a MUSTARD top with a YELLOW backpack | R-02 |
| `[MARA]` | a stick-figure park ranger in an OLIVE-GREEN hat and jacket, GREY backpack, holding a flashlight | R-03 |
| `[URSO]` | an adult DARK BROWN bear, real bear anatomy, on four legs, NOT anthropomorphic | R-05 |
| `[CLAREIRA]` | the forest clearing with a curved-root pine at back-left and a low flat rock at right | R-07 |
| `[PONTO-B]` | the forest spot with a flat rock at left and two parallel pines in the background | R-08 |
| `[CAMPING]` | the authorized campsite: picnic table, green tent, metal fire ring, water bucket | R-06 |
| `[ABRIGO]` | the lopsided ORANGE emergency shelter, pitched low and improvised | R-09 |

## Estado de continuidade por bloco

| Bloco | Luz / paleta | Figurino do Léo | Local |
| --- | --- | --- | --- |
| 1 (simulação) | tarde, quente | `[LÉO]` sem casaco | mata densa |
| 1 (trilha) | sol alto → luz baixa | `[LÉO]` | trilha marcada |
| 2 | tarde aberta | `[LÉO]` | trilha → mata |
| 3 | tarde caindo, vento | `[LÉO]` | mata |
| 4 | céu fechando, chuva fina | `[LÉO]` | mata → `[CLAREIRA]` |
| 5 | flashback noturno / mata anoitecendo | `[LÉO]` → `[LÉO+C]` a partir de 5.16 | `[CAMPING]` → `[CLAREIRA]` |
| 6 | noite chegando, azulada | `[LÉO+C]` | riacho / `[CLAREIRA]` |
| 7 | crepúsculo, paleta fria | `[LÉO+C]` | `[CLAREIRA]` → `[PONTO-B]` |
| 8 | noite fechada, luz de lanterna | `[LÉO+C]` | `[PONTO-B]` |
| 9 | manhã clara | `[LÉO+C]` → sem casaco em 9.10–9.12 | `[CAMPING]` |

> ⚠️ **A partir de 5.16 o casaco azul-petróleo não sai mais**, até o chuveiro (9.10).
> ⚠️ **A mochila verde-musgo aparece em quase todos os planos.** Conferir plano a plano.
> ⚠️ Selos `SIMULAÇÃO: ESCOLHA ERRADA` e `NÃO CORRA DE UM URSO` são **edição**, não geração.
> Deixar margem superior limpa em 1.01–1.08 para a cartela entrar.

---

## Bloco 1 — Simulação da perseguição

**1.01 · 4s · PG**
```
[ESTILO] Wide shot of a dense forest, tall pines, warm late-afternoon light.
[LÉO] runs into frame from the right edge in full panic, arms flailing.
Leaves scattered on the ground. Clean empty sky area at the top of the frame.
```
*Animação:* corrida contínua da direita para a esquerda, câmera fixa.

**1.02 · 3s · PM lateral**
```
[ESTILO] Medium side-profile shot of [LÉO] running, seen from his left.
Thin stick arms and legs flailing out of control. Blurred pine trunks behind him.
```
*Animação:* tracking lateral acompanhando a corrida, fundo deslizando.

**1.03 · 3s · PG**
```
[ESTILO] Wide shot from behind [LÉO] in the foreground, small in frame.
[URSO] running in the mid-background between the trees, clearly closing the distance.
Late-afternoon forest light.
```
*Animação:* urso se aproxima em profundidade, Léo constante em primeiro plano.

**1.04 · 2s · CL**
```
[ESTILO] Close-up on the face of [LÉO], eyes wide open in panic, mouth small and tense.
Red cap slightly tilted. Blurred forest behind.
```
*Animação:* micro-tremor da cabeça, sem deslocamento.

**1.05 · 2s · DET**
```
[ESTILO] Detail shot of the thin stick legs of a running character hitting the forest
floor, dry leaves flying up around the feet. Low camera, close to the ground.
```
*Animação:* passada rápida em loop, folhas subindo.

**1.06 · 3s · PM**
```
[ESTILO] Medium shot of [LÉO] FROZEN mid-stride, one foot off the ground, body
tilted forward mid-run. Everything around him is still. Dense forest.
Clean empty area in the upper third of the frame.
```
*Animação:* **nenhuma.** Frame estático — o congelamento é o ponto.

**1.07 · 3s · —**
```
[ESTILO] Same frozen composition as 1.06, held. Large clean empty space across the
upper half of the frame for a title card to be added in editing.
```
*Animação:* nenhuma. Cartela `NÃO CORRA DE UM URSO` entra na montagem.

**1.08 · 3s · CL**
```
[ESTILO] Close-up of [LÉO] standing still, out of breath, small embarrassed smile,
looking straight at the camera. Forest background, no bear.
```
*Animação:* respiração ofegante, ombros subindo e descendo.

**1.09 · 4s · PG**
```
[ESTILO] Wide shot of a marked sunlit hiking trail, hours earlier. Bright warm
midday light, open canopy. [LÉO] walks calmly along the trail, relaxed posture.
```
*Animação:* caminhada tranquila, câmera fixa.

**1.10 · 3s · PM**
```
[ESTILO] Medium shot of [LÉO] adjusting the strap of his moss-green backpack with
one hand, confident posture. Sunlit trail behind him.
```
*Animação:* gesto único de ajustar a alça.

**1.11 · 3s · DET**
```
[ESTILO] Detail shot looking down into the open moss-green backpack: a wrapped
sandwich clearly visible inside, readable and centered.
```
*Animação:* leve balanço da mochila, sem corte.

**1.12 · 4s · PG**
```
[ESTILO] Wide shot of the same trail, now in low golden light, long shadows.
[LÉO] stopped in the middle of the path, head tilted up, noticing it got dark.
```
*Animação:* luz esmaecendo devagar ao longo do clipe.

**1.13 · 3s · DET**
```
[ESTILO] Detail shot of a small silver WHISTLE clipped to the side of the
moss-green backpack, sharply lit and highlighted. Rest of the frame soft.
```
*Animação:* apito balançando levemente; ninguém o toca.

---

## Bloco 2 — A trilha com Nina

**2.01 · 4s · PG**
```
[ESTILO] Wide establishing shot of a park entrance with a wooden trailhead sign.
[LÉO] and [NINA] walking side by side toward the trail. Bright afternoon light.
```
*Animação:* os dois entram em quadro caminhando.

**2.02 · 4s · PM**
```
[ESTILO] Medium two-shot. [NINA] holds up a paper map and points at it.
[LÉO] looks sideways, visibly uninterested. Trailhead behind them.
```
*Animação:* Nina aponta; Léo desvia o olhar.

**2.03 · 3s · DET**
```
[ESTILO] Detail shot of a simple hand-drawn route map held in two small stick hands,
a dotted trail line and a marked destination clearly readable.
```
*Animação:* mapa ligeiramente inclinado, papel tremendo.

**2.04 · 3s · PM**
```
[ESTILO] Medium shot of [NINA] handing a folded plan to a third person — only that
person's hand and forearm enter the frame from the right. Park entrance setting.
```
*Animação:* entrega do papel, mão sai de quadro.

**2.05 · 4s · PM**
```
[ESTILO] Medium two-shot. [NINA] holds up a water bottle, a folded coat and a
flashlight, showing them one by one. [LÉO] shrugs with both arms.
```
*Animação:* Nina apresenta os itens; Léo dá de ombros no fim.

**2.06 · 3s · CL**
```
[ESTILO] Close-up of [LÉO] with a dismissive "it's just a walk" expression,
eyebrows relaxed, small confident smile.
```
*Animação:* leve movimento de cabeça de desdém.

**2.07 · 4s · PG**
```
[ESTILO] Wide shot of [LÉO] and [NINA] walking together along a clearly marked
forest trail, trail markers on the tree trunks. Dappled afternoon light.
```
*Animação:* caminhada lateral, fundo deslizando.

**2.08 · 3s · PM**
```
[ESTILO] Medium shot of [LÉO] on the trail. A small bird crosses the frame in front
of him. He turns his head to follow it.
```
*Animação:* pássaro cruza; cabeça do Léo acompanha.

**2.09 · 4s · PA**
```
[ESTILO] American shot of [LÉO] stepping OFF the marked trail into the undergrowth,
camera raised in both hands, photographing up into the trees.
```
*Animação:* passo para fora do caminho, câmera sobe.

**2.10 · 3s · PG**
```
[ESTILO] Wide shot down the trail. [NINA] keeps walking ahead, already small in the
distance, and disappears around a bend. Empty trail in the foreground.
```
*Animação:* Nina diminui em profundidade e sai de quadro.

**2.11 · 3s · PM**
```
[ESTILO] Medium shot of [LÉO] lowering his camera, alone among the trees.
No trail visible anywhere in frame. Still, quiet composition.
```
*Animação:* câmera desce; parada longa, sem movimento.

**2.12 · 3s · PM**
```
[ESTILO] Medium shot of [LÉO] looking at a pine tree and pointing at it with
confidence, as if he recognizes it.
```
*Animação:* braço sobe apontando.

**2.13 · 3s · PM**
```
[ESTILO] Medium shot, IDENTICAL camera angle and pose to the previous shot, but a
different pine tree — same confident pointing gesture from [LÉO].
```
*Animação:* repetir exatamente o movimento de 2.12.

**2.14 · 3s · PG**
```
[ESTILO] Wide 360-degree panorama of the forest around [LÉO], who stands in the
center. Every tree looks the same, repeating endlessly.
```
*Animação:* giro lento de câmera 360° em torno dele.

**2.15 · 4s · PM**
```
[ESTILO] Medium shot of [LÉO] standing still, shoulders dropping, taking a deep
breath. Forest closing in around him.
```
*Animação:* ombros caem devagar na respiração.

**2.16 · 3s · DET**
```
[ESTILO] Detail shot of a phone held in a small stick hand, a simple map/location
screen glowing, no signal bars.
```
*Animação:* tela pisca; nenhuma barra de sinal aparece.

**2.17 · 4s · CL**
```
[ESTILO] Close-up of [LÉO], the realization landing — eyes widening slightly,
smile fading. Forest darkening behind him.
```
*Animação:* transição lenta de expressão, sem corte.

---

## Bloco 3 — A chamada de emergência

**3.01 · 4s · PM**
```
[ESTILO] Medium shot of [LÉO] holding his phone up above his head, turning slowly,
searching for a signal. Late afternoon forest, light already lower.
```
*Animação:* braço erguido varrendo o ar devagar.

**3.02 · 3s · DET**
```
[ESTILO] Detail shot of the phone screen: an emergency call connected, one signal
bar. Simple flat interface, clearly readable.
```
*Animação:* indicador de chamada pulsando.

**3.03 · 4s · PM**
```
[ESTILO] Medium shot of [LÉO] talking into the phone, his free arm drawing the shape
of a tree in the air, over-explaining. Forest behind him.
```
*Animação:* gesto desenhando a árvore no ar.

**3.04 · 3s · —**
```
[ESTILO] A visual thought-bubble insert: a pine tree with the face of a grumpy old
man — frowning eyebrows and a downturned mouth drawn into the trunk.
Plain cream background, no characters.
```
*Animação:* sobrancelhas da árvore se franzem.

**3.05 · 4s · PM**
```
[ESTILO] Medium shot of [LÉO], posture now straighter and more businesslike,
pointing at his own RED cap while speaking into the phone.
```
*Animação:* muda de postura e aponta para o boné.

**3.06 · 3s · DET**
```
[ESTILO] Detail shot of the phone screen showing a location pin on a simple map.
Clearly readable, flat interface.
```
*Animação:* pin de localização assentando na tela.

**3.07 · 4s · PG**
```
[ESTILO] Wide shot of [LÉO] standing in the forest, turning his head to look around
and mentally mark the place where he will stay. Late afternoon.
```
*Animação:* giro lento da cabeça, pés parados.

**3.08 · 4s · PM**
```
[ESTILO] Medium shot — parallel cut. [NINA] at the park base talking to a park
employee (an adult stick-figure in a uniform), gesturing toward the forest.
Ranger station and vehicles behind them.
```
*Animação:* Nina gesticula em direção à mata.

**3.09 · 3s · PG**
```
[ESTILO] Wide shot of the park base and the treeline. [NINA] stands at the edge of
the forest and does NOT enter it — she stays at the base with the staff.
```
*Animação:* Nina para na borda da mata; ninguém entra.

**3.10 · 3s · PM**
```
[ESTILO] Medium shot of [LÉO] putting the phone into his pocket, calm and decided.
```
*Animação:* gesto único de guardar o celular.

**3.11 · 4s · PG**
```
[ESTILO] Wide shot of the forest canopy. Wind arrives: treetops swaying, loose
leaves crossing the frame diagonally. Cooler light than the previous shots.
```
*Animação:* copas balançando, folhas atravessando o quadro.

**3.12 · 3s · CL**
```
[ESTILO] Close-up of [LÉO] feeling the cold for the first time, shoulders pulled up,
arms close to his body. No coat on yet.
```
*Animação:* ombros encolhem com uma lufada.

---

## Bloco 4 — O abrigo

**4.01 · 3s · PG**
```
[ESTILO] Wide shot of the forest with a closing sky, grey clouds gathering above the
canopy, light dropping. No characters in frame.
```
*Animação:* nuvens avançando, luz caindo.

**4.02 · 3s · DET**
```
[ESTILO] Detail shot of the first raindrops landing on a single broad green leaf,
close up, drops beading on the surface.
```
*Animação:* gotas caindo uma a uma na folha.

**4.03 · 5s · PG**
```
[ESTILO] FANTASY shot, warmer palette than the rest of the film: a cozy wooden cabin
with a covered porch, a lit fireplace glowing inside, and a wi-fi signal icon
floating above the roof. Forest around it. Golden, inviting light.
```
*Animação:* fumaça saindo da chaminé, ícone de wi-fi pulsando.

**4.04 · 3s · PM**
```
[ESTILO] Medium shot, same warm fantasy palette: [LÉO] relaxed on the imaginary
cabin porch, leaning back, completely at ease.
```
*Animação:* balanço relaxado, sem tensão.

**4.05 · 3s · —**
```
[ESTILO] HARD CUT back to reality: the real forest in cold grey light, thin rain
falling. [LÉO] standing in the same pose as on the porch, but wet and exposed,
nothing around him.
```
*Animação:* nenhuma transição suave — corte seco, chuva fina contínua.

**4.06 · 4s · PM**
```
[ESTILO] Medium shot of [LÉO] crouching, opening his moss-green backpack on the
forest floor. Thin rain.
```
*Animação:* abre o zíper da mochila.

**4.07 · 4s · DET**
```
[ESTILO] Top-down detail shot of the backpack contents spread on the forest floor:
a folded TEAL-BLUE coat, a folded ORANGE emergency shelter, a rolled sleeping pad.
Each object clearly separated and readable. Matches R-10.
```
*Animação:* câmera desce lentamente sobre os objetos.

**4.08 · 4s · PG**
```
[ESTILO] Wide shot of [LÉO] walking through the forest assessing the ground,
head tilted UP to check what is above him.
```
*Animação:* caminhada lenta com a cabeça erguida.

**4.09 · 3s · DET**
```
[ESTILO] Detail shot looking up: dead dry branches hanging loose overhead,
clearly unsafe, dark against the grey sky.
```
*Animação:* galhos balançando, ameaçadores.

**4.10 · 4s · PG**
```
[ESTILO] Wide shot of [LÉO] arriving at [CLAREIRA], nodding in approval.
No shelter pitched yet. Overcast late-afternoon light.
```
*Animação:* entra em quadro, para e assente com a cabeça.

**4.11 · 5s · PM**
```
[ESTILO] Medium shot of [LÉO] pitching the ORANGE emergency shelter in [CLAREIRA],
clumsily — fabric bunched, one corner higher than the other.
```
*Animação:* sequência desajeitada de puxar e prender o tecido.

**4.12 · 4s · PG**
```
[ESTILO] Wide shot of [ABRIGO] pitched in [CLAREIRA], finished but crooked,
looking like a badly wrapped sandwich. [LÉO] standing beside it.
```
*Animação:* tecido tremulando de leve.

**4.13 · 3s · PM**
```
[ESTILO] Medium shot of [LÉO] carefully smoothing one fold of the orange fabric,
taking his time, proud of the detail.
```
*Animação:* mão alisa a dobra devagar.

**4.14 · 3s · PM**
```
[ESTILO] Same framing: a gust of wind undoes the fold he just fixed,
the orange fabric flapping loose again.
```
*Animação:* rajada desmancha a dobra em um movimento.

**4.15 · 4s · CL**
```
[ESTILO] Close-up of [LÉO] staring at the fabric, indignant, mouth set — the face of
someone about to negotiate with an object.
```
*Animação:* expressão endurece, cabeça inclina.

**4.16 · 4s · PM**
```
[ESTILO] Medium shot of [LÉO] fixing the fold again. This time it holds.
```
*Animação:* ajusta; tecido para de tremular.

**4.17 · 3s · PG**
```
[ESTILO] Wide shot of [LÉO] sitting on the ground next to the crooked [ABRIGO] in
[CLAREIRA], accepting the result. Rain stopping, light low.
```
*Animação:* senta e se acomoda.

**4.18 · 3s · CL**
```
[ESTILO] Close-up of [LÉO] sitting, eyes drifting to the side — thinking about fire.
```
*Animação:* olhar desvia devagar para fora de quadro.

---

## Bloco 5 — Flashback dos gravetos

**5.01 · 3s · —**
```
[ESTILO] Transition shot into a flashback: the same forest palette washing into the
warm night colors of [CAMPING], the previous evening. No characters.
```
*Animação:* virada de paleta, fria para quente.

**5.02 · 4s · PM**
```
[ESTILO] Medium shot at [CAMPING], warm evening light. [LÉO] stands with his chest
puffed out, holding TWO DRY STICKS up, announcing something.
```
*Animação:* levanta os gravetos com orgulho.

**5.03 · 4s · PM**
```
[ESTILO] Medium shot of [LÉO] rubbing the two sticks together. Nothing happens —
no smoke, no spark. [CAMPING] behind him.
```
*Animação:* fricção rápida, nenhum efeito.

**5.04 · 3s · CL**
```
[ESTILO] Close-up of [LÉO] with a doubtful expression, looking down at the sticks.
```
*Animação:* sobrancelha franze.

**5.05 · 4s · PM**
```
[ESTILO] Medium shot of [LÉO] rubbing the sticks with far more force, whole body
committed. Still nothing.
```
*Animação:* fricção violenta, corpo inteiro balançando.

**5.06 · 3s · DET**
```
[ESTILO] Detail shot of the two dry sticks, completely intact — not even scorched.
```
*Animação:* gravetos parados, um leve giro de câmera.

**5.07 · 4s · PM**
```
[ESTILO] Medium shot: [NINA] steps into frame holding up a simple lighter,
matter-of-fact. [LÉO] beside her with his sticks.
```
*Animação:* Nina entra em quadro e ergue o acendedor.

**5.08 · 3s · CL**
```
[ESTILO] Close-up of [LÉO] changing the subject, looking away, small awkward smile.
```
*Animação:* olhar desvia, sorriso amarelo.

**5.09 · 4s · PG**
```
[ESTILO] Wide shot at [CAMPING]: a small controlled fire burning inside the METAL
FIRE RING, with the BUCKET OF WATER clearly visible beside it. Warm night light.
```
*Animação:* chamas baixas tremulando dentro do anel.

**5.10 · 3s · DET**
```
[ESTILO] Detail shot of the bucket of water being poured over the embers in the
metal fire ring. Steam rising, fire COMPLETELY out, only wet black ash left.
```
*Animação:* água despejada, vapor subindo, brasas apagam.

**5.11 · 3s · —**
```
[ESTILO] Transition back to the forest: warm camp colors washing into the cold blue
of [CLAREIRA] at nightfall. No characters.
```
*Animação:* virada de paleta, quente para fria.

**5.12 · 4s · PM**
```
[ESTILO] Medium shot of [LÉO] in [CLAREIRA] looking down at a small fire-starting kit
in his open hand. Night falling, cold palette.
```
*Animação:* olha o kit na mão, imóvel.

**5.13 · 3s · PG**
```
[ESTILO] Wide shot of the ground around [CLAREIRA]: dry brush and dead leaves
everywhere, no water source anywhere in frame.
```
*Animação:* panorâmica lenta pelo mato seco.

**5.14 · 4s · PM**
```
[ESTILO] Medium shot of [LÉO] putting the fire kit BACK into his moss-green backpack
and closing it. Decided, no hesitation.
```
*Animação:* guarda o kit e fecha a mochila.

**5.15 · 3s · PM**
```
[ESTILO] Medium shot of [LÉO] adjusting [ABRIGO] in [CLAREIRA], settling in for
the night. Cold blue light.
```
*Animação:* ajusta o tecido do abrigo.

**5.16 · 4s · DET**
```
[ESTILO] Detail shot of a small stick hand pulling up the zipper of a flat
TEAL-BLUE winter coat, closing it all the way. Matches R-04.
```
*Animação:* zíper subindo até o topo.

**5.17 · 3s · CL**
```
[ESTILO] Close-up of [LÉO+C], a small proud smile — a tiny victory.
Night, cold palette.
```
*Animação:* sorriso discreto se formando.

**5.18 · 3s · PM**
```
[ESTILO] Medium shot of [LÉO+C] turning his head sharply to one side — he heard
running water somewhere off-frame.
```
*Animação:* giro rápido da cabeça e pausa.

---

## Bloco 6 — Água, cogumelo, sanduíche

**6.01 · 4s · PG**
```
[ESTILO] Wide shot of a shallow stream running between rocks in the forest,
clear transparent water. Cold blue evening light. No characters.
```
*Animação:* água correndo entre as pedras.

**6.02 · 3s · PM**
```
[ESTILO] Medium shot of [LÉO+C] approaching the stream, leaning forward, excited
at the sight of the clear water.
```
*Animação:* aproxima-se e se inclina sobre a água.

**6.03 · 4s · —**
```
[ESTILO] FANTASY insert, styled like a cheerful TV commercial: a cartoon
microorganism wearing dark sunglasses drifting across a bright water background,
waving. Flat colors, upbeat composition, no characters from the film.
```
*Animação:* micro-organismo atravessa o quadro acenando.

**6.04 · 3s · PM**
```
[ESTILO] Medium shot of [LÉO+C] stepping BACK from the stream, deflated by his own
mental commercial. He does not drink.
```
*Animação:* passo para trás, ombros caem.

**6.05 · 4s · PM**
```
[ESTILO] Medium shot of [LÉO+C] taking a water bottle OUT OF HIS OWN BACKPACK and
drinking from it, standing away from the stream.
```
*Animação:* tira a garrafa, bebe.

**6.06 · 3s · PG**
```
[ESTILO] Wide shot of [LÉO+C] walking back to [ABRIGO] in [CLAREIRA],
staying close, not wandering off. Night settling in.
```
*Animação:* caminha de volta e entra no enquadramento do abrigo.

**6.07 · 3s · DET**
```
[ESTILO] Detail shot of the character's midsection with simple cartoon motion lines
around the belly, indicating a loud stomach rumble.
```
*Animação:* linhas de movimento pulsando.

**6.08 · 4s · PM**
```
[ESTILO] Medium shot of [LÉO+C] spotting a single mushroom on the forest floor
and leaning down toward it, curious.
```
*Animação:* inclina-se em direção ao cogumelo.

**6.09 · 3s · DET**
```
[ESTILO] Close detail shot of a single wild mushroom on the forest floor,
UNTOUCHED — no hand in frame, nothing near it.
```
*Animação:* leve movimento de ar; nada o toca.

**6.10 · 3s · CL**
```
[ESTILO] Close-up of [LÉO+C] considering it... then deciding against it,
shaking his head once.
```
*Animação:* pondera e nega com a cabeça.

**6.11 · 4s · PM**
```
[ESTILO] Medium shot of [LÉO+C] taking the wrapped sandwich out of his backpack
and eating it, sitting beside [ABRIGO]. Night, cold palette.
```
*Animação:* desembrulha e dá uma mordida.

**6.12 · 4s · PM**
```
[ESTILO] Medium shot of [LÉO+C] putting the leftovers and the wrapper into a
BEAR-RESISTANT CONTAINER — a sturdy hard-sided canister — and locking the lid.
```
*Animação:* guarda os restos e fecha a trava.

**6.13 · 3s · PG**
```
[ESTILO] Wide shot showing the bear-resistant container placed FAR from [ABRIGO] —
container in the foreground, the orange shelter small in the background.
The distance between them must read clearly.
```
*Animação:* câmera estática; distância evidente.

**6.14 · 3s · DET**
```
[ESTILO] Detail shot of a dry branch snapping on the dark forest floor,
splintered wood, leaves disturbed around it.
```
*Animação:* galho quebra no meio do clipe.

**6.15 · 4s · CL**
```
[ESTILO] Close-up of [LÉO+C] stopping mid-chew, eyes fixed and unblinking,
looking off-frame into the dark.
```
*Animação:* mastigação para; olhos se fixam.

---

## Bloco 7 — O urso real

**7.01 · 5s · PG**
```
[ESTILO] Wide shot deep into the forest. [URSO] FAR AWAY between the trees,
sniffing the ground, facing away, completely unaware of anyone.
Cold dusk light. No character in frame.
```
*Animação:* urso fareja o chão, andando devagar, sem olhar para a câmera.

**7.02 · 3s · CL**
```
[ESTILO] Close-up of [LÉO+C] completely motionless, eyes wide but calm,
holding his breath.
```
*Animação:* imobilidade total, apenas um piscar.

**7.03 · 3s · DET**
```
[ESTILO] Detail shot of thin stick legs trembling slightly, feet planted on the
forest floor, not moving from the spot.
```
*Animação:* tremor nas pernas; os pés não saem do lugar.

**7.04 · 4s · —**
```
[ESTILO] MENTAL FLASH: three desaturated frames of the chase from Block 1 —
[LÉO] running, [URSO] behind him — washed out, low contrast, ghostly.
```
*Animação:* três frames piscando em sequência rápida.

**7.05 · 3s · CL**
```
[ESTILO] Close-up of [LÉO+C] shutting his eyes tight, cutting the thought off.
```
*Animação:* olhos fecham com força e reabrem calmos.

**7.06 · 4s · PM**
```
[ESTILO] Medium shot of [LÉO+C] standing perfectly still and calm.
He does NOT run. Body relaxed, arms down.
```
*Animação:* respiração lenta; nenhum deslocamento.

**7.07 · 4s · PG**
```
[ESTILO] Wide shot of [URSO] still sniffing the ground in the distance,
indifferent, never looking in the character's direction. Trees between them.
```
*Animação:* urso segue farejando, alheio.

**7.08 · 5s · PA**
```
[ESTILO] American shot of [LÉO+C] taking slow backwards and sideways steps,
facing the bear's direction, never turning his back, never running.
```
*Animação:* passos lentos para trás, sem correr.

**7.09 · 4s · PG**
```
[ESTILO] Wide shot of [LÉO+C] arriving at [PONTO-B]. Dusk, colder palette than
the earlier clearing. No shelter pitched yet.
```
*Animação:* entra em quadro e para.

**7.10 · 4s · PM**
```
[ESTILO] Medium shot of [LÉO+C] pitching [ABRIGO] again at [PONTO-B],
faster and slightly more competent than the first time.
```
*Animação:* monta o abrigo em movimentos decididos.

**7.11 · 4s · PM**
```
[ESTILO] Medium shot of [LÉO+C] with the phone in his hand, reporting his change of
position. [ABRIGO] pitched behind him at [PONTO-B].
```
*Animação:* fala ao celular apontando para o chão.

**7.12 · 4s · PG**
```
[ESTILO] Wide shot of [URSO] in the far background walking away, leaving the frame
at the edge. Foreground empty forest floor. Dusk.
```
*Animação:* urso se afasta e sai de quadro.

**7.13 · 3s · CL**
```
[ESTILO] Close-up of [LÉO+C] exhaling in relief, shoulders dropping.
```
*Animação:* expiração longa, ombros relaxam.

**7.14 · 3s · PM**
```
[ESTILO] Medium shot of [LÉO+C] in a self-satisfied pose, hands on hips,
like someone who thinks he earned a bear's respect.
```
*Animação:* assume a pose e a segura.

---

## Bloco 8 — Zíper, apito e resgate

**8.01 · 4s · PG**
```
[ESTILO] Wide shot of [PONTO-B] at dusk turning to night, last light draining from
the sky. [ABRIGO] pitched, [LÉO+C] small in frame.
```
*Animação:* luz caindo ao longo do clipe.

**8.02 · 3s · PM**
```
[ESTILO] Medium shot of [LÉO+C] organizing the inside of [ABRIGO],
tucking the sleeping pad in. Night.
```
*Animação:* arruma o interior do abrigo.

**8.03 · 3s · DET**
```
[ESTILO] Detail shot of a flashlight switched on, its beam cutting a clear cone
through the dark forest. Strong contrast, night palette.
```
*Animação:* facho acende e varre para o lado.

**8.04 · 3s · CL**
```
[ESTILO] Close-up of [LÉO+C] freezing, head half-turned — he heard a noise behind
him. Night, flashlight glow on his face.
```
*Animação:* congela no meio do movimento.

**8.05 · 3s · PM**
```
[ESTILO] Medium shot of [LÉO+C] completely still in the dark. Nothing moves,
no sound source visible anywhere in frame.
```
*Animação:* imobilidade total.

**8.06 · 3s · PM**
```
[ESTILO] Same framing: [LÉO+C] moves one arm slightly — and reacts, because the
noise came back with the movement.
```
*Animação:* move o braço e olha em volta assustado.

**8.07 · 3s · DET**
```
[ESTILO] Detail shot of the ZIPPER PULL on the moss-green backpack swinging against
the fabric — the source of the noise, obvious and anticlimactic.
```
*Animação:* zíper balançando e batendo no tecido.

**8.08 · 3s · CL**
```
[ESTILO] Close-up of [LÉO+C] playing it off, looking around to check that nobody saw.
```
*Animação:* olhar de disfarce para os lados.

**8.09 · 4s · PG**
```
[ESTILO] Wide shot from behind [LÉO+C], facing total darkness between the trees.
He takes one step forward, toward leaving.
```
*Animação:* um passo à frente, rumo ao escuro.

**8.10 · 4s · CL**
```
[ESTILO] Close-up of [LÉO+C] hesitating — remembering that he has to be findable.
Expression shifting from impulse to restraint.
```
*Animação:* expressão muda devagar; nenhum passo.

**8.11 · 3s · PM**
```
[ESTILO] Medium shot of [LÉO+C] sitting back down beside [ABRIGO] at [PONTO-B],
staying put. Night.
```
*Animação:* senta e se acomoda.

**8.12 · 4s · PM**
```
[ESTILO] Medium shot of [LÉO+C] taking the small silver WHISTLE and blowing it,
cheeks puffed, head tilted back. Night forest.
```
*Animação:* leva o apito à boca e sopra.

**8.13 · 3s · PG**
```
[ESTILO] Wide shot of the dark forest around [PONTO-B], [LÉO+C] small and still,
listening. Nothing answers.
```
*Animação:* pausa longa, apenas folhas se mexendo.

**8.14 · 3s · PM**
```
[ESTILO] Medium shot of [LÉO+C] blowing the whistle a second time, more insistently.
```
*Animação:* sopra de novo, mais forte.

**8.15 · 5s · PG**
```
[ESTILO] Wide night sky shot above the forest canopy: the moon travelling across the
frame and the stars rotating, showing HOURS passing. Deep night palette.
```
*Animação:* time-lapse — lua se deslocando, estrelas girando.

**8.16 · 4s · PM**
```
[ESTILO] Medium shot of [LÉO+C] curled up against the cold beside [ABRIGO],
arms wrapped around his knees, still in the same spot.
```
*Animação:* tremor de frio, respiração visível.

**8.17 · 4s · PG**
```
[ESTILO] Wide shot of the dark forest: a distant flashlight beam moving between the
trees, far away, sweeping. [LÉO+C] small in the foreground.
```
*Animação:* facho distante varrendo entre os troncos.

**8.18 · 3s · CL**
```
[ESTILO] Close-up of [LÉO+C] lifting his head, eyes catching the distant light.
```
*Animação:* cabeça levanta, olhos acendem.

**8.19 · 4s · PM**
```
[ESTILO] Medium shot of [LÉO+C] waving both arms above his head toward the light —
but STAYING exactly where he is, feet planted.
```
*Animação:* acena com os braços; os pés não saem do lugar.

**8.20 · 5s · PG**
```
[ESTILO] Wide shot of [MARA] arriving at [PONTO-B] with a small rescue team of
stick-figure adults, flashlights in hand, beams crossing the clearing.
[LÉO+C] standing beside [ABRIGO]. Night.
```
*Animação:* equipe entra em quadro, lanternas varrendo.

**8.21 · 4s · PM**
```
[ESTILO] Medium two-shot of [MARA] assessing [LÉO+C]'s condition, flashlight raised,
checking him over. Night, team behind them.
```
*Animação:* Mara ergue a lanterna e o examina.

**8.22 · 3s · CL**
```
[ESTILO] Close-up of [LÉO+C]: cold, hungry and humbled — no trace of the confident
expression from Block 2.
```
*Animação:* tremor leve, olhar baixo.

**8.23 · 4s · PG**
```
[ESTILO] Wide shot of the group walking out together along the trail, flashlight
beams lighting the path ahead. Night forest.
```
*Animação:* grupo se afasta pela trilha.

**8.24 · 3s · DET**
```
[ESTILO] Detail shot of an empty branch where the bird sat in Block 2,
lit by moonlight. Nothing on it. Quiet composition.
```
*Animação:* galho balançando de leve, vazio.

---

## Bloco 9 — Reencontro e piada final

**9.01 · 4s · PG**
```
[ESTILO] Wide establishing shot of [CAMPING] in clear morning light.
[NINA] waiting by the picnic table, looking toward the trail.
```
*Animação:* Nina olhando para a trilha, expectante.

**9.02 · 4s · PM**
```
[ESTILO] Medium shot of [NINA] seeing [LÉO+C] arrive — relief on her face,
arms dropping. [CAMPING] behind her.
```
*Animação:* expressão de alívio, braços relaxam.

**9.03 · 3s · PM**
```
[ESTILO] Medium shot of [LÉO+C] raising one finger, about to justify everything
that happened. Morning light at [CAMPING].
```
*Animação:* dedo sobe, boca abre para explicar.

**9.04 · 3s · CL**
```
[ESTILO] Close-up of [NINA] with one eyebrow raised, unconvinced.
```
*Animação:* sobrancelha sobe devagar.

**9.05 · 4s · PM**
```
[ESTILO] Medium shot, later: [LÉO+C] noticing the TWO DRY STICKS lying on the picnic
table at [CAMPING]. Morning light.
```
*Animação:* olhar encontra os gravetos na mesa.

**9.06 · 3s · PM**
```
[ESTILO] Medium shot of [LÉO+C] looking over at [NINA], checking whether she is
watching.
```
*Animação:* vira a cabeça em direção a ela.

**9.07 · 3s · CL**
```
[ESTILO] Close-up of [LÉO+C] looking straight into the camera, complicit.
```
*Animação:* olhar direto para a lente, imóvel.

**9.08 · 4s · PM**
```
[ESTILO] Medium shot of [LÉO+C] quietly slipping the two dry sticks into his pocket.
```
*Animação:* pega os gravetos e guarda no bolso.

**9.09 · 4s · PG**
```
[ESTILO] Wide shot of [LÉO+C] and [NINA] at the picnic table at [CAMPING], going
over the route map together, heads down, actually studying it.
```
*Animação:* os dois apontam pontos no mapa.

**9.10 · 4s · PG**
```
[ESTILO] Wide shot of a simple campsite shower stall at [CAMPING].
[LÉO] (no coat, still wearing the red cap) stepping into it. Morning light.
```
*Animação:* entra no boxe e fecha a porta.

**9.11 · 3s · PM**
```
[ESTILO] Medium shot of [LÉO] inside the shower stall, calmly turning the tap,
relaxed and looking forward to it.
```
*Animação:* gira o registro.

**9.12 · 4s · PG**
```
[ESTILO] Wide shot: muddy BROWN forest water pouring out of the showerhead over
[LÉO], who throws his arms up in despair. Comic composition.
```
*Animação:* jato de água marrom desce; braços sobem em desespero.

**9.13 · 4s · —**
```
[ESTILO] Final channel card: clean cream background with subtle paper texture,
large empty centered area for the channel name and end-card elements to be added
in editing. No characters.
```
*Animação:* nenhuma. Fundo estático para a cartela final.

---

## Conferência antes de disparar cada bloco

- [ ] Mochila verde-musgo presente em todos os planos em que o Léo aparece
- [ ] Casaco azul-petróleo fechado em **todos** os planos a partir de 5.16 (até 9.09)
- [ ] Exatamente 2 braços e 2 pernas em cada personagem
- [ ] Urso só nos planos 1.01–1.03, 7.01, 7.04, 7.07, 7.12 — e nunca perto do Léo
- [ ] Fogo só em 5.09 e 5.10, dentro do anel metálico, com o balde em quadro
- [ ] Clareira A (blocos 4–6) e Ponto B (blocos 7–8) visivelmente diferentes
- [ ] Margem limpa no topo em 1.06–1.07 para as cartelas de simulação
- [ ] Continuidade de luz dentro do bloco, sem salto entre planos vizinhos

## Volume e ordem

144 planos: 13 (B1) + 17 (B2) + 12 (B3) + 18 (B4) + 18 (B5) + 15 (B6) + 14 (B7) +
24 (B8) + 13 (B9).

Disparar na ordem dos blocos. Dentro de cada bloco, gerar **todas** as imagens-base
antes de animar qualquer clipe — um erro de figurino descoberto na animação custa
o bloco inteiro.
