

# `[WIP]` Valve Hammer

## GERAL

### SKY

Map > Map Properties > Skubox TextureName > [paste]
* https://developer.valvesoftware.com/wiki/Skybox_(2D)
* https://developer.valvesoftware.com/wiki/Counter-Strike:_Global_Offensive_Sky_List

add env_fog_controller
* https://developer.valvesoftware.com/wiki/Env_fog_controller


### LEAKS ERROR

LoadPortals: couldn't read c:\users\roger\dropbox\rio2\maps\de_rio\de_rio_001.prt


### ENTIDADES

como criar ponto

como criar brush / textura a usar

Propriedades: shortcuts / double-click na view 3D / second click na view 2D

prop_physics / prop_static

- se prop_physics nao aparecer no mapa, verifique se tem este erro no console e troque por prop_static
prop_physics at 1632 2240 137 uses model models/props_foliage/urban_tree_giant01_small.mdl, which has no propdata which means it must be used on a prop_static. DELETED.

- Para encontrar uma entidade

Map > Entity Report
* https://developer.valvesoftware.com/wiki/Hammer_Entity_Report_Dialog


## DICAS

- Tools > Options > 2D Views > Default to 15 degree rotations

- Centralizar views no object selectionado

```
View > Center Views on Selection ou CTRL+E
```


- GROUPS

https://developer.valvesoftware.com/wiki/Grouping_and_VisGrouping

```
Seleciona objetos
Segure CTRL para selecionar multiplos
CTRL+G para AGRUPAR
CTRL+U para DESAGRUPAR
```


- VISGROUPS

```
VisGroups window > Edit > Name > New Group
Select objects
View > Move selection to VisGroup > "Place objects in existing VisGroup" > Select VisGroup > OK
VisGroups window > User > Check/uncheck VisGroup
```



