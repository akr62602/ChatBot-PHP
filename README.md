# PHP Chatbot

This is a simple PHP-based chatbot web application that allows users to interact with a chatbot. The chatbot responds to user messages in real-time, providing personalized answers.

## Features
- User-friendly interface with a clean design.
- Responsive layout that adapts to various screen sizes.
- Uses PHP, HTML, CSS, and JavaScript for smooth functionality.
- Data storage and retrieval facilitated by MySQL database.
- Messages are displayed in a conversation-style format.
- Timestamps for each message showing the time of sending/receiving.
- Two avatars for user and chatbot, enhancing the chat experience.
- Users can type messages and send them to the chatbot.
- The chatbot responds with appropriate answers based on user input.
- Utilizes jQuery for asynchronous communication with the server.
- Automatic scrolling for a better user experience when new messages are displayed.

## How to Use
1. Clone this repository to your local machine or server.
2. Set up the necessary database configuration in `database.inc.php`.
3. Import the provided `message.sql` file into your MySQL database.
4. Ensure your server supports PHP and MySQL.
5. Open the `index.php` file in your browser to start chatting with the chatbot.
6. Type a message in the input box and press "Send" to communicate with the chatbot.
7. Observe the chatbot's responses displayed in the chat area.
8. Enjoy conversing with the chatbot!

Note: The chatbot responses are based on predefined answers stored in the database (`message` table). You can customize and expand the responses as per your requirements.

## Credits
- This project uses Bootstrap 4.1.1 for CSS styling.
- The avatars are provided by `user_avatar.png` and `bot_avatar.png`.
- The chatbot logic is implemented in `get_bot_message.php`.
- Special thanks to the developers and contributors of the used libraries and resources.

## License
This project is open-source and free to use. Feel free to modify and improve it for your needs.
