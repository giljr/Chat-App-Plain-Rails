Chat App - Third Implementation

#### Overview

This is the third iteration of my Chat App, built with Ruby on Rails. Initially, I attempted to run the application using three separate containers, but due to persistent issues during development, I decided to proceed with a plain Rails app instead. This approach simplified the setup and allowed for more streamlined development.

#### Features

```
Real-time messaging

User authentication with Devise

Turbo Streams for live updates

Tailwind CSS for UI styling
```

#### Setup Instructions

Clone the repository:

```
git clone https://github.com/yourusername/chat-app-v3.git
cd chat-app-v3
```

Install dependencies:

```
bundle install
```

Set up the database:

```
rails db:create db:migrate db:seed
```

Run the server:

```
bin/dev
```

Access the app: Open http://localhost:3000 in your browser.

#### Notes

Originally, the app was containerized with three separate services, but due to issues with the setup, I opted for a traditional Rails environment.

Turbo Streams is used for real-time updates instead of ActionCable.

#### Future Improvements

Reintroduce containerization with a more refined approach.

Implement WebSockets for better real-time performance.

Add support for file sharing in chat.

##### License

This project is open-source and available under the MIT License.
