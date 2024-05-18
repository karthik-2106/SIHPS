# Smart India Hackathon Workshop
# Date: 18-05-2024
## Register Number: 212223110020
## Name: KARTHIKEYAN M
## Problem Title
E-Waste Facility Locator
## Problem Description
Website that tells you the location of the nearest e-waste collection and recycling facility. Offers educational pop-ups on the harmful components of your e-waste and their effects on the environment and human health if not disposed correctly. There could be an option to input the model of your old device and earn credit points relative to the amount of precious metals recovered from the device if disposed correctly.
## Problem Creater's Organization
Ministry of Environment
## Idea
The idea is to create a user-friendly, informative, and engaging platform that empowers individuals to make a positive impact on the environment by responsibly managing their electronic waste. By combining practical tools for finding recycling facilities with educational resources and incentives for recycling, the website aims to promote a culture of sustainability and responsible consumption.

## Proposed idea / architecture diagram

1. **Database of E-Waste Facilities**: Start by compiling a comprehensive database of e-waste collection and recycling facilities. Include information such as their locations, operating hours, accepted items, and contact details.

2. **Interactive Map Interface**: Design an interactive map interface where users can enter their location or allow the website to access their location to find the nearest e-waste facility. The map should provide clear directions and information about each facility.

3. **Educational Content**: Integrate educational pop-ups or sections throughout the website to inform users about the harmful components of e-waste and their impact on the environment and human health. You could include articles, infographics, videos, or interactive modules to make the learning experience engaging.

4. **Device Input and Credit Points System**: Create a feature where users can input the model of their old device. Based on this information, calculate the estimated amount of precious metals and other valuable materials that can be recovered from the device through recycling. Offer users credit points or rewards relative to the value of the materials recovered. 

5. **User Accounts and Rewards System**: Implement a user account system where users can track their recycling activity, earn points for each recycled item, and redeem rewards such as discounts on new electronics or donations to environmental organizations.

6. **Mobile-Friendly Design**: Ensure that the website is mobile-friendly, as many users may access it from their smartphones while on the go.

7. **Partnerships and Outreach**: Collaborate with e-waste recycling companies, environmental organizations, and government agencies to promote the website and encourage participation in responsible e-waste disposal practices.

8. **Feedback and Improvement**: Gather feedback from users to continually improve the website's functionality and user experience. Regularly update the database of e-waste facilities to ensure accuracy and inclusivity.

By combining user convenience with educational resources and incentives, you can create a platform that not only facilitates e-waste recycling but also raises awareness about its importance for environmental sustainability.
![image](https://github.com/Vigneshv-23/SIHPS/assets/110780412/d65009af-6221-4c2c-87e3-5d42abd8a175)

## Use cases
1. **Finding Nearest E-Waste Facilities**:
   - **Description**: Users can input their location or enable geolocation services to find the nearest e-waste collection and recycling facilities.
   - **Steps**:
     1. User visits the website and provides their location or enables geolocation.
     2. The website displays a map interface with nearby e-waste facilities marked.
     3. User selects a facility and views detailed information such as address, operating hours, and accepted items.

2. **Educational Resources on E-Waste**:
   - **Description**: Users can access educational content to learn about the harmful effects of e-waste on the environment and human health.
   - **Steps**:
     1. User navigates to the educational section of the website.
     2. They explore articles, infographics, videos, or interactive modules explaining the impact of e-waste and the importance of responsible disposal.
     3. Users gain awareness of proper e-waste disposal practices and their role in mitigating environmental damage.

3. **Device Recycling and Rewards**:
   - **Description**: Users can input the model of their old electronic devices and earn credit points for recycling them at designated facilities.
   - **Steps**:
     1. User logs in to their account or creates a new one.
     2. They navigate to the device recycling section and input the model of their old device.
     3. The website calculates the estimated amount of precious metals and materials that can be recovered from the device.
     4. Users receive credit points or rewards based on the value of the materials, which they can redeem for discounts or donations.

4. **Tracking Recycling Activity**:
   - **Description**: Users can track their recycling activity and view their contribution to environmental conservation.
   - **Steps**:
     1. User logs in to their account.
     2. They navigate to their profile or recycling dashboard.
     3. The website displays a history of their recycling activity, including items recycled, points earned, and environmental impact.
     4. Users can set recycling goals, track their progress, and share achievements with friends or social networks.

5. **Community Engagement and Events**:
   - **Description**: Users can participate in community events, workshops, or campaigns related to e-waste recycling and environmental conservation.
   - **Steps**:
     1. User browses the events section of the website.
     2. They discover upcoming events such as recycling drives, educational workshops, or environmental clean-up initiatives.
     3. Users can RSVP for events, join discussions, or volunteer to participate.
     4. The website fosters community engagement and encourages users to take collective action towards sustainability.
 ![image](https://github.com/Vigneshv-23/SIHPS/assets/110780412/bddd71b6-43c3-4cc8-814b-1abe873b1db1)

## Technology Stack

1. **Frontend**:
   - **HTML, CSS, JavaScript**: For building the user interface and handling client-side interactions.
   - **React.js or Vue.js**: JavaScript libraries for building interactive user interfaces. They offer reusable components and efficient state management.
   - **Bootstrap or Material-UI**: UI frameworks that provide pre-designed components and styles for faster development and responsive design.

2. **Backend**:
   - **Node.js**: A runtime environment for executing JavaScript code on the server-side.
   - **Express.js**: A minimalist web application framework for Node.js, used for building the backend API and handling HTTP requests.
   - **MongoDB or PostgreSQL**: NoSQL or SQL databases for storing data such as user accounts, e-waste facilities, and recycling activity.
   - **Mongoose (for MongoDB)** or **Sequelize (for PostgreSQL)**: Object Data Modeling (ODM) or Object-Relational Mapping (ORM) libraries for interacting with the database.

3. **APIs and External Services**:
   - **Google Maps API**: For integrating maps and location-based services to help users find nearby e-waste facilities.
   - **Geolocation API**: For determining the user's location automatically.
   - **Precious Metals API**: If available, an API that estimates the value of precious metals recovered from recycled devices based on their models.

4. **Authentication and Authorization**:
   - **JWT (JSON Web Tokens)**: For secure authentication and authorization of users.
   - **Passport.js**: A popular authentication middleware for Node.js that supports various authentication strategies like username/password, social logins, etc.

5. **Deployment and Hosting**:
   - **AWS (Amazon Web Services)** or **Heroku**: Cloud platforms for deploying and hosting the application.
   - **Docker and Kubernetes**: Containerization and orchestration tools for managing deployment environments and scaling the application.

6. **Development Tools**:
   - **Visual Studio Code** or **Atom**: Code editors with extensions for JavaScript and web development.
   - **Postman**: For testing API endpoints during development.
   - **Git and GitHub**: Version control system and hosting platform for collaborating on code with a team.

7. **Testing and Quality Assurance**:
   - **Jest or Mocha**: Testing frameworks for writing and running unit tests and integration tests.
   - **Supertest**: A library for testing HTTP assertions in Node.js.
   - **ESLint and Prettier**: Tools for code linting and formatting to maintain code quality and consistency.

## Dependencies

1. **Frontend Dependencies**:
   - React.js or Vue.js: These libraries have their own set of dependencies for managing state, routing, and other functionalities. Some common ones include:
     - React Router or Vue Router for client-side routing.
     - Redux or Vuex for state management.
     - Axios for making HTTP requests to the backend API.

2. **Backend Dependencies**:
   - Node.js: Node Package Manager (NPM) is used to manage backend dependencies. Some common dependencies might include:
     - Express.js: The web application framework itself.
     - Mongoose or Sequelize: ORM/ODM for interacting with the database.
     - Passport.js: Authentication middleware.
     - Body-parser: Middleware for parsing incoming request bodies.
     - Dotenv: For managing environment variables.
     - Helmet: Middleware for securing Express apps by setting various HTTP headers.
     - Morgan: HTTP request logger middleware.

3. **Database Dependencies**:
   - MongoDB or PostgreSQL: Each database has its own Node.js driver or ORM, so you'd install dependencies accordingly:
     - For MongoDB: `mongoose` is the most common choice.
     - For PostgreSQL: `sequelize` is a popular ORM.

4. **API and External Service Dependencies**:
   - Google Maps API and Geolocation API: These might not have specific dependencies but will require API keys and possibly SDKs for integration.
   - Precious Metals API: If available, you'll need to install any SDKs or libraries provided by the API provider.

5. **Authentication Dependencies**:
   - JWT: Libraries for creating and verifying JSON Web Tokens, such as `jsonwebtoken`.
   - Passport.js: Strategies for various authentication methods, like `passport-local` for username/password authentication or `passport-google-oauth` for Google OAuth.

6. **Testing and Development Dependencies**:
   - Jest, Mocha, or another testing framework.
   - Supertest for testing HTTP endpoints.
   - ESLint and Prettier for linting and code formatting.

7. **Deployment Dependencies**:
   - AWS or Heroku.



