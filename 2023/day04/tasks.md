# Day 4 Task: Basic Linux Shell Scripting for DevOps Engineers.

 ## What is Kernel

 The kernel is a computer program that is the core of a computer’s operating system, with complete control over everything in the system.
 
 ## What is Shell

 A shell is special user program which provide an interface to user to use operating system services. Shell accept human readable commands from user and convert them into something which kernel can understand. It is a command language interpreter that execute commands read from input devices such as keyboards or from files. The shell gets started when the user logs in or start the terminal.
 
 ## What is Linux Shell Scripting?

 A shell script is a computer program designed to be run by a linux shell, a command-line interpreter. The various dialects of shell scripts are considered to be scripting languages. Typical operations performed by shell scripts include file manipulation, program execution, and printing text.

 **Tasks**

 - Explain in your own words and examples, what is Shell Scripting for DevOps.
    `It involves writing scripts using shell programming languages (e.g., Bash, PowerShell) to automate tasks and manage various aspects of the software development and IT operations lifecycle.`

 - What is `#!/bin/bash?` can we write `#!/bin/sh` as well?    `
    `#!/bin/bash is called a shebang or hashbang line`

 - Write a Shell Script which prints `I will complete #90DaysOofDevOps challenge`
    `vi filename.sh`
    # write the script
    `#!/bin/bash` 
    `echo "I will complete #90DaysOofDevOps challenge"`
    # then save and close this with below command
    `:wq`
    # call file `bash filename.sh`
    # [ref link for answer 2](./bash_img_1.PNG)
    
 - Write a Shell Script to take user input, input from arguments and print the variables.
     `vi filename.sh`
    --- write the script
    `#!/bin/bash` 
    `echo "I will complete #90DaysOofDevOps challenge"`
    `read -p "Enter your age"`
    `echo "your age is $1 "`
    `echo your first argument is $1`
    `echo your second argument is $2`
    --- dont add space in between variable name and its value
    `name="KAMAL" ` 
    `echo "${name} has print the variable name and also work with arguments"`
    --- then save and close this with below command
    `:wq`
    --- call file `bash filename.sh`
    # [ref link for answer 2](./bash_img_2.PNG)
    
 - Write an Example of If else in Shell Scripting by comparing 2 numbers
    `vi filename.sh`
    write the script
    #!/bin/bash

    # assign value to variable
    `var_1=$1 # arg1`
    `var_2=$2 # arg2`

    `if [ $var_1 -gt $var_2 ];`
    `then`
            `echo "$var_1 is grter then $var_2"`
    `else`
            `echo "$var_1 is less then $var_2"`
    `fi`
    # then save and close this with below command
    `:wq`
    # call file `bash filename.sh`     
    # [ref link for answer 2](./bash_img_3.PNG)

 Was it difficult?
   # Okay Okay 
 