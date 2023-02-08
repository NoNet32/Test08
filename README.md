# Test08

**Das ist fett**

*Italic*

> Blockquote
> zweite Zeile

1. Erstens
2. Zweitens
3. Drittens
 
- Erstens
- Zweitens
- Drittens

`#include <stdio.h>`

```
private void Start() // 2
    {
        // Read the persisted data and set the initial hit count.
        hitCount = 0;
        SqliteDataAccess.createDB();
        PersonModel p = new PersonModel();
        p.FirstName = "Stefan";
        p.LastName = "Gratz";
        SqliteDataAccess.SavePerson(p);
        List<PersonModel> p1 = SqliteDataAccess.LoadPeople();
        foreach (PersonModel p2 in p1)
        {
            Debug.Log(p2.FullName);
        }
        Debug.Log("DKakd");
    }
````
*******
[Orf](https://www.orf.at)

![Bild](bild.jpg)