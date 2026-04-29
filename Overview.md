
---

# 🔷 What is the Laravel Framework?

- Laravel is:
    
    - An open-source PHP framework.
        
    - Follows the MVC (Model-View-Controller) design pattern.
        
    - Designed to build web applications with clean, maintainable code.
        
    - Inspired by other frameworks such as:
        
        - CodeIgniter
            
        - Yii
            
        - Ruby on Rails
            

---

# 🔷 Advantages of Laravel:

- Web applications become more scalable.
    
- Supports code reusability.
    
- Helps in organizing and managing projects using:
    
    - Namespaces
        
    - Interfaces
        
    - MVC structure
        
- Provides a large ecosystem and strong community support.
    

---

## 🔷 It uses:

### Composer

- A tool used to manage PHP libraries and dependencies.
    

### Artisan

- Command Line Interface (CLI) used in Laravel.
    
- Includes a set of helpful commands for building and managing projects.
    

> Note: Laravel is built using components from Symfony (not all features come directly from it).

---

# 🔷 Features of Laravel:

- **Modularity**
    
    - Provides many built-in libraries and modules.
        
    - Fully integrated with Composer.
        
- **Testability**
    
- **Routing**
    
- **Configuration Management**
    
- **Query Builder and ORM (Object Relational Mapper)**
    
- **Eloquent ORM**
    
    - Active Record implementation in Laravel.
        
- **Schema Builder**
    
- **Blade Template Engine**
    
- **E-mail**
    
    - Sending emails using Mail classes.
        
- **Authentication**
    
- **Redis**
    
    - Used for caching and session handling.
        
- **Queues**
    
    - Execute time-consuming tasks in the background.
        
    - Prevent blocking the application during heavy tasks.
        
- **Events and Command Bus**
    
    - Used to execute commands and dispatch events in a clean and structured way.
        

---

# 🔷 Command vs Event:

- **Command** = An action you want to perform (e.g., CreateUser).
    
- **Handler** = The logic that executes the command.
    

💡 Example:

Instead of:

```php
User::create($data);
```

Use:

```php
CreateUser::dispatch($data);
```

- **Command** = "Do something"
    
- **Event** = "Something has happened"
    

---

# 🔷 Additional Important Features:

- **Middleware**
    
    - Filters HTTP requests (authentication, authorization, etc.).
        
- **Migrations**
    
    - Version control for database structure.
        
- **Service Container**
    
    - Handles dependency injection automatically.
        
- **Service Providers**
    
    - Bootstraps and registers application services.
        
- **API Resources**
    
    - Transform data into structured API responses.
        
