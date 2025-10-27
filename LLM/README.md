# LLMs
Here i explored and learned fundamental principles for building LLMs. 
First looking at building and understanding the basics of what goes into
a LLM. Then exploring more complicated concepts and building a better LLM

## MiniLLM
I first created a very basic LLM using only numpy and one or two other libraries
See my very basic implementation in `miniLLM.ipynb`.
This was to learn how each component of a LLM works and to build a very basic,
character level based LLM.
- Understandably, this LLM did not perform very well
- But it works and build my foundational understanding and skills

## Bigger and Better LLM
In `Bigger_Better_LLM.ipynb` I demonstrate everything learnt from the book 
[Build a Large Language Model (From Scratch)](https://github.com/rasbt/LLMs-from-scratch)
. Here I build and LLM using pytorch and huggingface, then applied pretrained
weights to improved training and performance.
- performed much better than my original MiniLLM