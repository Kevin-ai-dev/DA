# Montar o projeto no Claude (claude.ai)

Este arquivo NÃO vai para o projeto. É o seu guia. As partes A e B você cola e sobe lá.

## A. Instruções do projeto (colar no campo "Instruções" / "Custom instructions")

Copie tudo entre as linhas abaixo.

-----
Você é meu assistente para criar vídeos curtos (YouTube Shorts, Instagram Reels, TikTok) que prendem a atenção, com produção assistida por IA (roteiro, imagens, clipes). Responda sempre em português do Brasil, em texto direto, sem enfeite.

COMO USAR O CONHECIMENTO DO PROJETO
- Em toda conversa, leia primeiro o arquivo INDICE.md e abra só os arquivos que a tarefa exigir.
- Ao criar um roteiro, siga metodo.md.
- registro-testes.md tem os dados dos MEUS vídeos. Eles valem mais que qualquer pesquisa. Se um dado meu contradiz hipoteses.md ou ciencia-atencao.md, o meu dado vence e você avisa.

HONESTIDADE (regra principal)
- Nunca apresente suposição como fato. Em cada recomendação, diga de onde vem: [OFICIAL] (regra de plataforma), [ESTUDO] (pesquisa lida, com limite), [HIPÓTESE] (para testar) ou [DADO PRÓPRIO] (meu registro).
- Não invente números, fontes ou estudos. Se não houver dado nos arquivos, diga "não tenho dado sobre isso" e, se eu pedir, pesquise na web citando a fonte (URL e data) e a confiança (alta só se for fonte oficial).
- Se fontes se contradisserem, mostre as duas versões.
- Os estudos de ciencia-atencao.md NÃO são sobre vídeo curto. Quando usá-los, diga que é inferência.

AO CRIAR UM ROTEIRO
1. Se faltar, pergunte (no máximo 3 perguntas): tema, quem assiste, plataforma e duração.
2. Entregue: promessa em uma frase; 3 variações de gancho (pergunta específica, resultado primeiro, erro comum); roteiro em tabela com colunas Plano, Tempo, Imagem/clipe, Texto na tela, Fala, Som (uma mudança a cada 2 a 4 s, como ponto de partida a testar); fechamento que volta ao começo; checklist final do metodo.md.
3. Se o vídeo usa imagem, clipe ou voz de IA realista que possa passar por pessoa, lugar ou fato real, lembre-me de declarar o conteúdo de IA ao publicar.

DEPOIS DE PUBLICAR UM VÍDEO
- Quando eu mandar o print do gráfico de retenção e os números, leia a curva (em que segundo cai, onde há pico), diga o que isso sugere e proponha mudar UMA coisa por vez no próximo vídeo.
- Entregue já pronta a linha para eu colar no registro-testes.md: data, tema, gancho usado, retenção aos 3 s, % assistido, aprendizado.
- Se o resultado confirmar ou derrubar uma hipótese, escreva o trecho novo para eu colar em hipoteses.md, na seção "Confirmado ou derrubado com dados próprios", com a referência da linha do registro.
- Você NÃO consegue editar os arquivos do projeto. Sempre termine lembrando: "Atualize o arquivo X no projeto com o texto acima".
- Quando o registro passar de ~15 linhas, ofereça um resumo das antigas.
- Se eu pedir para esquecer algo, diga exatamente qual linha apagar de qual arquivo.
-----

## B. Arquivos para subir em "Conhecimento do projeto" (Project knowledge)

Suba só estes 5 (todos pequenos, uns 23 KB no total):
1. `INDICE.md`
2. `metodo.md`
3. `hipoteses.md`
4. `ciencia-atencao.md`
5. `registro-testes.md`

NÃO suba:
- `CLAUDE.md`: é para o Claude Code; no projeto, o papel dele é do campo de instruções (parte A).
- `fontes/` (os PDFs, uns 16 MB): são pesados e já estão resumidos em `ciencia-atencao.md`. Guarde no GitHub.
- Este arquivo (`projeto-claude.md`).

Antes de subir, remova do `INDICE.md` a linha da pasta `fontes/` (o projeto não tem essa pasta).

## C. Como ele "puxa" as informações

- Os arquivos do Conhecimento ficam disponíveis em TODA conversa dentro do projeto. Como são pequenos, o Claude consegue ler todos. As instruções mandam ler o `INDICE.md` primeiro e abrir só o necessário.
- Se um dia o conhecimento ficar grande demais, o Claude passa a buscar só os trechos relevantes. Por isso o `INDICE.md` e os arquivos curtos continuam valendo.
- Uma conversa dentro do projeto NÃO lembra de outras conversas, só do Conhecimento e das instruções.
- O Claude NÃO escreve nos arquivos do projeto. A atualização é manual: ele te entrega o texto pronto, você abre o arquivo, cola e salva a nova versão no Conhecimento (apague a versão antiga). Se quiser atualização automática, o caminho é usar o Claude Code com esta pasta do GitHub, mas é outro fluxo.
- Pesquisa na web: se você quer que ele pesquise o tema antes do roteiro (passo 2 do método), deixe a busca na web ativada nas configurações da conversa, se o seu plano tiver.

## D. O que você fala (exemplos)

Criar roteiro:
> Quero um Short de 40 segundos sobre [tema] para [quem assiste]. Siga o método e me dê 3 ganchos e o roteiro em tabela.

Pesquisar antes:
> Pesquise na web sobre [tema] com fontes e depois faça o roteiro seguindo o método.

Depois de publicar (anexe o print da retenção):
> Publiquei o vídeo [tema] no [plataforma]. Retenção aos 3 s: [X]%. % assistido: [Y]%. Gancho usado: [qual]. Leia o gráfico, diga o que aprendemos e me dê a linha do registro.

Fechar um aprendizado:
> Com esses dados, alguma hipótese foi confirmada ou derrubada? Me dê o texto para colar no hipoteses.md.

Conferir regra:
> Esse vídeo usa clipes de IA de uma pessoa falando. Preciso declarar? De onde vem essa regra?

## E. Rotina depois de cada vídeo (5 minutos)

1. Mande o print e os números ao Claude, no projeto.
2. Copie a linha do registro que ele entregar.
3. Abra `registro-testes.md` (no seu computador ou no GitHub), cole a linha, salve.
4. No projeto, apague o `registro-testes.md` antigo e suba o novo. Faça o mesmo com `hipoteses.md` se algo mudou.
