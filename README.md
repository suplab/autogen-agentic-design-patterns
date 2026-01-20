# AI Agentic Design Patterns with AutoGen

This repository contains practical implementations of core agentic design patterns using AutoGen, a framework for building LLM-powered multi-agent systems. The focus is on role-based agents, structured collaboration, tool invocation, reflection loops, and human-in-the-loop workflows.

The repository is organized as a learning-by-building resource. Each example demonstrates a distinct agentic pattern applied to a concrete problem.

## What This Repository Covers

* Multi-agent conversations with explicit roles
* Sequential and nested agent interactions
* Agent reflection and critique loops
* Tool-using agents with constrained actions
* Coding agents for data analysis and visualization
* Human feedback integrated into agent workflows

## Implemented Scenarios

1. Two-Agent Conversational System

A conversational system built using `ConversableAgent`, simulating a dialogue between two stand-up comedians. Demonstrates:

- Turn-based agent interaction
- Role prompting
- Conversation control

2. Multi-Agent Customer Onboarding Flow

A sequence of coordinated agents delivering a playful product onboarding experience. Demonstrates:

- Multi-agent collaboration pattern
- Controlled message handoff
- Task-oriented agent sequencing

3. Blog Generation with Agent Reflection

A high-quality blog post generated through an agent reflection framework. Demonstrates:

- Writer agent producing content
- Critic agent coordinating nested reviewer agents
- Iterative refinement via nested chats

4. Tool-Using Conversational Chess Game

Two chess-playing agents capable of making legal moves by invoking a chess tool. Demonstrates:

- Tool use design pattern
- Action validation
- Constrained agent behavior

5. Coding Agent for Financial Visualization

A coding agent that generates Python code to plot stock gains. Demonstrates:

- Code generation
- Function calling
- Integration of user-defined utilities

6. Collaborative Financial Analysis Agents

Two systems for financial analysis with agent collaboration and human feedback:

- System A: Agents generate analysis code from scratch
- System B: Agents extend and reason over user-provided code

Demonstrates:

- Human-in-the-loop workflows
- Multi-agent reasoning
- Code critique and refinement

## Agentic Design Patterns Demonstrated

* Multi-Agent Collaboration
* Reflection and Self-Critique
* Tool Use
* Planning and Task Decomposition
* Human Feedback Integration

## Learning Objectives

* Use the AutoGen framework to build multi-agent systems with diverse roles and capabilities for implementing complex AI applications.
* Implement agentic design patterns: Reflection, Tool use, Planning, and Multi-agent collaboration using AutoGen.
