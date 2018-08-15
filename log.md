# 100 Days Of Code - Log

### Day 0: August 12, 2018

**Today's Progress**: Initial domain model and JPA implementation.

**Thoughts:** Tried Lombok for the first time, it does help reduce boiler plate code especially when dealing with JPA entities. The drawback is that I have to use the annotations in fields, I don't fancy it because it "pollutes" the field definitions.

**Link to work:** [Jurnal](https://github.com/bustanil/jurnal)

### Day 1: August 13, 2018

**Today's Progress**: Initial implementation of the Sale user interface. Disabled Spring Boot DevTools. I don't really like that it hot reloads every time I compile the source code. It's already slow even though there are not many classes. The slow hot reload is because Hibernate takes time to boot up. It also break the UI state (need to find out why later).

**Thoughts:** So far everything is enjoyable, not gonna do too much UI styling. I believe I have to focus on the functionalities first. I'll beautify the UI later, when the functions are done.

**Link to work:** [Jurnal](https://github.com/bustanil/jurnal)

### Day 2 and 3: August 14-15, 2018

**Today's Progress**: Got the sale line grid editor working, used built in Vaadin validators which work very nicely. Getting familiar with `Binder` and `GridEditor`.

**Thoughts:** It would be nice when we input the same product code, the row will merge with existing one and the quantity gets updated. Bonus point if we can flash the quantity cell to notify the user that the quantity has been updated.

**Link to work:** [Jurnal](https://github.com/bustanil/jurnal)
