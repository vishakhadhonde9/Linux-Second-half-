# Process Management in Linux-
# What is Process?
- Process is any program in its excecution.
- It generally takes an input, processes it and gives us the appropriate output.
- An active program which running now on the Operating System is known as the process.
# Why Process Management is required-
### 1)Resource Allocation-
### 2)Concurrency-
### 3)Isolation-
### 4)Process Prioritization-
### 5)Process Lifecycle-

# Types of Processes:

## Foreground Processes: 
- they run on the screen and need input from the user.
- also referred to as interactive processes
- for example: Office Programs
## Background Processes: 
- they run in the background and usually do not need user input.
- referred to as non-interactive or automatic processes
- for example: Antivirus.


#### &-
- Starts the command immediately in the background.
#### Ctrl+Z-
- Stops the job temporarily so that it can be managed.
- For instance, it can be moved to the background.
#### Ctrl+D- 
- Send the End Of File (EOF) character to the current job to indicate that it should stop waiting for further input.
#### Ctrl+C- 
- Can be used to cancel the current interactive job
#### bg- 
- Continues the job that has just been frozen using Ctrl+Z in the background.
#### fg-
- Brings the last job that was moved to background execution back to the foreground.
#### jobs-
- Shows which jobs are currently running from current shell. 
- Displays job numbers that can be used as an argument to the command bg and fg.
