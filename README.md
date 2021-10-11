# R3F-AST-Editor

GUI editors should only be editing initial state, and object-logic. Since, once the Game/experience begins running, the logic/interaction determines everything else.

So AST transformations are held primarily as JSON data, that gets translated to AST, then React Code.

So with unsaved changes, you can still preview using updates made as JSON, manually loaded through useState code. Then when saved/exported, can be loaded as R3F output code. 
