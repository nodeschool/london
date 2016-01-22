
# A bluffers guide to running a NodeSchool

Here is a recipe that we've converged on after a handful of nodeschools and picking
the best bits out of the other [event write-ups](https://github.com/nodeschool/discussions/issues/93)

Most importantly, it's your event so do what works for you and the assembled
wizards in training.

## Get everyone in and on the same page.

As people arrive, welcome them and figure out what level they are at. Ask them:
  - Done any JS / used the command line before?
  - Have you got `node` installed?
  - Have you got `learnyounode` installed?

Start helping anyone who doesn't have `node` & `learnyounode` installed.
Offer up the beverages & give out info about the space (wifi, toilets, escape tunnels, etc)
while you accumulate peoples.

## Give an introduction to the workshop style

On the projector walk everyone through a good set up for starting a new workshopper.
Briefly explain pair-programming, and do the following as a pair, 1 typing, 1 explaining.

- Fire up a shell
- `mkdir -p nodeshool/learnyounode-answers`
- `cd nodeshool/learnyounode-answers`
- `learnyounode`
- Select the first challenge and walk people through the challenge
- Make a new file in your preferred text editor
- `01-hello-world.js`
- Copy the the text for the challenge into it as a comment header
- Write out the code for a solution, but leave in a syntax error and a challenge error.
- `console.print('Hello World')`
- Explain that we've just written a node.js script. Show that we can run
it (and any node script) via `node 01-hello-world.js`
- Our script errors because `console.print` is not a thing.
- Show the [MDN docs](https://developer.mozilla.org/en/docs/Web/API/console) and point out that it should be `console.log`
- Fix the error and re-run via node, and show that it logs out `Hello World`
- Huzzah. All good, but we want to pass the challenge!
- Show how `learnyounode verify 01-hello-world.js` works and how to read the output.
- Boo! We failed. Show that `verify` helps us figure out where our code isn't doing what is expected.
- Fix our file `console.print('HELLO WORLD')` and verify again
- HOORAY! We passed! Gold star! Hands in the air! (get everyone to do that when they complete a challenge)
- Repeat the process with the second challenge...
- **SWAP OVER THE PAIRING**
- Run `learnyounode`, select **Baby Steps** and create a new file: `02-baby-steps.js`
- Explain about `process.argv` and how that **the workshop will provide the input**
- (IMPORTANT! The majority get stuck on that the first time so do explain it.)
- Show how `node 02-baby-steps.js` still works but we need to pass args to it.
- Explain the workshopper `run` command
- `learnyounode run 02-baby-steps.js`
- to get the challenge to provide the input but get the stacktrace if something goes wrong.
- Complete the challenge, get a volunteer from the audience to help!

**YOU ARE NOW READY TO NODESCHOOL: GO LEARN YOU A NODE!**

Encourage people to pair, and to throw their hands in the air when they complete
a challenge, to get a sense of their progress and to know where to give more help.
Plus, is funsies.

Keep an eye out for interesting solutions, occasionally pause things to highlight
them on the board.

Pause at some convinent point to hightlight other workshops that are availale.

If they are all wizards, go through how to build a workshopper / adventure

**-- Fin --**
