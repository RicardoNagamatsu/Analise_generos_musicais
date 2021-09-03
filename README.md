# Analise_generos_musicais

Projeto de classificação de gêneros musicais realizado ao final do módulo de Dados Não Estruturados em linguagem Python.

Projeto de Áudio
Introdução
A Letsound é um serviço de streaming de música aberto para qualquer produtor musical
importar e compartilhar suas músicas na internet. Devido ao alto volume de uploads, ficou difícil
fazer uma classificação manual dos gêneros que são utilizados para os algoritmos de
recomendação, assim, a Letsound os contratou para montar, preparar o dataset para serem
usados no processo de treinamento dos modelos.
Objetivo
Montar o pipeline para pré processamento dos arquivos de áudio que serão usados para treino
e teste nos modelos de classificação de gênero musical. Não será trabalhado o modelo, e sim,
somente o pré processamento
O que é para fazer
1) Baixar o mini dataset http://opihi.cs.uvic.ca/sound/mini-genres.tar.bz2 que contém uma
amostra de diferentes gêneros de música
2) Carregar os áudio com um limite de 10s por arquivo
3) Montar os scripts para extrair as seguintes features (hop_len e n_fft, podem manter padrão):
- Espectrograma em escala logaritmica de todos os áudios (figura)
- Espectrograma da escala de mel (MFCC) para n_mcc=13 (figura)
- Chroma feature (figura)
Dataset
http://opihi.cs.uvic.ca/sound/mini-genres.tar.bz2
