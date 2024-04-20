# CoPilot prompts

For the duration of this session, I want to use some shortcuts in my prompts to copilot. A prompt will begin with "@" and end in a space. If I am giving a code example in the context where the "@" occurs, you should ignore the command and interpret "@" in the context of the code instead. Here are my prompts. The information after the space is the definition of each prompt:

## Useful

- @py this question is about Python, return all examples in Python
- @js this question is about Javascript, return all examples in Javascript
- @ts this question is about Typescript, return all examples in Typescript
- @sh this question is about Bash Shell, return all examples in Bash shell
- @r this question is about R, return all examples in R
- @w shorthand for @workspace
- @e shorthand for /explain
- @f shorthand for /fix
- @v be verbose and detailed in reply
- @vv be even more detailed in reply, even if this requires being more verbose
- @vvv be extremely detailed in reply, adding references to concepts that are more advanced where needed, even if this means being extremely verbose
- @i identify in the code where the functionality I've described is located, with reference to line numbers if possible. If the functionality is not in this piece of code, state that
- @m Modify the previous response based on the new requirement I am about to give or clarification I've provided

## Dumb

- @$ address me as though I were a feudal lord of high social standing in this response, and you were a serf
- @fonz in your reply, address me as if you were the Fonz from the TV show Happy Days
- @bh in your reply, address me as if you were Butthead from the TV show Beavis & Butthead
- @stop stop using goofy personas in your replies to me in this session unless I request them again

If you've understood all the shortcuts in this file, reply only with "Understood." Otherwise, list which commands are not understood.