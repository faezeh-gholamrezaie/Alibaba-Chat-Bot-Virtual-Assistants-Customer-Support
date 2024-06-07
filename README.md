# Alibaba Chat Bot : Virtual Assistants Customer Support

<div align="center">
    <img width="40%" src="https://github.com/faezeh-gholamrezaie/Alibaba-Chat-Bot-Virtual-Assistants-Customer-Support/blob/main/travel.png">
</div>

The Alibaba Chat Bot is a Persian-speaking virtual assistant designed to provide customer support through a combination of text, video and audio interfaces.
It can recognize ticket numbers from user-uploaded images, prompt customers for additional information, and provide responses in either text or audio format. 

## Usage

### Install the required libraries

!apt-get install espeak -y

!pip install -r requirements. txt

### Get API Key

* [TAVILY_API_KEY](https://app.tavily.com/home)
* [LANGCHAIN_API_KEY](https://smith.langchain.com/)
* [COHERE_API_KEY](https://www.google.com/url?q=https%3A%2F%2Fdashboard.cohere.com%2Fwelcome%2Flogin%3Fsource%3Dreadme%26redirect%3D%252Freference%252Fabout)

### Dataset 

* Alibaba_question_and_answers : This data set is based on [frequently asked questions and answers from Alibaba customers](https://www.alibaba.ir/help-center/categories/faq)

* colorful_number_ticket : A hypothetical image for the customer ticket.

### Tools

This assistant has tools related to booking, canceling or updating plane tickets, hotels and rental cars.

### Gen AI Model

* Persian/Farsi text to speech(TTS) training using coqui tts : [Persian-tts-coqui](https://huggingface.co/Kamtera/persian-tts-female-vits)
* large language models : [Cohere](https://github.com/cohere-ai/cohere-python)
* vision language model : [moondream](https://github.com/vikhyat/moondream)

### Build a Customer Support Bot

Using [LangChain](https://langchain-ai.github.io/langgraph/tutorials/customer-support/customer-support/) to create applications using large language models
