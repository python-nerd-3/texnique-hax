# Texnique Hax
## Instant Complete
Instantly completes a question.

`$("#problemDesc").html(" " + problems.find(i => i.latex == Object.values($("math>semantics>annotation")).at(-4).innerHTML).description).css("font-size", "20px")`
## Show Description
Enables a setting to show an unused description variable hidden in the game's data.

`$(".problem-header").append("<span id='problemDesc'></span>"); $("#problemDesc").html(" " + problems.find(i => i.latex == Object.values($("math>semantics>annotation")).at(-4).innerHTML).description).css("font-size", "20px"); $("#problem-title").on("DOMSubtreeModified", (e) => {setTimeout(() => {$("#problemDesc").html(" " + problems.find(i => i.latex == Object.values($("math>semantics>annotation")).at(-4).innerHTML).description)}, 30)})`
