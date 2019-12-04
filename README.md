# zsh-config

First of all, I really don't recommend that you use this config for your machine.
.  
.  
.  
.  
.  

Still here? Okay then, don't say I didn't warn you. At least make a backup of your current setup, before you clone this mess.  

So, you've probably heard of zsh, right? [If you haven't, what are you doing here?] And you've probably heard of oh-my-zsh, a framework for the z shell. If not, try it, it's really cool. 

My problem with omz is that it runs a lot of unnecessary stuff, on every invocation of the shell, and as a person who lives in the the terminal, I can't have that now, can I? What I've tried to do here is to make a config that uses stuff from the omz framework, but only the stuff I need. Also, it helps that I'm using the [starship](starship.rs) theme. It's a rust based theme that works really well. starship being rust based means that most of the scripts that omz sources are now redundant, like the git, nvm, etc. So, I've removed all that. I've also removed some stuff I don't need. And also moved a some code from the omz script to the .zshrc file. 

So, if you really wanna use this, go ahead. But I'm not making any promises.

This won't break as long as it doesn't. I'm in the "Move fast, break stuff" stage.
