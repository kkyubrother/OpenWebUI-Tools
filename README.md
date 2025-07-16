# OpenWebUI-Tools

OpenWebUI-Tools는 OpenWebUI의 기능을 향상시키기 위해 설계된 종합적인 툴킷입니다. 이 컬렉션에는 웹 스크래핑, 지식 쿼리, 웹 검색, YouTube 동영상 분석을 위한 강력한 도구와 고급 순차적 다중 에이전트 추론 기법(SMART) 시스템이 포함되어 있습니다.

SMART 시스템은 복잡한 쿼리와 작업을 처리하기 위한 정교한 다중 에이전트 접근 방식을 제공하여 프로젝트의 수준을 높입니다. 계획, 추론, 도구 사용, 사용자 상호 작용을 순차적인 파이프라인으로 결합하여 사용자 입력에 보다 세심하고 효과적으로 대응할 수 있습니다.

이 툴킷은 개발자에게 보다 지능적이고 성능이 뛰어난 웹 기반 AI 애플리케이션을 구축할 수 있는 다양한 리소스를 제공하는 것을 목표로 합니다.

## ReAct 

---
**설치 방법:**
- `smart.py` 코드를 OpenWebUI의 새 함수에 복사합니다.
- `Workspaces -> Functions -> New Function (+ 아이콘)`로 새 함수를 생성하세요.

참고: 일부 구현된 도구에는 사용할 수 없는 외부 API가 필요합니다.

---

The ReAct system is a pipeline for automatic model and tool selection as well as model tool calling. 

## SMART - Sequential Multi-Agent Reasoning Technique

---
**Install instructions:**
- Simply copy the `smart.py` code into a new function in OpenWebUI.
- To create a new fuction go to `Workspaces -> Functions -> New Function (+ Icon)`

NOTE: I would not recommend using the smart_with_tools.py code _as is_. It implements my own tools, many of which don't work without some external self-hosted APIs. However you can use it as a template to automatically implement your own tools.

---

The SMART (Sequential Multi-Agent Reasoning Technique) system is a powerful pipeline for enhanced language model capabilities. It includes:

- Planning Agent: Prepares incoming user requests for subsequent agents in the chain.
- Reasoning Agent: Handles internal thought processes, planning, and thinking.
- Tool-use Agent: Interfaces with various tools to gather information or perform actions.
- User-interaction Agent: Manages direct communication with the user.

Key features:
- Adaptive model selection based on task complexity
- Multi-step reasoning process
- Integration with external tools
- Customizable prompts for each agent in the chain
- Advanced Planning and internal thought 

SMART enhances the problem-solving capabilities of language models by breaking down complex tasks into manageable steps and leveraging specialized agents for different aspects of the process.

## Available Tools

### 1. Scrape Website (scrape.py)
- Scrapes any website and returns readable, Markdown-formatted results.
- Optimized for LLM processing.

### 2. WolframAlpha API (wolfram.py)
- Queries the WolframAlpha knowledge engine for a wide variety of questions.
- Supports real-time data queries, mathematical equations, scientific questions, and more.

### 3. Web Search (webSearch.py)
- Performs web searches using the Brave Search API.
- Supports various search focuses including web, news, Wikipedia, academia, Reddit, images, and videos.

### 4. YouTube Tool (youtube.py)
- Retrieves information about YouTube videos, including metadata and transcriptions. Supports multiple languages for video transcripts.
- Searches YouTube by keyword (1–50 results), returning for each video its id and metadata.
- Uses YouTube API v3 and needs a free api key from Google Cloud. https://developers.google.com/youtube/v3/getting-started

**Installation**

To install these tools, simply copy the code into a new tool inside [OpenWeb UI](https://www.openwebui.com).

**Usage**

Each tool can be imported and used in your OpenWebUI projects. Refer to the individual tool files for specific usage instructions and required API keys.

## Project Info

**Contributing**

Contributions to OpenWebUI-Tools are welcome! Please feel free to submit pull requests or open issues for any improvements or bug fixes.

**License**

Licensed under the MIT License. 

**Authors**

[MartainInGreen](https://github.com/MartianInGreen)

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=MartianInGreen/OpenWebUI-Tools&type=Date)](https://star-history.com/#MartianInGreen/OpenWebUI-Tools&Date)

If you want to support me check my [GitHub Profile](https://github.com/MartianInGreen) for more info. [Buy Me a Coffee](https://rennersh.de/buy-me-a-coffee)
