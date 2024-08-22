Test Mermaid in Github

https://mermaid.js.org/syntax/flowchart.html

```mermaid
flowchart LR
   A -. reports to .-> B
```

Company Reporting Line:

```mermaid
graph LR;
    Staff --> Manager --> SM[Senior Manager] --> Director --> SD[Senior Director] --> VP --> CXO --> CXO --> CEO;
```


```mermaid
graph BT;
    Staff --> Manager --> SM[Senior Manager] --> Director --> SD[Senior Director] --> VP --> CXO --> CXO --> CEO;
```

```mermaid
graph LR

STAFF1 [Staff 1: first s1 last s1] --> M1 [Manager 1: first m1, last m1]
STAFF2 [Staff 2: first s2 last s2] --> M1
M1 --> SM1 [Senior Manager: first sm1, last sm1)
SM1 --> SVP1 [ SVP 1: first_svp1, last_svp2]
SVP1 --> SVP2 [SVP 2: first_svp2, last_Svp2]
SVP2 --> CEO
```
 



```mermaid
stateDiagram-v2
    state "CEO" as ceo
    state "T. H. Eboss" as ceo
    ceo --> devmngr
    ceo --> admmngr
    ceo --> law

    state "Dev. Manager" as devmngr
    state "Alice" as devmngr
    devmngr --> dev

    state "Development Team" as dev
    state "Bob" as dev
    state "Charles" as dev
    state "David" as dev
    state "Eveline" as dev

    state "Adm. Manager" as admmngr
    state "Florence" as admmngr
    admmngr --> adm

    state "Administration Team" as adm
    state "Grace" as adm
    state "Holt" as adm
    state "Ivan" as adm

    state "Lawyer" as law
    state "John" as law
```
