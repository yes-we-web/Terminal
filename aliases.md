# **What is the alias**

:one:

**Aliases** are used to create shorcuts for commands.

## **Creation of the alias**

:two:

*two hidden files* :

- `.bashrc`

- your file of aliases.

:information_source: provisional alias is also possible

The form remains the same :
```
alias name_of_your_alias='order your alias'
```

:bangbang: No space between the name of the alias, = and the order. :bangbang:

### **How to use them**

:three:

to validate your aliases, leave the terminal or type :
```
source ~/.bashrc
```

for create an alias :
```
alias upd='sudo apt update'
```

and type in a terminal :
```
upd
```

if you want all the aliases, write:
```
alias
```

It's possible to create temporary **aliases** :
```
alias name_alias='order your alias'
```

use this command :
```
name_alias
```

Finally remove alias of current session of terminal :
```
unalias my_alias
```

_**Antoine Goncalves**_

:wave: :wave:
