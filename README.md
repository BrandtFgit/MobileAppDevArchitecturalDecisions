# MobileAppDevArchitecturalDecisions
Team Anemone's Architectural Decisions Assignment


# Summary
- **Issue:** Choosing the appropriate architecture for developing a mobile app for a retail company.
- **Decision:** Use React Native with JavaScript for creating the mobile app.
- **Status:** Use React Native with JavaScript for creating the mobile app. Open to other architecture if applicable.

## Details

### Assumptions:
- The development team is proficient in JavaScript and React Native.
- React Native provides a well rounded environment for developers, as well as a good split between app performance and development efficiency.
- The app's requirements align with React Native's capabilities.
- We are not writing the database.

### Constraints:
- Potential limitations in React Native's capabilities.

### Positions:
- All members proposed development with React Native, as we all have been rapidly gaining experience in it, as well as being familiar with JavaScript.

### Argument:
React Native offers the advantages of a native-like user experience while leveraging JavaScript, a familiar language for the team. It allows for efficient development across iOS and Android platforms, reducing time and effort compared to maintaining separate codebases for each platform.

### Implications:
- Faster development cycles due to code reusability across platforms.
- Maintenance and updates are simplified with a single codebase.
- Access to native modules and libraries through React Native's bridging mechanism.
- Potential optimizations may be required for certain tasks.

## Related
### Related decisions:
- Selection of Redux for state management to enhance app scalability and maintainability.
### Related requirements:
- Support for offline mode, push notifications, and multiple languages.
### Related artifacts:
- Architectural diagrams outlining the app's components and interactions.
### Related principles:
- Principle of simplicity: Choosing the most straightforward solution that meets the project's needs.

## Notes
- Regular communication and collaboration among team members are crucial to address any challenges or limitations encountered during development.
- Continuous evaluation of the chosen architecture's performance and suitability throughout the development lifecycle is recommended.
