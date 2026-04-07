# vis-literacy

Project structure:

    data-visualization-chatbot:
        Source code for the chatbot-based onboarding prototype.

    data-visualization-scrollytelling:
        Source code for the scrollytelling-based onboarding prototype.

Steps to install:

    Chatbot:

        1. Install Node.js version v18.15.0 based on operating system.
            https://nodejs.dev/en/learn/how-to-install-nodejs/
        2. cd data-visualization-chatbot
        3. npm install

How to run the chatbot: 

    1. cd data-visualization-chatbot

    2. Server side:
        node src/backend.js

    3. Client side:
        npm start


How to run scrollytelling:

    1. cd data-visualization-scrollytelling

    2. Start the Server:
        python -m http.server

    3. Start heatmap onboarding:
        http://localhost:8000/Heatmap-Scrolly/

    4. Start treemap onboarding:
        http://localhost:8000/Treemap-Scrolly/
