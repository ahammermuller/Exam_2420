# Update most of the software on your Ubuntu OS

Run the command:

`sudo apt upgrade`

# Edit a text using vim

Use the commands: h = left, l = right, j = down and k = up to navigate in the file
I typed r+the character that I want to replace. In this case I replaced the Vs for Cs.
I type s+character to inser the symbol : near the digit word.

![text_edited](https://github.com/ahammermuller/Exam_2420/blob/main/Images/text_edited.jpg)

# journalctl

How to use journalctl

![use_journalctl](https://github.com/ahammermuller/Exam_2420/blob/main/Images/use_journalctl.jpg)

- print logs for the current boot(-b)

![b_option](https://github.com/ahammermuller/Exam_2420/blob/main/Images/b.jpg)

- logs should have a priority of warning or more important(-p, --priority=)

![p_option](https://github.com/ahammermuller/Exam_2420/blob/main/Images/p.jpg)

- output in a nice pretty json. (-o json-pretty)

![o_option](https://github.com/ahammermuller/Exam_2420/blob/main/Images/o.jpg)

![json_pretty](https://github.com/ahammermuller/Exam_2420/blob/main/Images/json_pretty.jpg)

`journalctl -p warning -b -o json-pretty`

