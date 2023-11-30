# SACER Parent

Fonte template redazione documento:  https://www.makeareadme.com/.


# Descrizione

Il seguente progetto è utilizzato come parent, secondo le specifiche del tool di dependency management ossia **maven** (https://maven.apache.org/) a cui fanno riferimento tutti progetti dell'ecosistema di applicazioni "SACER".


# Installazione

Come già specificato nel paragrafo precedente [Descrizione](# Descrizione) si tratta di un progetto di tipo parent che viene definito quindi con la seguente modalità all'interno dei singoli progetti:

```xml
<parent>
    <groupId>it.eng.parer</groupId>
    <artifactId>parer-pom</artifactId>
    <version>4.2.0</version>
</parent>
```

# Utilizzo

Parent pom per la definzione dei dei reposity utilizzati, con alcune proprietà globali riferite alla versioni delle third party libraries e di alcuni maven plugin.

# Supporto

Mantainer del progetto è [Engineering Ingegneria Informatica S.p.A.](https://www.eng.it/).

# Contributi

Se interessati a crontribuire alla crescita del progetto potete scrivere all'indirizzo email <a href="mailto:areasviluppoparer@regione.emilia-romagna.it">areasviluppoparer@regione.emilia-romagna.it</a>.

# Credits

Progetto di proprietà di [Regione Emilia-Romagna](https://www.regione.emilia-romagna.it/) sviluppato a cura di [Engineering Ingegneria Informatica S.p.A.](https://www.eng.it/).

# Licenza

Questo progetto è rilasciato sotto licenza GNU Affero General Public License v3.0 or later ([LICENSE.txt](LICENSE.txt)).
