# Blogify

## Overview

**Blogify** is a robust backend system for a blogging application, developed using Express, MongoDB, and Mongoose. This project provides a powerful API to manage blog content and user interactions, focusing on security and performance.

## Features

- **User Authentication**: Secure login via GitHub using Passport.js, with session management for an enhanced user experience.
- **Content Management**: Supports Markdown content with image uploads, enabling rich blog posts.
- **Structured Architecture**: Implemented a well-organized structure separating concerns across regex, models, routes, controllers, services, utils, and middlewares.
- **Cursor-Based Pagination**: Improved data retrieval with cursor-based pagination for better consistency and performance.
- **Comment System**: Stores individual comments as separate documents with references for scalability, including a nested reply feature for engaging discussions.
- **Custom Error Handling**: Comprehensive error management to ensure a seamless user experience.
- **Tagging System**: Allows users to index blogs according to their interests for improved discoverability.
