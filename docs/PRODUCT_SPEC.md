# STRIDEN — visão do produto

## Conceito
STRIDEN é um app esportivo que transforma corrida e ciclismo em uma disputa estratégica por áreas da cidade. O usuário registra uma atividade, percorre um trajeto válido e pode conquistar ou disputar territórios conforme regras transparentes.

## Modalidades
- Corrida
- Ciclismo
- Caminhada (opcional; pode pontuar de forma diferente)

## Funcionalidades previstas
1. Cadastro, login e perfil do atleta.
2. Permissões e explicação clara do uso de localização.
3. Iniciar, pausar, retomar e finalizar atividade.
4. Registro de GPS, distância, duração, velocidade e ritmo.
5. Mapa real com posição atual e camadas de territórios.
6. Territórios livres, próprios, de rivais e em disputa.
7. Regras de conquista e reconquista.
8. Histórico de atividades.
9. Ranking por área, temporada e modalidade.
10. Desafios, conquistas e notificações.
11. Denúncia de atividade suspeita e revisão de disputas.

## Princípios de segurança e integridade
- Não permitir que o usuário desenhe manualmente um percurso para reivindicar área.
- Validar velocidade plausível, continuidade do GPS, precisão e padrões anormais.
- Não atualizar território com uma atividade ainda não validada.
- Evitar revelar a localização residencial exata dos atletas.
- Permitir controles de privacidade e exclusão de conta/dados.
- Não incentivar correr ou pedalar olhando para a tela; usar alertas sonoros/vibração e interação pós-atividade.

## Regra de território — proposta inicial para testar
Uma atividade validada gera um trajeto. O sistema converte o trajeto em uma área fechada ou em células de mapa elegíveis. O atleta ganha influência nas células percorridas; uma área muda de dono apenas quando o critério mínimo de cobertura e esforço for atingido. A regra final precisa de testes para evitar que alguém capture uma região enorme com um contorno artificial ou um trajeto curto.

## Identidade visual atual
- Nome de trabalho: STRIDEN.
- Assinatura: RUN • RIDE • CONQUER.
- Cores do protótipo: azul-marinho profundo, verde-limão, azul e coral para estados de mapa.
- Ícone: percurso em curva com referência a roda/movimento e avanço.
