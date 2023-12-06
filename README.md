# Simple To Do list as a CLI tool

Table of Contents

- [Overview](#overview)

- [How it works](#how-it-works)

## Overview

The simple-todos-cli-tool is a node.js application that can be downloaded from npm as a package. The package allows you to add, view, and mark tasks done.

<p align="right">(<a href="#simple-to-do-list-as-a-cli-tool">back to top</a>)</p>

## How it works

1. **To install the package:** 
    ```
    npm install simple-todos-cli-tool
    ```

2. **To add a tasks:** 
    ```
    todos add <tasks>
    ```

3. **To view existing tasks:** 
    ```
    todos list
    ```

4. **To mark tasks as done:** 
    - To mark all tasks as done:
    ```
    todos mark-done
    ```

    - To mark a specific task as done, specify the index of the task you have completed:
    ```
    todos mark-done -t 1
    ```

    - To mark multiple tasks as done, specify the indexes of the tasks you have completed:
    ```
    todos mark-done -t 1 3 6
    ```

    <p align="right">(<a href="#simple-to-do-list-as-a-cli-tool">back to top</a>)</p>
