# Computers

## General

### What makes a computer?

After ages of creating machines that could help them with manual work, humans began to wonder if they could invent one that would help them with *"thinking"* work, so they came up with the computer.

Unlike traditional machines that were made to manipulate physical things, computers had to be designed so they could manipulate *information*.

Every **computer** has four main tasks: Take *input*, *store* information, *process* it and then *output* the results.

### Early Computers

The first computers were made out of wood and metal, with mechanical levers and gears. By the twentieth century though, they started using electrical components. However, those computers were massive, they were the size of an entire room and they were incredibly slow. It would take them hours just to solve a basic mathematical problem.

Back in the day, computers were basically just huge calculators, which was very awesome at the time. Modern computers look nothing like they used to, but they still perform those same four tasks mentioned earlier.

### Input

In simple terms, **input** is a command that you give the computer. It can be in all types and forms.

### Storage and Processing

After storing given input in memory, the computer takes it and manipulates it using *algorithm* (a series of commands) and then it sends the results back to the storage again. The information is now ready to be *output*.

### Output

*Output* can be anything, not just text. It can be photos, videos, games, signals etc.

When two computers connect to the internet, the output of one can be the input of another.

## Binary Data

Computers work with **ones** and **zeroes**, but what does that mean?

Inside a computer are electric wires and circuits that carry all the information in it. But how do you store or represent information using electricity?

If you have a single wire with electricity flowing through it, the signal can only be on (Yes/True : 1) or off (No/False : 0). The on/off state is called a **bit**, which is the smallest piece of information a computer can store. So more wires equal more bits (ones and zeroes) and representation of more complex information.

| Circuit On | Circuit Off |
| --- | --- |
| Yes State | No State |
| 1 | 0 |

### The Binary Number System

There are multiple number systems, the one we normally use is called the *decimal system* (0, 1, 2, 3...). Computers however, use the *binary system* (0 or 1). With these two digits, we can represent any number depending on how many wires we have. But what about other types of data like text, images or sound?

### Text in Binary

For every letter in the alphabet, we assign a decimal number which we can translate into binary. Example: The letter "A", we assign to the decimal number 1, which would be 0001 in binary. This way, we can represent any letter in the alphabet using wires. Modern computers however, use **ASCII** or **Unicode**.

| Letter | Decimal | Binary |
| --- | --- | --- |
| A | 0 | 0000 |
| B | 1 | 0001 |
| C | 2 | 0010 |
| D | 3 | 0011 |
| E | 4 | 0100 | 

### Images in Binary

Images, videos and graphics are made out of tiny dots called **pixels**. Each pixel has a color, and each color can be represented with numbers.

### Sound in Binary

Every sound is a series of vibrations in the air, these can be represented graphically as a *waveform*. This way, any sound can be broken down into a series of numbers. More bits equal better sound quality.

## Circuits

In order to *process* **input** and create **output**, a computer uses millions of tiny *electronic components* that form **circuit**.

### Types of Circuits

There are lots of types of **circuits**, some of them include:

* *NOT*; The signal that comes in is **not** the signal that comes out (0 turns into a 1 and vice versa).
* *AND*; Takes in two signals.
| Input | Output |
| --- | --- |
| 0 & 0 | 0 |
| 0 & 1 | 0 |
| 1 & 1 | 1 |

So both signals have to be **on** in order to output a 1.

* *OR*; Takes in to signals, only one of both has to be **on** for an output of 1.

Complicated circuits take *multiple* signals and *combine* them to give different results.

### Logic Gates

By connecting circuits together, we can create complex circuits that can perform more complex calculations.

For example, you can make a circuit that adds two bits together called an **adder**. The result is of course calculated in *binary* which is then translated into decimal.

If we only have two circuits, we can only add up to a binary number of 11, so 3 in decimal. To be able to calculate numbers larger than that, you have to put more adder circuits together. Here's an example of an 8-bit adder:

Let's say you want to add 25 and 50. Each number is represented using eight bits so it's 00011001 and 00110010 respectively, resulting in 16 different electrical signals that go into the circuit. This big circuit though, contains eight different adder circuits inside of it which can together calculate the sum. The same goes for other mathematical operations.

The reason modern computers can perform calculations much, much faster than older computers, is because the electrical signal has to travel a lot less distance in those tiny chips compared to in the huge computers we had back in the day.

## CPU, Memory, Input & Output

**CPU** stands for *Central Processing Unit*. It's main task is to calculate information after *input* and *storage*.

### How information travels through the CPU

Let's go through an example of what happens when you press the letter "B" on your keyboard;

When you press the letter on your keyboard, it gets converted into binary which gets sent into the computer. Starting from this binary number, the CPU requests information from memory on how to draw the letter "B", it then runs these instructions and stores the results as pixels into memory. Finally, this pixel information gets sent to the screen which is an output device.

The more complicated a task is, the more information that's input or output, the more processing power and memory a computer needs. Modern computers however, already have multiple CPU's and more GigaBytes of memory.

## Hardware and Software

