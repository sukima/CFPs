# Component Communications

## Abstract

Over the course of five years I've seen and handled many confusing questions concerning how components talk to each other. What is Data Down; Actions Up and why is Two-Way binding a bad thing? How do I pass a message to a child component? Who is responsible for what?

I will use the example of making a custom Modal Dialog to illustrate communication between components. Modals are good example as the use for opening/closing one is typically JavaScript driven and yet the implementation is template based. I will introduce concepts about providing a parent component an API to control a Modal instance, waiting for the modal to resolve, and using the resolution data.

## Presented at
