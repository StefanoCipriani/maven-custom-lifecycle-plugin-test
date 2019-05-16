# maven-custom-lifecycle-plugin-test

Prima di tutto installare nel repository locale maven-custom-lifecycle-plugin

## Esempi di utilizzo

mvn phase3 --> esegue automaticamente anche phase1 e phase2 
mvn package --> il goal associato a phase3 (vedi il pom.xml) 
mvn com.accenture:custom-lifecycle-plugin:0.0.1:phase1Goal --> richiama direttamente lo specifico goal del plugin

mvn phase3 package com.accenture:custom-lifecycle-plugin:0.0.1:phase1Goal --> esegue tutte e 3 le azioni sopra elencate
