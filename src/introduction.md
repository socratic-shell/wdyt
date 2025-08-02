# Introduction

## What This Project Is About

This directory contains a testing and evaluation tool for judging the effectiveness of AI "experiences" - not just whether AI systems get the right answer, but how the interaction itself feels and functions.

The core insight driving this work is that AI effectiveness isn't just about accuracy or task completion. It's about the quality of collaboration, the rhythm of interaction, and the subjective experience of working with the system. These qualitative aspects are crucial but difficult to measure systematically.

## The Problem

When experimenting with AI system prompts, tool descriptions, and other configuration changes, we often get intuitive impressions that the system "works less well" or "feels better" somehow, but it's very hard to assess these changes rigorously. We need tools to:

1. **Capture the full context** that shapes each interaction - not just the final outputs, but the prompts, tool descriptions, project files, and conversation history that influenced the AI's behavior
2. **Analyze interaction patterns** - where did the AI jump to action prematurely? Where did users need to redirect or correct? What does good collaborative attention look like?
3. **Track code quality evolution** - for coding tasks, how many iterations were needed? What kinds of errors occurred? Did the AI learn from compiler feedback effectively?

## Our Approach

We're building evaluation tools that can:

- **Snapshot and record** complete conversation transcripts along with all context files that produced them
- **Analyze attention quality** using pattern recognition to identify moments of good vs. poor collaborative behavior
- **Track code iteration patterns** to understand how AI-generated code evolves and what kinds of mistakes are common
- **Provide actionable insights** about what makes prompts, tool descriptions, and other system inputs more effective

## Two Evaluation Tracks

This project focuses on two complementary but distinct evaluation dimensions:

### 1. Collaboration Process Quality
How well does the AI engage in the collaborative process? Does it:
- Ask clarifying questions before jumping to implementation?
- Surface genuine concerns rather than just agreeing diplomatically?
- Wait for explicit agreement before taking action?
- Approach problems with beginner's mind rather than false confidence?

### 2. Technical Output Quality
For coding tasks specifically: Does the AI generate more idiomatic, correct code? Does it:
- Require fewer iterations to reach working solutions?
- Learn effectively from compiler feedback?
- Avoid common language-specific pitfalls?
- Follow project conventions and best practices?

## The Meta-Recursive Nature

There's something beautifully recursive about this project: we're using AI collaboration patterns to build a tool that evaluates AI collaboration patterns. The very techniques we've developed for effective human-AI partnership become the criteria by which we judge system improvements.

This creates a feedback loop where insights from our collaborative process directly inform the evaluation framework, which in turn helps us refine the collaboration patterns themselves.

## Next Steps

The following chapters detail:
- The specific collaboration patterns we've identified and want to measure
- How to design evaluation frameworks that capture subjective interaction quality
- Methods for analyzing code quality and iteration patterns
- Concrete implementation plans for building these evaluation tools

This is inherently an iterative project - we'll learn by building, measuring, and refining our approach based on what we discover.
