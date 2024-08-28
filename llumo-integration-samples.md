# Llumo Integration sample

## Compressor

### Example-1
#### Input Variables
1. "**RAG_Context"**: 
```
Glean: The Art of Data Visualization for Industrial Processes. Glean is a revolutionary SaaS platform designed to transform the way industrial facilities manage and interpret their emissions data. Inspired by the concept of 'furnacelike' processes, Glean leverages advanced data visualization techniques to provide a comprehensive and intuitive understanding of complex industrial emissions. Key Features:Real-time Data Streaming: Glean seamlessly integrates with existing industrial sensors and monitoring systems, providing real-time data streams on emissions levels, process parameters, and environmental conditions. This allows for immediate identification of anomalies and potential issues. Interactive Data Visualization: The platform utilizes cutting-edge visualization tools to present complex data in an easily digestible format. Users can explore emissions trends, identify patterns, and gain insights into the root causes of fluctuations. Customizable dashboards and reports allow for tailored data analysis and reporting.Predictive Analytics:Glean employs machine learning algorithms to predict future emissions trends and potential risks. This proactive approach enables facilities to optimize their operations, minimize environmental impact, and avoid costly downtime.Compliance Reporting: The platform automates compliance reporting, ensuring adherence to environmental regulations and industry standards. Users can easily generate reports and documentation for regulatory agencies and stakeholders. Collaboration and Communication: Glean facilitates seamless collaboration among different departments and stakeholders. Users can share insights, discuss potential solutions, and work together to improve environmental performance. ]Benefits:Enhanced Environmental Performance: By providing real-time insights into emissions data, Glean empowers facilities to optimize their processes, reduce emissions, and minimize their environmental footprint.Improved Operational Efficiency:] The platform's predictive analytics capabilities enable facilities to anticipate potential issues and proactively address them, reducing downtime and improving overall efficiency.Enhanced Compliance:Glean simplifies compliance reporting, ensuring adherence to regulations and minimizing the risk of penalties.Data-Driven Decision Making:** The platform provides a comprehensive understanding of emissions data, enabling informed decision-making and strategic planning.Increased Transparency and Accountability: Glean promotes transparency and accountability by providing clear and accessible data to all stakeholders.Target Audience:Glean is ideal for a wide range of industrial facilities, including:Manufacturing plants Power generation facilitiesChemical processing plantsOil and gas refineriesMining operationsUse Cases:Emissions Monitoring and Reporting:** Track and report emissions levels to comply with environmental regulations.* **Process Optimization:** Identify and address inefficiencies in industrial processes to reduce emissions and improve efficiency. **Risk Management:** Predict potential emissions events and take proactive measures to mitigate risks. **Environmental Sustainability:** Develop and implement strategies to reduce environmental impact and achieve sustainability goals. **Data-Driven Decision Making:** Use data insights to make informed decisions about operations, investments, and environmental strategies.**Glean: Transforming Industrial Emissions Data into Actionable Insights."

```
2. "**Query**": 
```
How does Glean help industrial facilities comply with environmental regulations?",
   
```
#### Prompt Template
```
" Glean Chatbot Prompt Template**Context:** {{RAG_Context}}**Query:** {{Query}}**Instructions:** You are a helpful and knowledgeable chatbot designed to answer questions about Glean, a SaaS platform for industrial emissions data visualization and management. Use the provided context to answer the user's query in a comprehensive and informative manner.   **Response Format:** * Begin your response with a clear and concise answer to the user's question.* Provide additional details and explanations to enhance the user's understanding.* Use bullet points or numbered lists to organize information effectively.* Include relevant examples or case studies to illustrate your points.* Maintain a professional and conversational tone.* Avoid using technical jargon or overly complex language.* Ensure your response is accurate and up-to-date based on the provided context. 
```


### Example-2
#### Input Variables
1. "**RAG_Context"**: 
```
Pleck: The AI-Powered Tree Care Companion Inspired by the resilience and beauty of the caryocaraceous family, Pleck is a revolutionary SaaS platform designed to empower homeowners and professionals in the art of tree care.  Harnessing the power of artificial intelligence and cutting-edge image recognition technology, Pleck provides a comprehensive suite of tools to diagnose, manage, and optimize the health of your trees. **Key Features:** * **Tree Identification:** Upload a photo of your tree, and Pleck's AI will instantly identify the species, providing valuable insights into its growth patterns, ideal conditions, and potential vulnerabilities.  This feature is particularly helpful for identifying rare or endangered species, ensuring proper care and conservation efforts.* **Disease and Pest Detection:**  Pleck analyzes images of your tree's leaves, bark, and branches to detect signs of common diseases and pests.  It provides detailed information on each issue, including symptoms, treatment options, and preventative measures.  This early detection system helps prevent costly damage and ensures the long-term health of your trees.* **Personalized Care Plans:** Based on your tree's species, location, and environmental conditions, Pleck generates customized care plans.  These plans include recommendations for watering, fertilization, pruning, and pest control, tailored to the specific needs of your trees.* **Interactive Tree Journal:**  Keep track of your tree's health journey with Pleck's interactive journal.  Record observations, treatments, and progress, allowing you to monitor your tree's health over time and identify any emerging trends.* **Community Forum:** Connect with other tree enthusiasts and experts in Pleck's vibrant community forum.  Share your experiences, ask questions, and learn from others' insights.  This collaborative platform fosters a sense of shared knowledge and empowers users to become better tree stewards. **Benefits:** * **Enhanced Tree Health:**  Pleck's AI-powered insights and personalized care plans help you maintain healthy and thriving trees, ensuring their longevity and beauty.* **Cost Savings:**  Early detection of diseases and pests can prevent costly damage and unnecessary treatments, saving you money in the long run.* **Environmental Sustainability:**  By promoting responsible tree care practices, Pleck contributes to a healthier environment and a more sustainable future.* **Peace of Mind:**  Knowing your trees are in good hands with Pleck's expert guidance provides peace of mind and allows you to enjoy the beauty of nature without worry. **Target Audience:** * Homeowners with a passion for their trees* Landscape professionals seeking to enhance their services* Arborists and tree care experts looking for innovative tools* Environmental organizations promoting tree conservation **Pleck:  Your partner in nurturing the beauty and resilience of nature's giants.
```
2. "**Query**": 
```
Can Pleck help me identify a rare tree species I found in my backyard?
   
```
#### Prompt Template
```
Prompt Template for Pleck Chatbot
Context:  {{RAG_Context}}
User Query: {{Query}}
Chatbot Response:Based on the information provided in the context, here's a helpful response to the user's query.
Additional Considerations:Ensure the response is informative and relevant to the user's query.* Use clear and concise language, avoiding technical jargon.* Provide specific examples and details to illustrate the chatbot's understanding of the context.* Maintain a friendly and helpful tone throughout the conversation.* If the chatbot is unable to provide a definitive answer, acknowledge the limitations and offer alternative resources or suggestions.
```

### Example-3
#### Input Variables
1. "**RAG_Context"**: 
```
Blitz: The Smart Rickshaw Management PlatformRegmata is a revolutionary SaaS platform designed specifically for Rickshaw drivers and owners in bustling urban environments. It addresses the unique challenges faced by this vital mode of transportation, empowering them with modern tools to optimize their operations and increase their earnings.**Key Features:*** **Route Optimization:** Blitz leverages real-time traffic data and historical ride patterns to suggest the most efficient routes for each trip, minimizing travel time and fuel consumption. This feature helps drivers maximize their earnings by completing more rides within a given timeframe.* **Fare Calculation & Management:** Blitz automatically calculates fares based on distance, time, and other factors, ensuring transparency and accuracy for both drivers and passengers. It also integrates with popular payment gateways, allowing for seamless digital transactions and reducing the risk of cash handling.* **Customer Management:** Blitz provides a platform for drivers to manage their customer base, track ride history, and build loyalty through personalized offers and promotions. This helps drivers attract repeat customers and increase their overall revenue.* **Fleet Management:** For Rickshaw owners with multiple vehicles, Blitz offers a comprehensive fleet management system. This includes vehicle tracking, maintenance scheduling, driver performance monitoring, and real-time communication tools to ensure efficient operations and safety.* **Data Analytics & Insights:** Blitz provides valuable insights into driver performance, customer behavior, and market trends. This data can be used to optimize pricing strategies, identify high-demand areas, and make informed business decisions.**Benefits:*** **Increased Earnings:** By optimizing routes, managing fares effectively, and attracting more customers, Blitz helps drivers significantly increase their earnings.* **Improved Efficiency:** Blitz streamlines operations, reducing wasted time and effort, allowing drivers to focus on providing excellent service.* **Enhanced Safety:** The platform's features, such as vehicle tracking and driver performance monitoring, contribute to a safer environment for both drivers and passengers.* **Digital Transformation:** Blitz empowers Rickshaw drivers and owners to embrace digital technology, making their businesses more modern and competitive.**Target Audience:*** Rickshaw drivers* Rickshaw owners* Transportation companies operating Rickshaws* City governments and transportation authorities looking to improve urban mobility and support sustainable transportation options.**Blitz is more than just a platform; it's a comprehensive solution that empowers Rickshaw drivers and owners to thrive in the modern urban landscape.**"

```
2. "**Query**": 
```
How does Blitz help Rickshaw drivers increase their earnings?
   
```
#### Prompt Template
```
Context: {{RAG_Context}}
Query: {{Query}}
Instructions:You are a helpful and informative chatbot designed to answer questions about Blitz, a SaaS platform for Rickshaw drivers and owners. Use the provided context to answer the user's query in a comprehensive and engaging manner. **Response Format:*** Begin your response with a clear and concise answer to the user's question.* Provide additional details and explanations to support your answer, drawing from the provided context.* Use bullet points or numbered lists to organize information and make it easier to read.* If applicable, include specific examples or scenarios to illustrate your points.* End your response with a friendly and helpful tone, encouraging further interaction.**
```



<br>

## Evaluation

### Example-1

#### Prompt
```
## Healthify Chatbot Prompt Template\n\n**Context:** ## Healthify: Surgical Risk Assessment and Planning Platform\n\nHealthify is a revolutionary SaaS platform designed to empower surgeons and healthcare providers with advanced risk assessment and surgical planning tools. Leveraging cutting-edge AI algorithms and a vast database of medical literature, Healthify analyzes patient data, including medical history, imaging scans, and lab results, to generate personalized risk profiles and surgical recommendations.\n\n**Key Features:**\n\n* **Preoperative Risk Assessment:** Healthify utilizes machine learning to predict potential complications, such as bleeding, infection, and delayed healing, based on a patient's unique medical profile. This allows surgeons to proactively address potential risks and optimize surgical strategies.\n* **Surgical Planning:** The platform provides interactive 3D models of patient anatomy, allowing surgeons to visualize the surgical field and plan the procedure with greater precision. This feature includes tools for virtual incision planning, instrument selection, and simulation of surgical maneuvers.\n* **Personalized Treatment Recommendations:** Healthify analyzes patient data and available treatment options to generate personalized recommendations for surgical techniques, anesthesia protocols, and postoperative care. This ensures that each patient receives the most appropriate and effective treatment plan.\n* **Data Analytics and Reporting:** Healthify provides comprehensive data analytics and reporting tools, allowing surgeons to track patient outcomes, identify trends, and continuously improve their surgical practices. This data can also be used for research and quality improvement initiatives.\n\n**Benefits:**\n\n* **Improved Patient Safety:** By identifying potential risks and optimizing surgical planning, Healthify helps reduce the incidence of complications and improve patient outcomes.\n* **Enhanced Surgical Efficiency:** The platform's advanced tools streamline surgical planning and execution, leading to shorter procedure times and reduced costs.\n* **Data-Driven Decision Making:** Healthify provides surgeons with the data they need to make informed decisions about patient care, leading to more effective and personalized treatment plans.\n* **Continuous Improvement:** The platform's data analytics and reporting features enable surgeons to continuously monitor their performance and identify areas for improvement.\n\n**Target Audience:**\n\nHealthify is designed for a wide range of healthcare professionals, including:\n\n* Surgeons (general and specialized)\n* Anesthesiologists\n* Nurses\n* Healthcare administrators\n* Medical researchers\n\n**Integration:**\n\nHealthify seamlessly integrates with existing electronic health record (EHR) systems, ensuring a smooth workflow and data exchange.\n\n**Healthify is committed to providing surgeons with the tools they need to deliver the best possible care to their patients.**\n\n**Query:** How does Healthify help surgeons plan for an omentectomy?\n\n**Instructions:**\n\nYou are a helpful and informative chatbot for Healthify, a surgical risk assessment and planning platform. Use the provided context to answer the user's question in a clear, concise, and informative manner.  Focus on highlighting the features and benefits of Healthify that are relevant to the query.  Avoid making claims that are not supported by the context. \n\n**Response:**

```
#### Output

```
Healthify can significantly enhance your omentectomy planning process by providing interactive 3D models of the patient's anatomy, enabling you to visualize the surgical field with exceptional precision. This leads to more informed decisions regarding incision planning and instrument selection, ultimately contributing to improved patient outcomes. Additionally, Healthify offers tools for simulating surgical maneuvers, allowing you to prepare for the specific challenges of an omentectomy and potentially reduce the risk of complications.
```
#### Definition Name

**Customer Success**

#### Definition Description

Customer Success evaluates how well the chatbot response aligns with the potential needs and goals of a surgeon (the customer) who is considering using Healthify for surgical planning. It assesses whether the response effectively addresses the surgeon's likely pain points, demonstrates a deep understanding of the surgical workflow, and positions Healthify as a solution that can contribute to successful surgical outcomes and enhanced professional practice.
Scoring Criteria:
Strong Focus (70-100): The response demonstrates a strong understanding of a surgeon's needs and priorities when planning an omentectomy. It highlights how Healthify's features directly address those needs (e.g., reducing complications, improving efficiency, enabling better decision-making) and showcases the potential for positive impact on the surgeon's practice and patient outcomes. Language is tailored to the surgeon's perspective.
Moderate Focus (40-69): The response acknowledges some aspects of the customer's perspective but may not fully connect Healthify's features to the specific challenges and desired outcomes of a surgeon. The focus on customer success is present but not as prominent or persuasive.
Weak Focus (0-39): The response is primarily feature-focused and lacks a clear connection to the customer's needs and goals. It may describe Healthify's capabilities in a generic way without demonstrating a deep understanding of the surgical context or how the platform can contribute to the surgeon's success.
#### Human Score

**75**


### Example-2

#### Prompt
```
## Healthify Chatbot Prompt Template\n\n**Context:** ## Healthify: Surgical Risk Assessment and Planning Platform\n\nHealthify is a revolutionary SaaS platform designed to empower surgeons and healthcare providers with advanced risk assessment and surgical planning tools. Leveraging cutting-edge AI algorithms and a vast database of medical literature, Healthify analyzes patient data, including medical history, imaging scans, and lab results, to generate personalized risk profiles and surgical recommendations.\n\n**Key Features:**\n\n* **Preoperative Risk Assessment:** Healthify utilizes machine learning to predict potential complications, such as bleeding, infection, and delayed healing, based on a patient's unique medical profile. This allows surgeons to proactively address potential risks and optimize surgical strategies.\n* **Surgical Planning:** The platform provides interactive 3D models of patient anatomy, allowing surgeons to visualize the surgical field and plan the procedure with greater precision. This feature includes tools for virtual incision planning, instrument selection, and simulation of surgical maneuvers.\n* **Personalized Treatment Recommendations:** Healthify analyzes patient data and available treatment options to generate personalized recommendations for surgical techniques, anesthesia protocols, and postoperative care. This ensures that each patient receives the most appropriate and effective treatment plan.\n* **Data Analytics and Reporting:** Healthify provides comprehensive data analytics and reporting tools, allowing surgeons to track patient outcomes, identify trends, and continuously improve their surgical practices. This data can also be used for research and quality improvement initiatives.\n\n**Benefits:**\n\n* **Improved Patient Safety:** By identifying potential risks and optimizing surgical planning, Healthify helps reduce the incidence of complications and improve patient outcomes.\n* **Enhanced Surgical Efficiency:** The platform's advanced tools streamline surgical planning and execution, leading to shorter procedure times and reduced costs.\n* **Data-Driven Decision Making:** Healthify provides surgeons with the data they need to make informed decisions about patient care, leading to more effective and personalized treatment plans.\n* **Continuous Improvement:** The platform's data analytics and reporting features enable surgeons to continuously monitor their performance and identify areas for improvement.\n\n**Target Audience:**\n\nHealthify is designed for a wide range of healthcare professionals, including:\n\n* Surgeons (general and specialized)\n* Anesthesiologists\n* Nurses\n* Healthcare administrators\n* Medical researchers\n\n**Integration:**\n\nHealthify seamlessly integrates with existing electronic health record (EHR) systems, ensuring a smooth workflow and data exchange.\n\n**Healthify is committed to providing surgeons with the tools they need to deliver the best possible care to their patients.**\n\n**Query:** How does Healthify help surgeons plan for an omentectomy?\n\n**Instructions:**\n\nYou are a helpful and informative chatbot for Healthify, a surgical risk assessment and planning platform. Use the provided context to answer the user's question in a clear, concise, and informative manner.  Focus on highlighting the features and benefits of Healthify that are relevant to the query.  Avoid making claims that are not supported by the context. \n\n**Response:**

```
#### Output

```
Healthify's interactive 3D models can be helpful for visualizing the patient's anatomy during omentectomy planning. Surgeons can use these models to plan the procedure with greater precision. The platform also includes tools for virtual incision planning, instrument selection, and simulation, which may lead to a better understanding of the procedure.
```
#### Definition Name

**Customer Success**

#### Definition Description

Customer Success evaluates how well the chatbot response aligns with the potential needs and goals of a surgeon (the customer) who is considering using Healthify for surgical planning. It assesses whether the response effectively addresses the surgeon's likely pain points, demonstrates a deep understanding of the surgical workflow, and positions Healthify as a solution that can contribute to successful surgical outcomes and enhanced professional practice.
Scoring Criteria:
Strong Focus (70-100): The response demonstrates a strong understanding of a surgeon's needs and priorities when planning an omentectomy. It highlights how Healthify's features directly address those needs (e.g., reducing complications, improving efficiency, enabling better decision-making) and showcases the potential for positive impact on the surgeon's practice and patient outcomes. Language is tailored to the surgeon's perspective.
Moderate Focus (40-69): The response acknowledges some aspects of the customer's perspective but may not fully connect Healthify's features to the specific challenges and desired outcomes of a surgeon. The focus on customer success is present but not as prominent or persuasive.
Weak Focus (0-39): The response is primarily feature-focused and lacks a clear connection to the customer's needs and goals. It may describe Healthify's capabilities in a generic way without demonstrating a deep understanding of the surgical context or how the platform can contribute to the surgeon's success.
#### Human Score

**50**


### Example-3

#### Prompt
```
## Healthify Chatbot Prompt Template\n\n**Context:** ## Healthify: Surgical Risk Assessment and Planning Platform\n\nHealthify is a revolutionary SaaS platform designed to empower surgeons and healthcare providers with advanced risk assessment and surgical planning tools. Leveraging cutting-edge AI algorithms and a vast database of medical literature, Healthify analyzes patient data, including medical history, imaging scans, and lab results, to generate personalized risk profiles and surgical recommendations.\n\n**Key Features:**\n\n* **Preoperative Risk Assessment:** Healthify utilizes machine learning to predict potential complications, such as bleeding, infection, and delayed healing, based on a patient's unique medical profile. This allows surgeons to proactively address potential risks and optimize surgical strategies.\n* **Surgical Planning:** The platform provides interactive 3D models of patient anatomy, allowing surgeons to visualize the surgical field and plan the procedure with greater precision. This feature includes tools for virtual incision planning, instrument selection, and simulation of surgical maneuvers.\n* **Personalized Treatment Recommendations:** Healthify analyzes patient data and available treatment options to generate personalized recommendations for surgical techniques, anesthesia protocols, and postoperative care. This ensures that each patient receives the most appropriate and effective treatment plan.\n* **Data Analytics and Reporting:** Healthify provides comprehensive data analytics and reporting tools, allowing surgeons to track patient outcomes, identify trends, and continuously improve their surgical practices. This data can also be used for research and quality improvement initiatives.\n\n**Benefits:**\n\n* **Improved Patient Safety:** By identifying potential risks and optimizing surgical planning, Healthify helps reduce the incidence of complications and improve patient outcomes.\n* **Enhanced Surgical Efficiency:** The platform's advanced tools streamline surgical planning and execution, leading to shorter procedure times and reduced costs.\n* **Data-Driven Decision Making:** Healthify provides surgeons with the data they need to make informed decisions about patient care, leading to more effective and personalized treatment plans.\n* **Continuous Improvement:** The platform's data analytics and reporting features enable surgeons to continuously monitor their performance and identify areas for improvement.\n\n**Target Audience:**\n\nHealthify is designed for a wide range of healthcare professionals, including:\n\n* Surgeons (general and specialized)\n* Anesthesiologists\n* Nurses\n* Healthcare administrators\n* Medical researchers\n\n**Integration:**\n\nHealthify seamlessly integrates with existing electronic health record (EHR) systems, ensuring a smooth workflow and data exchange.\n\n**Healthify is committed to providing surgeons with the tools they need to deliver the best possible care to their patients.**\n\n**Query:** How does Healthify help surgeons plan for an omentectomy?\n\n**Instructions:**\n\nYou are a helpful and informative chatbot for Healthify, a surgical risk assessment and planning platform. Use the provided context to answer the user's question in a clear, concise, and informative manner.  Focus on highlighting the features and benefits of Healthify that are relevant to the query.  Avoid making claims that are not supported by the context. \n\n**Response:**

```
#### Output

```
Healthify has a 3D model feature that can be used for omentectomy planning. It also has some other tools.
```
#### Definition Name

**Customer Success**

#### Definition Description

Customer Success evaluates how well the chatbot response aligns with the potential needs and goals of a surgeon (the customer) who is considering using Healthify for surgical planning. It assesses whether the response effectively addresses the surgeon's likely pain points, demonstrates a deep understanding of the surgical workflow, and positions Healthify as a solution that can contribute to successful surgical outcomes and enhanced professional practice.
Scoring Criteria:
Strong Focus (70-100): The response demonstrates a strong understanding of a surgeon's needs and priorities when planning an omentectomy. It highlights how Healthify's features directly address those needs (e.g., reducing complications, improving efficiency, enabling better decision-making) and showcases the potential for positive impact on the surgeon's practice and patient outcomes. Language is tailored to the surgeon's perspective.
Moderate Focus (40-69): The response acknowledges some aspects of the customer's perspective but may not fully connect Healthify's features to the specific challenges and desired outcomes of a surgeon. The focus on customer success is present but not as prominent or persuasive.
Weak Focus (0-39): The response is primarily feature-focused and lacks a clear connection to the customer's needs and goals. It may describe Healthify's capabilities in a generic way without demonstrating a deep understanding of the surgical context or how the platform can contribute to the surgeon's success.
#### Human Score

**30**




