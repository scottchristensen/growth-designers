# Guide: Installing and Using the Synthetic User Feedback Skill with Claude

## Overview
This guide explains how to install and use the synthetic user feedback skill created for Claude. This skill allows Claude to act as defined personas, perform actions, and provide stream of consciousness feedback, followed by final feedback. It is useful for quick spot checks and catching details that might otherwise be missed or take extensive in-person user feedback.

## Getting Started: Skill Installation

To install the skill, you can tell Claude to install it. For example, you can say: "Please install the skill."

## Setting Up Personas

When you download the skill, the persona section will either be empty or contain a template. You can fill this in with your own users or modify the skill to point to your existing personas. The example provided in the video uses personas like an entrepreneur, a direct-to-product marketing professional, a product manager, and a customer success leader.

## Running the Skill

1.  **Start a Claude Session**: Begin a Claude session with the Chrome extension active. This allows Claude to interact more deeply, such as clicking into LinkedIn profiles or logging into products. Playwright can also run in the background.
2.  **Input the Command**: Paste the command to run the synthetic feedback. An example command is `run synthetic feedback`.
3.  **Specify Target**: Indicate what the skill should run against. For instance, `run synthetic feedback against Cloudfluent`.

Essentially, this process instructs Claude to pretend to be your defined personas, perform an action, provide stream of consciousness feedback during the process, and then offer final feedback at the end.

## Interpreting the Results

After running the skill, you will receive:

*   **Stream of Consciousness Simulation**: This provides insights into the thought process of the different personas, which can be surprisingly useful for understanding their headspace.
*   **Summary**: A summary of the feedback for each persona. This includes observations like visibility of team pricing or emotional responses to content.
*   **Document Output**: The results will be compiled into a document. If you have a `docs` folder, it will be placed there. Otherwise, a `user research` folder will be created for it.

## Use Cases and Benefits

This skill has been found tremendously useful for:

*   **Quick Validation**: Rapidly spot-checking and validating ideas or changes.
*   **Spotting Details**: Identifying small details that might be overlooked with traditional feedback methods.
*   **Pricing Revamps**: Useful for understanding user skepticism, such as when pricing isn't immediately visible or listed discounts for larger organizations are absent.
