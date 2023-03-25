---
{}
---
   
```mermaid
stateDiagram-v2
		[*] --> 1818
		note left of 1818
			Magnus Institute is founded
		end note
        1818 --> Still
        Still --> [*]
    
        Still --> Moving
        Moving --> Still
        Moving --> Crash
        Crash --> [*]

```
