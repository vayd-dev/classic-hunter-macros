# Vayd's Classic WoW Hunter Macros

# Auto Shot
```
#showtooltip Auto Shot
/cleartarget [dead][help]
/targetenemy [noexists]
/cast !Auto Shot
/startattack [harm,nodead]
```
# Hunter's Mark Mouseover
```
#showtooltip
/cast [@mouseover, harm][] Hunter's Mark
```
# Flare on Cursor
```
#showtooltip
/cast [@cursor] Flare
```
# Scatter Shout Mouseover
```
#showtooltip
/petpassive
/stopattack
/cast [@mouseover, harm][] Scatter Shot
```
# Trap
```
#showtooltip
/petpassive
/cast [nomod] Freezing Trap
/cast [mod:alt] Frost Trap
/cast [mod:shift] Explosive Trap
/cast [mod:ctrl] Immolation Trap
```
# Serpent Sting / Viper Sting
```
#showtooltip
#showtooltip
/cleartarget [dead][help]
/cast [nomod] Serpent Sting
/cast [mod:alt] Viper Sting
/cast !Auto Shot
```
# Chain Eagle Eye
```
#showtooltip
/cast !Eagle Eye
```
# Feign Death PvP
```
#showtooltip Feign Death
/petpassive
/stopattack
/cast [combat] Feign Death
/petpassive
```
# Feign Death PvE (Trinket Swap)
```
#showtooltip Feign Death
/stopattack
/petpassive
/cast [combat] Feign Death
/petpassive
/equipslot 13 Royal Seal of Eldre'Thalas 
/equipslot 14 Blackhand's Breadth
```
# Aspect of the Hawk / Cancel Cheetah
```
#showtooltip Aspect of the Hawk
/cancelaura Aspect of the Cheetah
/cast !Aspect of the Hawk
```
# Aspect of the Monkey / Cancel Cheetah
```
#showtooltip Aspect of the Monkey
/cancelaura Aspect of the Cheetah
/cast !Aspect of the Monkey
```
# Multi-Shot
```
#showtooltip Multi-Shot
/cast Multi-shot
/cast !Auto Shot
```
# Melee
```
#showtooltip
/cast Raptor Strike
/cast Wing Clip
/cast Mongoose Bite
/startattack
```
# Call Pet / Revive Pet / Mend Pet
```
#showtooltip Call Pet
/cast [nopet] Call Pet
/cast [@pet, dead] Revive Pet
/cast [@pet] Mend Pet
```
# Scare Beast Mouseover
```
#showtooltip
/cast [@mouseover, harm][] Scare Beast
```
# Pet Auto Feed
```
#showtooltip Feed Pet
/cast [pet, nodead] Feed Pet
/use [pet, nodead] Roasted Quail
```
# Scorpid / Food & Water
```
#showtooltip Scorpid Sting
/cast [combat] Scorpid Sting
/use Conjured Crystal Water
/use Conjured Sweet Roll
/use Alterac Manna Biscuit
```
# Tranq / Food & Water
```
#showtooltip Tranquilizing Shot
/cast [combat] Tranquilizing Shot
/use Conjured Crystal Water
/use Conjured Sweet Roll
/use Alterac Manna Biscuit
```
# 1h / Skull
```
/equipslot 16 Doom's Edge
/equipslot 17 Skull of Impending Doom
/cancelaura Flee
```
# 2h
```
/equipslot 16 Ashkandi, Greatsword of the Brotherhood
```
# Dual 1h's
```
/equipslot 16 Doom's Edge
/equipslot 17 Core Hound
```
# Totem Stomp
```
/petattack
/petattack [target=Fire Nova Totem]
/petattack [target=Grounding Totem]
/petattack [target=Poison Cleansing totem]
/petattack [target=Searing Totem]
/petattack [target=Earthbind Totem]
```
# Shadowmeld / Prowl
```
#showtooltip Shadowmeld
/cast [nostealth] Shadowmeld
/cast Prowl(Rank 1)
```
# Mount / Cancelauras
```
#showtooltip Reins of the Black War Tiger
/use Reins of the Black War Tiger
/cancelaura Flee
/cancelaura Horde Flag
/cancelaura Blessing of Protection
```
# Camera
```
/console cameraDistanceMaxZoomFactor 4
```
# Weather
```
/console WeatherDensity 0
```
