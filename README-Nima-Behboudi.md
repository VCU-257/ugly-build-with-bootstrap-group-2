# Student Name: Nima Behboudi

## 1. My Assigned Work
*I was tasked for implementing Home Page of the credit score application.*
- Main landing layout
- Top navigation bar (desktop)
- Bottom navigation bar (mobile)
- Main action buttons: Finance, Accounts, Cards, Loans
- Credit score display section


## 2. Bootstrap Implementation
* **Components Used:**
1. Bootstrap Navbar (for top navigation and mobile bottom navigation)
2. Bootstrap Grid System (for container, row, col)
3. Bootstrap Buttons
4. Bootstrap Cards
5. Bootstrap Utility Classes (for spacing, responsiveness)
* **Note:** I used only Bootstrap 5 components with no custom CSS.

## 3. Technical Challenges & Solutions

- *Creating a **mobile bottom navigation bar** was one of my challenges, since Bootstrap doesn't include a native tab bar component.*
*I reused Bootstrap `navbar`, Added `fixed-bottom` to position it at the bottom and used `d-lg-none` to show it only on mobile, in order to solve it.*
- *My other challenge was displaying a **credit score dial**, which isn't on Bootstrap.*
*So I used a Bootstrap card and used `display-2` class to simulate a large score display to fix this.*

## 4. AI / LLM Usage

* **What I asked the AI:** 
*How to build a bottom navigation bar using only Bootstrap classes?*
*How to improve spacing and layout for the main action buttons?* 
*How can I build a Bootstrap 5 home page using navbar?*
* **How it helped & What I learned:** *Chatgpt helped by suggesting correct Bootstrap class usage. I made sure to review navbar, container, row and col and their affect layout and responsiveness! This helped me better understand the way Bootstrap components work together and to use them for both mobile and desktop views.*

## 5. Live Site Link

* **Live URL:** [https://vcu-257.github.io/ugly-build-with-bootstrap-group-2/]