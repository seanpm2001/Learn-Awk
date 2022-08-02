
***

![/The-AWK-Programming-Language.svg](/The-AWK-Programming-Language.svg)

### Learning AWK (programming language)

I know very little about the AWK programming language. This document will go over all of my knowledge of the AWK programming language.

#### Hello World in AWK

This is how you make a Hello World program in AWK:

```awk
BEGIN {
        print "Hello, world!"
        exit
}
```

#### Comments in AWK

Comments in AWK are the same as in Shell.

##### Single line comments

Single line comments in AWK are written like so:

```awk
# This is a single line comment
```

##### Multi-line comments

I don't know if AWK supports multi-line comments.

#### Break keyword in AWK

```awk
break
```

To this day, I am still not entirely sure what the `break` keyword does, but most languages support it.

_/!\ This example has not been tested yet, and may not work_

#### REGEX patterns in AWK

AWK supports REGEX (Regular Expression) patterns. They can be implemented like so:

```awk
/regex_pattern/ {
    # Actions to perform in the event the record (line) matches the above regex_pattern
    print 3+2
    print foobar(3)
    print foobar(variable)
    print sin(3-2)
}
```

The output can then be sent to a file directly

```awk
/regex_pattern/ {
    # Actions to perform in the event the record (line) matches the above regex_pattern
    print "expression" > "file name"
}
```

or through a pipe `|`

```awk
/regex_pattern/ {
    # Actions to perform in the event the record (line) matches the above regex_pattern
    print "expression" | "command"
}
```

These examples were taken directly from Wikipedia, and modified to fit how I interpret it.

_/!\ This example has not been tested yet, and may not work_

#### Other knowledge of the AWK programming language

1. AWK is a language by Alfred Aho, Peter Weinberger, and Brian Kernighan, of which the language is named after the first letter of their last names (AWK)

2. AWK is not a semicolon and curly bracket language, but it is a curly bracket language

3. AWK uses the `*.awk` file extension by default

4. AWK is a functional programming language

5. AWK is one of the default scripting languages in most UNIX/POSIX operating systems, such as Linux and BSD

6. AWK is one of the top 50 programming languages (as of 2022, July 31st, ranking #41)

7. AWK was first created in the year 1977

8. No other knowledge of the AWK programming language

#### Additional comments

1. I have not yet memorized the names of the developers

2. No other additional comments available

***

## File info

**File type:** `Markdown document (*.md *.mkd *.mdown *.markdown)`

**File version:** `1 (2022, Monday, August 1st at 5:08 pm PST)`

**Line count (including blank lines and compiler line):** `158`

***

## File history

<details><summary><p>Click/tap here to expand/collapse the history for this file</p></summary>

<details><summary><p><b>Version 1 (2022, Monday, August 1st at 5:08 pm PST)</b></p></summary>

> Changes:

> * Started the file

> * Added the `title` section

> * Added the `Hello World in AWK` section

> * Added the `Comments in AWK` section

> > * Added the `Single line comments` subsection

> > * Added the `Multi-line comments` subsection

> * Added the `break keyword in AWK` section

> * Added the `REGEX patterns in AWK` section

> * Added the `other knowledge of the AWK programming language` section

> * Added the `Additional comments` section

> * Added the `file info` section

> * Added the `file history` section

> * No other changes in version 1

</details>

</details>

***
