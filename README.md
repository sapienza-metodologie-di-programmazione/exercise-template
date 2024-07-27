# Esercizio 

## Per chi progetta l'esercizio 

Dopo aver creato un nuovo repository usando questo template, in `pom.xml` sostituire a `exercise-template` il nome dell'esercizio

```yaml
<artifactId>exercise-template</artifactId>
<name>exercise-template</name>
```
<!-- TODO: rimuovere questa sezione dal README -->

## Svolgimento 

Suggeriamo di scaricare [git](https://git-scm.com/) per comodità. Per scaricare in locale l'esercizio seguire le istruzioni nell'articolo [Cloning a repository](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository) (se non potete scaricare `git` si può usare `Download ZIP`)

Per importare il progetto scaricato su Eclipse basta andare su **File** > **Import...** > **Maven projects**

## Esecuzione

Se usate la CLI

```bash
mvn clean # Se ci sono problemi con le dipendenze 
mvn install # La prima volta che si apre il progetto o dopo un clean

mvn exec:java # Per eseguire App::main
mvn test # Per eseguire i test
```

Se usate Eclipse **Tasto destro** sul progetto > **Run As** > scegliete se eseguire il main o i test 

## Obiettivi 

<!-- TODO: spiegazione dell'esercizio -->
