# Welcome to the Crystal Documentation

## Commands

 - this list of commands applies to the latest development beta of the bot, some of these commands may not work on release versions

### Kick:

kicks the specified user

syntax:

>  $ kick @user "reason"

### Ban:

bans the specified user

syntax:

>  $ ban @user time "reason"

### Unban:

unbans the specified user

syntax:

>  $ unban @user "reason"

### Mute:

mutes the specified user
(this requires the role 'Muted' to already exist with the permissions required, if not a new muted role with the right permissions will be created but it will need to be manually set up so having the muted role will result in a being unable to type)

syntax:

>  $ mute @user time "reason"

(time must be an integer ending in ["y" = years,"d" = days,"h" = hours,"m" = minutes,"s" = seconds] )

### Unmute:

unmutes the specified user
(this requires the user to already have the 'Muted' role)

syntax:

>  $ mute @user

### Rickroll:

displays a Rickroll gif in the chat.

Don't. Just don't. Please, just don't.

syntax:

>  $ rickroll

### Help:

displays a list of all commands available to run through the bot

syntax:

>  $ help

### Rules:

for now this command displays a generic set of rules for the server
- the option to make a custom set of rules will be added later

syntax:

(list rules)

>  $ rules

(add new rule)

>  $ rules add "rule nmae" "rule description"

(remove a rule)

>  $ rules remove "rule name"


### Calc:

a useful calculator utility

can solve:
  - brackets
  - square roots
  - powers
  - standard arithmetic operations including integer and modulo
unfortunately at the moment there are some issues with BIDMAS such as division always executing before multiplication (will be fixed later)

syntax:

>  $ calc [equation]

eg:

>  $ calc 5+3

### Docs:

opens the documentation for the bot

syntax:

>  $ docs

### Rickrollvc:

causes the bot to join the voice channel that the user is in and play a rickroll

syntax:

>  $ rickrollvc

### Play:

causes the bot to play the specified song in the voice channel that the user is in
  - this must be a youtube link

syntax:

>  $  play [song]

### Pause:

pauses the music that the bot is playing

syntax:

>  $ pause

### Resume:

resumes the music that the bot is playing

syntax:

>  $ resume

### Stop:

disconnects the bot from the voice channel

syntax:

>  $ stop

### Setup:

sets up the discord server, this includes creating a default set of rules and a server-data.json file
 - many commands will throw errors if the server is not setup before they are used (i will manually implement the erros to prompt admins to setup)

###
