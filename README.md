## What is the purpose of the `on` section?
To automatically run when certain actions are performed.

## What does `workflow_dispatch` do?
It allows actions to be manually ran from GitHub.

## What does `runs-on` specify?
The type of machine that will run a specific action.

## Why is `actions/checkout` needed?
It gives the action runner access to the contents of the repository.

## What does the language setup action do?
It gives the action runner access to the tools it needs to compile/run the program.

## What is the difference between compiling and running the program?
Compiling the program converts the human-readable code to machine code or bytecode, and running the program is what executes it.

## Where can you see the program output?
In the actions tab, under the particular run and job.

## What is the difference between a workflow, a job, and a step?
A workflow contains all the jobs for an action, a job can contain several steps, and each step runs a specific command. 
