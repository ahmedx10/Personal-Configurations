## Bash Prompt :

     PS1='\[\e[0;38;5;46m\]╭─\[\e[0;1m\][\[\e[0;1;38;5;39m\]\u\[\e[0;1m\]]\[\e[0;2;3;38;5;46m\]─\[\e[0;1m\]{\[\e[0;1;2;48;5;27m\]\w\[\e[0;1m\]}\[\e[m\]\n\[\e[0;38;5;46m\]╰─\[\e[0m\][\[\e[0;1;91m\]$(git branch 2>/dev/null | grep '"'"'^*'"'"' | colrm 1 2)\[\e[0m\]]\[\e[0;38;5;232;48;5;51m\]\$\[\e[0;1;38;5;82m\]>\[\e0'
  

Output:


![Bash Prompt](https://ackeldic.sirv.com/github/bashrc.png)
 
