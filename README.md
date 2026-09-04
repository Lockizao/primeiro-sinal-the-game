# Primeiro Sinal 🎒

Um simulador de vida escolar brasileiro em 3D, câmera em terceira pessoa, feito num único arquivo HTML autocontido (HTML + CSS + JS + Three.js via CDN — sem etapa de build, sem servidor).

Inspirado na pegada sandbox dos jogos do mDickie (School Days, Wrestling Revolution) — a referência de câmera e exploração é a School Days, mas em visual próprio, tom cartunesco e leve, com um estilo propositalmente "3D antigo" (formas simples, sem textura fina).

## Como jogar

Abra `index.html` em qualquer navegador moderno. Não precisa de servidor, build ou instalação — é um arquivo só.

## O que já tem

- Criação de personagem e família (renda baixa/alta)
- Câmera 3D em terceira pessoa, atrás e acima do personagem, com controle "de tanque"
  (W/S andam, A/D giram) — sem projeção isométrica, mundo com geometria e luz/sombra reais
- Bairro com 4 casas mobiliadas, quiosque, avenida com pista própria (carros patrulhando,
  ciclista, pedestres), 2 lojas e 2 casas extras, ligado por uma rua longa até o portão da escola
- Escola grande e de verdade, com paredes e portas reais entre os ambientes: hall de entrada com
  corredor de armários e um armário de troféus, 2 salas de aula (com carteiras/cadeiras usáveis),
  sala dos professores, diretoria, cantina/cafeteria (com NPC funcional e horário certo pra
  comida), banheiro, auditório, biblioteca e laboratório
- Quintal externo bem maior: pátio, quadra poliesportiva, piscina, estacionamento de ônibus
  escolares estilo americano e um bicicletário (reservado pra uma futura atualização)
- Telhados que somem quando você entra num prédio (estilo The Sims), agora um plano 3D de verdade
- Calendário vivo com meses/estações reais (hemisfério sul), clima com efeitos de verdade (frio,
  calor, chuva, granizo) e vegetação com detalhes sazonais
- Ciclo de dia e noite, com postes de rua que acendem à noite (luzes de verdade na cena 3D)
- Atributos e necessidades (Saúde, Energia, Humor, Força, Agilidade, Inteligência, Resistência, Carisma)
- Aulas funcionais com quiz, sistema de atraso/disciplina, cabular aula
- Interação social (elogiar, piada, insultar, paquerar), facções, romance
- Combate cartunesco por turnos
- Economia (mesada, cantina, loja de roupas)
- NPCs com nome próprio, rotina de horário e personalidade — inclusive um editor pra customizar
  qualquer um deles
- Personagens como bonecos 3D articulados (cilindros/esferas, estilo "3D antigo"), com braços que
  balançam ao contrário das pernas, corpo que se inclina ao virar, respiração e piscadas individuais
- HUD compacto: informação essencial sempre visível, o resto (data/clima) escondido atrás de um
  botão "⋯" pra não poluir a tela
- Salvar e continuar o jogo, progressão de vários dias, sons ambiente sintetizados, controles touch
- Resumo de fim de dia

## Tecnologia

HTML/CSS/JavaScript, com Three.js (WebGL) carregado via CDN pra renderização 3D. Sem imagem
externa, sem modelo 3D importado — todo o cenário e os personagens são geometria gerada por código
(caixas, cilindros e esferas). Sem frameworks de UI, sem build step.
