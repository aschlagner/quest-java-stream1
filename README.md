# SEA8 - StreamQuest 01 - Filter

## Challenge: Heroes file

After years of applying, you finally got hired at the _S.H.I.E.L.D._! Unfortunately, your first job is to help the president of the Works Council with ungrateful tasks. Anyway, it's for the good of the Earth, so you do it!

The president provides you with a list of heroes, and gives you the following tasks:

    - the EC negotiated an advantage with Tony Stark to make some senior cards 30% off on slippers in vibranium. Your first mission is to find the list of heroes aged 60 and over!
    - Thor's birthday party is next week: to avoid drama, your second mission is to find the list of gluten-intolerant heroes!

To get started, make a Fork of the following deposit then clone it locally.

> Be sure to do a _Fork_ or you won't be able to grow anything!

    1. Opens the classes Hero and Shield in order to study their respective contents.
    2. In Shield.java uses a Stream and the filter to recover in elders the list of heroes aged 60 and over
    3. In Shield.java uses a Stream and the filter to recover in intolerants the list of gluten-intolerant heroes
    4. In both of the above cases, use a Predicate and lambda
    5. You don't have to change the class Hero !
    6. Compile and execute the code to check that both lists are displayed in the terminal.

Expected result in the execution of **Shield**:

```
$ Elders:
$ Captain America
$ Thor

$ Gluten intolerants:
$ Vision
$ Scarlet Witch
$ Hulk
```

## Validation criterias

- The deposit GitHub contains the files Hero.java and Shield.java. Only Shield.java must have been modified.
- The class Shield does contain a Stream which retrieves the list of heroes aged 60 and over, using the method filter and a Predicate
- The class Shield does contain a Stream which retrieves the list of gluten-intolerant heroes, using the method filter and a Predicate
- The class Shield compiles without error and displays in the terminal the same result as the one presented above.
