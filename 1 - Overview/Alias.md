# Use Multiple Aliases to save time
An alias is a shorthand way of writing a command. This is very useful as a great deal of kubernetes as you will find you often have to run the same command multiple times.

# Kubectl
`kubectl` is the command for the kubernetes command line tool.
Alias it with...
```
alias kubectl='k'
```
With this alias getting pods can be done by...
```
k get pods
```
Now that is what I call efficiency. :) 

## Enable Tab Completion 
...
## Persist Alias over multiple terminal sessions
...

# Some other handy aliases to use
## Pods
```
alias kubectl get pods='kgp'
```
## ReplicaSets
```
alias kubectl get rs='kgrs'
```
## Deployments
```
alias kubectl get deploy='kgd'
```
## Nodes 
```
alias kubectl get nodes='kgn'
```
## Cluster