# Copilot-Studio
Copilot Studio is a low-code development platform by Microsoft designed for creating AI-powered virtual agents. It allows users—ranging from business users to professional developers—to build and deploy conversational experiences quickly and effectively.

Key Features:
- Natural Language Processing (NLP): Understands and responds to user queries in natural language.
- Low-Code Interface: Simplifies bot development with visual authoring tools, making it accessible to non-developers.
- AI Integration: Leverages Microsoft Azure AI capabilities for intelligent conversation handling.
- Workflow Automation: Automates business processes by integrating with Microsoft Power Platform (Power Automate, Power Apps) and other external systems.
- Multichannel Support: Deploy bots across websites, Microsoft Teams, mobile apps, and other platforms.
- Extensibility: Connects to backend systems, databases, and APIs to provide dynamic responses and perform actions.

## Dataverse Knowledge Integration
This copilot uses Microsoft Dataverse tables (Account and Contact) as a knowledge source to answer business-related queries. It leverages Copilot Studio’s Knowledge feature to retrieve, interpret, and respond to structured organizational data with conversational context.

1. Use Dataverse tables (Account, Contact) as the primary knowledge source.
2. Retrieve accurate data from indexed table records.
3. Maintain conversation context across multiple questions.
4. Use column descriptions, synonyms, and glossary definitions to understand business terminology.
5. Provide clear, concise, and data-driven responses.
6. If information is unavailable, respond appropriately instead of generating assumptions.

 ![Alt Text](https://github.com/bacdillon/Copilot-Studio-Agents/blob/main/Dataverse%20Knowledge%20Integration/Dataverse%20Knowledge.png)

## Hair For Hope Agent
The Hair for Hope virtual assistant supports participants, donors, volunteers, and the public by providing timely, accurate, and friendly information about Singapore’s largest head-shaving event in solidarity with children with cancer. It helps users register, donate, explore event details, access press resources, and understand the cause — offering a warm and caring digital experience that reflects the spirit of Hair for Hope. 🎗️ https://hairforhope.org.sg/

 ![Alt Text](https://github.com/bacdillon/Copilot-Studio-Agents/blob/main/Hair%20For%20Hope%20Agent/img/main.png)

 ## Holland America Deck Plans – At a Glance
Holland America Line's deck plans provide a clear layout of each ship, showing where cabins, restaurants, lounges, pools, and entertainment venues are located. Each ship has its own design, and the plans help guests choose ideal staterooms, locate key amenities, and navigate the ship easily.

 ![IMAGE ALT TEXT HERE](https://github.com/bacdillon/Copilot-Studio/blob/main/Holland%20America%20Deck%20Plans/Rotterdam.png)

Whether you're booking a cabin or planning your onboard activities, deck plans are a handy guide for making the most of your cruise.

This Copilot Studio Agent uses uploaded images of Holland America cruise ship deck plans, stored in Dataverse. The images are automatically chunked and vectorized, allowing the Copilot to answer questions about ship layouts, such as locations of amenities like casinos. The current focus is on the deck plans for the Rotterdam ship.

![IMAGE ALT TEXT HERE](https://github.com/bacdillon/Copilot-Studio/blob/main/Holland%20America%20Deck%20Plans/Holland%20America%20Deck%20Plans%20Recording.gif)

## Intelligent IT Helpdesk Support
Assist you checking the status of ServiceNow IT helpdesk tickets (incidents) and provides information from knowledge articles related to company policies and HR scenarios and supports automatic detection of the user’s language for a seamless experience.

## Instruction
1. Launch the chat window 👉 <a href="https://bacdillon.github.io/Digital-IT-Helpdesk-Support/" target="_blank">Digital-IT-Helpdesk-Support</a>
2. Click Ticket Status Option <br>
3. Provide your email address that you have registered in ServiceNow. Or else enter given an email address: beth.anglin@example.com <br>
4. Enter the the Incident Number: INC0010008 or INC0010023 or INC0010040 <br>
5. You can ask for which category is this ticket? <br>
6. What department does my user profile say I am in? <br>
7. Close the chat session: Thanks that was helpful
 ![IMAGE ALT TEXT HERE](https://github.com/bacdillon/Digital-IT-Helpdesk-Support/blob/main/img/chat.png)

## Demo Restaurant - Authentic and Traditional German Cuisine and Beer restaurant
[![IMAGE ALT TEXT HERE](https://github.com/bacdillon/demo-coffee-house/blob/master/images/01.jpg
)](https://bacdillon.github.io/demo-coffee-house/)

