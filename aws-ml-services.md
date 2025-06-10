

### Category 1: Pre-Trained AI Services for Business Applications
*(These are "off-the-shelf" services. You provide your data, and the service gives you an intelligent result. No ML expertise is required.)*

#### **Amazon Rekognition**
*   **What It Is:** An AI service for analyzing images and videos. Think of it as giving your application "eyes."
*   **Best Suited For (Use Cases):**
    *   **Object & Scene Detection:** Identifying objects (cars, furniture, animals) and scenes (beach, city, indoors) in thousands of images.
    *   **Content Moderation:** Automatically detecting unsafe or inappropriate content in images and videos to reduce the need for human moderators.
    *   **Facial Analysis & Recognition:** Detecting faces, analyzing demographics (e.g., estimated age range), and comparing faces for user verification or searching against a private repository of faces.
    *   **Text in Image:** Reading text from images, like street signs, social media posts, or product packaging.

#### **Amazon Polly**
*   **What It Is:** A service that turns text into lifelike speech (Text-to-Speech or TTS).
*   **Best Suited For (Use Cases):**
    *   **Creating Audio Content:** Converting blog posts or news articles into audio podcasts.
    *   **Accessibility:** Providing voice-overs for users with visual impairments.
    *   **Voice-Enabled Applications:** Creating voice prompts for IVR (Interactive Voice Response) systems in call centers or for mobile apps.

#### **Amazon Transcribe**
*   **What It Is:** A service that converts speech into text (Speech-to-Text or STT). It's the opposite of Polly.
*   **Best Suited For (Use Cases):**
    *   **Meeting & Call Transcription:** Creating searchable text transcripts of customer service calls, clinical conversations, or business meetings.
    *   **Video Subtitling:** Automatically generating subtitles for video content to improve accessibility and engagement.
    *   **Voice-to-Text Applications:** Transcribing voice notes or commands within an application.

#### **Amazon Translate**
*   **What It Is:** A neural machine translation service for fast, high-quality, and affordable language translation.
*   **Best Suited For (Use Cases):**
    *   **Localizing Content:** Translating websites, mobile apps, and documents for a global audience.
    *   **Cross-Lingual Communication:** Enabling real-time translation of customer support chats or emails.
    *   **Analyzing Foreign Language Text:** Translating large batches of text (e.g., social media feeds) into a common language for analysis.

#### **Amazon Textract**
*   **What It Is:** A service that automatically extracts text, handwriting, and data from scanned documents. It's more advanced than simple Optical Character Recognition (OCR) because it understands forms and tables.
*   **Best Suited For (Use Cases):**
    *   **Automated Document Processing:** Extracting data from invoices, receipts, and tax forms to automate accounts payable processes.
    *   **Digitizing Archives:** Extracting information from financial reports, medical records, and other structured documents.
    *   **Form Processing:** Capturing data submitted via scanned application forms or insurance claims.

#### **Amazon Comprehend**
*   **What It Is:** A Natural Language Processing (NLP) service that uses ML to find insights and relationships in unstructured text.
*   **Best Suited For (Use Cases):**
    *   **Sentiment Analysis:** Determining if customer reviews, social media comments, or emails are positive, negative, or neutral.
    *   **Entity Extraction:** Identifying specific items in text, such as people, places, brands, dates, or organizations.
    *   **Key Phrase Detection:** Pulling out the main talking points from a large body of text.
    *   **Personally Identifiable Information (PII) Detection:** Finding and redacting sensitive data like social security numbers or credit card numbers.

#### **Amazon Fraud Detector**
*   **What It Is:** A fully managed service that helps you identify potentially fraudulent online activities.
*   **Best Suited For (Use Cases):**
    *   **E-commerce Fraud:** Detecting fraudulent online payment transactions.
    *   **New Account Fraud:** Identifying fake accounts created to abuse promotional offers or post fake reviews.
    *   **Loyalty Program Fraud:** Detecting abuse of customer loyalty programs.

#### **Amazon Lex**
*   **What It Is:** A service for building conversational interfaces (chatbots and voice bots) into any application. It uses the same deep learning technology that powers Amazon Alexa.
*   **Best Suited For (Use Cases):**
    *   **Customer Service Chatbots:** Answering frequently asked questions on a website or in a mobile app.
    *   **Application Bots:** Allowing users to perform tasks using natural language, like checking an account balance or booking a flight.
    *   **Informational Bots:** Creating bots to provide information, like weather updates or business hours.

#### **Amazon Personalize**
*   **What It Is:** An AI service to create real-time, personalized recommendations for your users. It uses the same technology developed for Amazon.com.
*   **Best Suited For (Use Cases):**
    *   **Product Recommendations:** Creating "Customers who bought this also bought..." sections on e-commerce sites.
    *   **Personalized Content:** Recommending specific articles, news, or videos to users based on their viewing history.
    *   **Targeted Marketing:** Sending personalized marketing emails with product recommendations.

#### **Amazon Kendra**
*   **What It Is:** A highly accurate and intelligent enterprise search service powered by machine learning. Think of it as a super-powered "Google for your company's internal documents."
*   **Best Suited For (Use Cases):**
    *   **Internal Knowledge Base Search:** Helping employees find answers from documents stored across multiple systems like SharePoint, Confluence, and Amazon S3.
    *   **Enhanced Website Search:** Providing a natural language search bar on a website that can understand user intent and find precise answers from FAQs and manuals.
    *   **Research and Development:** Allowing researchers to quickly find information across vast archives of research papers and documents.

---

### Category 2: Generative AI Services
*(These services focus on creating new content, code, or conversations.)*

#### **Amazon Bedrock**
*   **What It Is:** A fully managed service that provides access to a choice of high-performing foundation models (FMs) from leading AI companies (like Anthropic's Claude, AI21's Jurassic, Meta's Llama 2, and Amazon's own Titan) through a single API.
*   **Best Suited For (Use Cases):**
    *   **Rapidly Building GenAI Apps:** Building applications for text generation, summarization, chatbots, and image generation without managing the underlying infrastructure.
    *   **Comparing and Choosing Models:** Experimenting with different foundation models to find the best one for a specific task.
    *   **Securely Customizing Models:** Privately fine-tuning a foundation model on your own company data without exposing that data to the public internet.

#### **Amazon Q**
*   **What It Is:** A generative AI–powered assistant specifically designed for work. It can be tailored to your business and is integrated into many AWS services and third-party apps.
*   **Best Suited For (Use Cases):**
    *   **For Developers (Amazon Q in IDE):** Answering questions about AWS, writing and debugging code, and upgrading application versions.
    *   **For Business Users (Amazon Q in QuickSight):** Building business intelligence (BI) dashboards and visualizations using natural language questions.
    *   **For Employees (Amazon Q in Apps):** Answering questions based on your company’s internal information, policies, and data from systems like Confluence, Slack, or ServiceNow.

---

### Category 3: ML Platform & Human-in-the-Loop
*(These are for more technical users or for managing the ML process itself.)*

#### **Amazon SageMaker**
*   **What It Is:** A fully managed platform for the entire machine learning lifecycle. It is a **toolbox** for data scientists and developers to **build, train, and deploy their own custom ML models from scratch**.
*   **How It's Different:** Unlike services like Rekognition or Personalize (which are pre-trained), SageMaker gives you full control.
*   **Best Suited For (Use Cases):**
    *   **Custom Model Development:** When your problem is too specific for a pre-trained AI service (e.g., predicting customer churn, forecasting product demand, or creating a unique medical imaging analysis model).
    *   **End-to-End ML Workflow:** Managing everything from data labeling and preparation to model training, optimization, and hosting for inference.
    *   **Exam Key:** If a question mentions data scientists needing to **build, train, or deploy a custom model**, the answer is almost always SageMaker.

#### **Amazon Augmented AI (Amazon A2I)**
*   **What It Is:** A service that provides a "human-in-the-loop" workflow for machine learning predictions. It helps you get human review when an AI model's prediction is not confident enough.
*   **Best Suited For (Use Cases):**
    *   **Improving Model Accuracy:** When a service like Amazon Textract can't read a blurry form field or Rekognition is unsure about an object in an image, A2I routes it to a human for review. The human's feedback can then be used to retrain the model.
    *   **Content Moderation Workflows:** Flagging potentially inappropriate content for a human to make the final "allow" or "deny" decision.
    *   **Exam Key:** A2I is the bridge between AI automation and necessary human judgment. It integrates with Rekognition and Textract.
