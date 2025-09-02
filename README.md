# ai-experiments
A repo with a bunch of experiments of various AI code generators

This repo contains the output of a series of AI code generation experiments. I fed the following prompt to various AI models:

```
Make a web application that counts the number of times a keypress happens more than once for the same key within a short duration. To count as a duplicated keypress, it must be the same key pressed twice within the given time-frame. It needs to indicate duplicate keypresses in real-time. 

The app should have two inputs: the first takes the number of milliseconds and it indicates whether the keypresses are counted. The default value should be 50 milliseconds.

The second input is for the text input in which the user types.

The app should show which characters had multiple keypresses, and how many times the duplicates happened.

The app should run entirely in the browser (via Javascript) and be entirely built into a single file with the file with the name “index.html”. It should use dark-mode UI and ought to be stylized to look modern.
```

My goal was to see how well various AI models could understand and implement the requirements. The results were mixed, with some models producing functional code and others struggling with the specifications.


This page summarizes an experiment where various AI code generators were tasked with creating a web application that counts duplicated key presses in real-time. The goal was to evaluate how well these models understand complex requirements and produce functional, modern UI solutions.

Each section below provides a summary of the results for a specific AI model, including:
- A brief assessment of implementation quality
- Visual indicators (✅ Success / ⚠️ Danger) showing whether the application functions as expected
- A direct link to view the complete code in the generated `index.html` file

## GitHub Copilot (GPT-4.1)
The initial attempt by GitHub Copilot produced code that didn't work. The UI was basic and lacked modern design elements as requested in the prompt.

⚠️ Code didn't function:
[view results](github-gpt-4.1/index.html)

## GitHub Copilot (Sonnet 3.5)

✅ Success
[view results](github-sonnet-3.5/index.html)

