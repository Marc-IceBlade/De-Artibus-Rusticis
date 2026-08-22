### (Block) Drying rack:
- Block class: [[class DAR.MultiSelection|DAR.MultiSelection]]
- BlockEntity class: [[class DAR.GenericContainerNoGui|DAR.GenericContainerNoGui]]
- Block behaviors: 
	- [[behavior DAR.ContainerNoGui|DAR.ContainerNoGui]]
```json5
{  
    code: "test-rack",  
    class: "DAR.MultiSelection",
    entityClass: "DAR.GenericContainerNoGui",
    entityBehaviors: [{ name:  "DAR.GenericContainerNoGui" }],  
    behaviors: [{  
        name: "DAR.ContainerNoGui",  
        properties: {  
            allowedCollectibleTags: [ "flux" ]  
        }    
    }],    
    attributes: {  
        selectionBoxes: ["rope3", "rope4"],  
        inventoryClassName: "test_rack",  
        quantitySlots: 2,  
		transitionSpeedMul: {  
			dry: 8  
		}  
    },
    shape: {  
        base: "block/testing/woodherbrack",   
		rotateY: 90 // can be rotated
    },
    creativeinventory: { "general": ["*"] },  
}
```