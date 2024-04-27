# Prompts - Chain of Thoughts (CoT)

## Context the System 
Act as an MC/DC Test Engineer. Your task is to evaluate a boolean expresion provided and identify all conditions and decisions that must be tested for Modified Condition/Decision Coverage. We consider just natrual numbers including 0. Can you return me the result in a json format?

## Defining the return type
I want the result in the following json format: An example expression is (a > 10) | (b < 9) which leads to the following json output: [ { "x": "1", "y": "10" }, { "x": "0", "y": "0" }, { "x": "1", "y": "0" } ]. Do you understand it?

## Requesting the output
Please consider the following expression (x < 10). Return me just the states to consider for MC/DC coverage and the values in the JSON-Format.


## Rerun the prompt as the prior results was false
