## Chat App - Forth Implementation - in Vanilla Rails - No Docker
### Episode 4: User and Room Management

In this episode, we implement functionality for managing users and rooms in a Rails application. Users can create rooms, view their associated rooms, and log out. Rooms are displayed dynamically, and actions are handled using Turbo Frames for real-time updates.
Features

    User Authentication: Users can log in and log out.
    Room Management: Users can create and view rooms associated with them.
    Turbo Frames: Real-time updates for creating rooms and displaying user-specific content.

Setup

    Install dependencies:
    Run the following command to install all required gems:

bundle install

Set up the database:

Run the commands below to set up the database:

    rails db:drop
    rails db:migrate

Start the server:

Run the server on 0.0.0.0:3001:

    rails s -b 0.0.0.0 -p 3001

Create users and rooms:

Create two users and populate their rooms as shown in the application.
## Documentation

[Documentation](https://medium.com/jungletronics/turbo-powered-chat-rooms-real-time-updates-with-hotwire-fb196de42353)


## License

[MIT](https://choosealicense.com/licenses/mit/)

