# Library of Ruina PvP
Yes. It's real. Never forget Afterglow. :XD:

## How to Use
Boot up the video game, load your save and click the "Exercises" tab on the
left right under "Credenza." The background of the library should have turned a
bright orange to make sure you know you're about to sauce on people, since the
deckbuilding UI is indistinguishable otherwise. You'll be able to create, join
and configure lobbies on the new sidebar. For now, lobbies have capacity for
only two people.

Customize the floor you will be using like you would normally, and click "Ready"
at the bottom to lock in your selections. The floor you click "Ready" on
determines the patron librarian, assistant librarians, abnormality and E.G.O.
pages you will have access to during the battle. Once both players have readied
up, the game will load into the battle.

The look of the floor is determined by the floor of the "HOME" player. Players
will now take turns assigning their speed die to enemy units, with the HOME
player going first. Instant-use cards do not take a turn. However, each turn
will be placed on a 60-second timer, with a bank time of 180 seconds. If this
runs out, your turn will be forfeit. If you have more speed die than your
opponent, you can fill the rest out all in one turn.

Now that you've finished, let the scene pass, and be thorougly disappointed by
your rolls. Sadge. Rinse and repeat.

## The Theory
> `Programmer Stuff. End-users Beware!`

In the end, Library of Ruina is simply an Input-Output machine. It takes in user
input and spits out an output, so really, the only thing that needs to be
synchronized is user inputs.

In this method, everything just works. Mods work, pages work, no crazy
workarounds needed. Life is good. Except, **RNG doesn't work**. The solution is
simple: synchronize *gameplay* RNG at the start of the scene.

In a saner world, we would only need to synchronize RNG once at the start of the
battle, but just to make sure, we can keep going down layers until it works.
This would totally work, since RNG is the only non-deterministic thing in the
gameplay. Boom, add some flair and stuff so you can't mess with your opponent's
units, and we do a wee bit of trolling

## Licensing
**I OWN NONE OF THIS CODE**. [Seriously, I don't](./UNLICENSE). All the code I
write is dedicated to the public domain, so feel free to copy it, share it, maim
it, sell it, reupload as your own, call yourself the author, I don't care.

Contributors beware! Your rights to any major contributions must also be [waived
to the public domain](https://unlicense.org/). I am not managing 18 different
licenses because the rights to your code is more important than people enjoying
it.
