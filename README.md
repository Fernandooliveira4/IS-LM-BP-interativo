# IS-LM-BP interativo

Gráficos interativos de macroeconomia, em HTML puro (basta abrir no navegador).

- `is_lm.html`: modelo IS-LM de economia fechada.
- `is_lm_bp.html`: IS-LM com economia aberta (IS-LM-BP / Mundell-Fleming). Câmbio flutuante, fixo ou sem ajuste; mobilidade de capital nula, baixa, alta ou perfeita. Mostra o ponto de partida, o impacto antes do ajuste (E′) e o resultado.

## Versões

Cada versão salva recebe um número (v1.0.0, v1.0.1, v1.1.0…) e fica registrada no [CHANGELOG](CHANGELOG.md) e na aba *Tags* do GitHub.

- **Salvar uma versão:** depois de alterar algum arquivo, dê dois cliques em `salvar-versao.bat`. Ele mostra o que mudou, pergunta o tipo de mudança e uma descrição, e envia tudo para o GitHub.
  - 1 = pequena correção → v1.0.**1**
  - 2 = novidade → v1.**1**.0
  - 3 = mudança grande → v**2**.0.0
- **Ver uma versão antiga:** dê dois cliques em `abrir-versao.bat` e escolha a versão. Ela é aberta na pasta `versoes-antigas`, sem mexer nos arquivos atuais. Para voltar a ela, copie os arquivos de lá por cima dos atuais e salve uma versão nova.
