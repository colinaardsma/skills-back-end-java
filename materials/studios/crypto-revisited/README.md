# Cryptography: Revisited

Earlier in the course, you did some cryptography using Caesar's Cipher and Vignere's Cipher. You will be creating those ciphers again, this time in Java using the [strategy pattern](../exercises/strategy-pattern).

First, create an interface called `Encodable`. This interface should have one member called `encode()`.

##Implementing your interface

Once you are satisfied with your interface, you should implement it. Create a `CaesarEncode` class and a `VignereEncode` class that implement your interface. You are welcome (and encouraged!) to use your 

If your strategies need a piece of information to do their job (such as a key) this information should be provided to the constructor of the strategy.

## Putting it all together

Once you have finished creating your strategies, create an `Encoder` class. This class should include functionality for requesting a message from the user as well as a `setEncodeable(Encodeable)` method that takes in one of your strategies, and an `encode` method that uses the given strategy to encode the message.

## Commit and push

When you're done with your work, commit and push to GitHub.
