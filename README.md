# final-project-proposal-coolcode


## What does your application do?
Our application will be a terminal themed chat application. Although it may not be useful to the general public, we thought it would be a cool idea
to have our users send messages the hard way. The idea is there would be a set of commands that we implement and using these commands they can send messages,
start video calls, and perform any other features that would be useful for a chat app. For example, say Alice and Bob want to have a conversation on our terminal
themed chat app, Alice could send a message using a command like "send --user Bob -m "<message>." Bob on the other hand would have to use a command to read this 
message from Alice say "read -u -Bob" in order to read the message that the user Bob sent her. Will this be profitable, probably not, but we do think 
there is a lot to learn by implementing a chat application especially since we would try to implement some form of voice chat as well.

## What makes it different than a CRUD app? I.e., what functionality does it provide that is not just a user interface layer on top of a database of user information, and the ability to view / add to / change that information?
The chat feature is the real meat and potatoes of our application. How we send messages and ensure they were sent properly will be very important for our application.
The voice/face chat will also add additional complexity to our application. Also, all the individual commands that we implement will require additional logic
that we think will be non-trivial.

## What security and privacy concerns do you expect you (as developers) or your users to have with this application?
Ensuring that messages are sent securely and to the correct users (confidentiality and integryity) will be important. Also, we want to ensure that 
only users that have agreed to talk to each other can send messages to one another. For example, Alice must add Bob as a friend before he can send messages to her.