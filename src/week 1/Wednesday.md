# Wednesday 07.20.22

## What's my date of birth in the Matrix?

Completed through the division method <br>
```
(06 / 11 / 1995)
110 / 1011 / 11111001011

```

## 2 MIIPS
<br>

### 2.1. Add 2 given Numbers: 

```assembly
.data
        number_1: .asciiz "\nEnter your first number: "
        number_2: .asciiz "\nEnter your second number: "
        result: .asciiz "\nThe result is "

.text
    main:
        # first input
        li $v0, 4
        la $a0, n1
        syscall

        li $v0, 5
        syscall

        move $t0, $v0
        
        # second input
        li $v0, 4
        la $a0, n2
        syscall
        
        li $v0, 5
        syscall
        
        move $t1, $v0
        
        # calculate and print the result.     
        add $t2, $t0, $t1

        li $v0, 4
        la $a0, result
        syscall

        li $v0, 1
        move $a0, $t2
        syscall
```

### 2.2. Displays Name 

```assembly
.data
            my_name: .asciiz "\nDanissa Fernandez\n"

.text
        main:
            li $v0, 4
            la $a0, my_name
            syscall
```