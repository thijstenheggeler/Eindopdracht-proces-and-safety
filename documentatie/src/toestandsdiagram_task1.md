```plantuml
[*] --> Step0

state Step0 : Hoofdschakelaar 
state Step1 : Plaat in klem plaatsen
state Step2 : Boor aan zetten
state Step3 : Boor onderin
state Step4 : Boor uitzetten

Step0 --> Step1 : Hoofdschakelaar aan

Step1 --> Step0 : Hoofdschakelaar uit
Step1 --> Step2 : Plaat in klem

Step2 --> Step0 : Hoofdschakelaar uit
Step2 --> Step3 : Gat in de plaat boren

Step3 --> Step0 : Hoofdschakelaar uit
Step3 --> Step4 : Boor terug naar boven

Step4 --> Step0 : Hoofdschakelaar uit 

```