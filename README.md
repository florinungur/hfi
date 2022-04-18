```
NAME
    hfi - simple time(1) wrapper

SYNOPSIS
    hfi [-h] SCRIPT

DESCRIPTION
    hfi (short for "how fast is") is a wrapper over the time(1) command that shows the time, CPU, and memory use of a
    Bash script in a pretty format.

    This command may not work on your macOS version. Check your time(1) command.

ARGUMENTS
    SCRIPT
            Path to a Bash script.

OPTIONS
    -h      Show this message.

EXAMPLE
    hfi test_script.sh
            Assesses a Bash script called test_script.
```

... __Why do this at all?__

Not every project needs to be big, complex, with the aim of attaining perfection. This is a working piece of software. 
Useful? May be to some. Fun to make? Yes it was :)
