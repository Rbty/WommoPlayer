# White theme
![texto alternativo da imagem](https://media.discordapp.net/attachments/1075565638938009653/1092278486053421167/Captura_de_tela_2023-04-02_-_23.44.08.png?width=900&height=500)

# Black theme
![texto alternativo da imagem](https://media.discordapp.net/attachments/1075565638938009653/1092278486347038770/Captura_de_tela_2023-04-02_-_23.44.04.png?width=900&height=500)

[PT-BR] 

# OLÁ, ESSE É O MANUAL DE USO.

Os requisitos para utilizar a Wommo são: 

Ter o Python instalado (Sem ele você não vai conseguir instalar as bibliotecas)
Ter a biblioteca pytube (Disponivel no instalador de biblioteca (installlibrary))
Ter a biblioteca moviepy.editor (Disponivel no instalador de biblioteca (installlibrary))

Como usar?

A WommoDownloader.bat serve para você conseguir instalar as musicas diretas do youtube, elas ficaram armazenadas na pasta "Musics"
Abrindo A WommoPage.bat você consegue ter acesso ao player

Como apagar uma musica? 

Para conseguir apagar uma música você deverá seguir os seguintes passos:

Deletar o arquivo .mp3 da pasta "Musics"
Modifique o arquivo javascript, na primeira linha é apresentado a você a variavel "Sounds", você deverá apagar o
objeto da musica que você deseja deletar, exemplo:

 {titulo:'Paradise', src:'Musics/Coldplay - Paradise (Official Video).mp3'},


Obs: Não baixar musica que tenha pontuação no titulo

Obs²: Sempre que baixar uma nova musica lembre-se de reiniciar a pagina

Obs³: Se o player não estiver funcionando, verifique o script.js e apague o que precisar da variavel

-----------------------------------------------

[EN]

# HELLO, THIS IS THE USER MANUAL.

The requirements for using Wommo are:

Having Python installed (Without it you won't be able to install the libraries)
Having the pytube library (Available in the library installer (installlibrary))
Having the moviepy.editor library (Available in the library installer (installlibrary))

How to use?

The WommoDownloader.bat is used to install music directly from YouTube, which will be stored in the "Musics" folder.
By opening the WommoPage.bat, you can access the player.

How to delete a song?

To delete a song, you should follow these steps:

Delete the .mp3 file from the "Musics" folder.
Modify the javascript file. In the first line, you will see the variable "Sounds". You must delete the object of the song you wish to delete. Example:

{titulo:'Paradise', src:'Musics/Coldplay - Paradise (Official Video).mp3'},

Note: Do not download music that has punctuation in the title

Note²: Always remember to restart the page when you download a new song

Note³: If the player is not working, check the script.js file and delete what is necessary from the variable
