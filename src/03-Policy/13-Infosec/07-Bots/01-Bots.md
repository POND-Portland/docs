# Bots

<div class="warning">
This section is incomplete! 

It is TODO and will be fleshed out after the more urgent items.
</div>


Bots are used on the server for a variety of tasks. In general, such bots should be safe, but we have specific policies on their usage. In particular, when bots are collecting sensitive data, care should be taken to ensure the data is handled in a sensitive way. Any bot feature we're going to use for such purposes should be tested thoroughly before rolling it out to users - and a guide should be written so users can be reassured about what we can and cannot do or figure out with the data we get. 

In the event we realize a mistake in something we've used, we should acknowledge the mistake and quickly find a solution. There are no penalties for making such a mistake unless it was done maliciously, and a talking-to (or a "gentle suggestion" to maybe leave bot-related duties to other leaders) may be needed if it's done negligently more than once or twice.

### User-Created Bots

<div class="warning">
This section is incomplete! 

It is TODO and will be fleshed out after the more urgent items.
</div>


User-created bots add some special concerns. Unless a bot's permissions are not sufficiently scoped, the admin of the bot is essentially being given full control of the server for everything the bot can do. As such, user-created bots must be approved by users in a similar process to leadership applications - where objections are collected and a threshold of 0.8% rejects the bot. Leadership may also elect to reject the bot for any reason. A link to the code must be posted (for technically-inclined users to audit if they so choose) and a list of administrators and contributors to the bot. This can be thought of as informally giving the bot developer(s) the pseudo-"leadership position" of "bot maintainer".

This process doesn't need to be undergone by bots solely maintained by leaders in the Community Developer role **EXCEPT** if the bots are going to be handling otherwise anonymous or sensitive information (including changes to an already approved bot that add such a feature).

In this case, a fairly thorough and honest application must be submitted explaining what data, *exactly*, the administrator has access to, and a threat model for how easy or hard it is for the admin to derive revealing information from it. Bots handling such data are expected to maintain the absolute minimum amount of data necessary to enable their use. The bot feature need not engage in top-of-the-line Signal-tier encryption to be viable, but a plan must be submitted and users must approve it.