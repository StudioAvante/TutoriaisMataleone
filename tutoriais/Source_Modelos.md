
# `[WIP]` Modelos

## Criação de modelos

https://developer.valvesoftware.com/wiki/Model

* MDL = Arquivo de modelos usado pela Source Engine

Criados com o studiomdl
https://developer.valvesoftware.com/wiki/Studiomdl


## Usando Modelos

Modelos são adicionados ao mapa com uma destas entidades de ponto...

* `prop_static`: Ficam sempre parados, não saem do lugar, nem são animados. É a forma mais "barata" de se adicionar detalhes ao mapa.
  [source](https://developer.valvesoftware.com/wiki/Prop_static)

* `prop_dynamic`: Modelos animados
  [source](https://developer.valvesoftware.com/wiki/Prop_dynamic)

* `prop_physics`: Afetados pelo sistema de física do jogo, podem ser movidos, empurrados, quebrados, etc.
  [source](https://developer.valvesoftware.com/wiki/Prop_physics)


## Comandos úteis

```
# Recarrega modelos do disco
r_flushlod

# Liga/Desliga o nome do modelo na sua mira
r_drawmodelstatsoverlay 1
r_drawmodelstatsoverlay 0
```

![teste1](/images/source.gif)

![teste2][source]

![source]

[![teste2][source]](https://developer.valvesoftware.com/wiki/Prop_physics)

[![source]](https://developer.valvesoftware.com/wiki/Prop_physics)

[source]: /images/source.gif "Source Engine Doc"
