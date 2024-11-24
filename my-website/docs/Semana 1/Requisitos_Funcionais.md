---
title: Requisitos Funcionais e Não Funcionais
sidebar_position: 4
---

## Introdução
Os requisitos funcionais e não funcionais para o desenvolvimento de um jogo de Realidade Virtual, tem como objetivo oferecer uma visão geral das funcionalidades essenciais e dos padrões de qualidade necessários para a entrega de uma experiência imersiva e envolvente.

## Requisitos Funcionais (Jogo)
Os requisitos funcionais especificam o que o sistema deve realizar para atender aos objetivos do jogo. 

### Jogabilidade
- **Movimentação:** O jogador deve poder se mover dentro do ambiente virtual utilizando controladores ou por meio de interações físicas.
- **Interatividade:** O ambiente deve reagir às ações do jogador, como manipulação de objetos, combate ou resolução de quebra-cabeças.
- **Modo de pausa:** Deve haver a opção de pausar o jogo a qualquer momento.
- **Ajustes de conforto:** Oferecer opções para minimizar enjoo por movimento (ex.: modo de teletransporte).

## Requisitos Não Funcionais (Jogo)
Os requisitos não funcionais especificam padrões de qualidade e desempenho esperados.

### Desempenho
- **Taxa de quadros:** O jogo deve manter uma taxa mínima de 90 FPS para garantir uma experiência fluida e confortável.
- **Latência:** A latência dos controles deve ser menor que 20ms para evitar atrasos perceptíveis.

### Compatibilidade
- **Plataformas suportadas:** O jogo deve funcionar em todas as plataformas de navegação, inclusive mobile.
- **Sistemas Operacionais:** Suporte a todos os SO's como Windows, Ubuntu, Android e Linux.

### Usabilidade
- **Linguagem:** Suporte a múltiplos idiomas, incluindo português, inglês, espanhol, francês e mandarim.
- **Espaço:** O usuário não deve sair do lugar enquanto usufrui da experiência.

## Requisitos dos verbos aplicados
Foram escolhido 3 verbos da aba ***Ações e Verbos*** que mais participaram da característica do jogo, sendo assim, os requisitos funcionais e não funcionais deles podem ser definidos, logo abaixo:

## Requisitos Funcionais (Verbos)

### Reconhecer:
   - O sistema deve identificar e exibir inimigos, aliados ou objetos-chave no ambiente virtual.
   - Deve haver feedback visual ou auditivo para informar ao jogador sobre os elementos reconhecidos.
   - O jogo deve permitir a identificação de elementos de forma dinâmica (destacar alvos).

### Atirar:
   - O jogador deve poder usar armas ou dispositivos específicos para atacar alvos identificados.
   - As armas disponíveis devem ter diferentes tipos de mecânicas (ex.: disparos rápidos, tiros carregados).
   - Deve haver um sistema de munição com recarregamento manual ou automático.

### Mirar:
   - O jogo deve permitir ao jogador mirar utilizando controladores de movimento ou sistemas de rastreamento de cabeça.
   - Um cursor ou mira virtual deve estar visível para auxiliar no disparo.

## Requisitos Não Funcionais

### Reconhecer:
   - A detecção de elementos deve ser processada em menos de 100ms para garantir fluidez.
   - O sistema de reconhecimento deve ser compatível com dispositivos de rastreamento e funcionar mesmo em ambientes complexos.
 
### Atirar:
   - A latência entre o disparo e a ação no jogo deve ser inferior a 50ms.
   - Deve haver efeitos visuais e sonoros realistas para melhorar a experiência do jogador.
   - A física do disparo (trajetória, impacto) deve ser precisa e consistente.

### Mirar:
   - O sistema de mira deve funcionar com precisão em um campo de visão de 360°.
   - Deve ser compatível com diferentes controladores e headsets VR.
   - A calibração da mira deve ser intuitiva e executada em até 30 segundos.
