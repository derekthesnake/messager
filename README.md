messager is a python-based messaging program intended for multi-user linux servers, written fully in python3 with no other 
dependencies.

Next intended feature is the option to initialize users in the /var/local/messager folder.

It currently has no support for alerts once a message is received, but this is a possible future feature.

===Usage===
messager [c | h | l | r | s]
messager [check | help | list | read | send]

====messager check====
is typically put into ~/.bashrc and prints out a short string notifying the user whether or not they have unread messages.

====messager help====
provides the user with information about the various messager commands.

====messager list====
prints out a list of the user's received messages.

A numerical argument may be specified, which will show the last <number> messages received.

====messager read====
Without arguments, messager read shows unopened messages if the user has any.

If a numerical argument is specified, this will show the selected message.
Find the number of the message with message list.

====messager send====
sends a message containing text (prompted by the program) to a user (prompted by a program)

Optionally, you may supply the username as an argument, which will skip the username prompt.
