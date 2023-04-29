# ChatGPTCodePrompts
Here are my code prompts

# # General formating

## ## Format anything

~~[t~~emplate]

{INSERT TEMPLATE HERE - EXAMPLE  1/EXAMPLE  2}

[end of template]

Start of  Instructions

Please format text found in  [Text to be formatted]  in the exact same format as [template]. The
syntax is to be the exact same. Do not provide any explanations. Do not include the text example. Do not respond
with anything except the output of text from [Text to be formatted]

End of instructions

[Text to be formatted]

{INSERT FORMATED TEXT HERE}

[end of text to be formatted]

# SQL Generate data

## SQL insert data

> I want you to act as a SQL terminal in front of an example database.
>
> I will type in a database structure and you will reply with what the terminal would show with examples of inserting data for this database structure.
>
> The database structure is as below [INSERT SQL]
>
> I want you to reply with a commands to insert data with examples. Do not write explanations. Do not type commands unless I instruct you to do so.

## Create database

> Prompt 1
>
> I would like you to act as a database architect. I will ask you to look at an existing database in the below SQL [Insert SQL]  . Then I will ask you to update the SQL based on a new logical database design with updated table and attributes as well as new tables/tables to be removed. Say yes if you understand
>
> Prompt 2
> Here is the new logical database where the attributes are updated. please update the SQL [INSERT table and attributes]. Please provide the SQL commands for tables and attributes that need adjustments or new tables to be created as well as tables that should be deleted.

## # Python

# ## Python terminal

> I want you to act like a Python interpreter. I will give you Python code, and you will execute it. Do not provide any explanations. Do not respond with anything except the output of the code. The first code is: "print('hello world!')

# ## Data science

I want you to act as a data scientist and write Python code to [clean, analyze, visualize, or model] a dataset on [a specific topic].

## Python development

I want you to act as a Python developer and write a function that takes a data type as an input and returns the output.

# ## Python programming

I want you to act as a Python programmer and create a program that does something specific using a specific library.

## # General developing

## Create a code snippet

I want you to act as a code generator and provide a [programming language/technology/framework] code snippet for [specific programming task or function].

## Generate sample code

I want you to act as a code generator and provide a [programming language/technology/framework] code snippet for [specific library or framework] usage.

## Handle error or exception

I want you to act as a code generator and provide a [programming language/technology/framework] code snippet for handling [specific error or exception] in [programming language].

## Algorithm or data structure

I want you to act as a code generator and provide a [programming language/technology/framework] code snippet for [specific algorithm or data structure].

## UI component or feature

I want you to act as a code generator and provide a [programming language/technology/framework] code snippet for [specific UI component or feature].

## Algorithm/data structure

Can you generate a code snippet for [specific algorithm/data structure] in [programming language/technology/framework]?

## Specific functionality

Please provide a code snippet for [specific functionality] in [programming language/technology/framework].

## Library or tool usage

Give me a code snippet that demonstrates how to use [specific library or tool] in [programming language].

## Specific task

I want you to act as a code generator and provide a [programming language/technology/framework] code snippet for [specific task].

## # Improving code

## Code review and improvements

I want you to act as a code reviewer and review my [programming language/technology/framework] code for [specific task]: [paste your code here].

## Potential bugs or errors

I want you to act as a code reviewer and point out any potential bugs or errors in my [programming language/technology/framework] code: [paste your code here].

## Readable and maintainable code

I want you to act as a code reviewer and explain how to write more readable and maintainable [programming language/technology/framework] code.

## Security vulnerabilities review

I want you to act as a code reviewer and review my [programming language/technology/framework] code for security vulnerabilities and suggest any fixes: [paste your code here].

## Feedback and improvements

Can you provide feedback on my [programming language/technology/framework] code and suggest some improvements?

## Bugs and optimization opportunities

Please review my [programming language/technology/framework] code for potential bugs and optimization opportunities.

## Specific task code review

I want you to act as a code reviewer and review my [programming language/technology/framework] code for [specific task].

## Predicting Errors

Predict any potential errors or bugs in my [programming language/technology/framework] code related to [specific functionality or module]: [paste your code here].

## Specific Issue and Fix

What could be causing [specific issue] in my [programming language/technology/framework] code and how to fix it: [paste your code here].

## Preventing Errors

Explain how to prevent [specific type of error or bug] in my [programming language/technology/framework] code: [paste your code here].

# SQL


## SQL Query Review

Review my SQL query and suggest any improvements or optimizations: [paste your SQL query here].

## SQL Error Detection

Point out any potential errors or issues in my SQL query: [paste your SQL query here].

## SQL Query Explanation

Explain how my SQL query works and any potential improvements for better performance: [paste your SQL query here].

## SQL Security Review

Review my SQL query for security vulnerabilities and suggest any fixes: [paste your SQL query here].

## SQL Query Feedback

Can you provide feedback on my SQL query and suggest some improvements? [paste your SQL query here].

# Javascript

## Act as a JavaScript Console
I want you to act as a javascript console. I will type commands and you will reply with what the javascript console should show. I want you to only reply with the terminal output inside one unique code block, and nothing else. do not write explanations. do not type commands unless I instruct you to do so. when I need to tell you something in english, I will do so by putting text inside curly brackets {like this}. My first command is console.log("Hello World");
