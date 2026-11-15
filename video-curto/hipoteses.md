# Hipóteses para testar (pesquisa em 15/11/2026, atualizada na 2ª rodada)

Fonte oficial lida: YouTube Ajuda (4 páginas). TikTok Ajuda abre vazio (página montada por JavaScript) e Instagram/Meta não foi liberado. O resto vem de blogs e resumos de busca.
Itens marcados [OFICIAL] são regra ou definição da plataforma. Todo o resto é "para testar". Confiança: média = várias fontes concordam; baixa = fonte isolada ou sem método.

## Gancho (0 a 3 s)
- Os primeiros 3 a 5 s teriam peso dominante na distribuição. Blogs atribuem isso a TikTok e YouTube sem citar página; não achei isso nas páginas oficiais do YouTube. Confiança: baixa. https://dev.to/bulkdl/hook-engineering-the-science-of-the-first-3-seconds-in-short-form-video-2026-2jp9
- [OFICIAL] YouTube mede o gancho de Shorts assim: "Stayed to watch" = % das vezes em que o espectador ficou além dos segundos iniciais. O número de segundos NÃO é informado na página. https://support.google.com/youtube/answer/12220281
- [OFICIAL] O app do YouTube tem o botão "Get feedback" ao subir um Short, que analisa gancho e ritmo. Vale usar como segunda opinião (não foi testado). https://support.google.com/youtube/answer/10059070
- Tipos de gancho citados por blogs: curiosidade, afirmação polêmica, identificação com a dor, promessa de resultado, quebra visual. Sem estudo que ranqueie. Confiança: média (lista) / sem dado (ranking). https://www.sendible.com/insights/video-hook-ideas
- Texto grande e movimento nos 2 primeiros segundos aumentariam a retenção de 3 s (blog fala em até 50%, sem método). Confiança: baixa. https://nestscale.com/?p=47200
- Números soltos ("65% saem em 3 s", "taxa de gancho média 25-30%") vêm de blogs sem método. NÃO usar como meta.

## Retenção: como ler
- [OFICIAL] Formas da curva (YouTube, relatório de momentos-chave): linha plana = assistiram aquele trecho do começo ao fim; declínio gradual = perda de interesse ao longo do tempo (vídeos em geral decaem); pico = trecho mais assistido, revisto ou compartilhado (ou conteúdo confuso que precisou ser revisto); queda = abandono ou pulo naquele ponto. https://support.google.com/youtube/answer/9314415
- [OFICIAL] Limites do relatório de momentos-chave: o vídeo precisa ter pelo menos 60 s e 100 views. Para Shorts curtos pode não aparecer; conferir no Studio. Dados levam 1 a 2 dias para processar. Mesma página.
- [OFICIAL] "Retenção típica" compara com seus 10 últimos vídeos de duração parecida; "SEE MORE" compara com vídeos do YouTube de duração parecida. Mesma página.
- [OFICIAL] "Intro" = % que ainda assistia após 30 s (feito para vídeos longos). Para Shorts, a métrica é "Stayed to watch". Mesma página.
- [OFICIAL] Contagem de views em Shorts mudou em 31/03/2025: toda vez que começa ou repete conta, sem tempo mínimo. A métrica antiga virou "Engaged views" (ficaram além dos segundos iniciais, sem contar loops). Remuneração e elegibilidade usam as visualizações engajadas. https://support.google.com/youtube/answer/10059070
- [OFICIAL] "Duração média de visualização" = média de minutos assistidos entre quem ficou (viu além dos segundos iniciais). https://support.google.com/youtube/answer/12220281
- Corrige a 1ª rodada: a fonte que dizia que Shorts "não têm curva" estava parcialmente certa. Há "Stayed to watch" como número único; a curva depende do tamanho do vídeo (regra de 60 s acima). Conferir no seu Studio com um print.
- Não existe benchmark oficial para "stayed to watch". Metas como "70%+" vêm de criadores. Comparar com os próprios vídeos.
- TikTok: métricas citadas por guias: tempo médio assistido, taxa de conclusão, replays, curva por vídeo. Sem fonte oficial lida. Confiança: baixa. https://buffer.com/library/tiktok-analytics/
- Instagram Insights: sem resposta (domínio não liberado).

## Ritmo e cortes
- Blogs divergem: nova mudança visual a cada 1,5-2 s, 2-3 s, 3-4 s ou 5-7 s. Sem método. O `metodo.md` usa 2-4 s como ponto de partida; é hipótese. Confiança: baixa. https://blitzcutai.com/blog/3-second-rule-tiktok-jump-cuts
- Ritmo variado (calmo alternado com rajadas de cortes) tenderia a vencer taxa fixa. Confiança: baixa. https://autoclip.dev/glossary/clip-pacing
- Tirar trechos "mortos" é recomendação comum. Confiança: média. Base científica geral em `ciencia-atencao.md`.

## Loops de curiosidade e estrutura
- Base científica lida (ver `ciencia-atencao.md`): curiosidade surge de uma lacuna de informação reconhecida; é maior com lacuna intermediária e algum conhecimento prévio; adivinhar com retorno aumentou a curiosidade em laboratório; a curiosidade some se a atenção é desviada. São estudos com texto/perguntas, não vídeo. Para testar: gancho com uma lacuna específica e pagamento rápido.
- Abrir UMA pergunta cedo e fechar no fim. Confiança: média. https://faceless.so/blog/story-structures-for-short-form-video
- Fechamento em loop (última frase completa a primeira, ou último visual repete o primeiro). Confiança: média (técnica) / baixa (efeito). https://faceless.so/blog/looping-short-videos-tutorial-story-seamless-loops
- [OFICIAL] O YouTube não conta loops nas "Engaged views". Um loop pode render replays, mas não necessariamente views engajadas. Implica: medir o efeito do loop em tempo médio assistido e % assistido, não só em views.
- Efeitos citados ("35% vs 12%", "rewatches de 4% para 21%") vêm de fornecedor ou post anedótico. Não usar como meta.

## Formato técnico
- [OFICIAL] Shorts do YouTube: até 3 minutos; vídeo vertical; resolução máxima 1080p ao subir; título com até 100 caracteres. https://support.google.com/youtube/answer/10059070
- Para TikTok e Reels, durações: fontes de blog conflitam (Reels 90 s ou até 20 min; TikTok 10 a 60 min). Sem página oficial lida. Confiança: baixa. https://blckalpaca.at/en/knowledge-base/social-media/social-media-content-creation-formats/instagram-reels-format-shorts-tiktok-specs
- 9:16 / 1080x1920 / MP4 é a base comum citada por blogs. Confiança: média. https://blitzcutai.com/blog/social-video-specs-2026
- Zonas seguras: sem número oficial confirmado (blogs: ~210 px topo, ~270 px base). Manter texto e rosto no centro. Confiança: baixa.
- Legendas queimadas no vídeo: recomendação comum. Confiança: baixa.

## Regras de plataforma para conteúdo com IA
- [OFICIAL] YouTube exige declarar ("AI use", no upload, em Atributos) conteúdo gerado ou alterado por IA que pareça realista: (1) pessoa real dizendo ou fazendo algo que não fez; (2) imagem alterada de evento ou lugar real; (3) cena realista que não aconteceu; (4) música gerada por IA que é o foco do vídeo. https://support.google.com/youtube/answer/14328491
- [OFICIAL] NÃO precisa declarar: conteúdo claramente irreal (ex.: unicórnio em mundo fantástico), edições pequenas (filtros, cor, desfoque), apoio de produção (roteiro, esboço, título, miniatura, infográfico com IA), legendas, upscaling/reparo de imagem ou áudio, ideias, clonar a própria voz para narração ou dublagem, cenário de fundo gerado ou estendido. Mesma página. Isso cobre roteiro e voz próprios que você usa; clipes realistas de IA mostrando pessoas, lugares ou fatos reais exigem declaração.
- [OFICIAL] Rótulo no player para música ou conteúdo fotorrealista; na descrição expandida para áudio não musical ou conteúdo animado/não fotorrealista. Declarar sozinho não limita audiência nem a monetização. Mesma página.
- [OFICIAL] O YouTube pode rotular sozinho: conteúdo feito com ferramentas de IA do YouTube, com metadados C2PA ou detectado pelos sistemas internos. Você recebe aviso no Studio. Pode contestar na maioria dos casos, exceto ferramentas do YouTube, C2PA e revisão manual. Mesma página.
- [OFICIAL] Quem não declara de forma recorrente pode ter rótulo manual, remoção de conteúdo ou suspensão do Programa de Parcerias. Mesma página.
- Divergência: imprensa especializada (mai/2026) descreve rótulo único sobreposto em Shorts; a página oficial lida diz rótulo no player (música/fotorrealista) ou na descrição. Conferir no Studio ao publicar. https://www.techwyse.com/news/platform-updates/youtube-automatic-ai-labels-disclosure-may-2026
- TikTok: guias dizem que exige rotular IA realista e que o rótulo automático não sai. Sem página oficial lida. Confiança: baixa. https://blog.hootsuite.com/ai-disclosure-policy-for-tiktok/
- Instagram/Meta: "AI info" ao publicar ou automático; rótulo de perfil "AI-generated profile" em 2026. Sem página oficial lida. Confiança: baixa. https://techspot.com/news/113695-instagram-cracks-down-ai-accounts-pretending-human.html
- Conduta provisória: rotular sempre que imagem, clipe ou voz puder passar por pessoa, lugar ou fato real.

## Diferenças entre Shorts, Reels e TikTok
- Só há consenso no 9:16. Diferenças de duração, alcance e distribuição não foram confirmadas fora do YouTube. https://www.shortimize.com/blog/compare-watch-time-tiktok-vs-reels-vs-shorts

## Sem resposta (próximas pesquisas)
- TikTok Ajuda e Meta: a página do TikTok carrega por JavaScript e não abre por download simples; liberar `help.instagram.com` e `creators.instagram.com` ou trazer prints/PDF.
- Artigos científicos completos: PubMed, PMC e Springer bloqueiam robôs (reCAPTCHA). Trazer os PDFs para a pasta.
- Quantos segundos o YouTube considera "segundos iniciais" em Shorts.
- Leitura da retenção no Instagram Insights e no TikTok Studio.
- Zonas seguras oficiais.

## Confirmado ou derrubado com dados próprios
(vazio por enquanto)
