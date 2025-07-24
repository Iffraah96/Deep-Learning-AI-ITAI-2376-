1.	Project Overview:

a.	Description of the agent and its purpose


The agent developed Virtual Academic Research Assistant that has been designed to help students and researchers efficiently gather academic sources, summarize key information, identify relationships between studies, and format proper citations (in MLA and APA). It uses natural language understanding to interpret user queries and interact with external tools such as the Semantic Scholar API and a text summarization model and arranging these capabilities through a reasoning and acting (ReAct) framework.
Its primary purpose is to streamline the research process by automating the time consuming and hectic tasks like literature search, content summarization, and citation formatting, allowing users to focus on critical analysis and writing.
The agent can be found in the GitHub repository by accessing the following link:

b.	Key features and capabilities


Following are some of the key features that are found in the developed agent:


i.	Natural Language Input Processing: It classifies user requests into multiple intents (search, summarize, connect, cite) using pattern matching.


ii.	Academic Paper Search: The agent uses the Semantic Scholar API to retrieve relevant research papers with metadata including titles, abstracts, authors, years, and URLs.


iii.	Summarization: The agent Employs a pre-trained transformer-based model (DistilBART) to generate concise summaries of long abstracts or texts.


iv.	Memory Buffer: This maintains session-based storage of retrieved papers, summaries, citations, and feedback, enabling stateful multi-step interactions.


v.	Citation Formatting: Generates APA-style citations based on paper metadata, supporting multiple authors.


vi.	Reasoning and Acting Loop (ReAct): The workflow of the agent is controlled by reasoning over tasks, deciding which tools to invoke, and maintaining session continuity.


vii.	User Interface: A web-based Gradio interface has also been added in the development of the agent so that end users can have easy and interactive access from environments
like Google Colab.


viii.	Error Handling & Feedback: The agent is designed to manage API errors, missing data, and guides users to rephrase or modify queries.


c.	Target Use Cases


Following are the use cases that has been solved by the developed academic research agent.


i.	Student Research Assistance: The agent has the capability to quickly locate and summarize academic papers for assignments, term papers, or literature reviews.


ii.	Academic Writing Support: This agent can automatically generate formatted citations that reduces manual effort and improves accuracy.


iii.	Preliminary Literature Review: The agent has the quality of identifying key papers and understand their main points without reading full texts upfront.


iv.	Research Idea Exploration: The agent can assist end users to find connections or relationships between studies for deeper insights.


v.	Educational Tools: This developed agent can also be integrated into learning platforms to support research skills development.
