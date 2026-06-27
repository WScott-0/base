# Data Scientist

#### Technical Skills: Python, R, SQL, JavaScript, PHP, HTML/CSS, PowerShell, Bash, MySQL, Git/GitHub, Jupyter Notebook, RStudio, ServiceNow Reporting, Google Apps Script  

## Education
- B.S., Data Science | Arizona State University (_May 2026_)

## Projects
#### Public Health: Measles Data Pipeline and Interactive Mapping
[Live Dashboard](https://bleachmedia.net/measles/)

Developed an end-to-end public health data pipeline to monitor and visualize measles outbreak activity using scheduled data collection, database design, API development, and interactive geospatial mapping. Built a scheduled Python application to retrieve CDC measles case snapshots, process cumulative reporting into weekly and two-week case deltas, and normalize the data for structured storage. Designed and developed a relational database framework to preserve historical snapshots, support trend analysis, and separate geographic entities such as New York City from the rest of New York for improved mapping accuracy.

Created an API layer to serve processed measles data to the front-end application, allowing map views to dynamically display weekly changes, two-week changes, and cumulative totals. Integrated the API with an interactive map interface to provide a clearer visual understanding of outbreak progression across regions. The overall purpose of the project is to transform static public health reporting into an automated, repeatable, and decision-support-oriented visualization system. The framework was designed for future expansion, allowing additional data sources such as Johns Hopkins telemetry, county-level hotspot indicators, and other public health datasets to be integrated without requiring a full rebuild of the pipeline.

---

#### Accessability: AI Video Localization Pipeline for Niche Media
*Python, FFmpeg, Speech-to-Text, Machine Translation, Text-to-Speech, Natural Language Processing, AI Audio Generation, Subtitle Generation, Media Processing, Pipeline Automation*

[Workflow Diagram](#)

Developed a fully automated AI powered video localization pipeline designed to make niche and non mainstream media accessible to audiences outside of the original language region. The project was created with a specific focus on Japanese electronic music artist interviews, where historically significant, esoteric, or vintage media may not receive professional translation or localization due to limited commercial demand.

The system ingests a source-language video, separates the audio using FFmpeg, routes the extracted audio through a speech-to-text transcription model, translates the transcript into a target language, generates synchronized subtitle files, and creates an AI-generated overdub audio track. The pipeline then recombines the original video, translated subtitles, original audio, and generated target-language audio using FFmpeg, resulting in a final video file that supports both languages through selectable audio and subtitle tracks.

This project demonstrates practical experience with applied AI, NLP, speech processing, media automation, and end-to-end workflow orchestration. Beyond the technical implementation, the project highlights the role of AI-assisted accessibility in media production, especially for archival, experimental, regional, or culturally important media that may otherwise remain unavailable to broader audiences.

By automating transcription, translation, subtitle generation, AI voice creation, and video recombination, the pipeline provides a scalable framework for preserving and expanding access to specialized media communities while reducing the manual effort traditionally required for localization.
