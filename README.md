# CalendifyPlus - Calendar Event Scheduling Web Application

This is a prototype web application for scheduling calendar events, developed using Java and MongoDB.

## Available APIs

1. **Create Busy Slots**: Allows users to create busy slots for themselves during the day.
   - Endpoint: `/rest/save/addEvent`
   - Method: POST

2. **Fetch Events**: Allows users to fetch events of themselves and other users.
   - Endpoint: `/rest/retrive/fetchEvent`
   - Method: GET

3. **Fetch Conflicting Events**: Allows users to fetch events where they have conflicts for a particular day.
   - Endpoint: `/rest/retrive/fetchConflict`
   - Method: GET

4. **Fetch Favourable Upcoming Empty Slot**: Allows organizers of an event to fetch the most favorable upcoming empty slot for a given set of users and a particular duration.
   - Endpoint: `/rest/retrive/fetchUpcomingSlot`
   - Method: GET

5. **Create Event**: Allows users to create events with other users for a defined start time and end time.
   - Endpoint: `/rest/save/addEvent`
   - Method: POST

## Technical Choices

- **Java**: Chosen for its robustness, scalability, and extensive ecosystem of libraries and frameworks.
- **MongoDB**: Chosen as the database for its flexibility, scalability, and ability to handle unstructured data, which is suitable for storing calendar events.

## Trade-offs

- **Authentication**: Due to time constraints, authentication has been omitted. This simplifies the development process but sacrifices security.
- **UI**: The focus was on backend functionality, so no UI has been developed. This may limit the usability for end users who prefer graphical interfaces.
- **Testing**: While the code is designed to be modular and testable, comprehensive unit and integration testing may not have been implemented due to time constraints.

## Future Improvements

If I were to spend additional time on the project, I would:

- Implement authentication and authorization to secure the application.
- Develop a frontend UI to improve the user experience.
- Enhance testing coverage with unit tests, integration tests, and end-to-end tests.
- Optimize performance, especially for fetching events and calculating favorable slots.
- Refactor code for better readability, maintainability, and extensibility.

## Contributors

- [Pritam Saha](https://github.com/Pritamsaha-gitHub?tab=repositories)

Feel free to add more sections or customize the README according to your project's specific needs.
