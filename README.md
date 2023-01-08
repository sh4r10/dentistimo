# T1-Project Documentation

# Purpose 
 - Team members Roles, and Tasks,  
 - Links to all relevant related team resources (Trello board, source-code repositories etc.) 

# Software Requirement Specification (SRS): 
 - focus on proper (SMART) phrasing of requirements 
 - requirements shall have unique ID’s 
 - team requirements logically 

# Software Architecture Document (SAD): 
 - include a clear description of the conceptual design  of  the  architecture; including architectural styles 
 - include a section that explains how the conceptual design is mapped onto implementation/technologies. 
 - Identify, state and justify any architecture design decisions or tactics used 

# Program Management Report (PMR): 
 - describe the project management practices used 
 - report on important project management decisions regarding schedule and scope. (weekly updates) 


## Architecture

### Functional Decomposition Model (FDM)

![functional-decomposition-model.drawio.png](./functional-decomposition-model.drawio.png)
*Figure X - The purpose of a functional decomposition model is to break down a system into its smaller components of functions. Our FDM can be read from left to right in a chronological order, from the point of when a user registers a new account to notification of a successful appointment booking.*

### Service-oriented Architecture (SOA)

![service-oriented-architecture.png](./service-oriented-architecture.png)
*Figure X - placeholder*

### Entity Relationship (ER) Diagram

![er-diagram-dentistimo.drawio.png](./er-diagram-dentistimo.drawio.png)
*Figure X - placeholder*

### Design decision tamplate

![Design_Template_2.png](./Design_Template_2.png)

### Sitemap

![Dentistimo_Sitemap.png](./Dentistimo_Sitemap.png)

## Visuals

Depending on what you are making, it can be a good idea to include screenshots or even a video (you'll frequently see GIFs rather than actual videos). Tools like ttygif can help, but check out Asciinema for a more sophisticated method.

## Installation instructions

### MongoDB and Studio 3T

#### 1. Check that you have mongo version ≥ 5, by running ’mongosh’ in your terminal. Install or update if you don't have mongo version 5 or above. Installtion instructions for various different OS's can be found here: https://www.mongodb.com/docs/manual/installation/.

![mongosh.png](./mongosh.png)

#### 2. Download and install Studio 3T from https://studio3t.com/download/. Studio 3T is a GUI that enables easier interaction between the user and the database.

![download-studio3t.png](./download-studio3t.png)

#### 3. Open Studio 3T and create a new connection if not already existing. This new connection is part of the setup where you declare through which URI your database and your backend service is communication through.

![fromURI.png](./fromURI.png)

#### 4. Create the new connection by importing your URI ('mongodb://localhost:27017' for example in this project) with Connection Manager.

![connectionURI.png](./connectionURI.png)

#### 5. Click ’save’ and then click ’connect’.

![connect-studio3t.png](./connect-studio3t.png)

#### 6. Test your mongoDB connection and configuration by running one of your services through MQTT. Below follows an example from one of our sevices that creates a user in the DB when the user signs up on our web page.

![test-mongoDB.png](./test-mongoDB.png)

## Usage

Use examples liberally, and show the expected output if you can. It's helpful to have inline the smallest example of usage that you can demonstrate, while providing links to more sophisticated examples if they are too long to reasonably include in the README.

## The Team

- Armin Balesic gusbalar@student.gu.se
- Victor Campanello
- Labiba Eshaba
- Conny Luong
- Umar Mahmood
- Shariq Shahbaz
- Alaa Taleb

## License

MIT License

Copyright (c) 2023 DENTISTIMO

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
