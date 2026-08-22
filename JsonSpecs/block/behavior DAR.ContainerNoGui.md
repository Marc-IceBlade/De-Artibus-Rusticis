Allows for interaction with container inventory via selection boxes.
Best used with [[class DAR.MultiSelection|DAR.MultiSelection]] block class.

Required properties:
- `allowedCollectibleTags : Array[string]` -> List of collectible tags that are allowed to be inserted via interactions //The collectible has to have at least one of the tags defined in this list

Optional properties:
- `maxTransferAmount : Integer` -> Maximum amount of items inserted/extracted by a single interaction, default is 1