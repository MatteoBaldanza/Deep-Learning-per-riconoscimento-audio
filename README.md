Deep-Learning per il riconoscimento musicale

I l progetto illustra la creazione di reti neurali di
diversa tipologia che possiedono l’obbiettivo di
riconoscere il genere musicale di appartenenza
di mille tracce musicali di trenta secondi. L’elaborato
è suddiviso in due parti sulla base del tipo di
metodo di classificazione. Attraverso l’utilizzo di
reti convoluzionali si è cercato di catturare l’informazione
presente negli spettrogrammi: immagini
che mostrano, su una scala di colori, le frequenze
dei suoni delle diverse tracce per risalire al relativo
genere. E’ stato in seguito adoperato un approccio
differente: si sono estratte informazioni dalle
tracce audio e raccolte in un DataSet che ha successivamente
avuto la funzione di Input in reti neuarli
di tipo Feed Forward. In particolare per ogni traccia
si sono riuscite a ottenere 164 feature relative
alle caratteristiche specifiche del suono che sono
diverse tra tracce di generi differenti. Per ogni rete
si è effettuata un’analisi di tuning per ispezionare
gli iperparametri della rete che assicurassero un ottimo
adattamento ai dati e al contempo una buona
performance di classificazione. Si sono inoltre testate
tecniche diverse al fine di evitare il fenomoeno di
overfitting. I risultati delle reti hanno fornito anche
un’informazione e una conferma circa le similitudini
e differenze di alcuni generi musicali per quanto
riguarda suoni e periodi storici. Vengono effettivamemnte
mostrate maggiori difficoltà a classificare
generi particolarmente prevalenti in diversi periodi
che hanno influenzato altre correnti musicali con
suoni più standard, e invece testimoniate caratteristiche
più singolari per quei generi particolari. La
capacità previsiva migliore è stata esibita dalla rete
neurale feed forward applicata alle tracce audio
con la quale è stata ottenuta un’accuracy sui dati
del test set del 90%. I risultati delle reti convoluzionali
hanno invece mostrato un valore dell’accuracy
nel test set pari al 58%.
