![image](cog_metasci.png)

# An Overview of Essential Resources for the Study of Cognitive Metascience

We are committed to creating a platform that facilitates the sharing of resources and knowledge for anyone interested in cognitive metascience and related fields. Our mission is to advance the study of cognitive metascience and promote open access to valuable resources. Whether you are a researcher, student, or enthusiast, we invite you to explore our curated collection and contribute your own insights, tools, or findings.
This platform is open to everyone, and we believe that collective knowledge-sharing can guide us forward in our pursuit of understanding the complexities of this scientific field. Feel free to browse, engage, and join us in the exploration and discovery of resources that can make our scientific work more efficient and impactful.

In the following sections, you will find a list of resources for Natural Language Processing (NLP) and citation analysis, as well as a literature overview regarding scientific theories and peer review processes.

## Introductory materials

<details>
<summary>Tools</summary>

### Digital Humanities

* [The AI for Humanists Project](https://aiforhumanists.com/)

Focus on BERT and LLMs for Digital Humanities.
</details>

## Tools for NLP

From robust language models like SciBERT to annotation platforms like Doccano, these resources offer a diverse array of tools designed for text analysis and understanding. Whether you're exploring sentiment analysis, entity recognition, or document summarization, these tools provide the necessary infrastructure for work in the field of natural language processing, making them useful for anyone interested in advancing their understanding of linguistics, machine learning, or cognitive science.

<details>
<summary>Tools</summary>

### Topic Modeling

* [ Lingo4G ](https://carrotsearch.com/lingo4g/)

By using Lingo46 you can get an overview of thousands of documents within seconds, instantly drill-down to documents of interest. You can build custom text mining pipelines ranging from simple search to 2D mapping, time-series analysis and duplicate detection. You can combine topics, clusters and 2D document maps into powerful visualizations. Closed source. *Our lab has a research licence*.

* [ Text Visualization Browser ](https://textvis.lnu.se/)

### Annotation Tools

* [ doccano ](https://github.com/doccano/doccano)

Doccano is an open-source text annotation tool for humans. It provides annotation features for text classification, sequence labeling, and sequence to sequence tasks. You can create labeled data for sentiment analysis, named entity recognition, text summarization, and so on. Just create a project, upload data, and start annotating. You can build a dataset in hours.

### Language Models

* [ SciBERT ](https://github.com/allenai/scibert)

SciBERT is a BERT model trained on scientific text. SciBERT is trained on papers from the corpus of semanticscholar.org. Corpus size is 1.14M papers, 3.1B tokens. We use the full text of the papers in training, not just abstracts. SciBERT has its own vocabulary (scivocab) that's built to best match the training corpus. We trained cased and uncased versions. We also include models trained on the original BERT vocabulary (basevocab) for comparison. It results in state-of-the-art performance on a wide range of scientific domain nlp tasks.

### Vector databases

* [ WEAVIATE ](https://github.com/weaviate/weaviate)

Weaviate is an open source vector database that stores both objects and vectors, allowing for combining vector search with structured filtering with the fault-tolerance and scalability of a cloud-native database, all accessible through GraphQL, REST, and various language clients.

![image](https://github.com/sofijakrivokapic/cognitivemetascience/assets/125128460/f1dbc4b5-5735-40ea-8712-8d3875ffb0fd)


### Chatbots

* [Poe](https://poe.com/)

Multiple LLMs under a single interface.

* [You](https://you.com/)

Web search and multiple LLMs (academic subscriptions available).

* [LM Studio](https://lmstudio.ai/) 

Run (quantized) LLMs locally.

* [ChatBot Arena](https://chat.lmsys.org/)

Ask any question to two anonymous models (e.g., ChatGPT, Claude, Llama) and vote for the better one! You can continue chatting until you identify a winner. Vote won't be counted if model identity is revealed during conversation.

* [ ChatGPT Retrieval](https://github.com/openai/chatgpt-retrieval-plugin)

### Speech-to-text

* [OpenAI’s Whisper](https://towardsdatascience.com/transcribe-audio-files-with-openais-whisper-e973ae348aa7)

### Semantic search systems

* [OP Vault](https://github.com/pashpashpash/vault-ai)

OP Vault uses the OP Stack (OpenAI + Pinecone Vector Database) to enable users to upload their own custom knowledgebase files and ask questions about their contents. The primary focus is on human-readable content like books, letters, and other documents, making it a practical and valuable tool for knowledge extraction and question-answering. You can upload an entire library's worth of books and documents and recieve pointed answers along with the name of the file and specific section within the file that the answer is based on!

* [ Haystack ](https://haystack.deepset.ai/)

* [ Atlas ](https://atlas.nomic.ai/)

Interact, discover insights and build with **unstructured text, image and audio data.** Uncover data insights from your text and images - right from your web browser. Make sense of your data with AI computed topics, data labels and groupings and embeddings. Share text, image, and embeddings datasets with your team or customers. Scales from 100 to 100 million unstructured datapoints.

* [ PaperAI ](https://github.com/neuml/paperai)

paperai is a semantic search and workflow application for medical/scientific papers. Applications range from semantic search indexes that find matches for medical/scientific queries to full-fledged reporting applications powered by machine learning.

### Processing / Corpora systems

* [ SciWING ](https://sciwing.io/) 

Scientific Document Processing Toolkit, from PDF processing to citation intent.

* [SketchEngine](https://sketchengine.eu)

A comprehensive corpus management and search engine, for lexicographers and digital humanities. Many academic institutions have a license.


### Scraping

* [twarc](https://github.com/DocNow/twarc)

Twarc is a command line tool and Python library for collecting and archiving Twitter JSON data via the Twitter API. It has separate commands (twarc and twarc2) for working with the older v1.1 API and the newer v2 API and Academic Access (respectively).
 
### Other tools

* [ twXplorer](https://twxplorer.knightlab.com/) 

Search engine for Twitter.

* [ CADE ](https://federicobianchi.io/cade/)

CADE can and has been used for several different tasks: from general temporal vector space alignment [1] and a more general comparison of language variation [2], to tasks like semantic change detection in diachronic contexts [3,6] and narrative understanding [5].
![image](https://github.com/sofijakrivokapic/cognitivemetascience/assets/125128460/d06257d3-48ec-4c7c-b078-e04f76072ae4)

* [AI Library](https://library.phygital.plus/)

Overview of many useful AI tools.



</details>


<details>
<summary>Articles</summary>

* [Google "We Have No Moat, And Neither Does OpenAI](https://www.semianalysis.com/p/google-we-have-no-moat-and-neither)
 
* [A La Carte Embedding: Cheap but Effective Induction of Semantic Feature Vectors](https://arxiv.org/abs/1805.05388)
  
* [Reinventing search for research](https://about.system.com/blog/reinventing-search-for-research)
  
* [Sentiment Analysis through LLM Negotiations](https://arxiv.org/abs/2311.01876)
  
* [Chatbots Are Not Reliable Text Annotators](https://arxiv.org/abs/2311.05769)
  
* [Becoming Proficient in Document Extraction](https://www.llamaindex.ai/blog/becoming-proficient-in-document-extraction-32aa13046ed5)
  
* [LLM pricing sheet](https://docs.google.com/spreadsheets/d/1NX8ZW9Jnfpy88PC2d6Bwla87JRiv3GTeqwXoB4mKU_s/edit?pli=1#gid=0)
  
* [How should the advent of large language models affect the practice of science?](https://arxiv.org/abs/2312.03759)

* [Fine-Tuning ChatGPT for Sentiment Analysis With W&B](https://wandb.ai/mostafaibrahim17/ml-articles/reports/Fine-Tuning-ChatGPT-for-Sentiment-Analysis-With-W-B--Vmlldzo1NjMzMjQx)


</details>

<details>
<summary>Additional resources</summary>
 
* [OpenBooks: Concept Search](https://scholar.harvard.edu/stephenosadetz/digitalresearch)

* [GitHub list: Scholarly Data Analysis](https://github.com/napsternxg/awesome-scholarly-data-analysis)
  
* [GPT-4 Open-Source Alternatives](https://www.datacamp.com/blog/12-gpt4-open-source-alternatives?ref=emergentmind)
  
* [ChatGPT Cheat Sheet for Data Science](https://www.datacamp.com/cheat-sheet/chatgpt-cheat-sheet-data-science)
  

</details>

## Citation Analysis

The Citation Analysis tools featured here are essential for researchers seeking to navigate the scholarly landscape efficiently. From databases like Microsoft Academic Graph to visualization tools like CiteSpace, these resources empower users to uncover trends and gain insights into academic discourse through bibliometric analysis.

<details>
<summary>Tools</summary>
 
* [ Lens ](https://www.lens.org/)

An aggregator for diverse open knowledge sets, including scholarly works and patents. Offers discovery and analytics tools, ‘The Lens MetaRecord’ integrates multiple identifiers and sources to provide comprehensive and normalized metadata while maintaining provenance. 
* [ SN SciGraph ](https://communities.springernature.com/users/82895-sn-scigraph)

* [ Webometric Analyst ](http://lexiurl.wlv.ac.uk/)

Free Windows-based program, designed for altmetrics, citation analysis, social web analysis, and webometrics, including link analysis. Data is downloaded through APIs or directly, and various text and citation processing options are provided. Altmetrics and citation analysis cover data sources like Mendeley, Altmetric.com, Google Books, and WorldCat. Social web analysis includes platforms such as YouTube, Twitter, Goodreads, and Flickr.

* [ Microsoft Academic Graph ](https://www.microsoft.com/en-us/research/project/microsoft-academic-graph/)
 
Depracated project; Knowledge graph with scientific publications, citation relationships and authors; supporting various applications 

* [ Dimensions.AI ](https://www.dimensions.ai/)

Database that integrates data and analytical tools in a single platform with over 106 million publications linked to grants, patents, clinical trials, datasets, policy papers, citations and article metrics. Extremely expensive, acquiring free access is near-impossible.

* [ CiteSpace ](https://sourceforge.net/projects/citespace/)

Visual analytic tool designed for studying scholarly literature trends. The workflow involves analytic tasks and a variety of configurations, emphasizing the importance of understanding underlying concepts and principles. The tool is unique for linking publications with grants, patents, clinical trials, datasets, and policy papers, offering a holistic research landscape.

* [ OpenAIRE ](https://graph.openaire.eu/)

OpenAIRE providesn a large database of research data that is stored in a graph format (that represents relationships between research outputs, citations, funding, organizations and collaborations). Used for research evaluation in replacement of proprietary databases such as Web of Science or Scopus.

* [ Scite.AI ](https://scite.ai/)

Analyses the textual context of citations, distinguishing between supporting, mentioning, and contrasting citations. Processes full-text articles to create ‘Smart Citations’, which contain information about citation relationships, contextual details, and classification types. Also offers Custom Dashboards, a Zotero Plugin, and a Browser Extension. Sources papers from publishers, preprint servers, and other reputable sources, accessing full-text PDFs and XMLs for analysis.

* [Sciveyor](https://pencelab.be/projects/sciveyor/)

* [ CR Explorer ](https://andreas-thor.github.io/CRExplorer/)

The CRExplorer uses data from Web of Science (Clarivate Analytics) or Scopus (Elsevier) as input. Publication sets have to be downloaded including the references cited. The program focusses on the analysis of the cited references, in particular on the referenced publication years. Over time, "citation classics" of a field become more pronounced. When the aggregated citations are plotted along the time axis, one obtains a "spectrogram" with distinct peaks. CRExplorer visualizes this spectrogram, cleans the cited references (disambiguation), and uses a smoothing algorithm to suppress the noise.

* [Cortext Manager](https://www.cortext.net/projects/cortext-manager/)

The basic workflow of Cortex Manager is following: (1) upload raw files from various scientific bibliography databases (ISI Thomson Web of Science, Pubmed, etc) and simple CSV files, (2) transform text files into standard corpus database file, (3) perform a series of graphical analysis to produce descriptive statistical analysis, social graphs of entities and timeline based phylogenetic reconstructions, (4) download outputs in format compatible with third party software.



</details>

<details>
<summary>Papers and background</summary>

* [CausalCite: A Causal Formulation of Paper Citations](https://arxiv.org/abs/2311.02790v2)

The paper proposes a novel method called TextMatch for evaluating the significance of scientific papers, addressing the limitations of traditional citation counts. TextMatch utilizes high-dimensional text embeddings generated by large language models (LLMs) to encode papers, extracts similar samples using cosine similarity, and synthesizes a counterfactual sample based on the weighted average of similar papers. The resulting metric, called CausalCite, offers a causal formulation of paper citations. The effectiveness of CausalCite is demonstrated through its high correlation with paper impact, as assessed by scientific experts, and its stability across various sub-fields of AI. The study provides insights for future researchers to leverage this metric for a more comprehensive understanding of a paper's quality. Code and data are available for further exploration.

</details>

## [Peer review](peer-review.md)

## [What makes a scientific theory good?](theory.md)


### Books and articles about replication crisis (mostly in psychology).

<details>
<summary>Replication Crisis in Psychology</summary>
 
* [Stepping in the Same River Twice: Replication in Biological Research](https://www.jstor.org/stable/j.ctt1n2tvtj)
 
* [A discipline-wide investigation of the replicability of Psychology papers over the past two decades](https://www.pnas.org/doi/10.1073/pnas.2208863120)
  
* [No Evidence for a Replicability Crisis in Psychological Science](https://projects.iq.harvard.edu/psychology-replications/)
  
* [The problem with science: the reproducibility crisis and what to do about it](https://academic.oup.com/book/39705)
  
* [Rethinking Reproducibility as a Criterion for Research Quality](https://www.emerald.com/insight/content/doi/10.1108/S0743-41542018000036B009/full/html)
 
* [Reproducibility failures are essential to scientific inquiry](https://www.pnas.org/doi/full/10.1073/pnas.1806370115)
 
* [The logical structure of experiments lays the foundation for a theory of reproducibility](https://www.biorxiv.org/content/10.1101/2022.08.10.503444v1)
 
* [Perhaps Psychology’s Replication Crisis is a Theoretical Crisis that is Only Masquerading as a Statistical One ](https://tidsskrift.dk/irtp/article/view/127764)

</details>