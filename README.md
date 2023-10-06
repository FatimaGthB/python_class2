# python_class2

1/  create a change_price method to modify the price of the harry_potter instance:
The price of the harry_potter instance must be 14.99 at the end of the script.

The price of the Book class must remain at 9.99.

class Book:
    price = 9.99

    def __init__(self, price):
        self.price = price


harry_potter = Book(19.99)
harry_potter.change_price(price=14.99)

2/ create a class to represent a book.

This class will have three attributes:

name
number_of_pages
price
From this class, we'll then create two book instances.

The first instance is called livre_HP and will have the following attributes:

name = "Harry Potter
number_of_pages = 300
price = 10.99
The second instance is called livre_LOTR and will have the following attributes:

name = "The Lord of the Rings
number_of_pages = 400
price = 13.99

3/ The aim of this exercise is to transform the chante_pour method to make it static.

The method must sing Happy Birthday for a person defined by the argument sent to the prenom parameter.

In this case, the script should display Happy Birthday for Paul (the chante_pour method should not display the song text, but just return it).

You therefore need to make the method static and modify it so that it displays the text contained in the lyrics attribute of the Song class, adapted for the first name Paul.

4/ In this exercise, we'll create a Bank class.

The Bank class will contain two attributes: the name of the bank and a dictionary representing bank accounts.

Each account is identified by an account number (which is unique) and contains a sum of money.

Your task is to add an add_account method to create a new account with an account number and initial balance.

Also add a deposit method to deposit a certain amount of money into a specific account, and a withdrawal method to withdraw a certain amount of money.
