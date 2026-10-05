UPS Concept V3
Principais melhorias:
- Alarmes com causa, efeito, relação possível e confirmação
- Cadeia plausível PSU → inversor → EA inibido
- Falha de terra CC tratada separadamente
- Simulador UPS 1 × UPS 2
- 6 cenários operacionais
- Quiz técnico com 12 questões
- Distinção entre bypass estático e bypass de manutenção
- PWA instalável

Para atualizar no GitHub Pages: substitua os arquivos do repositório pelos deste pacote e faça commit.

V3.1:
- Corrigido viés das respostas do quiz.
- Distribuição fixa balanceada: 3 respostas A, 3 B, 3 C e 3 D.
- Mantido o mesmo nível técnico e conteúdo das 12 questões.

V3.2:
- Embaralhamento automático da ordem das 12 questões a cada abertura/reinício do quiz.
- Embaralhamento automático das alternativas A/B/C/D em cada questão.
- Novo botão "Reiniciar quiz".
- Gabarito recalculado dinamicamente após o embaralhamento.
- Feedback técnico preservado após a correção.

V3.3:
- Adicionada seção "Diferença entre EA e EN".
- Adicionada seção "O que acontece se EA e EN estiverem ativos ao mesmo tempo?".
- Incluídas as consequências de sobreposição sincronizada e de condução simultânea inadequada.
- Quiz ampliado para 14 questões, com 2 novas perguntas sobre EA/EN e simultaneidade.

V3.4:
- Adicionado detalhamento completo do caminho do bypass.
- Incluído fluxo: rede de bypass → EN → barra de saída → carga.
- Explicado o que muda quando a carga está em bypass.
- Incluídas condições de transferência inversor → bypass e retorno bypass → inversor.
- Diferenciado bypass estático de bypass manual/manutenção.
- Quiz ampliado para 16 questões, com 2 novas perguntas de bypass.

V3.5:
- Adicionado circuito detalhado do lado do inversor.
- Adicionado circuito detalhado do lado do bypass.
- Descrita função e objetivo de cada item.
- Adicionada comparação direta entre os dois caminhos.
- Adicionado seletor visual de modos: Normal, Bateria, Bypass, Falha do inversor e Manutenção.
- Quiz ampliado para 18 questões.

V3.6:
- Removida a imagem/infográfico geral do topo da página, conforme solicitado.
- Removido o arquivo infografico-ups.png do pacote e do cache do PWA.
- Mantidos todos os conteúdos técnicos, simuladores, cenários, alarmes e quiz.
