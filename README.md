# EbacProject

Developed with Unreal Engine 5.5.4

Project created on the Ebac's classes. Its purpose is to learn about the engine and take on new development challenges



Optimizations implemented on the scripts ABP\_Player, BP\_ThirdPersonCharacter\_Player, and other scripts, by creating new variables instead of using multiple casts in a BP

Optimizations implemented on the meshes SM\_Bush and SM\_Chair, both of which are used as interactable items, by changing their number of LODs from 1 to 4, as shown in the images BeforeLOD1, BeforeLOD2, AfterLOD1, AfterLOD2

Comparando os resultados no Unreal Insights, em BeforeOptimization e AfterOptimization, essas mudanças não pareceram ter nenhum impacto significante, fora uma pequena melhora na renderização durante alguns frames.

