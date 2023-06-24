# Front-end Continuous Integration
## Instruction
- Dev   

  dev job will run only on commited changes into dev branch

- Stage  
  
  stage job will run only on **stage-v*** tags

- Live  

  live job will run only on **main-v*** tags

each job follows this tasks structure:
> 1. add ssh key to ssh agent and disable checking ansible host key
> 2. clone ansible project
> 3. run relevant ansible playbook of each stage