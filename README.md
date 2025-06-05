# Activity Suggester

A simple Express.js application that fetches random or filtered “boredom-busting” activities from the Bored API and renders them via EJS templates. Users can either get a completely random suggestion or specify filters (activity type and participant count) to receive a tailored suggestion.

## Table of Contents

1. [Features](#features)  
2. [Prerequisites](#prerequisites)  
3. [Installation](#installation)  
4. [Environment Variables](#environment-variables)  
5. [Usage](#usage)  
6. [Project Structure](#project-structure)  
7. [Dependencies](#dependencies)  
8. [Error Handling](#error-handling)  
9. [Contributing](#contributing)  
10. [License](#license)  

---

## Features

- Fetch a **completely random** activity suggestion on page load.  
- Filter by **activity type** (e.g., “education,” “recreational,” “social”) and **number of participants** on form submission.  
- Displays results in a clean, EJS-rendered template.  
- Graceful error handling when no activities match the criteria or if the API request fails.

---

## Prerequisites

- **Node.js** (v14 or higher)  
- **npm** (v6 or higher)  
