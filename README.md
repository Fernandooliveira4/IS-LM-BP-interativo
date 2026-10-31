# IS-LM-BP interativo

Gráficos interativos de macroeconomia, em HTML puro (basta abrir no navegador).

- `is_lm.html`: modelo IS-LM de economia fechada, com um gráfico embaixo no mesmo eixo de renda. Esse gráfico pode ser a OA-DA (nível de preços) ou a IS-LM-PC (inflação, Blanchard 7ª ed.), escolhida no seletor *Gráfico de baixo*. Na IS-LM-PC, o banco central escolhe o juro real (LM horizontal), a curva de Phillips dá a inflação e o controle θ define se as expectativas são ancoradas ou seguem a inflação passada. Há um gráfico da trajetória no tempo, botões para avançar períodos e levar r ao juro natural, e choques prontos (consolidação fiscal, alta do petróleo e desancoragem das expectativas).
  - Na OA-DA, a oferta agregada pode ser keynesiana (horizontal, preços fixos), do Blanchard (curto prazo positivamente inclinada e médio prazo vertical em Yₙ, com o botão "Avançar um período" ajustando as expectativas de preço até a economia voltar ao produto natural) ou clássica (vertical).
- `is_lm_bp.html`: IS-LM com economia aberta (IS-LM-BP / Mundell-Fleming). Câmbio flutuante, fixo ou sem ajuste; mobilidade de capital nula, baixa, alta ou perfeita. Mostra o ponto de partida, o impacto antes do ajuste (E′) e o resultado.

Nos dois HTMLs, o seletor *Simulador | Teoria* no topo abre um resumo da teoria do modelo: ideia central, hipóteses, equações, resultados, limitações e referências (Blanchard para o IS-LM e a OA-DA; Mankiw e os artigos de Mundell e Fleming para o IS-LM-BP). O endereço terminado em `#teoria` abre direto nessa aba.

## Versões

Cada versão salva recebe um número (v1.0.0, v1.0.1, v1.1.0…) e fica registrada no [CHANGELOG](CHANGELOG.md) e na aba *Tags* do GitHub.

- **Salvar uma versão:** depois de alterar algum arquivo, dê dois cliques em `salvar-versao.bat`. Ele mostra o que mudou, pergunta o tipo de mudança e uma descrição, e envia tudo para o GitHub.
  - 1 = pequena correção → v1.0.**1**
  - 2 = novidade → v1.**1**.0
  - 3 = mudança grande → v**2**.0.0
- **Ver uma versão antiga:** dê dois cliques em `abrir-versao.bat` e escolha a versão. Ela é aberta na pasta `versoes-antigas`, sem mexer nos arquivos atuais. Para voltar a ela, copie os arquivos de lá por cima dos atuais e salve uma versão nova.
