[![Version](https://img.shields.io/static/v1?label=bayesian-data-analysis-voice-in&message=0.1&color=brightcolor)]
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

# bayesian-data-analysis-voice-in: Voice In commands related to Bayesian Data Analysis

## Introduction
This repo contains voice commands about Bayesian Data Analysis (BDA) for the speech recognition software Voice In Plus.
The utilization of these custom commands requires a subscription to Voice In Plus.
These commands can be used in the text area of most websites opened in Google Chrome.
They can be used during dictation of manuscripts about artificial intelligence.
This topic includes inside its envelope the topics of machine learning and deep learning.
Some of the commands including equations that are represented as LaTeX math.
These short snippets of LaTeX are recognized and rendered correctly by most markdown type setting languages, including org-mode--an enhanced form of Markdown that is best used from inside Emacs.

## Usage
After the commands have been uploaded, you can utilize them immediately.
I toggle Voice In on and off by using a keyboard shortcut.
I then dictate the command.
See the documentation for the Voice In plug-in to learn how to configure keyboard shortcuts.

## Installation
Each command is paired with the inserted text on a single line in of a comma separated value file (bda.csv).
Use the **bulk add** button in Voice In Plus to upload these commands into your collection of custom commands.

## Contents of the library ai.csv

- Acronyms used in artificial intelligence, including machine learning and deep learning.
- Key equations typeset in LaTeX.
- URLs of key websites.
- Names of key people in the field to ensure the correct spelling of their name.

## Related repos
See [Voice Computing section of landing page](https://github.com/MooersLab/MooersLab?tab=readme-ov-file#voice-computing)

## Rules for developing voice commands

### Pick word combinations rarely used in normal prose
The basic rule for developing a voice command is to pick a word combination that is very unlikely to be used in one's prose.
This choice can avoid the accidental insertion of an unintended set of words.

### Pick word combinations that do not contain other commands
If you pick a word combination with a subset of words already assigned to another command, the commands will collide, and you will not get the intended effect.
It is better to pick a synonym for the new command than include the old one.

### Use verbs are prefaces
I use the verb `insert` in front of the name for the computer code or equation that I want to insert.
I use the verb `expand` to expand acronyms.
I use `url` to insert a URL.

## Status
Ready to use but still under development.
