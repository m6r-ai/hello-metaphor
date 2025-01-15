# Hello, Metaphor

This is a simple introduction to Metaphor so you can get an idea of the way Metaphor (.m6r) files are
built and how to use them.

In the `metaphor` directory you can find a file, `hello-metaphor.m6r`.  This explains the basic elements
of a a Metaphor file and what should go in them.  It describes a simple problem to solve and provides
the instructions to have an AI solve that problem by writing some software and a markdown `README.md`
file that describes the result.

You can compiler `hello-metaphor.m6r` into a large-context prompt using the standalone `m6rc` compiler,
but it's probably simpler to do this using `Humbug`.

With `Humbug` use "New Workspace" to create a workspace using the `hello-metaphor` directory.  If you've
done this already then you can use "Open Workspace" to open the existing workspace.

You can open the `hello-metaphor.m6r` file by clicking on the `metaphor` directory in the file view or by
using "Open File..." from the menu.

To use this file, you can start a new Metaphor-based conversation using "New Metaphor Conversation..."
and opening the `hello-metaphor.m6r` file.  This will compile it into a prompt and open a new conversation
tab with the prompt already inserted into the message box.  You can read the compiled prompt and see
some of the changes made from the source version to the compiled version and this means you can also
edit the prompt to try out different things.

You can change which AI assistant model will be messaged by using the "Conversation Settings" option.

When you're happy with everything then you can use "Submit Message" and it will send the prompt to the
AI assistant and you'll see an answer stream back from it.  Different AIs respond at different speeds.

You can also open another Metaphor conversation in a different tab and change those conversation settings.
This will let you see how different AIs respond.  If you're quick you could start two or three
conversations at the same time and watch all the AIs responding simultaneously.

Each conversation is unique and the AIs will not remember anything about any other conversation.  This
is a huge advantage because it means they don't remember anything that didn't work out as planned, but
the will remember everything that happened previously in the same conversation.

If you want to, you can create a duplicate of the current conversation by using "Fork Conversation".
The original and duplicate conversations will start with exactly the same starting point, so both
will know everything up to the point where they were duplicated, but after that each will not be aware
of anything said in the other conversation.  This means if you want to explore two or more ideas to
see which works best you can do so and then discard the one you don't want to continue.

