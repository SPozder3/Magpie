# Start -

* My mother and I talked last night. -> Tell me more about your family.
* I said no! -> Why so negative?
* The weather is nice -> You don't say.
* Do you know my brother? -> Why so negative?
* "Do you know my brother" responded with "Why so negative?" because the word "no" is in "know". A more fitting response for this would be "Tell me more about your family." I will probably fix this later on.

# Exercises -

* Dog || Cat -> Tell me more about your pets.
* Mr. Padjen -> He sounds like a good teacher.
* "" -> Say something, please.

## Two more random responses:
* That's pretty eric.
* Awesome!

## Three more keyword responses:
* sugar gay -> Sugar what?
* studle -> Sounds like a regime to me.
* gentlemen -> GET OUT!
* hi || hello || hola -> Hi, how are you?

* When more than one keyword appears in a string its response is based off of the first keyword found in the else if list. Ex: No, I love my dog. -> Why so negative? You can prioritze responses by moving the keyword higher in the else if list in the getResponse function.

# Question -
## 1. What happens when a keyword is included in another word?
* One of the keywords is "no" so any word with "no" inside of it will respond with the response for the keyword "no" rather than anything else found in the user input. To fix this I could add a space to the end of the keyword to indicate that it is its own word rather than inside of a word.