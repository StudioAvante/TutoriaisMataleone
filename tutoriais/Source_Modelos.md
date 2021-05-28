
# `[WIP]` Modelos

## Criação de modelos

https://developer.valvesoftware.com/wiki/Model

* MDL = Arquivo de modelos usado pela Source Engine

Criados com o studiomdl
https://developer.valvesoftware.com/wiki/Studiomdl


## Usando Modelos

Modelos são adicionados ao mapa com uma destas entidades de ponto...

* `prop_static` [![source]](https://developer.valvesoftware.com/wiki/Prop_static)
: Ficam sempre parados, não saem do lugar, nem são animados. É a forma mais "barata" de se adicionar detalhes ao mapa.

* `prop_dynamic` [![source]](https://developer.valvesoftware.com/wiki/Prop_dynamic) 
: Modelos animados

* `prop_physics` [![source]](https://developer.valvesoftware.com/wiki/Prop_physics)
: Afetados pelo sistema de física do jogo, podem ser movidos, empurrados, quebrados, etc.


## Comandos úteis

```
# Recarrega modelos do disco
r_flushlod

# Liga/Desliga o nome do modelo na sua mira
r_drawmodelstatsoverlay 1
r_drawmodelstatsoverlay 0
```

[source]: ../images/source.gif "Source Engine Doc"
