# HEXACO Personality Visualization Project

## Description:

This project is based on data from the HEXACO psychological assessment tool (https://hexaco.org/). The HEXACO acronym comes from these six dimensions of personality measured: Honesty-Humility, Emotionality, eXtraversion, Agreeableness (versus Anger), Conscientiousness, and Openness to Experience.

The survey itself consists of 100 questions, each mapped to one of the six personality dimensions. Respondents rate each question on a 5-point Likert scale, from 1 (strongly disagree) to 5 (strongly agree).

This project simulates 200 respondents, calculates their scores, and then displays the output using Plotly visualizations in a web UI using Dash.

Inspiration for this project taken from https://github.com/salastro/hexaco-person/blob/main/README.md

## How to Install & Run

This project uses a number of Python packages and tools. After you've cloned this repo, refer to `requirements.txt` to setup the required packages. For additional installation troubleshooting, please refer to these documentation pages as needed:

- Dash: https://dash.plotly.com/installation
- Pandas: https://pandas.pydata.org/getting_started.html
- Plotly: https://plotly.com/python/getting-started/

After packages are installed, open and run `main.py`; this is the single-source-of-truth file. You can run the file either by opening a terminal and running `python main.py` or click to run it within the VSCode interface:

![Image of where to click in VSCode to run a file](https://github.com/erincodes/hexaco-personality-viz/blob/main/images/run-file-VS-Code.png)

A message like this will appear in your terminal when `main.py` runs successfully: `Dash is running on http://127.0.0.1:8050/`. Navigate to the link provided to view the interactive web UI on a local server:

![Example of expected output in web browser](https://github.com/erincodes/hexaco-personality-viz/blob/main/images/output-iu-example.png)

## Potential Gotchas:

Presently, if you want to see different results in the web output, you will need to re-run `main.py`. A potential future enhancement is to include a way to regenerate a new group of X users from the UI and see what changes.
