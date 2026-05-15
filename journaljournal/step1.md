# Step 1 – System Planning

## 1. System Description and Goal

The planned system is an AI-based study assistant developed in Python. The goal is to help users answer study-related questions using tools and reasoning.

The system accepts user input and generates structured responses based on the request.

---

## 2. AI / Agent-Based Approach

The system will use a single intelligent agent.

The agent will analyze the user input and decide what action is needed:
- perform calculations
- retrieve information
- process text

Based on this decision, it will call the appropriate tool.

---

## 3. Tools to be Used

# Step 3 – Testing, Deployment, and Data Handling

## Testing Process
Testing was performed during development to ensure all components work correctly. 
Both individual modules and the full system were tested.

Methods used:
- Manual testing
- Functional testing
- Tool testing
- Error handling testing

---

## Test Scenarios

### 1. Normal Input
Input: Valid user request  
Expected: Correct output using tools  

### 2. Tool Testing
Input: Direct tool usage  
Expected: Accurate results  

### 3. Invalid Input
Input: Incorrect user input  
Expected: Error message, no crash  

### 4. Edge Cases
Input: Empty or extreme values  
Expected: Safe handling  

### 5. Workflow Test
Input: Full task  
Expected: Correct multi-step execution  

---

## Deployment Preparation

Steps to run:

1. Install dependencies:
pip install -r requirements.txt

2. Run program:
python main.py

Project includes:
- Source code
- Tools
- Tests
- README

---

## Data Conversion

System flow:
User input → parsed → agent → tool → formatted output

Examples:
- String → structured command
- Tool result → readable output

---

## Deployment Strategy

Current: Local CLI application

Future:
- Web app (Flask/FastAPI)
- API service

Strategy:
- Local testing → controlled release → deployment

- Calculator tool (for math operations)  
- Search tool (for information retrieval)  
- File reader (optional for later extension)  

---

## 4. Programming Concepts

- Functions  
- Object-Oriented Programming (OOP)  
- Conditional statements (if/else)  
- Error handling  
- Modular design  
