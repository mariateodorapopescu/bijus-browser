# Website Management System

This project involves handling and processing data related to websites, including their structure, content, and specific tasks. Below, you'll find an overview of the main components and their functionalities:

## util.h

### Overview
- **Time Spent:** Three hours
- **Description:** The `util.h` file plays a crucial role in initializing essential structures and functions needed for the entire project. Initially, the `add_website` function was designed for the main array of websites. However, after modifications, it now accepts a `struct website**` as a parameter, allowing its use for constructing other arrays as well.

## task1.c

### Overview
- **Time Spent:** Two minutes
- **Description:** Before the implementation of `util.h`, this file was responsible for displaying websites as they were added to the array. Post-modifications, with the separation of concerns, `task1.c` now simply contains a loop with `printf` statements.

## task2.c

### Overview
- **Time Spent:** Three hours
- **Description:** This file focuses on reading input from `stdin` character by character. A string containing all words is created because using two `strtok` calls simultaneously is not viable. A frequency array is utilized to determine whether each site should be displayed or not.

## task3.c

### Overview
- **Time Spent:** Two hours
- **Description:** Similar to `task2.c`, this file reads input character by character. Additionally, it includes the handling of words with hyphens. The frequency array is marked based on whether at least one word from `stdin` is found in the site's content. If the content includes a word with a hyphen, it is not marked in the frequency array.

## task4.c

### Overview
- **Time Spent:** Over four hours (including two for addressing an extra '\n' in the site's content)
- **Description:** Reading all URLs from `stdin`, this file checks if they exist in the list of websites. If a match is found, the checksum is calculated. The `rotl` and `rotr` functions are implemented, performing k % 8 circular shifts on the binary representation of each character.

## How to Use

Each task is implemented in a separate file. You can explore the code within each file for a detailed understanding of the functionalities. Feel free to reach out if you have any questions or suggestions for improvement. Happy coding! 🚀👩‍💻👨‍💻
