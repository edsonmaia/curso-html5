# Curso de HTML 5

## Áudio e Vídeo em HTML5

* Formatação css do perfil.html e projetos.html

## Tags utilizadas
* audio
* video

### Propriedades ou Atributos
* src
* type
* conntrols
* autoplay
* muted
* width
* height

## types
* audio/ogg
* audio/mpeg
* video/mp4
* video/ogg

### Áudio
~~~html
<audio controls>
  <source src="midia/safety_net_riot.ogg" type="audio/ogg">
  <source src="midia/safety_net_riot.mp3" type="audio/mpeg">
Seu navegador não tem suporte para áudio.
</audio>
~~~

* Formatos aceitos: MP3, OGG e WAV.

### Vídeo
~~~html
<video width="320" height="240" controls> <!-- autoplay muted -->
  <source src="midia/jogo-com-acessibilidade.mp4" type="video/mp4">
  <source src="midia/jogo-com-acessibilidade.ogg" type="video/ogg">
Seu navegador não tem suporte para vídeo.
</video>
~~~

* Formatos aceitos: MP4, OGG e WEBM.

## Por que colocar duas ou mais tags source?

* Caso o seu navegador não tenha suporte para uma extensão ou não consiga carregar um arquivo ele irá procurar o próximo.

## Links de referências
<https://www.w3schools.com/html/html5_audio.asp>
<https://www.w3schools.com/html/html5_video.asp>

