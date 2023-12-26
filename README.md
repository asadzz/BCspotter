# BCspotter
Bad character spotter for exploit writers
# BCspotter

## Introduction

BCspotter is a Python script designed to ease the process of finding bad characters in memory dumps, specifically in the context of exploit development. The inspiration for this project came from the "Finding Bad Characters" course video by Heath Adams (TCM), where he referred to the task of finding bad characters as an "eye-spotting exercise."

As someone who has experienced the challenges of identifying bad characters in memory dumps using tools like Immunity Debugger, I wanted to automate and simplify this process. BCspotter serves as a tool to automate the detection of bad characters, making it less prone to human error and significantly reducing the time and effort required for this task.

## How It Works

BCspotter reads a memory dump file, identifies hex values, and compares them against a predefined list of bad characters. It then provides a list of absent bad characters, streamlining the identification process.

## Features

- Automatic detection of bad characters in memory dumps.
- Efficient comparison against a predefined list of bad characters.
- Simplifies the "eye-spotting exercise" mentioned in exploit development.

## Usage

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/asadzz/BCspotter.git
   
