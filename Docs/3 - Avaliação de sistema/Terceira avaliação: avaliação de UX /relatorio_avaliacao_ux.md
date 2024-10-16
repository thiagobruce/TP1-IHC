# Primeira Etapa 

## Interpretação das Métricas e Problemas de Acessibilidade Identificados pelo Lighthouse
Na primeira etapa da análise, utilizamos a ferramenta Lighthouse para avaliar o site da Siri Cascudo Lanchonete, com foco nas métricas de desempenho, acessibilidade, boas práticas e SEO.

## Análise da Ferramenta Lighthouse

![WhatsApp Image 2024-10-16 at 00 37 31](https://github.com/user-attachments/assets/80d00b3f-1481-40f5-afb3-e8dca9d6a2cf)

![WhatsApp Image 2024-10-16 at 00 37 21](https://github.com/user-attachments/assets/6eab898d-6008-4237-946d-99680c653d06)

![WhatsApp Image 2024-10-16 at 00 32 23](https://github.com/user-attachments/assets/fa44b50a-ab9e-4873-b3e1-8f2c1f3b4c72)

![WhatsApp Image 2024-10-16 at 00 32 23 (1)](https://github.com/user-attachments/assets/2a8f9570-a95c-4046-adf4-00a400b4487f)

![WhatsApp Image 2024-10-16 at 00 32 23 (3)](https://github.com/user-attachments/assets/f25a85de-2c0c-4428-a7d5-96841029e07b)

As métricas de desempenho analisadas revelam problemas significativos na experiência do usuário, principalmente em relação ao tempo de carregamento e à estabilidade da página. Apresentamos uma análise detalhada de cada métrica, juntamente com os principais problemas de acessibilidade identificados:

### Análise das Métricas:
1. **Largest Contentful Paint (LCP):** 
   - O LCP foi registrado em 4,4 segundos, acima do ideal de 2,5 segundos. Isso significa que o maior elemento visível da página leva muito tempo para carregar, o que aumenta a frustração dos usuários e a chance de abandono do site.

2. **Interaction to Next Paint (INP):**
   - O INP ficou em 487ms, enquanto o recomendado é abaixo de 200ms. Isso indica que a página não responde de forma fluida às interações, como cliques, toques ou rolagens, o que compromete a sensação de responsividade e pode afetar a experiência geral do usuário.

3. **Cumulative Layout Shift (CLS):**
   - O CLS foi de 0,66, muito acima do ideal de 0,1. Esse valor elevado indica movimentações inesperadas dos elementos da página durante o carregamento, prejudicando a usabilidade. Essas mudanças inesperadas podem fazer com que o usuário clique acidentalmente em elementos, gerando frustração.

4. **First Contentful Paint (FCP):**
   - O FCP foi registrado em 4,1 segundos, bem acima do recomendado de 1,8 segundos. O FCP é o tempo que leva para que os usuários vejam o primeiro conteúdo na tela. Um valor elevado transmite a sensação de lentidão.

5. **Time to First Byte (TTFB):**
   - O TTFB foi de 0,85 segundos, classificado como moderado (o ideal é abaixo de 0,8 segundos). Embora esse tempo não esteja muito distante do ideal, uma redução no TTFB poderia melhorar o tempo de carregamento inicial da página e proporcionar uma sensação de maior desempenho.

### Problemas de Acessibilidade:
1. **Demora no Carregamento de Conteúdo:**
   - O alto tempo de LCP e FCP pode dificultar a navegação para pessoas com conexões mais lentas ou dispositivos de menor desempenho, aumentando o risco de abandono da página antes de seu carregamento completo.

2. **Interatividade Comprometida:**
   - O INP elevado prejudica a experiência de pessoas com deficiências motoras, que precisam de interações rápidas para navegar com eficiência. O atraso nas respostas aos comandos pode gerar frustração e afetar a usabilidade.

3. **Instabilidade de Layout (CLS):**
   - O CLS elevado afeta negativamente pessoas com baixa visão ou deficiências cognitivas, que podem ter dificuldade em acompanhar as mudanças abruptas de layout. Isso também pode ser um problema para usuários que dependem de leitores de tela, já que elementos em movimento podem gerar confusão na interpretação do conteúdo.

4. **Carregamento Inconsistente (TTFB):**
   - Embora o TTFB seja moderado, qualquer atraso no carregamento inicial pode impactar negativamente pessoas com deficiências auditivas ou visuais, que dependem de elementos carregados para ativar descrições, legendas ou ajustes de áudio e vídeo.

A otimização dessas métricas não só tornará a página mais rápida e eficiente, mas também mais acessível e inclusiva, proporcionando uma experiência superior para todos os usuários.

---

# Segunda Etapa

## Avaliação da Experiência do Usuário (UX) com o UEQ Online

Após a execução de testes de usabilidade, utilizamos a ferramenta **UEQ Online** para capturar a percepção dos usuários sobre a experiência no site.

## Link para o Relatório UEQ Online:
[Relatório UEQ Online](https://onedrive.live.com/personal/c6a52d825040847a/_layouts/15/doc2.aspx?resid=2c413782-54c2-4034-84fe-dc27936ddeec&cid=c6a52d825040847a&ct=1728801614322&wdOrigin=OFFICECOM-WEB.START.UPLOAD&wdPreviousSessionSrc=HarmonyWeb&wdPreviousSession=5ed75e1d-b19e-4863-873a-70dc7c77056d)

## Resultados da Avaliação de UX:
Os dados coletados pelo **UEQ Online** foram organizados em pares de adjetivos, onde os usuários avaliaram o site de acordo com sua experiência. A seguir, os principais resultados de quatro usuários diferentes:

## **USUÁRIO 1:**
|                |                                                |                |
|----------------|------------------------------------------------|----------------|
| Obstrutivo     | ○ ○ ○ ○ ○ ○ ○ ○ ● ○                            | Condutor       |
| Complicado     | ○ ○ ○ ○ ○ ○ ○ ○ ○ ●                            | Fácil          |
| Ineficiente    | ○ ○ ○ ○ ○ ○ ○ ● ○ ○                            | Eficiente      |
| Confuso        | ○ ○ ○ ○ ○ ○ ○ ● ○ ○                            | Evidente       |
| Aborrecido     | ○ ○ ○ ○ ○ ● ○ ○ ○ ○                            | Excitante      |
| Desinteressante| ○ ○ ○ ○ ○ ○ ● ○ ○ ○                            | Interessante   |
| Convencional   | ○ ○ ○ ○ ○ ● ○ ○ ○ ○                            | Original       |
| Comum          | ○ ○ ○ ○ ○ ○ ● ○ ○ ○                            | Vanguardista   |

## **USUÁRIO 2:**
|                |                                                |                |
|----------------|------------------------------------------------|----------------|
| Obstrutivo     | ○ ○ ○ ○ ○ ○ ○ ● ○ ○                            | Condutor       |
| Complicado     | ○ ○ ○ ○ ○ ○ ○ ● ○ ○                            | Fácil          |
| Ineficiente    | ○ ○ ○ ○ ○ ○ ○ ○ ● ○                            | Eficiente      |
| Confuso        | ○ ○ ○ ○ ○ ○ ○ ● ○ ○                            | Evidente       |
| Aborrecido     | ○ ○ ○ ○ ○ ○ ○ ● ○ ○                            | Excitante      |
| Desinteressante| ○ ○ ○ ○ ○ ○ ● ○ ○ ○                            | Interessante   |
| Convencional   | ○ ○ ○ ○ ● ○ ○ ○ ○ ○                            | Original       |
| Comum          | ○ ○ ○ ○ ● ○ ○ ○ ○ ○                            | Vanguardista   |


## **USUÁRIO 3:**
|                |                                                |                |
|----------------|------------------------------------------------|----------------|
| Obstrutivo     | ○ ○ ○ ○ ○ ○ ○ ○ ○ ○                            | Condutor       |
| Complicado     | ○ ○ ○ ○ ○ ○ ○ ○ ○ ○                            | Fácil          |
| Ineficiente    | ○ ○ ○ ○ ○ ○ ○ ○ ○ ○                            | Eficiente      |
| Confuso        | ○ ○ ○ ○ ○ ○ ○ ○ ○ ○                            | Evidente       |
| Aborrecido     | ○ ○ ○ ○ ○ ○ ○ ○ ○ ○                            | Excitante      |
| Desinteressante| ○ ○ ○ ○ ○ ○ ○ ○ ○ ○                            | Interessante   |
| Convencional   | ○ ○ ○ ○ ○ ○ ○ ○ ○ ○                            | Original       |
| Comum          | ○ ○ ○ ○ ○ ○ ○ ○ ○ ○                            | Vanguardista   |

## **USUÁRIO 4:**
|                |                                                |                |
|----------------|------------------------------------------------|----------------|
| Obstrutivo     | ○ ○ ○ ○ ○ ○ ○ ○ ○ ○                            | Condutor       |
| Complicado     | ○ ○ ○ ○ ○ ○ ○ ○ ○ ○                            | Fácil          |
| Ineficiente    | ○ ○ ○ ○ ○ ○ ○ ○ ○ ○                            | Eficiente      |
| Confuso        | ○ ○ ○ ○ ○ ○ ○ ○ ○ ○                            | Evidente       |
| Aborrecido     | ○ ○ ○ ○ ○ ○ ○ ○ ○ ○                            | Excitante      |
| Desinteressante| ○ ○ ○ ○ ○ ○ ○ ○ ○ ○                            | Interessante   |
| Convencional   | ○ ○ ○ ○ ○ ○ ○ ○ ○ ○                            | Original       |
| Comum          | ○ ○ ○ ○ ○ ○ ○ ○ ○ ○                            | Vanguardista   |

------

Com essa análise detalhada das métricas e da experiência dos usuários, podemos identificar claramente áreas que necessitam de melhorias no site, tanto em termos de acessibilidade quanto de usabilidade, visando proporcionar uma navegação mais fluida e inclusiva para todos os perfis de usuários.


