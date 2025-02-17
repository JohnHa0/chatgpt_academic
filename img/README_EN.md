# ChatGPT Academic Optimization
> **Note**
>
> This English readme is automatically generated by the markdown translation plugin in this project, and may not be 100% correct.
>


**If you like this project, please give it a star. If you have come up with more useful academic shortcuts or functional plugins, feel free to open an issue or pull request (to the `dev` branch).**

> **Note**
>
> 1. Please note that only function plugins (buttons) marked in **red** support reading files, and some plugins are located in the **dropdown menu** in the plugin area. Additionally, we welcome and process PRs for any new plugins with the **highest priority**!
>
> 2. The functions of each file in this project are detailed in the self-translation report [self_analysis.md](https://github.com/binary-husky/chatgpt_academic/wiki/chatgpt-academic%E9%A1%B9%E7%9B%AE%E8%87%AA%E8%AF%91%E8%A7%A3%E6%8A%A5%E5%91%8A). With the version iteration, you can click on a relevant function plugin at any time to call GPT to regenerate the self-analysis report for the project. Commonly asked questions are summarized in the [`wiki`](https://github.com/binary-husky/chatgpt_academic/wiki/%E5%B8%B8%E8%A7%81%E9%97%AE%E9%A2%98).
>
> 3. If you are not used to the function, comments or interface with some Chinese names, you can click on the relevant function plugin at any time to call ChatGPT to generate the source code of the project in English.

<div align="center">
    
Function | Description
--- | ---
One-click refinement | Supports one-click refinement, one-click searching for grammatical errors in papers.
One-click translation between Chinese and English | One-click translation between Chinese and English.
One-click code interpretation | Can correctly display and interpret the code.
[Custom shortcuts](https://www.bilibili.com/video/BV14s4y1E7jN) | Supports custom shortcuts.
[Configure proxy server](https://www.bilibili.com/video/BV1rc411W7Dr) | Supports configuring proxy server.
Modular design | Supports custom high-order experimental features and [function plug-ins], and plug-ins support [hot update](https://github.com/binary-husky/chatgpt_academic/wiki/%E5%87%BD%E6%95%B0%E6%8F%92%E4%BB%B6%E6%8C%87%E5%8D%97).
[Self-program analysis](https://www.bilibili.com/video/BV1cj411A7VW) | [Function Plug-in] [One-Key Understanding](https://github.com/binary-husky/chatgpt_academic/wiki/chatgpt-academic%E9%A1%B9%E7%9B%AE%E8%87%AA%E8%AF%91%E8%A7%A3%E6%8A%A5%E5%91%8A) the source code of this project.
[Program analysis](https://www.bilibili.com/video/BV1cj411A7VW) | [Function Plug-in] One-click can analyze other Python/C/C++/Java/Golang/Lua/Rect project trees.
Read papers | [Function Plug-in] One-click reads the full text of a latex paper and generates an abstract.
Latex full-text translation/refinement | [Function Plug-in] One-click translates or refines a latex paper.
Batch annotation generation | [Function Plug-in] One-click generates function annotations in batches.
Chat analysis report generation | [Function Plug-in] Automatically generate summary reports after running.
[Arxiv assistant](https://www.bilibili.com/video/BV1LM4y1279X) | [Function Plug-in] Enter the arxiv paper url and you can translate the abstract and download the PDF with one click.
[PDF paper full-text translation function](https://www.bilibili.com/video/BV1KT411x7Wn) | [Function Plug-in] Extract title and abstract of PDF papers + translate full text (multi-threaded).
[Google Scholar integration assistant](https://www.bilibili.com/video/BV19L411U7ia) (Version>=2.45) | [Function Plug-in] Given any Google Scholar search page URL, let GPT help you choose interesting articles.
Formula display | Can simultaneously display the tex form and rendering form of formulas.
Image display | Can display images in Markdown.
Multithreaded function plug-in support | Supports multi-threaded calling of chatgpt, one-click processing of massive texts or programs.
Support for markdown tables output by GPT | Can output markdown tables that support GPT.
Start dark gradio theme [theme](https://github.com/binary-husky/chatgpt_academic/issues/173) | Add ```/?__dark-theme=true``` to the browser URL to switch to the dark theme.
Huggingface free scientific online experience](https://huggingface.co/spaces/qingxu98/gpt-academic) | After logging in to Huggingface, copy [this space](https://huggingface.co/spaces/qingxu98/gpt-academic).
[Mixed support for multiple LLM models](https://www.bilibili.com/video/BV1EM411K7VH/) ([v3.0 branch](https://github.com/binary-husky/chatgpt_academic/tree/v3.0) in testing) | It must feel great to be served by both ChatGPT and [Tsinghua ChatGLM](https://github.com/THUDM/ChatGLM-6B)!
Compatible with [TGUI](https://github.com/oobabooga/text-generation-webui) to access more language models | Access to opt-1.3b, galactica-1.3b and other models ([v3.0 branch](https://github.com/binary-husky/chatgpt_academic/tree/v3.0) under testing).
… | ...

</div>

<!-- - New interface (left: master branch, right: dev development frontier) -->
- New interface (modify the `LAYOUT` option in `config.py` to switch between "left and right layout" and "up and down layout").
<div align="center">
<img src="https://user-images.githubusercontent.com/96192199/230361456-61078362-a966-4eb5-b49e-3c62ef18b860.gif" width="700" >
</div>

- All buttons are dynamically generated by reading `functional.py`, and custom functions can be added freely, freeing up the clipboard.
<div align="center">
<img src="公式.gif" width="700" >
</div>

- Refinement/Correction
<div align="center">
<img src="润色.gif" width="700" >
</div>

- Supports markdown tables output by GPT.
<div align="center">
<img src="demo2.jpg" width="500" >
</div>

- If the output contains formulas, both the tex form and the rendering form are displayed simultaneously for easy copying and reading.
<div align="center">
<img src="https://user-images.githubusercontent.com/96192199/230598842-1d7fcddd-815d-40ee-af60-baf488a199df.png" width="700" >
</div>

- Don't want to read project code? Let chatgpt boast about the whole project.
<div align="center">
<img src="https://user-images.githubusercontent.com/96192199/226935232-6b6a73ce-8900-4aee-93f9-733c7e6fef53.png" width="700" >
</div>

- Multiple large language models mixed calling. ([v3.0 branch](https://github.com/binary-husky/chatgpt_academic/tree/v3.0) in testing)


## Running Directly (Windows, Linux or MacOS)

### 1. Download the Project
```sh
git clone https://github.com/binary-husky/chatgpt_academic.git
cd chatgpt_academic
```

### 2. Configure API_KEY and Proxy Settings

In `config.py`, configure the overseas Proxy and OpenAI API KEY, as follows:
```
1. If you are in China, you need to set an overseas proxy to use the OpenAI API smoothly. Please read the instructions in config.py carefully (1. Modify the USE_PROXY to True; 2. Modify the proxies according to the instructions).
2. Configure OpenAI API KEY. You need to register on the OpenAI official website and obtain an API KEY. Once you get the API KEY, configure it in the config.py file.
3. Issues related to proxy network (network timeout, proxy not working) are summarized to https://github.com/binary-husky/chatgpt_academic/issues/1
```
(Note: When the program is running, it will first check whether there is a private configuration file named `config_private.py`, and use the configuration in it to overwrite the same name configuration in `config.py`. Therefore, if you can understand our configuration reading logic, we strongly recommend that you create a new configuration file next to `config.py` named `config_private.py` and transfer (copy) the configuration in `config.py` to `config_private.py`. `config_private.py` is not managed by Git, which can make your privacy information more secure.)

### 3. Install Dependencies
```sh
# (Option 1) Recommended
python -m pip install -r requirements.txt   

# (Option 2) If you use anaconda, the steps are also similar:
# (Option 2.1) conda create -n gptac_venv python=3.11
# (Option 2.2) conda activate gptac_venv
# (Option 2.3) python -m pip install -r requirements.txt

# Note: Use the official pip source or the Ali pip source. Other pip sources (such as some university pips) may have problems. Temporary substitution method:
# python -m pip install -r requirements.txt -i https://mirrors.aliyun.com/pypi/simple/
```

### 4. Run
```sh
python main.py
```

### 5. Test Experimental Features
```
- Test C++ Project Header Analysis
    In the input area, enter `./crazy_functions/test_project/cpp/libJPG` , and then click "[Experiment] Parse the entire C++ project (input inputs the root path of the project)"
- Test Writing Abstracts for Latex Projects
    In the input area, enter `./crazy_functions/test_project/latex/attention` , and then click "[Experiment] Read the tex paper and write an abstract (input inputs the root path of the project)"
- Test Python Project Analysis
    In the input area, enter `./crazy_functions/test_project/python/dqn` , and then click "[Experiment] Parse the entire py project (input inputs the root path of the project)"
- Test Self-code Interpretation
    Click "[Experiment] Please analyze and deconstruct this project itself"
- Test Experimental Function Template (asking GPT what happened in history today), you can implement more complex functions based on this template function
    Click "[Experiment] Experimental function template"
```

## Use Docker (Linux)

``` sh
# Download Project
git clone https://github.com/binary-husky/chatgpt_academic.git
cd chatgpt_academic
# Configure Overseas Proxy and OpenAI API KEY
Configure config.py with any text editor
# Installation
docker build -t gpt-academic .
# Run
docker run --rm -it --net=host gpt-academic

# Test Experimental Features
## Test Self-code Interpretation
Click "[Experiment] Please analyze and deconstruct this project itself"
## Test Experimental Function Template (asking GPT what happened in history today), you can implement more complex functions based on this template function
Click "[Experiment] Experimental function template"
## (Please note that when running in docker, you need to pay extra attention to file access rights issues of the program.)
## Test C++ Project Header Analysis
In the input area, enter ./crazy_functions/test_project/cpp/libJPG , and then click "[Experiment] Parse the entire C++ project (input inputs the root path of the project)"
## Test Writing Abstracts for Latex Projects
In the input area, enter ./crazy_functions/test_project/latex/attention , and then click "[Experiment] Read the tex paper and write an abstract (input inputs the root path of the project)"
## Test Python Project Analysis
In the input area, enter ./crazy_functions/test_project/python/dqn , and then click "[Experiment] Parse the entire py project (input inputs the root path of the project)"

```

## Other Deployment Methods
- Use WSL2 (Windows Subsystem for Linux subsystem)
Please visit [Deploy Wiki-1] (https://github.com/binary-husky/chatgpt_academic/wiki/%E4%BD%BF%E7%94%A8WSL2%EF%BC%88Windows-Subsystem-for-Linux-%E5%AD%90%E7%B3%BB%E7%BB%9F%EF%BC%89%E9%83%A8%E7%BD%B2)

- nginx remote deployment
Please visit [Deploy Wiki-2] (https://github.com/binary-husky/chatgpt_academic/wiki/%E8%BF%9C%E7%A8%8B%E9%83%A8%E7%BD%B2%E7%9A%84%E6%8C%87%E5%AF%BC)


## Customizing New Convenient Buttons (Academic Shortcut Key Customization)
Open functional.py and add the entry as follows, and then restart the program. (If the button has been successfully added and is visible, both the prefix and suffix support hot modification and take effect without restarting the program.)

For example,
```
"Super English to Chinese Translation": {

    # Prefix, which will be added before your input. For example, it is used to describe your requirements, such as translation, code interpretation, polishing, etc.
    "Prefix": "Please translate the following content into Chinese, and then use a markdown table to explain each proprietary term in the text:\n\n", 
    
    # Suffix, which will be added after your input. For example, in conjunction with the prefix, you can bracket your input in quotes.
    "Suffix": "",
    
},
```
<div align="center">
<img src="https://user-images.githubusercontent.com/96192199/226899272-477c2134-ed71-4326-810c-29891fe4a508.png" width="500" >
</div>


If you invent a more user-friendly academic shortcut key, welcome to post an issue or pull request!

## Configure Proxy
### Method 1: General Method
Modify the port and proxy software corresponding in ```config.py```

<div align="center">
<img src="https://user-images.githubusercontent.com/96192199/226571294-37a47cd9-4d40-4c16-97a2-d360845406f7.png" width="500" >
<img src="https://user-images.githubusercontent.com/96192199/226838985-e5c95956-69c2-4c23-a4dd-cd7944eeb451.png" width="500" >
</div>


After configuring, you can use the following command to test whether the proxy works. If everything is normal, the code below will output the location of your proxy server:

```
python check_proxy.py
```

### Method Two: Pure Beginner Tutorial
[Pure Beginner Tutorial](https://github.com/binary-husky/chatgpt_academic/wiki/%E4%BB%A3%E7%90%86%E8%BD%AF%E4%BB%B6%E9%97%AE%E9%A2%98%E7%9A%84%E6%96%B0%E6%89%8B%E8%A7%A3%E5%86%B3%E6%96%B9%E6%B3%95%EF%BC%88%E6%96%B9%E6%B3%95%E5%8F%AA%E9%80%82%E7%94%A8%E4%BA%8E%E6%96%B0%E6%89%8B%EF%BC%89)

## Compatibility Testing

### Image Display:

<div align="center">
<img src="https://user-images.githubusercontent.com/96192199/228737599-bf0a9d9c-1808-4f43-ae15-dfcc7af0f295.png" width="800" >
</div>


### If the program can read and analyze itself:

<div align="center">
<img src="https://user-images.githubusercontent.com/96192199/226936850-c77d7183-0749-4c1c-9875-fd4891842d0c.png" width="800" >
</div>

<div align="center">
<img src="https://user-images.githubusercontent.com/96192199/226936618-9b487e4b-ab5b-4b6e-84c6-16942102e917.png" width="800" >
</div>

### Any other Python/Cpp project analysis:
<div align="center">
<img src="https://user-images.githubusercontent.com/96192199/226935232-6b6a73ce-8900-4aee-93f9-733c7e6fef53.png" width="800" >
</div>

<div align="center">
<img src="https://user-images.githubusercontent.com/96192199/226969067-968a27c1-1b9c-486b-8b81-ab2de8d3f88a.png" width="800" >
</div>

### Latex paper reading comprehension and abstract generation with one click
<div align="center">
<img src="https://user-images.githubusercontent.com/96192199/227504406-86ab97cd-f208-41c3-8e4a-7000e51cf980.png" width="800" >
</div>

### Automatic Report Generation
<div align="center">
<img src="https://user-images.githubusercontent.com/96192199/227503770-fe29ce2c-53fd-47b0-b0ff-93805f0c2ff4.png" height="300" >
<img src="https://user-images.githubusercontent.com/96192199/227504617-7a497bb3-0a2a-4b50-9a8a-95ae60ea7afd.png" height="300" >
<img src="https://user-images.githubusercontent.com/96192199/227504005-efeaefe0-b687-49d0-bf95-2d7b7e66c348.png" height="300" >
</div>

### Modular Function Design
<div align="center">
<img src="https://user-images.githubusercontent.com/96192199/229288270-093643c1-0018-487a-81e6-1d7809b6e90f.png" height="400" >
<img src="https://user-images.githubusercontent.com/96192199/227504931-19955f78-45cd-4d1c-adac-e71e50957915.png" height="400" >
</div>


### Translating source code to English

<div align="center">
<img src="https://user-images.githubusercontent.com/96192199/229720562-fe6c3508-6142-4635-a83d-21eb3669baee.png" height="400" >
</div>

## Todo and Version Planning:

- version 3 (Todo): 
- - Support for gpt4 and other llm
- version 2.4+ (Todo): 
- - Summary of long text and token overflow problems in large project source code
- - Implementation of project packaging and deployment
- - Function plugin parameter interface optimization
- - Self-updating
- version 2.4: (1) Added PDF full-text translation function; (2) Added input area switching function; (3) Added vertical layout option; (4) Optimized multi-threaded function plugin.
- version 2.3: Enhanced multi-threaded interactivity
- version 2.2: Function plug-in supports hot reloading
- version 2.1: Collapsible layout
- version 2.0: Introduction of modular function plugins
- version 1.0: Basic functions

## References and Learning


```
The code refers to the design of many other excellent projects, mainly including:

# Reference Project 1: Referenced the method of reading OpenAI json, recording historical inquiry records, and using gradio queue in ChuanhuChatGPT
https://github.com/GaiZhenbiao/ChuanhuChatGPT

# Reference Project 2:
https://github.com/THUDM/ChatGLM-6B

```


