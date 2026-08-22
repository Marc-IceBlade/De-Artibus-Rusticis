Attributes are similar to vanilla containers, like chests


Required attributes:
- `inventoryClassName : String` -> a "type" of the container ~={comment}//I don't exactly know what this does but is required for inventories, for example chest has "chest", cheese has "cheese"=~
- `quantitySlots : Integer` -> amount of slots, must be positive

Optional attributes:
- `stackSizeLimit : Integer` -> Maximum amount of items per slot ~={comment}//Not Yet Implemented=~
- `transitionSpeedMul : Dictionary[TransitionType > Float]` -> Multipliers for transition times
- `spoilSpeedMulByFoodCat : Dictionary[FoodCategory > Float]` -> Multipliers of `Perish` transition time based food type 