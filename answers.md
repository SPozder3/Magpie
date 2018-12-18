# Exploration-
* Statement: I want to build a robot. Response: What would it mean to build a robot?
* Statement: I want to understand French. Response: What would it mean to understand French?
* Question: Do you like me? Response: What makes you think that I like you?
* Statement: You confuse me. Response: What makes you think that I confuse you?

# Exercises-
* When you say "I want to" it responds with "What would it mean to" + what you want to do ex: build a robot.
* When you say you/me statements it responds with  "What makes you think I" + rest of statement + "you"
* This structure does not work well when someone is ranting on and on using you/me statements and I want statements. This can make too many iterations with the substring that we are looking for and make the response complicated. This can be fixed by putting a maximum amount of characters that it will use these methods on.