# CodeCon-Team-5
<br>Team Details 
Inspiration : The inspiration for creating the Food Bot stemmed from the increasing demand for user-friendly and efficient ways to explore dining options and food delivery services. As more people rely on technology to simplify their lives, we envisioned a conversational agent that could provide instant access to restaurant recommendations, meal ordering, and recipe suggestions—all through natural language interactions. <br>

What it does : The Food Bot serves as a virtual food assistant, allowing users to:

Order Food: Users can browse menus and place orders from nearby restaurants.
Get Restaurant Recommendations: It provides personalized restaurant suggestions based on cuisine preferences and location.
Receive Recipe Ideas: Users can ask for recipes based on ingredients they have at home or specific dietary needs.
Track Orders: The bot can integrate with delivery services to keep users updated on their order status. <br>

How we built it  : Dialogflow Setup: We created an account on Dialogflow and set up the project, defining intents and entities for various user interactions.
Intent Definition: We crafted intents such as "Order Food," "Restaurant Suggestions," and "Recipe Ideas" to handle user requests.
Entity Creation: Custom entities were defined to capture user inputs like cuisine type, dietary preferences, and location.
Webhook Fulfillment: We developed a backend service using Python/Node.js to process requests, communicate with external APIs, and return dynamic responses to the bot.
API Integration: Integrated third-party APIs like Zomato and Google Places to fetch restaurant data and menus, enhancing the bot's capabilities.
Testing & Deployment: We tested the bot thoroughly on the Dialogflow console and deployed it on platforms such as Facebook Messenger and a custom web application.<br>

Challenges we ran into: Natural Language Understanding: Ensuring the bot accurately understood diverse user inputs and regional dialects required extensive training and testing of intents.
API Limitations: Navigating the limitations and restrictions of third-party APIs posed challenges, particularly concerning data retrieval and usage quotas.
User Experience: Balancing between providing enough information and avoiding overwhelming users was critical in designing the conversation flow.
Integration Issues: Ensuring seamless integration between the Dialogflow agent, backend service, and APIs required careful planning and troubleshooting. <br>

What we learned : The importance of user feedback in refining conversational agents and improving the overall user experience.
Techniques for effectively handling natural language understanding challenges, including the use of training phrases and synonyms.
Strategies for optimizing API calls to enhance performance and minimize latency.
The value of iterative testing and deployment, allowing for quick adjustments based on real-world usage and feedback.<br>

Built With : Dialogflow: For creating the conversational interface and managing intents and entities.
Frontend Technologies: HTML, CSS, JavaScript for building the user interface.

<br>
