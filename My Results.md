# Här är mina resultat hittils:

# Fråga 7:

## a)
Enligt våra experiment så ser vi ingen tidskillnad vid höjd inlärningshastighet (från 0.01 höjt till 0.1). Under Relative, se figur a.1
![a.1](fig/7.1.png "Höjd inlärninghastighet till 0.10")

Vid testning av att öka inlärningshastighet ännu mer (från 0.01 höjt till 0.5) så ser vi att accuracy på train och validation börjar gå ifrån varandra.
Specifickt att validation accuracy är mindre än train accuracy, se figur a.2
![a.2](fig/7.2.png "Höjd inlärninghastighet till 0.50")

## b)
Enligt våra experiment så ser vi att vid minskande av batch_size (från 256 till 128 och 64) leder till högre prestanda och längre träningstider.
![b.1](fig/b.1.png "Minskad batch_size från 256 till 128 och 64")