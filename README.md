<br/>
<p align="center">
  <a href="https://github.com/MeerUzairWasHere/Jobify">
        <img src="https://github.com/MeerUzairWasHere/Jobify/blob/main/client/src/assets/images/logo.svg" alt="Logo" width="80" height="80">
    

  </a>


  <h3 align="center">"jobify-v2" - Your ultimate job application tracker.</h3>

  <p align="center">
    jobify-v2: Elevate Your Career, Simplify Your Search!
    <br/>
    <br/>
    <a href="https://github.com/MeerUzairWasHere/jobify-v2"><strong>Explore the docs »</strong></a>
    <br/>
    <br/>
    <a href="https://github.com/MeerUzairWasHere/jobify-v2">View Demo</a>
    .
    <a href="https://github.com/MeerUzairWasHere/jobify-v2/issues">Report Bug</a>
    .
    <a href="https://github.com/MeerUzairWasHere/jobify-v2/issues">Request Feature</a>
  </p>
</p>

![Downloads](https://img.shields.io/github/downloads/MeerUzairWasHere/jobify-v2/total) ![Contributors](https://img.shields.io/github/contributors/MeerUzairWasHere/jobify-v2?color=dark-green) ![Forks](https://img.shields.io/github/forks/MeerUzairWasHere/jobify-v2?style=social) ![Stargazers](https://img.shields.io/github/stars/MeerUzairWasHere/jobify-v2?style=social) ![Issues](https://img.shields.io/github/issues/MeerUzairWasHere/jobify-v2) ![License](https://img.shields.io/github/license/MeerUzairWasHere/jobify-v2) 

## Table Of Contents

* [About the Project](#about-the-project)
* [Built With](#built-with)
* [Getting Started](#getting-started)
  * [Prerequisites](#prerequisites)
  * [Installation](#installation)
* [Usage](#usage)
* [Roadmap](#roadmap)
* [Contributing](#contributing)
* [License](#license)
* [Authors](#authors)

## About The Project


**Introducing jobify-v2: Your Premier Job Application Management Solution**

In the fast-paced world of job hunting, staying organized and efficient is key to securing your dream career. Enter jobify-v2, the cutting-edge job application tracker designed to revolutionize your job search experience effortlessly.

**Effortless Application Tracking:**
jobify-v2 takes the hassle out of job application management. Effortlessly keep tabs on every application you submit, from the initial submission to the final decision. With a sleek and intuitive interface, tracking your progress has never been more seamless.

**Seamless Status Management:**
Say goodbye to the chaos of scattered application statuses. jobify-v2 allows you to seamlessly manage the status of each application, providing clear insights into your job search journey. Receive timely reminders for follow-ups, interviews, and important deadlines, ensuring you never miss a beat.

**User-Friendly Interface:**
Navigating your job search has never been more user-friendly. jobify-v2 boasts an intuitive interface that simplifies the entire process. Easily access key information, update application statuses, and organize your job hunt with just a few clicks. Your job search, your way.

**Advanced Features, Powered by MERN Stack:**
jobify-v2 leverages cutting-edge MERN (MongoDB, Express.js, React.js, Node.js) Stack technologies to deliver advanced features that elevate your job search experience. Benefit from a robust and secure platform that combines the best in database management, server-side scripting, and front-end development for a seamless user experience.

**Tailor-Made for Your Success:**
jobify-v2 is not just a job application tracker; it's a personalized tool crafted to enhance your chances of success in the competitive job market. Customize job profiles, access analytics to refine your strategy, and leverage the power of a platform designed to align with your unique career goals.

In a world where every opportunity matters, jobify-v2 is your partner in success. Stay organized, stay informed, and stay ahead with jobify-v2 – because your dream job deserves a tool as dynamic as your aspirations. Elevate your job search game; embrace jobify-v2 today.

## Built With

Certainly! Integrating Clerk Auth, React Query, Shadcn-UI, Recharts, Prisma, and PostgreSQL into jobify-v2 enhances the application with efficient data management and a sleek, styled UI. Here's an updated list of technologies used in jobify-v2:

1. **PostgreSQL (P):**
   - A powerful relational database management system known for its reliability and robustness. PostgreSQL efficiently stores and manages data related to job applications, profiles, and user information in jobify-v2.

2. **Prisma (P):**
   - An ORM (Object-Relational Mapping) tool that simplifies database access and manipulation. Prisma provides a type-safe and auto-generated query builder that streamlines database operations within jobify-v2.

3. **Express.js (E):**
   - A web application framework for Node.js that simplifies the process of building scalable and robust server-side applications. Express.js is the backbone of jobify-v2's server architecture, handling routes and business logic.

4. **React.js (R):**
   - A powerful JavaScript library for building user interfaces. React.js is used to create the dynamic and responsive front-end of jobify-v2, ensuring a smooth and engaging user experience for job seekers.

5. **React Router:**
   - A library for adding navigation and routing functionality to React applications. React Router is integrated into jobify-v2 to enable seamless navigation between different views, such as the dashboard, application profiles, and analytics.

6. **React Query (R):**
   - A library for managing and caching asynchronous data fetching in React applications. React Query optimizes data fetching and state management, providing a more efficient way to handle data throughout jobify-v2.

7. **Shadcn-UI (S):**
   - A UI component library that provides pre-designed and customizable UI elements. Shadcn-UI enhances the aesthetics and usability of jobify-v2 by offering a sleek and modern design for its user interface.

8. **Recharts (R):**
   - A charting library for React applications. Recharts is utilized in jobify-v2 to visualize data and analytics, providing users with insightful representations of job application trends and statistics.

9. **Clerk Auth (C):**
   - An authentication and user management solution designed to simplify user authentication workflows. Clerk Auth secures jobify-v2 by providing robust authentication mechanisms and user management features.

These technologies collectively contribute to making jobify-v2 a powerful and modern job application tracking solution. With efficient data management, a visually appealing UI, and secure authentication mechanisms, jobify-v2 offers a seamless experience for both job seekers and recruiters alike.

## Getting Started

Certainly! Here's an example guide on how to set up the jobify-v2 project locally:

### Setting Up jobify-v2 Locally

Follow these simple steps to get a local copy of jobify-v2 up and running on your machine:

#### Prerequisites:

Before you begin, make sure you have the following installed on your system:

- Node.js
- npm (Node Package Manager)
- MongoDB

#### Step 1: Clone the Repository

```bash
git clone https://github.com/your-username/jobify.git
```

Replace `your-username` with your GitHub username.

#### Step 2: Navigate to the Project Directory

```bash
cd jobify-v2
```

#### Step 3: Install Dependencies

```bash
npm install
```

#### Step 4: Set Up MongoDB

Make sure MongoDB is running on your machine. You may need to start the MongoDB server using:

```bash
mongod
```

#### Step 5: Set Up Environment Variables

Create a `.env` file in the root of the project and configure the following variables:

```env
# MongoDB connection URI
MONGODB_URI=your_mongodb_uri

# Other environment variables if applicable
```

Replace `your_mongodb_uri` with the URI for your MongoDB database.

#### Step 6: Run the Application

```bash
npm start
```

This command will start both the server and the React application. The application should be accessible at `http://localhost:3000/`.

#### Step 7: Access jobify-v2

Open your web browser and navigate to [http://localhost:3000/](http://localhost:3000/) to access the jobify-v2 application locally.

### Congratulations!

You've successfully set up jobify-v2 locally. Feel free to explore the features and customize it according to your preferences. If you encounter any issues, refer to the project's documentation or seek help from the community. Happy job tracking!

## Roadmap

See the [open issues](https://github.com/MeerUzairWasHere/jobify-v2/issues) for a list of proposed features (and known issues).

## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.
* If you have suggestions for adding or removing projects, feel free to [open an issue](https://github.com/MeerUzairWasHere/jobify-v2/issues/new) to discuss it, or directly create a pull request after you edit the *README.md* file with necessary changes.
* Please make sure you check your spelling and grammar.
* Create individual PR for each suggestion.
* Please also read through the [Code Of Conduct](https://github.com/MeerUzairWasHere/jobify-v2/blob/main/CODE_OF_CONDUCT.md) before posting your first idea as well.

### Creating A Pull Request

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

Distributed under the MIT License. See [LICENSE](https://github.com/MeerUzairWasHere/jobify-v2/blob/main/LICENSE.md) for more information.

## Authors

* **Mir Uzair** - *Crafting immersive user experiences through clean and elegant code* - [Mir Uzair](https://github.com/MeerUzairWasHere)


