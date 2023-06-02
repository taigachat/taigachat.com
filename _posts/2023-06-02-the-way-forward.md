---
layout: default
title:  "The Future is Not The Matrix"
date:   2023-06-02 15:03:0 +0200
categories: discussions
author: Alexander Björkman
---
### Draft 1
Warning: this is the first draft of this post.

# The Future is Not The Matrix
Matrix.org (sometimes called Element after their main client)
is a protocol with a similar stance on freedom of expression and privacy
as TaigaChat.
That said, I do not view the future of Matrix very optimistically.
My belief does not come from any animosity or distrust towards the developers
of Matrix. Rather it comes from my scepticism towards the recent
"federation" trend that has been growing among crowds disenfranchised by
big tech. Federation is a pragmatic middle ground between total
decentralization and total centralization. I would argue that
Matrix didn't have to make the compromise between centralization
and decentralization. And to prove my point, I created a client & server
for the TaigaChat protocol instead. And while some features are still missing
from TaigaChat. I do think that it will eventually become robust enough to
prove my point fully.

# What are the Advantages?
There are some things that TaigaChat can do that Matrix can't.
And these differences are not caused by technical competence but simply
by the choice of making Matrix federated.

## TaigaChat is more censorship resistant
The freedom of exprssion is only safe on Matrix as long as the majority of
users choose to not register using the matrix.org homeserver. Homeservers
have the ability to blacklist other homeservers, to the detriment of users
still wishing to access rooms on the blacklisted servers. Because
homeservers don't exist in TaigaChat, this isn't a problem.

## TaigaChat is less sensitive to server outage
Because users can connect directly to server without the use of
an intermediate home server, server outages affect less people.
Whereas in Matrix, should Matrix.org go down, one can expect around half of your group (numbers depend on
how dominant the matrix.org homeserver is in your field)
members to not be able to connect.

## TaigaChat is Simpler
The protocol is easier to explain. And can be fully implemented in less
lines of code. See for yourself:
- [Matrix Server Code](https://github.com/matrix-org/synapse)
- [TaigaChat Server Code](https://github.com/taigachat/taigachat/tree/master/server)

## TaigaChat is faster
Because each homeserver in Matrix must have a complete copy of each chat room
that the users have joined, joining a new chat room can sometimes take entire minutes.
TaigaChat does not have this deficiency.

# Can it be fixed?
It is too late now for Matrix to change their entire approach to providing
a decentralized service. Which is why I maintain that Matrix is not the future.



