# CodeEngine - A Search Engine Based on DSA Problems

[Visit](http://codeengine.ap-southeast-2.elasticbeanstalk.com/)

## Description

CodeEngine is a Search Engine where users can search for a DSA Problem. Even if a User makes a mistake while typing he/she can fetch appropriate top 6 results matching his/her request.

## Features

- Developed a high-performance search engine using the MERN stack, incorporating modern web technologies to deliver a seamless user experience.
- Scraped and processed a diverse dataset of 3,500 problems from leading coding platforms (LeetCode, InterviewBit, Codeforces) using Selenium, ensuring a comprehensive collection of programming challenges.
- Implemented robust edge case handling techniques, including converting numbers to words and vice versa, lemmatization, spell-checking, and camel case-to-word conversion, to generate relevant keywords from user query strings.
- Utilized the BM25 algorithm and TF-IDF indexes to rank documents efficiently against query strings, and optimized search speed by leveraging RAM-based indexes and
efficient data structures to enhance search performance.
- Incorporated custom scoring metrics, including title matching and source reliability, to further enhance search relevance and user experience, ensuring accurate
  and trustworthy results appear prominently.

## Technology Stack

- Node.js
- EJS Template Engine (For Frontend)
- Selenium

## Setup

1. Clone the repository from GitHub.
2. Run `npm install` to install all the dependencies.
3. Run `npm run dev` to start the server.
4. Vist `http://localhost:3000/` on your browser.


## Authors

- [Shruti Koshta](https://www.linkedin.com/in/shruti-koshta-951b2720b/)
