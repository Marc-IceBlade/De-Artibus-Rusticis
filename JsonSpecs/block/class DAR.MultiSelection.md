Alows the block to have multiple selection/interaction boxes, defined in the shape file

Required attributes:
- `selectionBoxes : Array[string]` -> Selection box ids
	Ids can be either:
	- a name of a shape **element** ~={comment}// Can be an empty box=~
	- `@n` where `n` is an index of a block selection box