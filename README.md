# Forge Crater - SERVER-SIDE (Fabric, Minecraft 1.21.11)

Put the jar + Fabric API (0.141.1+1.21.11) in the SERVER's mods folder. Players need NOTHING installed.

## Get the Forge Shard
Craft it (amethyst shard / diamond ring around a nether star), or as an op run:

/give @s minecraft:echo_shard[custom_name={text:"Forge Shard",color:"aqua",italic:false},custom_data={forge_shard:true},enchantment_glint_override=true,max_stack_size=1,use_cooldown={seconds:20,cooldown_group:"forge_crater:forge_shard"}]

## Use
Hold it, aim at the ground (up to 96 blocks) and right-click. 20 second cooldown.

## Tweak
ForgeCraterMod.TARGET_RANGE / COOLDOWN_TICKS, CraterManager.RADIUS, CraterEvent.CHARGE_TICKS / CARVE_TICKS.

## Build the jar (GitHub)
Upload this folder (incl. hidden .github) to a NEW GitHub repo -> Actions -> "Build jar" -> download artifact forge-crater-jar.
