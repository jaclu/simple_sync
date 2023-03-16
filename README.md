# simple_sync

Super simple two way sync, created for the iSH App, linux like,
but not able to run any normal shared file-systems between nodes
beyond sharing an iCloud folder - great for two iPads using the same
AppleID, not so much if you are sharing between iSH and a linux node.
You could obviously use a shared git-repo, the drawback then is that
it is completely manual, you must remember to commit, push and pull.

The aim for this is when you work on something in both ends, and you
want to easily change sync direction.
Run this on the "active" side, when you start working on the other end
just fire this up on that node, first it terminates this on the other
end, then it will continously sync content there, until you stop it
or it gets terminated by the other end starting to source the syncing.
