# GPT-Humanizer
a Pynecone app that converts AI-generated text into human-readable text, allowing users to bypass AI detection.

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
        <li><a href="#create your first pynecone App">Create your first Pynecone App</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->
## About The Project

![GPT-Humanizer](https://ibb.co/hVhvH21)
![AI Detection](https://ibb.co/dLWV3vC)

The purpose of this project is to convert AI-generated text into human-readable text, allowing users to bypass AI detection.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- GETTING STARTED -->
## Getting Started

This project is built on the new [Pynecone] Python framework that allows making web-apps in pure Python.

### Prerequisites
* Python 3.7+
* [Node.js 12.22.0+](https://nodejs.org/en/) (Don't worry, you'll never have to write any Javascript)
* [OpenAI API Key](https://platform.openai.com/account/api-keys)
* [Pynecone](https://github.com/pynecone-io/pynecone)
* [OpenAI 0.27.2](https://pypi.org/project/openai/)

### Installation

1. Get a free [API Key](https://platform.openai.com/account/api-keys)
2. Install [Node.js](https://nodejs.org/en/)
3. Install Pynecone
   ```sh
   pip install pynecone
   ```
   
4. Install OpenAI
   ```sh
   pip install openai==0.27.2
   ```
   
5. Enter your API in `gpt-humanizer.py`
   ```py
   openai.api_key = 'ENTER YOUR API KEY'
   ```
   
### Create your first Pynecone App

Installing Pynecone also installs the `pc` command line tool. Test that the install was successful by creating a new project.

Replace `my_app_name` with your project name (preferably `gpt-humanizer`):
```sh
mkdir my_app_name
cd my_app_name
pc init
```
When you run this command for the first time, it will download and install [bun](https://bun.sh) automatically.

This command initializes a template app in your new directory. You can run this app in development mode:
```sh
pc run
```
You should see your app running at [http://localhost:3000](http://localhost:3000).

Now you can modify the source code in `my_app_name/my_app_name.py`. This is where you copy my code from `gpt-humanizer.py` and paste it in yours. Pynecone has fast refreshes so you can see your changes instantly when you save your code.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- USAGE EXAMPLES -->
## Usage
After initialising your directory, copying my code in `gpt-humanizer.py` and pasting it in `my_app_name/my_app_name.py`, running it from terminal with `pc run`, you should see a text box that lets you input text. Copy any AI generated text and paste it in there, wait a few seconds and click "Humanize" for better results. Usually, the output text above the "Humanize" button is sufficient enough to bypass AI detection, but sometimes it may not be as accurate; this is why you must click "Humanize", scroll down and copy the text that was rewritten. Also understand that it may be slow due to GPT-servers. 

<p align="right">(<a href="#readme-top">back to top</a>)</p>
