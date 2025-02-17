### Chatbot2025:
#### Q1 2025 (March 31):

### Summary of Overall Features:

1. User-side H5 page supports voice input and output; supports ASR (Automatic Speech Recognition) and TTS (Text-to-Speech) functions.
2. How to output intents, questions, answers, and summarize user tickets/knowledge from user historical conversation records.
3. How to quickly summarize intents, questions, and answers from knowledge documents, operation manuals, QA, and ServiceNow to assist users in filling the knowledge base.
4. Extract questions and entities from operation manuals.
5. Human customer service: how to identify similar questions and answers from users.
6. Extract necessary data for tickets from historical conversations (data extraction).
7. Assist users in organizing knowledge, corpora, and tables.
8. Assist human customer service in Q&A, answering user questions by combining public knowledge base, private knowledge base of human customer service, and personal historical chats.
9. Quickly identify emotions in user chats.
10. Recommend common, high-frequency, and related questions and answers to users.
11. Application of data annotation.

### User Side:

1. User-side supports voice input and output.
2. Supports multilingual voice input and output.

### Customer Service Side:

1. Supports generating questions and solutions with one click after SD (Service Desk) and user communication is completed. After SD review, submit questions and solutions to the management backend for display.
2. Supports SD maintaining their private documents as a support library for their manual assistance.
3. Private support knowledge base supports multiple sources, quick replies, document materials, and web links.
4. Supports SD setting multiple statuses, serving existing users but not taking new users.
5. Supports more user queuing strategies.
   1. **Supports generating questions and solutions with one click after SD and user communication is completed**
      - Automatically generate conversation summaries to help SD quickly generate questions and solutions.
      - Supports SD editing and correcting the generated content.
      - Automatically submit questions and solutions to the management backend for display.
   2. **Supports SD maintaining private documents**
      - Supports SD uploading and managing private documents (such as PDF, Word, Excel, etc.).
      - Supports full-text search and keyword highlighting in private documents.
      - Supports SD quickly inserting content from private documents into the conversation.
   3. **Private support knowledge base**
      - Supports multiple sources of knowledge base, including quick replies, document materials, web links, etc.
      - Supports SD customizing knowledge base categories and tags.
      - Supports version management and update reminders for knowledge base content.
   4. **Supports SD setting multiple statuses**
      - Supports SD setting "online but not taking orders" status, only serving existing users.
      - Supports SD setting "busy" status, temporarily not accepting new users.
      - Supports SD setting "offline" status, completely exiting the service.
   5. **Supports more user queuing strategies**
      - Supports queuing based on user priority, waiting time, question type, etc.
      - Supports dynamically adjusting queuing strategies to optimize user experience.
      - Supports real-time display of queuing status and estimated waiting time.
   6. **Intelligent auxiliary Q&A**
      - Supports SD obtaining system-recommended answers in real-time during the conversation.
      - Supports SD quickly viewing public knowledge base, private knowledge base, and personal historical chat records.
      - Supports SD rating and providing feedback on system-recommended answers to optimize recommendation algorithms.
   7. **Emotion recognition and warning**
      - Real-time recognition of user emotions, reminding SD to pay attention to user emotional changes.
      - Supports SD adjusting conversation strategies based on user emotions to improve user satisfaction.

### Management Backend:

Supports recommending new user questions and answers through large models for manual review. After review, they are stored in the public knowledge base as standard knowledge.

1. **Knowledge Base Management**
   - Supports administrators in adding, deleting, modifying, and querying the public knowledge base.
   - Supports version control and review processes for knowledge base content.
   - Supports batch import and export of knowledge base.
2. **User Management**
   - Supports administrators viewing and managing user information.
   - Supports administrators setting user permissions and roles.
   - Supports administrators viewing user behavior analysis and feedback.
3. **Ticket Management**
   - Supports administrators viewing and handling all tickets.
   - Supports automatic allocation and manual adjustment of tickets.
   - Supports tracking and statistical analysis of ticket status.
4. **Reports and Analysis**
   - Supports generating various reports, such as user satisfaction, problem resolution rate, ticket processing time, etc.
   - Supports custom report templates and export formats.
   - Supports real-time monitoring of system operating status and performance indicators.
5. **System Configuration**
   - Supports administrators configuring system parameters, such as queuing strategies, emotion recognition thresholds, etc.
   - Supports administrators setting system notification and reminder rules.
   - Supports administrators viewing system logs and operation records.

### Intelligent Reports:

### Technical Operations Expansion:

Support deploying projects through Docker files.
