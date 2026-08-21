- Add 2 (potentially 4, depending on variants) new cheese options. These would be two versions of herb and spice cheese each.
- Basically, in a barrel, you would mix cottage cheese with either herbs or spices, turning it into a new liquid type specifically. You would then press that like in vanilla to get a new type of chees
- Lastly, you could interact with a ripe wheel of cheese and cover it in herbs, adding extra satiety. (In world right click interaction)

**Required code**

- Harmony? patches for the Linen class, as pressing the cheese is hardcoded, so that it checks if the barrel is filled with regular curdled milk, an herb variant, or a spice variant, which then produces the according cheese wheel
- Slicing the cheese with a knife is hardcoded and not done in JSON. So, the code needs to decide what piece of cheese to give out
- Not sure if this would be done in JSON or code, but once you have ripened cheese, maybe you can right click it to rind/cover it with some herbs, adding extra satiety.