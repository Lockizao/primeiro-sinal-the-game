# Primeiro Sinal 🎒

Um simulador de vida escolar brasileiro em câmera isométrica 2D, feito num único arquivo HTML autocontido (HTML + CSS + JS, sem dependências externas, tudo em Canvas 2D).

Inspirado na pegada sandbox dos jogos do mDickie (School Days, Wrestling Revolution), mas em tom cartunesco e leve.

## Como jogar

Abra `index.html` em qualquer navegador moderno. Não precisa de servidor, build ou instalação — é um arquivo só.

## O que já tem

- Criação de personagem e família (renda baixa/alta)
- Bairro com 4 casas mobiliadas e um quiosque, ligado por uma rua longa até o portão da escola
- Escola de verdade, com paredes e portas reais entre os ambientes: hall de entrada com corredor
  de armários e um armário de troféus, 2 salas de aula (com carteiras/cadeiras usáveis), sala dos
  professores, diretoria, cantina/cafeteria (com NPC funcional e horário certo pra comida),
  banheiro e um auditório
- Quintal externo bem maior: pátio, quadra poliesportiva, piscina, estacionamento de ônibus
  escolares estilo americano e um bicicletário (reservado pra uma futura atualização)
- Telhados que somem quando você entra num prédio (estilo The Sims), com textura de telha e cumeeira
- Calendário vivo com meses/estações reais (hemisfério sul), clima com efeitos de verdade (frio,
  calor, chuva, granizo) e detalhes sazonais na grama (flores, folhas caindo)
- Ciclo de dia e noite, com postes de rua que acendem à noite
- Atributos e necessidades (Saúde, Energia, Humor, Força, Agilidade, Inteligência, Resistência, Carisma)
- Aulas funcionais com quiz, sistema de atraso/disciplina, cabular aula
- Interação social (elogiar, piada, insultar, paquerar), facções, romance
- Combate cartunesco por turnos
- Economia (mesada, cantina, loja de roupas)
- NPCs com nome próprio, rotina de horário e personalidade — inclusive um editor pra customizar
  qualquer um deles
- Personagens com um toque de física: braços que balançam ao contrário das pernas, corpo que se
  inclina e volta devagar ao mudar de direção, respiração e piscadas individuais por personagem
- Salvar e continuar o jogo, progressão de vários dias, sons ambiente sintetizados, controles touch
- Resumo de fim de dia

## Tecnologia

Puro HTML/CSS/JavaScript. Sprites em pixel art gerados por código (canvas offscreen), sem nenhuma
imagem externa. Sem frameworks, sem build step.
