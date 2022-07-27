# Lisarbgh2 (dta)

Repositório para guardar o progresso do Lisarb GH2 - somente scripts "dta". Não vejo necessidade de guardar mudanças de outros arquivos (vgs,midi,imagens...)

## Anotações de scripts modificados 

**Nota: foi o usado o GH2 DELUXE 2.0, não a versão original, como jogo de base para a custom**

+ [config/campaign.dta](https://github.com/naonemeu/lisarbgh2/blob/main/ark/config/campaign.dta): Define a ordem das músicas principais **a partir do nome interno**. Como eu vou mudar todos os nomes internos, então preciso mudar aqui também (pra ter aquele extra que faz parecer oficial) 
+ [config/mc.dta](https://github.com/naonemeu/lisarbgh2/blob/main/ark/config/mc.dta): Muda o ID do jogo salvo (aquele que começa com SLUS...), para separar do GH2 oficial.
+ [config/modes.dta](https://github.com/naonemeu/lisarbgh2/commit/b1098375311a9ef794f03e6b47a4341e4c6cfda0) configurações de modo do jogo. Usado para habilitar o bot (obvio que vou usar isso somente para testes, daar...)
+ [config/songs.dta](https://github.com/naonemeu/lisarbgh2/blob/main/ark/config/songs.dta): definições das músicas, nome (interno e externo), metadados, balanço de audio..
+ [config/synth.dta](https://github.com/naonemeu/lisarbgh2/blob/main/ark/config/synth.dta): Usado para customizar os nomes dos metaloops (que são as músicas que tocam no menu). Esses "metaloops" devem ter um SR de 22050 Hz, 2 canais e (preferencialmente) duração de até 2 min / 3 MB, para não pesar muito no carregamento. Os arquivos de audio estão localizados em ark/sfx/streams (que não estão upados no github)
+ [ui/eng/locale.dta](https://github.com/naonemeu/lisarbgh2/blob/main/ark/ui/eng/locale.dta): textos principais do jogo, traduzido. falta revisar
+ [ui/init.dta](https://github.com/naonemeu/lisarbgh2/commit/ca6768b296a6ed3de7ab4e5bbf107ec7555d8faa) configura parâmetros iniciais do GH2. Usado para colocar hyperspeed e cores GRYBO
+ [ui/quickplay.dta](https://github.com/naonemeu/lisarbgh2/blob/main/ark/ui/quickplay.dta): Estrutura de seleção de instrumento, dificuldade... Modificado para desabilitar o baixo.

## Programas Usados

+ [Feedback](https://github.com/TurkeyMan/feedback-editor/tree/master/Builds): Usado para colocar as notas da chart. Na minha opinião, é mais rápido para colocar as notas do que o Moonscraper, porem é menos intuitivo. (eu usava o feedback muito tempo antes do Moonscraper existir, então era a minha única opção)
+ [Mackiloha](https://github.com/PikminGuts92/Mackiloha): Usado para extrair e recompilar o arquivo do GH2 "MAIN_0.ARK", que é o que contem praticamente tudo do jogo
+ [Moonscraper Chart Editor](https://github.com/FireFox2000000/Moonscraper-Chart-Editor): Usado para criar as charts (que são as notas que você toca no jogo). No **MEU CASO**, uso mais como um programa auxiliar para fazer a sincronia (BPM! porque toda chart precisa disso) e finalização.
+ [Reaper](https://reaper.fm/): Ajuste fino de charts em MIDI (formato usado pelo GH2)
+ [Notepad++](https://notepad-plus-plus.org/): Porque não é uma boa ideia usar somente o bloco de notas do Windows.
