# dnd-attr-charts

## Description
The purpose of this tool is to provide a clean and easy way to visually and get a description of a character attributes from roll20. works with NPC's  and PC's alike
 
### Macro for roll20 5th Edition OGL Sheet.

```
&{template:default} {{name=@{selected|token_name}}} {{Attr Chart=[Attribute Chart](https://guillapre.github.io/dnd-attr-charts/?name=@{selected|token_name}&level=@{selected|class_display}@{selected|npc_type}&attributes=@{selected|strength}+@{selected|dexterity}+@{selected|constitution}+@{selected|intelligence}+@{selected|wisdom}+@{selected|charisma}&npc=@{selected|npc}&skills_player=@{selected|athletics_bonus}+@{selected|acrobatics_bonus}+@{selected|sleight_of_hand_bonus}+@{selected|stealth_bonus}+@{selected|arcana_bonus}+@{selected|history_bonus}+@{selected|investigation_bonus}+@{selected|nature_bonus}+@{selected|religion_bonus}+@{selected|animal_handling_bonus}+@{selected|insight_bonus}+@{selected|medicine_bonus}+@{selected|perception_bonus}+@{selected|survival_bonus}+@{selected|deception_bonus}+@{selected|intimidation_bonus}+@{selected|performance_bonus}+@{selected|persuasion_bonus}&skills_npc=@{selected|npc_athletics}+@{selected|npc_acrobatics}+@{selected|npc_sleight_of_hand}+@{selected|npc_stealth}+@{selected|npc_arcana}+@{selected|npc_history}+@{selected|npc_investigation}+@{selected|npc_nature}+@{selected|npc_religion}+@{selected|npc_animal_handling}+@{selected|npc_insight}+@{selected|npc_medicine}+@{selected|npc_perception}+@{selected|npc_survival}+@{selected|npc_deception}+@{selected|npc_intimidation}+@{selected|npc_performance}+@{selected|npc_persuasion})}}
```

## Setting up and using the macro:
![Installing Macro](https://media.discordapp.net/attachments/779505441985789974/787376317406380032/C44jP99Fop.gif?width=1338&height=675)

## What we use?
The webpage is made with bootstrap 5, a simple JavaScript code and Plotly to make the chart.
We also used the attributes descriptions found on [this reddit thread](https://www.reddit.com/r/dndnext/comments/81cras/dd_ability_score_ranges_described/). 

If you want you can check those out.

https://www.reddit.com/r/dndnext/comments/81cras/dd_ability_score_ranges_described/

https://plotly.com/javascript/

https://getbootstrap.com/

## Example
[![Aeda's Braarzyer's Macro](https://media.discordapp.net/attachments/779505441985789974/787367085327253534/unknown.png)](https://guillapre.github.io/dnd-attr-charts/?name=Aeda%27s%20Braarzyer%27s&level=Path%20of%20the%20Ancestral%20Guardian%20Barbarian%204&attributes=20+20+20+13+10+10&npc=0&skills_player=7+5+5+5+1+3+3+1+1+0+0+0+2+0+0+2+0+2&skills_npc=5+5+5+5+1+1+1+1+1+0+0+0+0+0+0+0+0+0)

![you can also SPIN THE GRAPH](https://media.discordapp.net/attachments/779505441985789974/787365685105131540/iHoToKNwNI.gif)
![the skills graph as well!](https://media.discordapp.net/attachments/779505441985789974/787365675503976498/MeNQcxHNJu.gif)
#### Double click the graphs to return to default positions
![roll20 in game macro](https://cdn.discordapp.com/attachments/722006558317215841/786004986340704306/msedge_5HiDZlIGdL.png)



## Final considerations 
If this project helps you, you can give me a cup of coffee :P

[![Donate](https://img.shields.io/badge/Donate-PayPal-green.svg)](https://www.paypal.com/donate?hosted_button_id=H2JKXRTGJUG26)
