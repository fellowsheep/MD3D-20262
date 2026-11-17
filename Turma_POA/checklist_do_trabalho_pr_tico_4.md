# Checklist - Trabalho Prático 4: Modelagem 3D de Personagem

## 📅 Informações Gerais
- [ ] **Prazo de Entrega:** 30/11/2026 (até 23h59min)
- [ ] **Onde Enviar:** Enviar o link do projeto do itch.io na atividade do Moodle.
- [ ] **Apresentação:** Apresentação oral em aula no dia 30/11/2026.

## ⚙️ Requisitos Técnicos no Blender
### 1. Modelagem Poligonal e Topologia
- [ ] Escolher um *Concept Art* ou *Character Sheet* (humanoide ou criatura antropomórfica bípede).
- [ ] Fazer modelagem poligonal focada em subdivisão (*Subdivision Surface*).
- [ ] **NÃO** utilizar escultura (*Sculpting*), exceto para ajustes muitos sutis nas proporções.
- [ ] Manter o número de polígonos/triângulos otimizado (dentro das referências para assets de jogo).
- [ ] Manter a geometria separada em múltiplas partes e o **Outliner organizado**.

### 2. Mapeamento UV e Textura
- [ ] Criar um **Mapa UV Único** (*Texture Atlas*) para todo o personagem (corpo, roupa, cabelo, etc.).
- [ ] Evitar distorções graves e otimizar espaços, priorizando resolução no rosto.
- [ ] Atribuir **apenas 1 Material** no Blender conectado à textura única.
- [ ] Usar textura baseada em imagem (pintura manual ou PBR com *baking* se necessário).

### 3. Rigging e Skinning
- [ ] Criar um Esqueleto (*Armature*) funcional (manual ou via Rigify/Mixamo).
- [ ] Fazer o *Skinning* (ajustes de *Weight Paint*) para corrigir deformações em dobras (cotovelos, joelhos, ombros).

### 4. Posing (Poses)
- [ ] **NÃO** entregar o personagem em *T-pose* ou *A-pose*.
- [ ] Salvar na *Pose Library* ou marcar na *Timeline* pelo menos **3 poses distintas**:
  - [ ] 1. Pose Neutra / Idle.
  - [ ] 2. Pose de Ação.
  - [ ] 3. Pose Expressiva.

## 🎮 Requisitos da Página no itch.io
- [ ] O projeto pode ser configurado como Privado, usando a **senha: MD3D20262**
- [ ] Fazer o upload dos seguintes itens:
  - [ ] 1. Arquivo `.blend`.
  - [ ] 2. Board de referências (preferencialmente do PureRef).
  - [ ] 3. Imagem principal do *Concept Art / Character Sheet* com devidos créditos ao artista.
  - [ ] 4. Screenshots da *viewport* do modelo (vistas frontal, lateral, perspectiva e *wireframe* no modo edição).
  - [ ] 5. Screenshot do mapeamento UV.
  - [ ] 6. Screenshots do rigging em pose de descanso e nas 3 poses criadas.
  - [ ] 7. Renders (Item Opcional).
  - [ ] 8. Pequena descrição do projeto:
    - [ ] Informar ferramentas usadas (Blender, Krita, Photoshop, Mixamo, etc.).
    - [ ] Citar repositórios de texturas (se utilizados).
    - [ ] Citar/Creditar tutoriais acompanhados no processo.
    - [ ] (Recomendado) Incluir as respostas do Roteiro da Apresentação Oral nesta descrição.

## 🗣️ Roteiro da Apresentação Oral (Preparação)
Preparar os seguintes pontos para comentar em aula (sem necessidade de slides, mas opcional se preferir):
- [ ] **Conceito e Estilo:** Qual estilo escolhido e as principais inspirações.
- [ ] **Topologia:** Contagem final de triângulos e como a topologia se comportou na deformação.
- [ ] **Textura:** Processo de criação do *atlas* (pintura manual ou procedural com *bake*).
- [ ] **Rigging:** Método de esqueleto usado e se houve dificuldades no *Weight Paint*.
- [ ] **Posing:** Por que as 3 poses foram escolhidas e o que elas revelam sobre a personalidade.