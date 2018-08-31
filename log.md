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

**Thoughts:** It would be nice when we input the same product code, the row merges with existing one and the quantity gets updated. Bonus point if we can put a flash animation the quantity cell to notify the user that the quantity has been updated.

**Link to work:** [Jurnal](https://github.com/bustanil/jurnal)

### Day 4-7: August 16-19, 2018

**Today's Progress**: On vacation.

**Thoughts:** Thinking to learn how to test Vaadin app.

**Link to work:** [Jurnal](https://github.com/bustanil/jurnal)

### Day 8: August 20, 2018

**Today's Progress**: Use the `Binder` to auto calculate total sale. Implemented New Sale button.

**Thoughts:** We should have a text field above the grid, so the user can input the product code to quickly add a sale item.

**Link to work:** [Jurnal](https://github.com/bustanil/jurnal)

### Day 9: August 21, 2018

**Today's Progress**: I've implemented the quick add product functionality, but Vaadin is lacking key press listener. I need to implement a custom text field for this purpose. I also have finished implementing a logic to check whether the user inputs the same product. If it does then don't add new row, just add the quantity instead.

**Thoughts:** Let's try setup a CI server next time.

**Link to work:** [Jurnal](https://github.com/bustanil/jurnal)

### Day 12-13: August 21, 2018

**Today's Progress**: Decided to give it jOOQ a try, together with FlywayDB. It's interesting to find out that you miss a lot when not using Hibernate/JPA. With jOOQ you need to use Mapper to map values to domain objects and vice versa. You also lose Spring Data JPA which means that I need to implement my own repository classes. 

**Thoughts:** I'm thinking to be more serious with the application development. I want to make it a usable product.

**Link to work:** [Jurnal](https://github.com/bustanil/jurnal)

### Day 15: August 21, 2018

**Today's Progress**: New sale and Complete Transaction using popup dialog

**Thoughts:** Code is growing. Tomorrow should be refactor and unit testing day

**Link to work:** [Jurnal](https://github.com/bustanil/jurnal)
