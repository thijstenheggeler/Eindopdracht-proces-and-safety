```plantuml
[*] --> Uit : Hoofdschakelaar

state Uit : Hoofdschakelaar uit\n Lamp uit
state Aan : Hoofdschakelaar aan\n Lamp aan

Uit --> Aan : Hoofdschakelaar aan\n Lamp Hoofdschakelaar aan
Aan --> Uit : Hoofdschakelaar uit\n Lamp Hoofdschakelaar uit
```