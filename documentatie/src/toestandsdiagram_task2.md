```plantuml
[*] --> Step0

state Step0 : Hoofdschakelaar 
state Step1 : Plaat in klem en boren klaar
state Step2 : Tap aan zetten
state Step3 : Tap onderin
state Step4 : Tap uitzetten
state Step5 : plaat uit klem

Step0 --> Step1 : Hoofdschakelaar aan

Step1 --> Step0 : Hoofdschakelaar uit
Step1 --> Step2 : boren klaar en plaat zit in de klem

Step2 --> Step0 : Hoofdschakelaar uit
Step2 --> Step3 : draad in de plaat tappen

Step3 --> Step0 : Hoofdschakelaar uit
Step3 --> Step4 : Tap terug naar boven

Step4 --> Step0 : Hoofdschakelaar uit
Step4 --> Step5 : Hoofdschakelaar uit 

Step5 --> Step0 : Hoofdschakelaar uit  

```