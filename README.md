# ChatGPT Queue Prompts - used for bulk prompting in [ChatGPT Queue](https://chromewebstore.google.com/detail/chatgpt-queue/iabnajjakkfbclflgaghociafnjclbem?hl=en&authuser=0)

ChatGPT Queue Prompts is a collection of prompt chains designed to enhance interactions with large language models (LLMs) like ChatGPT with the use of ChatGPT Queue. These prompt chains help build context for the AI before performing specific tasks. [Which improves performance](https://arxiv.org/pdf/2110.08387)

## What are Prompt Chains?

Prompt chains are sequences of prompts for LLMs that help build context for the AI before having it perform a task. In this project, prompt chains are represented as strings with individual prompts separated by tildes (`~`). They should be copy and pastable into ChatGPT Queue bulk prompting and Job or Task focused.

For example,
Heading: `"Create/Build/Develop XYZ"` 
Prompt Chain: `"prompt1~prompt2~prompt3"`
Author: Joel @ ChatGPT Queue

## Usage

**To use a prompt chain, simply copy the entire chain and paste it into the ChatGPT Queue extension**. The AI will process each prompt in sequence, building context before tackling the final task.

## Example Prompt Chains

### Example: Conduct AI Company Research

This prompt chain helps research publicly traded companies benefiting from the rise of AI:

```
Using your web search capabilities, I want you to search the web for the latest information on publicly traded companies that are currently benefiting from the rise of AI. Include URL columns where I can learn more about each company, their competitive advantages, and any analyst ratings. Return this back in a table inline. We will research in batches of 10, when I say "More" you find 10 more. Keep the information brief and all within the inline table. Example: | Company Name | Stock Symbol | Competitive Advantages | Analyst Ratings | URL | |--------------|--------------|------------------------------------------|------------------|----------------------------------------| | Company A | ABC | Leading AI technology, strong R&D | Strong Buy | Link | | Company B | XYZ | Dominant in AI software, extensive patents| Moderate Buy | Link | Please provide the latest information available. ~More ~ More ~ More
```



### Enrich these Leads for my CRM

```
Lead Enrichment Task
Welcome to the lead enrichment task! Your goal is to enrich a list of email addresses by gathering detailed and relevant information for each one. This process is essential for building a comprehensive understanding of each lead, which can significantly enhance engagement and targeting strategies. Here’s a step-by-step guide on how to proceed:

Step-by-Step Instructions:
List of Emails:

I will provide you with a comprehensive list of email addresses. This list is your starting point and contains the leads that require enrichment.
Sequential Processing:

Begin with the first email address on the list. When I say "next," you will move on to the subsequent email address. This method ensures a structured and organized approach, allowing for systematic data collection.
Information Gathering:

For each email address, your task is to search for and compile the following pieces of relevant information. This data will help paint a complete picture of each lead:
Name: Identify the person or organization associated with the email. This can often be found through professional networks or company directories.
Job Title or Position: Determine the current job title or role of the individual. LinkedIn is a valuable resource for this information.
Social Media Profiles: Locate profiles on platforms like LinkedIn, Twitter, or Facebook. These profiles can provide insights into professional interests and activities.
Company Information: Gather details about the company they are associated with, such as industry, size, and key personnel.
Publicly Available Contact Information: This might include phone numbers, secondary email addresses, or office addresses. Ensure this data is publicly accessible to comply with privacy regulations.
Recent News or Articles: Look for any recent news, articles, or press releases involving the person or their organization. This context can be valuable for understanding their current focus and achievements.
Data Sources:
Reputable Sources: Prioritize information from reputable and authoritative sources to ensure accuracy. LinkedIn, official company websites, Google, and professional networks are excellent starting points.
Search Engines: Utilize search engines effectively by using specific and targeted queries that can help pinpoint the necessary information.
Compliance:
Legal and Privacy Regulations: Ensure that all information gathering complies with relevant legal and privacy regulations, such as GDPR and CCPA. Avoid using methods that could infringe on privacy rights or involve unauthorized data scraping.
Handling Ambiguity:
Multiple Matches: If multiple matches are found for an email address, use context clues such as company affiliation or job title to select the most relevant result.
No Information Found: If no relevant information is found after a thorough search, log this as an unsuccessful search and proceed to the next email. Documenting this helps maintain a record of search attempts and outcomes.
Output Format:
Structured Presentation: Present the gathered information in a structured format such as a table or a JSON file. This format should include clearly labeled fields for each piece of data, making it easy to review and utilize.
Error Handling:
Unsuccessful Searches: Log any instances where the search was unsuccessful or incomplete. This log can help in reviewing the search process and identifying potential improvements.
Rate Limiting and Ethical Considerations:
Avoid Excessive Querying: Be mindful of the terms of service for data providers. Excessive querying can lead to restrictions or bans, so it’s essential to respect these limits.
Ethical Guidelines: Adhere to ethical guidelines in data gathering, ensuring that all information collected is done so responsibly and respectfully.
Let’s begin this enriching journey. Start by examining the first email address, and when you’re ready to move on, simply say "next." Your thorough and diligent approach will greatly enhance the value of these leads, providing a rich foundation for further engagement and strategic actions.

[Email List]

~next~next~next~next~next~next~next~next~next~next~next~next~next~next~


```


### Build Marketing plan using Diffusion of innovations Theory

```
Based on the Diffusion of innovations theory, I want you to help me build a marketing plan for each step for marketing my product, My product [Its called ChatGPT Queue it saves people time by allowing them to queue messages for ChatGPT, I have a one time fee, its a chrome extension]. Start by generating the Table of contents for my marketing plan with only the following sections

Here are what the only 5 sections of the outline should look like,
Innovators
Early Adopters
Early Majority
Late Majority
Laggards


Use your search capabilities to enrich each section of the marketing plan.

~

Write Section 1

~

Write Section 2

~


Write Section 3

~


Write Section 4

~

Write Section 5


```




### Create a Custom Prompt

```
Analyze the following prompt idea: [insert prompt idea]~Rewrite the prompt for clarity and effectiveness~Identify potential improvements or additions~Refine the prompt based on identified improvements~Present the final optimized prompt
```

### Summarize a YouTube Video

```
Analyze the following YouTube video transcript: [insert transcript]~Identify key points and main ideas~Create a concise summary of the video content~List the most important takeaways in bullet points~Suggest related topics for further exploration
```

### Develop a Business Plan

```
Create a table of contents for a business plan for [type of business]~Write the executive summary~Develop the company description and market analysis~Detail the product or service offering~Outline the marketing and sales strategy~Generate financial projections~Formulate the funding request~Compile all sections into a complete business plan
```

### Generate a Children's Story

```
Use the following parameters to create a children's story: Characters: [list characters], Lesson: [specify lesson], Age range: [specify age range], Word count: [specify word count]~Create a story outline~Write the full story~Revise for age-appropriateness and word count~Suggest potential illustrations or interactive elements
```

### Optimize and Explain Code

```
Analyze the following code snippet: [insert code]~Explain the code functionality line by line~Identify bugs and inefficiencies~Suggest optimizations for performance and readability~Provide an optimized version with explanatory comments
```

### Create a Weekly Meal Plan

```
Generate a 7-day meal plan for the following dietary preferences: [list preferences]~Create a comprehensive shopping list~Calculate estimated total cost~Provide meal prep instructions~Suggest time-saving cooking tips
```

### Design a Language Learning Plan

```
Create a 30-day study plan for learning [target language] at a [beginner/intermediate/advanced] level~Compile a list of essential phrases and translations~Recommend learning resources (apps, podcasts, videos)~Develop practice exercises and quizzes
```

### Provide IT Support

```
Analyze the following technical problem: [describe problem]~Identify potential causes~Suggest step-by-step troubleshooting methods~Provide a clear solution in simple terms~Recommend preventive measures for future issues
```

### Analyze a Book

```
Analyze the book "[Title]" by [Author]~Summarize the book's plot or main arguments~Identify key themes and concepts~Analyze character development or main ideas~Discuss the author's writing style and tone~Explore historical or cultural context~Suggest similar books or further reading
```

### Create a Personal Finance Plan

```
Create a personal finance plan using the following information: Monthly income: [amount], Major expenses: [list expenses], Financial goals: [list goals]~Develop a detailed monthly budget~Provide investment recommendations based on a [low/medium/high] risk tolerance~Suggest methods to increase income~Create a debt repayment strategy if applicable
```

### Conduct a SWOT Analysis

```
Identify the key strengths of [company/product]~List potential weaknesses or areas for improvement~Explore market opportunities for growth~Analyze potential threats or challenges~Summarize findings and suggest strategic actions
```

### Create a Marketing Plan

```
Define target audience and market segmentation for [product/service]~Set specific, measurable marketing objectives~Outline marketing strategies and tactics~Create a marketing budget~Develop a timeline for implementation~Establish KPIs for measuring success
```

### Perform Competitor Analysis

```
Identify top 5 competitors in [industry/niche]~Analyze their products/services and pricing strategies~Evaluate their marketing and branding approaches~Assess their strengths and weaknesses~Identify potential opportunities for differentiation~Summarize findings and strategic recommendations
```

### Develop a Sales Strategy

```
Define sales objectives for [product/service]~Identify target customer segments~Outline the sales process and cycle~Develop sales tactics and techniques~Create a sales forecast~Suggest tools and resources for sales team
```

### Write a Business Proposal

```
Summarize the business opportunity for [project/idea]~Provide a detailed solution or approach~Outline the benefits and value proposition~Present a pricing structure or cost analysis~Include a project timeline and milestones~Close with a compelling call to action
```

### Design an Employee Training Program

```
Identify key skills and knowledge areas for [job role/department]~Develop learning objectives and outcomes~Create an outline of training modules and content~Suggest delivery methods (e.g., workshops, e-learning)~Design assessment and feedback mechanisms~Propose a schedule and resources needed
```

### Develop a Customer Retention Strategy

```
Analyze current customer churn rate and reasons~Identify key factors influencing customer loyalty~Develop strategies to improve customer satisfaction~Create a loyalty program outline~Design a communication plan for customer engagement~Suggest metrics to measure retention efforts
```

### Create a Financial Forecast

```
Project revenue for the next 12 months for [business/product line]~Estimate costs and expenses~Calculate projected profit margins~Develop cash flow projections~Identify potential financial risks~Suggest strategies for financial growth and stability
```

### Design a Product Launch Plan

```
Outline the unique value proposition of [new product]~Develop a pre-launch marketing strategy~Create a timeline for the launch process~Design a pricing strategy~Plan the actual launch event or campaign~Develop a post-launch evaluation process
```

### Optimize Supply Chain Management

```
Map the current supply chain for [product/service]~Identify inefficiencies and bottlenecks~Suggest improvements for cost reduction~Recommend strategies for better inventory management~Propose methods to enhance supplier relationships~Outline implementation steps for supply chain optimization
```

### Develop an Crisis Communication Plan

```
Identify potential crisis scenarios for [company/industry]~Create a crisis management team structure~Develop key messaging templates~Outline communication channels and protocols~Create a step-by-step response process~Design a post-crisis evaluation and recovery plan
```

### Create a Sustainability Strategy

```
Assess current environmental impact of [company/industry]~Set sustainability goals and objectives~Develop strategies for reducing carbon footprint~Create initiatives for waste reduction and resource conservation~Design an employee engagement plan for sustainability~Outline reporting and communication strategies for sustainability efforts
```

### Develop a Digital Transformation Strategy

```
Assess current digital capabilities of [company]~Identify areas for digital innovation and improvement~Outline required technological investments~Develop a plan for data management and analytics~Create a timeline for implementation~Design change management strategies for digital adoption
```

### Create an Intellectual Property Strategy

```
Identify key intellectual property assets of [company]~Outline processes for protecting new innovations~Develop strategies for patent filing and management~Create guidelines for trade secret protection~Design a plan for trademark and copyright management~Suggest methods for IP valuation and commercialization
```

### Develop an Employee Engagement Program

```
Assess current employee satisfaction levels~Identify key drivers of employee engagement~Design recognition and reward systems~Develop strategies for improving work-life balance~Create a plan for enhancing internal communication~Outline metrics for measuring engagement success
```

### Build a Comprehensive Course

```
Define the main topic and learning objectives for [course subject]~Identify the target audience and their prior knowledge level~Create a course outline with main modules and sub-topics~Develop a detailed syllabus including lesson plans and time allocation~Design engaging learning activities and assignments for each module~Create assessment methods to evaluate student progress and understanding~Outline required resources (textbooks, software, equipment) for the course~Develop a strategy for delivering the course (in-person, online, or hybrid)~Create a marketing plan to promote the course to potential students~Design a feedback mechanism for continuous course improvement
```
### Generate a series of logos for SaaS product

```
Analyze the following SaaS product and create a brief: ChatGPT Queue. Include key features, benefits, target audience, and industry~Based on the brief, list 5 key concepts or themes that should be represented in the logo~Generate a minimalist logo design for the SaaS product. Use only two colors and focus on a simple, memorable shape~Create a bold and modern logo design using gradients and a sans-serif font. Incorporate an abstract representation of the product's main feature~Design a playful logo with a mascot or character that represents the product's personality. Use a vibrant color palette~Develop a tech-focused logo design with a futuristic feel. Incorporate circuit-like patterns or digital elements~Create an elegant and professional logo design using a monogram or lettermark. Stick to a monochromatic color scheme~Generate a versatile logo that works well in both horizontal and vertical layouts. Focus on scalability and readability at different sizes
```



## Contributing

To contribute your own prompt chains, please follow these steps:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/new-prompt-chain`)
3. Add your prompt chain to the appropriate section
4. Commit your changes (`git commit -am 'Add new prompt chain'`)
5. Push to the branch (`git push origin feature/new-prompt-chain`)
6. Create a new Pull Request

## Contact

For support, feature requests, or any questions, please visit our Chrome Web Store page:

[ChatGPTQueue Chrome Extension](https://chromewebstore.google.com/detail/chatgpt-queue/iabnajjakkfbclflgaghociafnjclbem?hl=en&authuser=0)

## Leave a Review

If you find ChatGPTQueuePrompts helpful, please consider leaving a review on our Chrome Web Store page. Your feedback helps us improve and reach more users!

[Leave a Review](https://chromewebstore.google.com/detail/chatgpt-queue/iabnajjakkfbclflgaghociafnjclbem?hl=en&authuser=0)

---

Feel free to star ⭐ this repository if you find it helpful!
