Project: better-ticket-machine
Authors: David Barnes and Michael Kölling

This project is part of the material for the book

   Objects First with Java - A Practical Introduction using BlueJ
   Seventh edition
   David J. Barnes and Michael Kölling
   Pearson Education

It is discussed in chapter 2.

Purpose of project: To illustrate conditional statements.
How to start this project: Create one or more TicketMachine objects.

Questions of part 3

47: No, i think it doesn't change. When I added 0 cents, it asked be to add a positive value and the balance stays 0.
48: I think you'll have to add a value greater then or equal to the value neeeded to insert the money. After experiencing, we could now put the value 0.
50: It was the sunset feature and it's controlled by two values.
51: In the better ticket machine, they use boolean expressions and in the native, they don't.
52: After removing the word else and the block, the ticket won't print without any money nor leave any message saying to add a specified amount of money.
53: No, beceause we have to insert a specified amount of money to print the ticket, once printed the balance will always be the amount inserted - the price, until you don't have enough for 1 ticket.
55: Added saving and discount.
56: mean = total / count;
57: public void affordable(int budget)
    {
        if(price > budget) {
            System.out.printIn("Just right.");
        }
        else {
            System.out.println("Too expensive.");
        }
    }
58: public void affordable(int budget) {
    if (price > budget) {
        System.out.println("Too expensive, your budget is " + budget);
    } else {
        System.out.println("Just right");
    }
} 
    

     public void affordable(int budget) {
    if (price > budget) {
        System.out.printf("Too expensive %d, your budget is %n", budget);
    } else {
        System.out.println("Just right");
    }
}
     I find the first version much more easier to understand.
59: Because it sets the balance to 0 before it could get returned.
60: After writing a returned statement, any code written after that becomes unreachable.
61: It stays 0 because of the int which make it not assigne to a variable.
62: public int emptyMachine()
    {
     int amountEmpty = total;
     total = 0;
    }
63: 
