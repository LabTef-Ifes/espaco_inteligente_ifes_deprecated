**Observação:** Esta é uma versão desatualizada (porém funcional) do espaço inteligente do Ifes Vitória. Decidimos manter esta versão em nosso repositório para eventuais consultas. O repositório mais atualizado pode ser encontrado [aqui](https://github.com/LabTef-Ifes/espaco_inteligente_ifes).

# ESPAÇO INTELIGENTE - IFES - CAMPUS VITÓRIA

![Reconstrução tridimensional](https://github.com/wyctorfogos/ESPACOINTELIGENTE-IFES/blob/main/caminhada.gif)

Antes de tudo, instale as bibliotecas necessárias que se encontram descritas no arquivos requiremensts.txt através do comando 'pip install -r requirements.txt'.
Uma dica é utilizar o virtualenv, para que se tenha um espaço com todas as bibliotecas desejadas.

1. Suba os containeres (rode 'iniciar_principais_containeres.py' - inicia os containeres na ordem correta). Mude os volumes dos containeres de acordo com o seus diretórios.
2. No terminal digite '(sudo) docker ps' para verificar se os containeres estão de pé.
3. Mude o diretório dda pasta com os vídeos a serem analisads no arquivo 'options.json', na parte do folder.
4. Rode o arquivo principal 'export-video-3d-medicoes-erros-no-3d.py' na pasta data-creator para analisar o vídeo desejado

Em caso de dúvidas sobre os serviços e/ou outras questões, acesse: https://github.com/labviros, projeto original.
