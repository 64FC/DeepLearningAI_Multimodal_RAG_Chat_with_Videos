# Multimodal RAG: Chat with Videos (DeepLearning.AI)

This course, developed in partnership with Intel, teaches you to build an interactive system for querying video content using multimodal AI. You’ll create a sophisticated question-answering system that processes, understands, and interacts with video. 

Increasingly, language models and AI applications have added the capability to process images, audio, and video. In this course, you will learn more about these models and applications by implementing a multimodal RAG system. You will understand and use a multimodal embedding model to embed images and captions in a multimodal semantic space. Using that common space, you will build and use a retrieval system that returns images using text prompts. You will use a Large Vision Language Model (LVLM) to generate a response using the images and text from the retrieval.

By the end of this course, you’ll have the expertise to create AI systems that can intelligently interact with video content. This skill set opens up possibilities for developing advanced search engines that understand visual context, creating AI assistants capable of discussing video content, and building automated systems for video content analysis and summarization. Whether you’re looking to enhance content management systems, improve accessibility features, or push the boundaries of human-AI interaction, the techniques learned in this course will provide a solid foundation for innovation in multimodal AI applications.

In this course, you will make API calls to access multimodal models hosted by Prediction Guard on Intel’s cloud.

## What you’ll learn in this course

* __Introduction to Multimodal RAG Systems__: Understand the architecture of multimodal RAG systems and interact with a Gradio app demonstrating multimodal video chat capabilities.
* __Multimodal Embedding with BridgeTower__: Explore the BridgeTower model to create joint embeddings for image-caption pairs, measure similarities, and visualize high-dimensional embeddings.
* __Video Pre-processing for Multimodal RAG__: Learn to extract frames and transcripts from videos, generate transcriptions using the Whisper model, and create captions using Large Vision Language Models (LVLMs).
* __Building a Multimodal Vector Database__: Implement multimodal retrieval using LanceDB and LangChain, performing similarity searches on multimodal data.
* __Leveraging Large Vision Language Models (LVLMs)__: Understand the architecture of LVLMs like LLaVA and implement image captioning, visual question answering, and multi-turn conversations.

## Key technologies and concepts

* __Multimodal Embedding Models__: BridgeTower for creating joint embeddings of image-caption pairs
* __Video Processing__: Whisper model for transcription, LVLMs for captioning
* __Vector Stores__: LanceDB for efficient storage and retrieval of high-dimensional vectors
* __Retrieval Systems__: LangChain for building a retrieval pipeline 
* __Large Vision Language Models (LVLMs)__: LLaVA 1.5 for advanced visual-textual understanding
* __APIs and Cloud Infrastructure__: PredictionGuard APIs, Intel Gaudi AI accelerators, Intel Developer Cloud

## Hands-on project

Throughout the course, you’ll build a complete multimodal RAG system that:
* Processes and embeds video content (frames, transcripts, and captions)
* Stores multimodal data in a vector database
* Retrieves relevant video segments given text queries
* Generates contextual responses using LVLMs
* Maintains multi-turn conversations about video content

## Who should join?

Anyone with intermediate to advanced knowledge of Python programming, familiarity with machine learning concepts and deep learning frameworks, and a basic understanding of natural language processing and computer vision.

Link to the course: [here](https://www.deeplearning.ai/short-courses/multimodal-rag-chat-with-videos/).
