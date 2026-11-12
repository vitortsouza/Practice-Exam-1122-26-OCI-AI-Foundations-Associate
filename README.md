# Oracle OCI AI Foundations 1Z0-1122-2026 - Practical Exam Guide

Este repositório contém o compilado das 40 questões do exame prático (Practice Exam) da certificação **Oracle Cloud Infrastructure AI Foundations Associate (1Z0-1122-2026)**, incluindo as respostas corretas e as justificativas (rationales) oficiais.

## 📌 Destaques do Exame
O exame foca em cenários práticos que exigem a diferenciação entre:
- **Serviços de IA da OCI** (Language, Speech, Vision, Document Understanding, Data Science).
- **Conceitos de Machine Learning** (Supervisionado, Não Supervisionado, Reforço).
- **Arquiteturas de Deep Learning** (CNN, RNN, Transformers, Autoencoders).
- **Generative AI** (Fine-tuning, Few-shot prompting, T-Few, Tokens).
- **Infraestrutura** (GPUs NVIDIA, RDMA).

---

## 📝 Questões Comentadas

### Questão 1
**David está transcrevendo uma chamada de suporte ao cliente usando o OCI Speech. A chamada contém linguagem imprópria e ele quer manter as palavras originais, mas marcá-las como inapropriadas, em vez de descartá-las. Qual opção de filtragem de profanidade ele deve usar?**
- [ ] Masking
- [ ] Normalization
- [ ] Removing
- [x] **Tagging**
> **Rationale:** Para manter as palavras, mas marcá-las, a opção correta é o *Tagging*. Ele adiciona rótulos para indicar profanidade sem remover o texto original.

### Questão 2
**Qual recurso do OCI Document Understanding é útil para identificar se um documento é uma fatura (invoice), recibo (receipt) ou currículo (resume), com base em sua aparência e palavras-chave?**
- [ ] OCR (Optical Character Recognition)
- [x] **Document classification**
- [ ] Table extraction
- [ ] Image classification
> **Rationale:** A classificação de documentos ajuda a categorizar documentos com base em sua estrutura visual e palavras-chave extraídas.

### Questão 3
**Um carro autônomo precisa detectar pedestres e fazer mudanças de faixa seguras. Qual conceito de IA está sendo aplicado aqui?**
- [x] **Artificial Intelligence**
- [ ] Natural Language Processing
- [ ] Machine Learning
- [ ] Deep Learning
> **Rationale:** Detectar pedestres e mudar de faixa simula o comportamento humano. Portanto, é um exemplo amplo de Inteligência Artificial.

### Questão 4
**Um serviço de streaming quer recomendar programas de TV com base no comportamento do usuário. Qual abordagem de aprendizado de máquina deve ser usada?**
- [x] **Supervised Learning** *(Nota: O gabarito oficial marca como Supervisionado, pois baseia-se no histórico passado do usuário)*
- [ ] Reinforcement Learning
- [ ] Deep Learning
- [ ] Unsupervised Learning
> **Rationale:** Recomendações são dadas com base nas escolhas passadas do usuário. Portanto, é um exemplo de aprendizado supervisionado.

### Questão 5
**Você precisa de uma GPU adequada para cargas de trabalho de treinamento e inferência de IA em escala massiva (HPC). Qual GPU NVIDIA você provavelmente escolheria?**
- [x] **GB200**
- [ ] A100
- [ ] H100
- [ ] A10
> **Rationale:** A GB200 (Grace Blackwell) é projetada para IA exascale e HPC, sendo mais adequada para escalas massivas do que a A100 ou H100.

### Questão 6
**Você está trabalhando em um projeto de deep learning para gerar música. Qual tipo de rede neural é mais adequada para essa tarefa?**
- [ ] Convolutional Neural Network (CNN)
- [x] **Recurrent Neural Network (RNN)**
- [ ] Feedforward Neural Network (FNN)
- [ ] Autoencoder
> **Rationale:** Prever a próxima nota musical requer o contexto das notas anteriores. As RNNs são adequadas para dados sequenciais.

### Questão 7
**Qual é o propósito do Model Catalog no OCI Data Science?**
- [x] **It serves as a repository for storing, tracking, and managing machine learning models.**
- [ ] It is used to deploy models as API endpoints.
- [ ] It functions as a real-time data processing engine.
- [ ] It only stores raw datasets for training ML models.
> **Rationale:** O Model Catalog atua como um repositório centralizado para armazenar, rastrear e compartilhar modelos com a equipe.

### Questão 8
**Qual é a função primária do processo de inferência em machine learning?**
- [ ] Adjusting the weights of a neural network
- [ ] Labeling the training data
- [ ] Collecting training data
- [x] **Predicting outcomes from new data points**
> **Rationale:** A inferência refere-se a prever um resultado para uma nova entrada usando um modelo já treinado.

### Questão 9
**Como o Select AI gera consultas SQL a partir de perguntas em linguagem natural?**
- [x] **It connects to an LLM, infers the query intent, and formulates the SQL command.**
- [ ] It provides the best SQL query based on predefined templates.
- [ ] It requires users to manually input query parameters.
- [ ] It only works with structured datasets that contain predefined SQL commands.
> **Rationale:** O Select AI usa LLMs para inferir a intenção da consulta e construir o comando SQL necessário.

### Questão 10
**Qual é o objetivo principal do fine-tuning (ajuste fino) de um Large Language Model (LLM)?**
- [x] **To adjust the pretrained model's parameters using a smaller, task-specific dataset, improving its performance on specific tasks**
- [ ] To train the model from scratch using a completely new dataset
- [ ] To decrease the number of parameters in the model to reduce computational cost
- [ ] To convert the model into a different type of neural network architecture
> **Rationale:** O fine-tuning adapta um LLM pré-treinado a um domínio ou tarefa específica, treinando-o com um conjunto de dados menor e especializado.

### Questão 11
**Qual técnica é usada para prever o preço de uma casa com base em suas características?**
- [ ] Classification
- [ ] Clustering
- [ ] Time Series Analysis
- [x] **Regression**
> **Rationale:** Prever um valor numérico (preço) é um exemplo de aprendizado supervisionado, especificamente um algoritmo de Regressão.

### Questão 12
**Como a normalização melhora a legibilidade das transcrições no OCI Speech?**
- [ ] It replaces all uppercase letters with lowercase.
- [x] **It converts elements like numbers, dates, and URLs into standard readable formats.**
- [ ] It translates transcriptions into multiple languages.
- [ ] It removes unnecessary words from the transcription.
> **Rationale:** A normalização garante que endereços, horários, números e URLs sejam formatados corretamente para leitura.

### Questão 13
**Você está desenvolvendo um software de classificação de imagens que pode identificar objetos específicos. Qual subconjunto da IA você usaria?**
- [ ] Reinforcement Learning
- [ ] Natural Language Processing
- [x] **Deep Learning**
- [ ] Machine Learning
> **Rationale:** A detecção de objetos é implementada usando Deep Learning (redes neurais convolucionais).

### Questão 14
**Qual afirmação descreve melhor o processo de pré-treinamento de um modelo de IA Generativa?**
- [ ] It only memorizes examples and reproduces them exactly.
- [x] **It learns patterns in unstructured data without requiring labeled training data.**
- [ ] It learns from labeled data and maps inputs to corresponding labels.
- [ ] It exclusively relies on reinforcement learning from human feedback.
> **Rationale:** Modelos generativos não requerem dados rotulados no pré-treinamento. Eles aprendem padrões a partir de grandes volumes de dados não estruturados.

### Questão 15
**Qual destes componentes NÃO faz parte da Infraestrutura de IA da OCI?**
- [x] **OCI Vault**
- [ ] NVIDIA GPUs
- [ ] RDMA Network
- [ ] OCI Storage
> **Rationale:** O OCI Vault é usado para segurança e gerenciamento de chaves criptográficas, não faz parte da infraestrutura de IA.

### Questão 16
**Lisa gerencia um sistema de segurança automatizado que monitora estacionamentos usando câmeras. Ela quer localizar e rotular veículos e placas em cada quadro. Qual recurso do OCI Vision ela deve usar?**
- [ ] Image classification
- [x] **Object detection**
- [ ] Document Classification
- [ ] Speech-to-text
> **Rationale:** Para detectar e rotular objetos específicos (veículos e placas) em imagens, usa-se a detecção de objetos.

### Questão 17
**Que tipo de dado é mais provável de ser usado com algoritmos de deep learning?**
- [ ] Data with human interpretable features
- [ ] Time series data
- [x] **Complex data with non-human interpretable features**
- [ ] Only string data
> **Rationale:** Deep Learning é adequado para dados complexos como imagens, áudio ou vídeo, que geralmente não são interpretáveis por humanos individualmente (ex: pixels).

### Questão 18
**Qual afirmação descreve melhor a principal diferença entre Large Language Models (LLMs) e modelos tradicionais de Machine Learning (ML)?**
- [x] **LLMs are pretrained on a large text corpus whereas ML models need to be trained on custom data.**
- [ ] LLMs have a limited number of parameters compared to ML models.
- [ ] LLMs require extensive feature engineering, while traditional ML models can generate human-like text with minimal feature engineering.
- [ ] Traditional ML models are better at understanding and generating natural language, while LLMs are primarily used for numerical data analysis.
> **Rationale:** LLMs são treinados em datasets massivos e diversos, permitindo generalização. Modelos tradicionais de ML geralmente requerem treinamento em datasets específicos.

### Questão 19
**Qual é o papel da função de perda (loss function) em algoritmos de aprendizado supervisionado?**
- [x] **It quantifies the cost of incorrect predictions.**
- [ ] It evaluates the model's complexity.
- [ ] It helps in feature scaling.
- [ ] It measures the similarity between predictions and actual targets.
> **Rationale:** A função de perda verifica a diferença entre o valor real e o valor previsto, quantificando o custo do erro.

### Questão 20
**John precisa analisar a precisão das transcrições do OCI Speech para um caso legal. Ele quer avaliar o quão segura a máquina está sobre cada palavra na transcrição. Qual recurso ele deve usar?**
- [ ] Batch support
- [ ] Profanity filtering
- [ ] Normalization
- [x] **Confidence scoring**
> **Rationale:** O *Confidence scoring* fornece níveis de confiança palavra por palavra e gerais para a transcrição.

### Questão 21
**Emma trabalha para uma empresa de mídia que produz conteúdo de vídeo. Ela precisa adicionar legendas ocultas (closed captions) aos vídeos para acessibilidade. Qual recurso do OCI Speech ela deve usar?**
- [x] **SRT file support**
- [ ] Profanity filtering
- [ ] Batching support
- [ ] Confidence scoring
> **Rationale:** O suporte a arquivos SRT permite adicionar legendas facilmente aos vídeos no formato padrão da indústria.

### Questão 22
**Como o Select AI melhora a interação com o Oracle Autonomous Database?**
- [ ] By eliminating the need for database administrators
- [ ] By improving network security protocols
- [x] **By enabling natural language prompts instead of SQL code**
- [ ] By providing advanced data visualization tools
> **Rationale:** O Select AI permite que os usuários interajam com o banco de dados usando linguagem natural em vez de escrever código SQL.

### Questão 23
**Qual destes resume os três princípios orientadores para que a IA seja confiável?**
- [ ] AI should be cost-effective, cloud-based, and user-friendly.
- [x] **AI should be lawful, ethical, and robust.**
- [ ] AI should replace human oversight, be independent, and highly scalable.
- [ ] AI should be fast, unbiased, and autonomous.
> **Rationale:** Para ser confiável, a IA deve cumprir leis (lawful), aderir a valores éticos (ethical) e ser confiável técnica e socialmente (robust).

### Questão 24
**O T-Few fine-tuning no OCI Generative AI Service reduz custo e tempo de treinamento em comparação com o fine-tuning tradicional. Qual afirmação explica corretamente o motivo disso?**
- [ ] It trains the entire model from scratch for each task.
- [ ] It does not allow customization of pretrained models.
- [ ] It requires manually configuring each layer of the model for optimization.
- [x] **It selectively updates only a fraction of the model's weights.**
> **Rationale:** O T-Few adiciona novas camadas ao modelo pré-treinado e modifica apenas uma fração dos pesos, reduzindo significativamente tempo e custo.

### Questão 25
**Uma empresa quer automatizar seu sistema de filtragem de e-mail para reduzir spam. Qual técnica de IA você recomendaria?**
- [ ] Deep Learning
- [ ] Reinforcement Learning
- [ ] Natural Language Processing
- [x] **Machine Learning**
> **Rationale:** Detectar spam é um problema de classificação, portanto, pode ser resolvido com Machine Learning (Aprendizado Supervisionado).

### Questão 26
**Mark está analisando recibos de clientes e quer encontrar e salvar automaticamente detalhes como nome do comerciante, data da transação e valor total. Qual recurso do OCI Vision ele deve usar?**
- [ ] OCR (Optical Character Recognition)
- [x] **Key-value extraction**
- [ ] Document classification
- [ ] Table extraction
> **Rationale:** Para extrair valores específicos de recibos, a extração de chave-valor é a melhor opção, pois identifica e extrai campos predefinidos.

### Questão 27
**Qual é o papel de uma variável alvo (target variable) no aprendizado supervisionado?**
- [ ] It is used to split the dataset.
- [x] **It contains the desired output or class labels.**
- [ ] It helps in feature selection.
- [ ] It represents the input data.
> **Rationale:** A variável alvo refere-se ao resultado desejado, que pode ser um valor numérico ou um rótulo de classe.

### Questão 28
**Você está escrevendo poemas. Você precisa que seu computador ajude a completar as linhas sugerindo as palavras certas. Qual modelo de deep learning é mais adequado para essa tarefa?**
- [ ] Convolutional Neural Network (CNN)
- [ ] Variational Autoencoder (VAE)
- [x] **Recurrent Neural Network (RNN)**
- [ ] Generative Adversarial Network (GAN)
> **Rationale:** Prever a próxima palavra dada uma sequência requer o uso do contexto de palavras anteriores. RNNs são adequadas para isso.

### Questão 29
**Qual destes NÃO é uma aplicação comum de aprendizado de máquina não supervisionado?**
- [ ] Outlier detection
- [x] **Spam detection**
- [ ] Targeted marketing campaigns
- [ ] Customer segmentation
> **Rationale:** A detecção de spam é um problema de aprendizado supervisionado (classificação), e NÃO um exemplo de aprendizado não supervisionado.

### Questão 30
**Você precisa de uma GPU adequada para cargas de trabalho de treinamento e inferência de IA em pequena ou média escala. Qual GPU NVIDIA você provavelmente escolheria?**
- [ ] B200
- [x] **A100**
- [ ] GB200
- [ ] H200
> **Rationale:** A NVIDIA A100 é amplamente utilizada para cargas de trabalho de pequeno e médio porte, oferecendo alto desempenho. Embora a H200 seja mais nova, a A100 continua sendo uma forte escolha para essa escala.

### Questão 31
**Qual é a limitação primária das Redes Neurais Recorrentes (RNNs) ao processar sequências longas?**
- [x] **RNNs struggle with long-range dependencies due to the vanishing gradient problem.**
- [ ] RNNs can only understand words that appear at the beginning of a sentence.
- [ ] RNNs can only process numerical data, not text.
- [ ] RNNs process words in parallel, making them less efficient than transformers.
> **Rationale:** As RNNs processam texto sequencialmente e têm dificuldade em reter contexto de palavras distantes devido ao problema do desaparecimento do gradiente.

### Questão 32
**Qual técnica envolve fornecer exemplos explícitos em um prompt para guiar a resposta de um LLM?**
- [ ] Zero-shot learning
- [x] **Few-shot prompting**
- [ ] Self-supervised learning
- [ ] Chain-of-thought prompting
> **Rationale:** O Few-shot prompting envolve dar k exemplos de uma tarefa antes de pedir ao modelo para gerar uma resposta.

### Questão 33
**Como o Oracle Database 23ai permite o uso de modelos de IA pré-treinados para busca vetorial?**
- [x] **By loading ONNX models directly into the database**
- [ ] By restricting models to only Oracle-provided APIs
- [ ] By storing only raw image files for direct comparison
- [ ] By manually converting AI models into SQL queries
> **Rationale:** O Oracle Database 23ai permite que modelos ONNX sejam carregados no banco de dados, possibilitando a geração de embeddings vetoriais e buscas por similaridade.

### Questão 34
**John treinou com sucesso um modelo de machine learning usando a OCI. Agora ele precisa implantá-lo para previsões em tempo real, onde possa processar entradas do usuário e gerar respostas. Qual serviço da OCI ele deve usar para a implantação?**
- [ ] OCI Speech
- [ ] OCI Object Storage
- [ ] OCI Language
- [x] **OCI Data Science**
> **Rationale:** Uma vez treinado, o modelo precisa ser implantado para inferência em tempo real usando o OCI Data Science e GPU Compute.

### Questão 35
**Você está treinando um modelo de deep learning para reconhecer rostos. Qual tipo de rede neural é mais adequada para essa tarefa?**
- [x] **Convolutional Neural Network (CNN)**
- [ ] Recurrent Neural Network (RNN)
- [ ] Feedforward Neural Network (FNN)
- [ ] Autoencoder
> **Rationale:** O reconhecimento facial é baseado na extração de características de uma imagem. A CNN é bem adequada para esse propósito.

### Questão 36
**Você está treinando um modelo de deep learning para prever preços de ações. Que tipo de dado é este um exemplo?**
- [x] **Time series data**
- [ ] Sequential data
- [ ] Text data
- [ ] Image data
> **Rationale:** Dados de ações consistem em pares de carimbo de data/hora e preço, portanto, são considerados dados de séries temporais.

### Questão 37
**Qual o papel dos tokens em Large Language Models (LLMs)?**
- [ ] They determine the size of the model's memory.
- [ ] They represent the numerical values of model parameters.
- [ ] They are used to define the architecture of the model's neural network.
- [x] **They are individual units into which a piece of text is divided during processing by the model.**
> **Rationale:** Tokens são as unidades fundamentais de texto que os LLMs processam. Podem ser palavras, subpalavras ou caracteres.

### Questão 38
**John trabalha em uma plataforma de agregação de notícias e quer categorizar automaticamente artigos em tópicos como "Política", "Tecnologia" e "Esportes". Qual recurso do OCI Language o ajudaria?**
- [ ] Named entity recognition
- [ ] Sentiment analysis
- [ ] Language detection
- [x] **Text classification**
> **Rationale:** O recurso de classificação de texto atribui conteúdo a uma das mais de 600 categorias.

### Questão 39
**Qual é o propósito da camada oculta (hidden layer) em uma rede neural artificial?**
- [ ] This layer applies filters to the image data.
- [ ] This layer produces the final outputs of the network based on the processed information from the other layers.
- [ ] This layer receives and passes input data to the subsequent layers; it does not perform any computations.
- [x] **This layer is optional, and it processes and transforms inputs from the network's weights and activation functions.**
> **Rationale:** As camadas ocultas recebem a entrada da camada de entrada ou de outras camadas ocultas e a multiplicam por pesos e ativações.

### Questão 40
**Qual algoritmo é uma abordagem não-paramétrica para aprendizado supervisionado?**
- [ ] Linear Regression
- [ ] Random Forest
- [ ] Decision Trees
- [x] **K-Nearest Neighbors (KNN)**
> **Rationale:** O KNN é considerado não-paramétrico porque não possui parâmetros que precisam ser aprendidos a partir dos dados. O único parâmetro a ajustar é o número de vizinhos (K).

# OCI AI Foundations (1Z0-1122-2026) - Practice Exam 2

## 📝 Questões e Respostas Comentadas

### Pergunta 1
**How does AI enhance human efforts?**
- [ ] By increasing the physical strength of humans.
- [ ] By deleting data humans need to handle.
- [x] **By processing data at a speed and effectiveness far beyond human capability.**
> **Rationale:** A IA potencializa (augments) o trabalho humano processando dados em velocidade e eficácia muito além da capacidade humana.

### Pergunta 2
**In machine learning, what does the term "model training" mean?**
- [ ] Analyzing the accuracy of a trained model.
- [x] **Establishing a relationship between input features and output.**
- [ ] Performing data analysis on collected and labeled data.
- [ ] Writing code for the entire program.
> **Rationale:** O treinamento de modelo consiste em estabelecer a relação entre as características de entrada (input features) e a saída (output) desejada.

### Pergunta 3
**Which feature of OCI Speech helps make transcriptions easier to read and understand?**
- [ ] Timestamping
- [ ] Audio tuning
- [ ] Profanity filtering
- [x] **Text normalization**
> **Rationale:** A normalização de texto (Text Normalization) converte elementos como números, datas e URLs em formatos padrão legíveis, melhorando a legibilidade.

### Pergunta 4
**You are training a logistic regression model to classify emails as spam or not spam. The model is currently classifying too many emails as spam. What would you do to adjust the model?**
- [ ] Decrease the number of iterations.
- [x] **Increase the threshold value for classification.**
- [ ] Increase the regularization parameter.
- [ ] Decrease the weight of the feature representing the presence of certain keywords.
> **Rationale:** Se o modelo está classificando muitos e-mails como spam (falsos positivos), aumentar o limiar (threshold) fará com que ele seja mais conservador, exigindo uma probabilidade maior para classificar como spam.

### Pergunta 5
**What are Convolutional Neural Networks (CNNs) primarily used for?**
- [ ] Image generation
- [ ] Time series prediction
- [ ] Text processing
- [x] **Image classification**
> **Rationale:** As CNNs são projetadas principalmente para tarefas de visão computacional, como classificação de imagens, detecção de objetos, etc.

### Pergunta 6
**What is the primary purpose of reinforcement learning?**
- [ ] Making predictions from labeled data
- [x] **Learning from outcomes to make decisions**
- [ ] Identifying patterns in data
- [ ] Finding relationships within data sets
> **Rationale:** O aprendizado por reforço foca em aprender com as consequências das ações (resultados/recompensas) para tomar melhores decisões.

### Pergunta 7
**Which is NOT a category of pretrained foundational models available in the OCI Generative AI service?**
- [ ] Chat models
- [x] **Translation models**
- [ ] Generation models
- [ ] Embedding models
> **Rationale:** As categorias principais no OCI Generative AI são Chat, Generation e Embedding. Modelos de tradução dedicados não são uma categoria listada nesse serviço (a tradução pode ser feita via OCI Language ou prompts).

### Pergunta 8
**You are working on a multilingual public announcement system. Which AI task will you use to implement it?**
- [x] **Text to speech**
- [ ] Audio recording
- [ ] Speech recognition
- [ ] Text summarization
> **Rationale:** Para um sistema de anúncios públicos, você tem o texto e precisa convertê-lo em áudio (voz). Isso é feito via Text-to-Speech.

### Pergunta 9
**You are part of the media transcription team and need to automate transcription tasks. Which OCI AI service are you most likely to use?**
- [ ] Document Understanding
- [x] **Speech**
- [ ] Vision
- [ ] Language
> **Rationale:** O OCI Speech é o serviço especializado em transcrição de áudio/vídeo para texto.

### Pergunta 10
**Which capability is supported by Oracle Cloud Infrastructure Language service?**
- [ ] Translating text into speech
- [ ] Detecting objects and scenes in images
- [ ] Converting text into images
- [x] **Analyzing text to extract structured information like sentiment or entities**
> **Rationale:** O OCI Language analisa textos para extrair informações estruturadas, como sentimento, entidades, classificação, etc.

### Pergunta 11
**Which component in OCI Data Science provides an interactive coding environment for building and training models?**
- [x] **Notebook Sessions**
- [ ] Model Catalog
- [ ] Data Science Jobs
- [ ] Conda Environments
> **Rationale:** As Notebook Sessions fornecem o ambiente interativo (Jupyter) para codificação e treinamento.

### Pergunta 12
**Lisa is working on a project that involves transcribing thousands of audio files stored in Oracle Cloud. She wants to process multiple files efficiently instead of transcribing them one by one. Which OCI Speech feature should Lisa use?**
- [ ] Profanity filtering
- [x] **Batch support**
- [ ] Confidence scoring
- [ ] Time stamping
> **Rationale:** O suporte a Batch (lote) permite processar múltiplos arquivos de uma vez, aumentando a eficiência.

### Pergunta 13
**Which statement best describes the relationship between Artificial Intelligence (AI), Machine Learning (ML), and Deep Learning (DL)?**
- [ ] AI is a subset of DL, which is a subset of ML.
- [x] **ML is a subset of AI, and DL is a subset of ML.**
- [ ] DL is a subset of AI, and ML is a subset of DL.
- [ ] AI, ML, and DL are entirely separate fields with no overlap.
> **Rationale:** A hierarquia correta é: IA contém ML, que contém DL.

### Pergunta 14
**What is the main function of the hidden layers in an Artificial Neural Network (ANN) when recognizing handwritten digits?**
- [ ] Directly predicting the final output.
- [ ] Storing the input pixel values.
- [x] **Capturing the internal representation of the raw image data.**
- [ ] Providing labels for the output neurons.
> **Rationale:** As camadas ocultas processam os dados brutos e capturam representações internas e abstratas (features) da imagem.

### Pergunta 15
**How is "Prompt Engineering" different from "Fine-tuning" in the context of Large Language Models (LLMs)?**
- [ ] Both involve retraining the model, but Prompt Engineering does it more often.
- [ ] Prompt Engineering adjusts the model's parameters, while Fine-tuning crafts input prompts.
- [ ] Prompt Engineering modifies training data, while Fine-tuning alters the model's structure.
- [x] **Prompt Engineering creates input prompts, while Fine-tuning retrains the model on specific data.**
> **Rationale:** Prompt Engineering apenas molda a entrada (prompt). Fine-tuning altera os pesos do modelo treinando-o com dados específicos.

### Pergunta 16
**Which statement describes the Optical Character Recognition (OCR) feature of Oracle Cloud Infrastructure Document Understanding?**
- [ ] It converts audio files into text.
- [ ] It provides real-time translation of text.
- [ ] It enhances the visual quality of documents.
- [x] **It recognizes and extracts text from a document.**
> **Rationale:** O OCR extrai texto de imagens ou documentos escaneados.

### Pergunta 17
**Which AI domain can be employed for identifying patterns in images and extract relevant features?**
- [ ] Natural Language Processing
- [ ] Speech Processing
- [ ] Anomaly Detection
- [x] **Computer Vision**
> **Rationale:** Visão Computacional é o domínio focado em analisar e extrair informações de imagens e vídeos.

### Pergunta 18
**Which feature is NOT supported as part of the OCI Language service's pretrained language processing capabilities?**
- [ ] Sentiment Analysis
- [ ] Text Classification
- [ ] Language Detection
- [x] **Text Generation**
> **Rationale:** O OCI Language é focado em análise, não em geração de texto. A geração é feita por LLMs no OCI Generative AI.

### Pergunta 19
**What would you use Oracle AI Vector Search for?**
- [ ] Manage database security protocols.
- [x] **Query data based on semantics.**
- [ ] Query data based on keywords.
- [ ] Store business data in a cloud database.
> **Rationale:** O Vector Search permite consultas baseadas no significado (semântica) dos dados, e não apenas em correspondência exata de palavras-chave.

### Pergunta 20
**Which feature is NOT available as part of OCI Speech capabilities?**
- [ ] Transcribes audio and video files into text
- [ ] Supports multiple languages including English, Spanish, and Portuguese
- [ ] Provides timestamped, grammatically accurate transcriptions
- [x] **Uses extensive data science experience to operate**
> **Rationale:** O OCI Speech é um serviço pré-treinado e gerenciado. Ele não exige que o usuário tenha experiência extensiva em ciência de dados para operá-lo.

### Pergunta 21
**What is a key advantage of using dedicated AI clusters in the OCI Generative AI service?**
- [x] **They provide high-performance compute resources for fine-tuning tasks.**
- [ ] They allow access to unlimited database resources.
- [ ] They are free of charge for all users.
- [ ] They provide faster internet connection speeds.
> **Rationale:** Clusters dedicados fornecem GPUs dedicadas para tarefas pesadas, como fine-tuning ou inferência de alto volume.

### Pergunta 22
**What is the primary benefit of using the OCI Language service for text analysis?**
- [ ] It only works with structured data.
- [ ] It provides image processing capabilities.
- [x] **It allows for text analysis at scale without machine learning expertise.**
- [ ] It requires extensive machine learning expertise to use.
> **Rationale:** Sendo um serviço pré-treinado, ele permite análise de texto em escala sem exigir que o usuário seja um especialista em ML.

### Pergunta 23
**Emma is developing a customer support chatbot for an e-commerce website. The chatbot needs to provide accurate and up-to-date return policies, which change frequently. She initially tries fine-tuning but finds that the model still uses outdated information. Which approach should Emma use instead?**
- [ ] Zero-shot Prompting
- [x] **Retrieval-Augmented Generation (RAG)**
- [ ] Prompt Engineering
- [ ] Reinforcement Learning
> **Rationale:** O RAG conecta o modelo a uma base de dados externa atualizada, permitindo que ele busque as políticas de devolução mais recentes antes de responder.

### Pergunta 24
**A customer feedback analysis team needs to extract insights from thousands of online product reviews. They want to determine if customers express positive or negative opinions about different aspects of a product or service. Which feature of OCI Language is helpful?**
- [ ] Named entity recognition
- [ ] Key phrase extraction
- [ ] Language detection
- [x] **Sentiment analysis**
> **Rationale:** A análise de sentimento (Sentiment Analysis) identifica se o texto expressa opiniões positivas, negativas ou neutras.

### Pergunta 25
**What is the role of the self-attention mechanism in a transformer model?**
- [x] **It assigns different importance to each word in a sequence based on context.**
- [ ] It memorizes and retrieves specific words from past training examples.
- [ ] It forces the model to only focus on the most recent words in a sequence.
- [ ] It replaces all previous deep learning techniques for text processing.
> **Rationale:** O self-attention permite que o modelo pondere a importância de cada palavra na frase com base no contexto geral.

### Pergunta 26
**What is the primary benefit of using Oracle Cloud Infrastructure Supercluster for AI workloads?**
- [ ] It provides a cost-effective solution for simple AI tasks.
- [x] **It delivers exceptional performance and scalability for complex AI tasks.**
- [ ] It is ideal for tasks such as text-to-speech conversion.
- [ ] It offers seamless integration with social media platforms.
> **Rationale:** O Supercluster RDMA é projetado para altíssimo desempenho e escalabilidade em cargas complexas de IA (HPC/LLMs).

### Pergunta 27
**What distinguishes Generative AI from other types of AI?**
- [ ] Generative AI involves training models to perform tasks without human intervention.
- [x] **Generative AI creates diverse content such as text, audio, and images by learning patterns from existing data.**
- [ ] Generative AI focuses on making decisions based on user interactions.
- [ ] Generative AI uses algorithms to predict outcomes based on past data.
> **Rationale:** A IA Generativa é definida pela capacidade de criar novos conteúdos originais (texto, imagem, áudio) a partir de padrões aprendidos.

### Pergunta 28
**What role do Transformers perform in Large Language Models (LLMs)?**
- [ ] Limit the ability of LLMs to handle large datasets by imposing strict memory constraints.
- [ ] Manually engineer features in the data before training the model.
- [x] **Provide a mechanism to process sequential data in parallel and capture long-range dependencies.**
- [ ] Image recognition tasks in LLMs.
> **Rationale:** Os Transformers processam dados em paralelo e capturam dependências de longo alcance via self-attention.

### Pergunta 29
**Which type of machine learning is used to understand relationships within data and is not focused on making predictions or classifications?**
- [ ] Active learning
- [ ] Reinforcement learning
- [x] **Unsupervised learning**
- [ ] Supervised learning
> **Rationale:** O aprendizado não supervisionado foca em encontrar estruturas e relações ocultas nos dados (ex: clustering), sem um alvo de predição explícito.

### Pergunta 30
**Which AI Ethics principle leads to the Responsible AI requirement of transparency?**
- [ ] Respect for human autonomy
- [ ] Fairness
- [ ] Prevention of harm
- [x] **Explicability**
> **Rationale:** A Explicabilidade (Explicability) exige que os sistemas de IA sejam transparentes e capazes de explicar suas decisões.

### Pergunta 31
**What is "in-context learning" in the realm of Large Language Models (LLMs)?**
- [x] **Providing a few examples of a target task via the input prompt**
- [ ] Modifying the behavior of a pretrained LLM permanently
- [ ] Training a model on a diverse range of tasks
- [ ] Teaching a model through zero-shot learning
> **Rationale:** In-context learning (ou few-shot prompting) é a capacidade do LLM de aprender uma tarefa apenas observando exemplos fornecidos no próprio prompt.

### Pergunta 32
**How does Oracle Cloud Infrastructure Document Understanding service facilitate business processes?**
- [ ] By analyzing sentiment in text documents
- [ ] By generating lifelike speech from documents
- [ ] By transcribing spoken language
- [x] **By automating data extraction from documents**
> **Rationale:** O Document Understanding automatiza a extração de dados (texto, tabelas, key-values) de documentos.

### Pergunta 33
**What is the key feature of Recurrent Neural Networks (RNNs)?**
- [ ] They process data in parallel.
- [x] **They have a feedback loop that allows information to persist across different time steps.**
- [ ] They do not have an internal state.
- [ ] They are primarily used for image recognition tasks.
> **Rationale:** As RNNs têm um loop de retroalimentação (memória) que permite reter informações de etapas anteriores da sequência.

### Pergunta 34
**What does "fine-tuning" refer to in the context of OCI Generative AI service?**
- [ ] Doubling the neural network layers.
- [ ] Encrypting the data for security reasons.
- [ ] Upgrading the hardware of the AI clusters.
- [x] **Adjusting the model parameters to improve accuracy.**
> **Rationale:** Fine-tuning é o processo de ajustar os parâmetros de um modelo pré-treinado com dados específicos para melhorar a precisão em uma tarefa.

### Pergunta 35
**What is the difference between classification and regression in Supervised Machine Learning?**
- [ ] Classification and regression both predict continuous values.
- [ ] Classification and regression both assign data points to categories.
- [ ] Classification predicts continuous values, whereas regression assigns data points to categories.
- [x] **Classification assigns data points to categories, whereas regression predicts continuous values.**
> **Rationale:** Classificação prevê categorias discretas; Regressão prevê valores numéricos contínuos.

### Pergunta 36
**Which capability is supported by the Oracle Cloud Infrastructure Vision service?**
- [ ] Analyzing historical data for unusual patterns
- [ ] Generating realistic images from text
- [x] **Detecting vehicle number plates to issue speed citations**
- [ ] Detecting and preventing fraud in financial transactions
> **Rationale:** O OCI Vision faz análise de imagens, como detecção de objetos (ex: placas de veículos).

### Pergunta 37
**What is the purpose of the Model Catalog in OCI Data Science?**
- [ ] To create and switch between different environments
- [x] **To store, track, share, and manage models**
- [ ] To deploy models as HTTP endpoints
- [ ] To provide a preinstalled open source library
> **Rationale:** O Model Catalog é o repositório central para armazenar, rastrear, compartilhar e gerenciar modelos.

### Pergunta 38
**You are training a deep learning model to classify images. What is the primary function of the convolutional layer?**
- [x] **To detect specific features in the input image.**
- [ ] To generate new images.
- [ ] To classify the input image.
- [ ] To reduce the spatial dimensions of the input image.
> **Rationale:** A camada convolucional aplica filtros para detectar características (bordas, texturas). A redução de dimensão é feita pela camada de Pooling.

### Pergunta 39
**Which algorithm is primarily used for adjusting the weights of connections between neurons during the training of an Artificial Neural Network (ANN)?**
- [ ] Support Vector Machine
- [ ] Gradient Descent
- [x] **Backpropagation**
- [ ] Random Forest
> **Rationale:** O Backpropagation (Retropropagação) é o algoritmo que calcula o gradiente e ajusta os pesos das conexões da rede neural.

### Pergunta 40
**How do Large Language Models (LLMs) handle the trade-off between model size, data quality, data size, and performance?**
- [ ] They disregard model size and prioritize high-quality data only.
- [ ] They prioritize larger model sizes to achieve better performance.
- [ ] They focus on increasing the number of tokens while keeping the model size constant.
- [x] **They ensure that the model size, training time, and data size are balanced for optimal results.**
> **Rationale:** O desempenho ideal de um LLM depende do equilíbrio entre o tamanho do modelo, a quantidade/qualidade dos dados e o tempo de treinamento, evitando overfitting ou desperdício computacional.
