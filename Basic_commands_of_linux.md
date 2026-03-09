------------------------- Basic Commands of Linux ------------------------

here, we use linux as CLI - Command line interface 

==> root@ : user 
==> master-node : hostname
==> ~] : present working Directory 
==> # : user login 


------------------ uses of commands and syntax of commands 
1. Command 
2. Command Option
3. Command option arguments 
4. Command arguments 

1) commands : 
    1. pwd : present working directory 
    2. cs : change directory 
    3. ll : (long list ) provide all details about directories and files 
    4. ls : (list short) not providing all details 
    5. ll - a: a= all (if you want to hidden files)
    6. (.) : . for hidden  files 
    Ex: .ssh, .hiloni, etc.. 
    7. ll -ld : to see particular folder using long list 
    Note: without changing directory
    8. history : Provide all history of commands which is run in terminal 
    9. date : show current date in terminal (date show all thing Ex: date, time, day, ..)
    10. date -- help : provide options
    11. man : manual page (how to run)
    12. man date : provide options and details 


Ex : date + %a
 + : is mendatory for show days or any date related commands (options).
 %a : abberiates week days (mon, sun,)

    13. cal : show calender

    cal - 1 : show January
    cal - 2 : show jan, feb
    cal -- help : show all details and command options 

    14. whoami : present Identity of directory 
    Ex: root 

    - whoami : root 
    - hostname : worker - node 
    15. touch : create a new file 
    Ex : touch text.txt, touch file.txt

    16. mkdir : create a directory 
    Ex : mkdir grras 

    17. touch file {1....10}.txt
    (It create to files)

    