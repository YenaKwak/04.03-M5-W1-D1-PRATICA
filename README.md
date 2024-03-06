## ReactJS ##

<br>
1. Cos’è ReactJS? <br>
una libreria JavaScript open-source progettata per creare interfacce utente con l'obiettivo di facilitare lo sviluppo di applicazioni web e mobile in modo efficiente e organizzato. 

<br>
2. ReactJS è un framework, non una libreria.<br>
Falso. ReactJS è comunemente definita come una libreria, non un framework

<br>
3. Il file package.json contiene…<br>
Molte informazioni utili, come ad esempio l’elenco di tutte le dipendenze richieste dall’applicazione


<br>
4. create-react-app è l’unico modo possibile per creare un’applicazione React.<br>
falso. Sebbene create-react-app sia un metodo popolare e consigliato per avviare un nuovo progetto React, esistono altri strumenti e approcci manuali per configurare un ambiente di sviluppo React.

<br>
5. Qual è il comando da lanciare nel terminale per creare una nuova create-react-app con nome “test”?<br>
npx create-react-app test


<br>
6. Cos’è un componente React?<br>
Un blocco di logica/contenuto riutilizzabile all’interno dell’applicazione

<br>
7. Un componente React può venire creato in tre modi: come funzione, classe o interfaccia.<br>
Falso. I componenti React possono essere definiti principalmente in due modi: come funzioni o come classi. Non c'è un modo definito come "interfaccia" per creare componenti React.


<br>
8. Le props sono frammenti di informazione assegnati all’invocazione di un componente React, utili al fine di rendere il componente dinamico e più riutilizzabile.<br>
Vero. Le props sono utilizzate per passare dati da un componente all'altro, rendendoli dinamici e riutilizzabili.

<br>
9. Le props possono essere passate solamente da un componente genitore ad un componente figlio, non è possibile fare il contrario <br>
Vero. Le props sono passate in modo unidirezionale, dal componente genitore al componente figlio. Non esiste un modo nativo per passare props da un figlio al genitore, anche se ci sono modi per comunicare indirettamente (ad esempio, tramite callback).


<br>
10. Da dove possono venire recuperate le props all’interno di un componente React creato come classe?<br>
Possono essere recuperate all’interno dello oggetto ‘this’, dentro un sotto-oggetto chiamato ‘props’
In un componente React definito come classe, le props sono accessibili tramite this.props.