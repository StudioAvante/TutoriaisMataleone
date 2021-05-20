
# `[WIP]` CS:GO Overviews / Raadar

https://developer.valvesoftware.com/wiki/Creating_a_working_mini-map
https://github.com/18swenskiq/CS-GO-Auto-Radar

# TAR / CS:GO Auto Radar
https://github.com/18swenskiq/CS-GO-Auto-Radar
- Install TAR 2.5
- Criar visgroup: tar_layout
- adicionar tudo o que vai aparecer no radar a este visgroup
- no menu de compilacao, vai aparecer uma nova configuracao: [TAR] Generate Radar
- roda esta configuracao, ele vai criar os arquivos...

```
C:\SteamLibrary\steamapps\common\Counter-Strike Global Offensive\csgo\
resource\overviews\de_rio_001.txt
resource\overviews\de_rio_001_radar.dds
```

Opcional...
- Criar entidade tar_min no chao mais baixo do mapa
- Criar entidade tar_max no chao mais alto do mapa
- Criar entidade tar_config
- Trocar Color Scheme para Custom Scheme
  - agora vai usar as cores Custom Low/Middle/High Level Color
- Ou usar o Color Scheme para Use auto-gradient entities
- E criar entidades tar_color onde sedeseja que tenha uma cor especifica



### GIMP DDS Plugin
https://github.com/pixlsus/registry.gimp.org_static/tree/master/registry.gimp.org/files/gimp-dds-*



### CS GO Radar Maker (???)

https://refilenter.wordpress.com/2016/03/05/csgo-radar-maker/

https://gamebanana.com/tuts/11983
- Instalar JAVA (win 64 offline)

https://www.java.com/en/download/manual.jsp
- CS:GO options: `-novid -windowed -w 1024 -h 1024`
- seguir tutorial
- Tirar screenshot, guardar infos do console
- Instalar DDS GIMP
- abrir TGA no GIMP
- Export > Select File Type > DDS > compression: BC1/DXT1
- MAPA NAO CARREGA NO CS!!!!

Tutorial
https://www.youtube.com/watch?v=SSheuw9ASuM

JPG to DDS (nao tentei)
http://www.easy2convert.com/jpg2dds/


