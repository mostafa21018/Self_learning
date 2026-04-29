
---

# 🔷 MVC Architecture

## What is the MVC Architecture ?

- Software Architecture pattern used to structure and organize application development (not only UI).
    
- It divides a given application into 3 interconnected parts.
    
- Standard for => Model View Controller design pattern.
    
- Main aim is to separate the business logic & application data from user interface.
    
- Advantages of it: Reusable, secure, scalable, and improves maintainability and performance of application.
    

---

## Parts of the Architecture:

### 🔷 Model :

- Handles database operations (update - delete - fetch - insert).
    
- Knows about data which need to be processed and returned.
    
- Represents application data, business rules, and sometimes validation logic.
    
- Not aware about how the data will be displayed.
    
- Returns data to the Controller after processing.
    

---

### 🔷 View :

- End-user GUI where the user interacts with the system.
    
- Represents the presentation layer of the application.
    
- View depends on data that is passed to it from the Controller.
    
- View remains independent from business logic changes.
    
- It can dealing with Model directly but:
    
    - Technically possible ✔
        
    - Architecturally wrong ❌
        
- In proper MVC, View should NOT directly access Model; it only receives data from Controller.
    

---

### 🔷 Controller :

- Contains application logic and acts as a bridge between View and Model.
    
- User requests always go to it first.
    
- Responsible for intercepting (اعتراض) requests from View and passing them to Model.
    
- After getting data from Model, it sends the appropriate View with data back to the user.
    
- View and Controller work very closely together.
    

---

## 🔷 Model & View Independence

When we say:

> **Model is independent from View**

### Meaning:

- ✔ Model works alone
    
- ✔ It does not care how data is displayed
    
- ✔ It has no direct relation with UI (View)
    

---

### Simply:

- Model = handles data only 🧠
    
- View = handles presentation only 🖥️
    
- Each one is independent from the other
    

---

### Example:

If you change the View (UI):

- ❌ Model is not affected
    

If you change Model logic or database:

- ❌ View is not directly affected
    

---

## 🔷 Meaning of Controller & View relationship

When we say:

> **View and Controller work very closely together**

### Meaning:

- Controller:
    
    - Receives user requests
        
    - Gets data from Model
        
    - Prepares data
        
- View:
    
    - Displays data to the user
        

👉 They work together to produce the final result shown to the user.

---

## 🔷 MVC Diagram

```text
            User
              |
              v
           View (UI)
              |
              v
         Controller
              |
              v
            Model
              |
              v
          Database
              |
              v
         Controller
              |
              v
           View (UI)
              |
              v
             User
```
