# Índice

- [Do que se trata](#do-que-se-trata)
- [Features](#features)
- [Tecnologias e ferramentas utilizadas](#tecnologias-e-ferramentas-utilizadas)
- [Como executar](#como-executar)
- [Estudos](#estudos)





# Do que se trata

Jogo Candy Crush simplificado baseado em um [tutorial no Youtube](https://youtu.be/pLS_l3fVnwA) do canal "Solution Code Android" incluindo melhorias, correções de bugs e documentação do projeto para a comunidade 





# Features:

Principais:
- [x] Tela de início
- [x] Pontuação do jogador
- [x] Layout dos doces
- [x] Evento de permutar doces
- [x] Evento de checar trios de doces nas linhas e colunas

Correções de bugs do tutorial:
- [x] PlayActivity.kt: linha 19 (Not enough information to infer type variable T)
- [x] MainActivity.kt: linha 198
- [x] OnSwipeListener.kt: linha 23
- [x] build.gradle: linha 37 e 42 
- [x] Sincronizar o gradle do projeto
- [x] Arrastar o doce para fora do intervalo

Melhorias:
- [ ] Criar sistema de fases
- [ ] Limitar a quantidade de jogadas para cada fase
- [ ] Ofecerer dicas ao jogador nas fases iniciais quando o mesmo levar muito tempo para acertar





# Tecnologias e ferramentas utilizadas:

Linguagens/Ferramentas | Uso                                    | Bibliotecas/frameworks
---------------------- | -------------------------------------- | ------------------------------------------------
`Kotlin`               | Layouts e lógica do jogo               | pl.droidsonroids.gif:android-gif-drawable:1.2.17 
`Android Studio`       | Codificação e versionamento do projeto |





# Como executar:

Clone o repositório utilizando o Android Studio e vá em `run` > `run app`





# Estudos:

Caso queira as fontes de estudo utilizadas para construir o projeto, basta acessar a pasta `resources`
