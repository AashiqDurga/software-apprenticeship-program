# Cli Basics
Dating back to the 1960s, a [Command Line Interface](https://en.wikipedia.org/wiki/Command-line_interface) is a computer language interpreter with which users are able to communicate with computer systems via a statement or command.

Though less widely used nowadays, it is still a useful tool for many software developers due to the efficient nature.

A [shell](https://en.wikipedia.org/wiki/Shell_(computing)) is a user interface that used to access the services of an operating system. These shells can either be text-based in the form of a CLI or graphically with a graphical user interface (GUI).

Examples of such command-lines interfaces are:
- Bash and [GitBash](https://www.atlassian.com/git/tutorials/git-bash)
- Powershell
- Interactive Ruby Shell


However, there are [differences](https://en.wikipedia.org/wiki/Comparison_of_command_shells) between the different shells and their available commands.

## Basic Structure
The basic structure of a Cli is:
- Prompt: the program provides this to help give the user context
- Command: the user provides a command for the interface
- Parameter(s): one or more optional parameters are provided from the user depending on the command given

*Whitespace acts as a delimiter.*

*Newline acts as the end-of-line delimiter*

## Commands
### The HELP command 🙋

One of a beginner CLI users most helpful commands. It can allow the user to see the list of available commands, subcommands and options.

The syntax of a command commonly follows:

|   Syntax  |   Symbol   |
|   :---   |   :---:   |
|   __*As written*__ items are without braces or brackets    |   Type as shown   |
|   __*Required*__ parameters are enclosed in angle brackets   |   `<Placeholder>`   |
|   __*Optional*__ parameters are enclosed in square brackets   |   `[Placeholder]`   |
|   __*Sets of required*__ parameters are enclosed in square brackets   |   `{Placeholder}`   |
|   __*Mutually exclusive*__ options are differenciated via a vertical bar   |   `|`   |
|   __*Optionally repeated*__ items are shown using ellipses   |   `...`   |

\
For example:
```
$ git help -a
usage: git [--version] [--help] [-C <path>] [-c <name>=<value>]
           [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
           [-p | --paginate | -P | --no-pager] [--no-replace-objects] [--bare]
           [--git-dir=<path>] [--work-tree=<path>] [--namespace=<name>]
           <command> [<args>]
```



### Abbreviation of commands
The hypen indicates the beginning of a new option. Conventionally two hyphens are used followed by a word, for example: 

**--help**, however some languages allow the abbreviation by using a single hyphen follwed by a character 

**-h** and even combination of commands when more than one character follows, while other languages may not allow this.
```
$ rm -rf [FILE]
```

In Bash can be the same command to remove the file(s) as:
```
$ rm -r -f [FILE]
$ rm -R -f [FILE]
$ rm --recursive --force
```


## Things to read
A comprehensive list of Microsoft commands with explanations, abbreviations, options and examples of their useage can be found [here](https://docs.microsoft.com/en-us/windows-server/administration/windows-commands/cd).

Code Academy's breakdown of some [basic cli commands](https://www.codecademy.com/articles/command-line-commands)


## Exercises
Learn about basic [Shell](https://www.learnshell.org)
