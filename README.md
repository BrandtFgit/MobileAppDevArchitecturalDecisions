# MobileAppDevArchitecturalDecisions
Team Anemone's Architectural Decisions Assignment


# Summary
- **Issue:** Choosing the appropriate architecture for developing a mobile app for a retail company.
- **Decision:** As a group we have decided that we are going to make use of React Native with JavaScript for the creation of the mobile app.
- **Status:** We will use React Native with JavaScript for creating the mobile app, this is the best approach for the time being. Although we are open to other architecture if applicable.

## Details

### Assumptions:
- The development team is proficient in JavaScript and React Native.
- React Native provides a well rounded environment for developers, as well as a good split between app performance and development efficiency.
- The app's requirements align with React Native's capabilities.
- We will not be writing the database.

### Constraints:
- Potential limitations in React Native's capabilities.
- Possibly running into performance issues while the app is running on different devices.

### Positions:
- All members proposed development with React Native, as we all have been rapidly gaining experience in it, as well as being familiar with JavaScript.
- We considered using Native Development as it has great performance but it would require a large amount of time and work to run on all platforms.

### Argument:
React Native offers the advantages of a native-like user experience while leveraging JavaScript, a familiar language for the team. It allows for efficient development across iOS and Android platforms, reducing time and effort compared to maintaining separate codebases for each platform.

### Implications:
- There would be faster development cycles due to code reusability across platforms.
- The maintenance and updates are simplified with the use of a single codebase.
- Access to native modules and libraries through React Native's bridging mechanism.
- Potential optimizations may be required for certain tasks.

## Related
### Related decisions:
- Selection of Redux for state management to enhance app scalability and maintainability.
- Choosing to use React Native Elements for creating the UI.
- For the navigation, we have decided to use React Native Navigation, as it has a large amount of development support.
- Implementing the strongest security protocols, such as HTTPS to handle delicate private information. 

### Related requirements:
- Support for offline mode, push notifications, and multiple languages.
- Looking into any third-party services would need to be implemented if applicable.
### Related artifacts:
- Architectural diagrams outlining the app's components and interactions.
### Related principles:
- Principle of simplicity: Choosing the most straightforward solution that meets the project's needs.

## Notes
- Regular communication and collaboration among team members are crucial to address any challenges or limitations encountered during development.
- Expressing any concerns team members have with upcoming project deadlines or milestones. 
