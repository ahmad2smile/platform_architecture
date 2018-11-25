# Platform Architecture

## Intro

Platform based architecture is a solution to boilerplate in our projects.

As a very keen student of Theory of Evolution I just applied its way of doing things to this architecture.

Evolution didn't keep its best gene pool in a separate vessel. Everything was in play all the time or it was just dropped out of race. Species (in our case projects) were introduced along the way with existing improvements that were available and they refined the process for next iteration/species.

No iteration was a failure of success just a step towards the next one.

Platform Architecture is system of Evolution. Every project that you would build based on this architecture would an iteration that would improve you Platform. But unlike Evolution its gonna have a guiding hand, we don't need to discard old project that were based on previous iterations of Platform. We can just bring them up to speed with lessons learned along the way (update the version).


## Usage

This architecture is generic enough that it doesn't relay on any tools or Programming Paradigm. To implement this there needs to be a Platform "go figures". Its essentially the bare minimum setup that is gonna be common among iterations. 

It being the platform it gonna keep growing as iterations pass. As every iteration adds things to the platform it can also remove dead things out of it too if its certain that those parts are absolutely don't server any purpose anymore.

When a new project/iteration is required that iteration brings along its features that are unique to it (else they be in common setup i.e platform) through common interface and Platform spits out a new iteration. This is creation time, at this moment iteration provide all its feature requirements and gets generated. 

The main concept of this setup is the Platform is the endpoint. It generates outputs. It doesn't gets plugged into anything rather iterations/projects get plugged in to Platform just like a USB stick gets plugged into a PC not the other way around.

## Examples

Examples are WIP. Links will be posted here.

A Xamarin Framework and a React App implementation is underway but its core concept looks something like following,

