
---

# 🔷 PSR-FIG

**PSR-FIG** stands for **PHP Standards Recommendations – Framework Interoperability Group**.

---

## 🔷 What is PSR-FIG?

PHP-FIG is a group of PHP developers and framework authors who work together to define **common coding standards**.

These standards are called **PSRs (PHP Standards Recommendations)**.

> 🎯 The main goal:  
> Make different PHP frameworks and libraries work together smoothly.

---

## 🔷 Why PSR-FIG exists?

### ❌ Before PSR-FIG:

- Every framework had its own coding style
    
- Switching between frameworks was hard
    
- Code reuse between projects was messy
    

### ✅ After PSR-FIG:

- Unified coding standards
    
- Better interoperability between frameworks like Laravel, Symfony, etc.
    
- Cleaner and more maintainable code
    

---

## 🔷 What are PSRs?

PSRs are rules or guidelines for writing PHP code.

---

### 🧩 1. PSR-1 (Basic Coding Standard)

- PHP tags must be `<?php`
    
- Class names in PascalCase
    
- Method names in camelCase
    

---

### 🧩 2. PSR-4 (Autoloading Standard) ⭐

Defines how PHP classes are loaded automatically.

Example:

```text
App\Controllers\UserController
```

maps to:

```text
/app/Controllers/UserController.php
```

👉 This is heavily used in Laravel and Composer.

---

### 🧩 3. PSR-7 (HTTP Message Interface)

Defines how HTTP requests and responses should be structured.

Used in:

- APIs
    
- Middleware systems
    

---

### 🧩 4. PSR-12 (Extended Coding Style Guide)

Modern coding style rules:

- Indentation
    
- Braces placement
    
- Line length
    
- Code structure
    

---

### 🧩 5. PSR-3 (Logger Interface)

Standard way to handle logging in PHP applications.

---

## 🔷 Why PSR-FIG matters for you (Laravel developer)

✔ Laravel follows PSR standards  
✔ Composer depends heavily on PSR-4  
✔ Most modern PHP packages follow PSR-7 / PSR-12

> 💡 Understanding PSR = better Laravel understanding + cleaner architecture thinking

---

## 🔷 Simple way to understand it

Think of PSR-FIG like:

> 🚦 “Traffic rules for PHP developers”

- Without rules → chaos ❌
    
- With rules → organized and compatible systems ✅
    

---

## 🔷 Summary

- PSR-FIG = group that defines PHP standards
    
- PSRs = rules for writing clean PHP code
    
- Important ones: PSR-1, PSR-4, PSR-7, PSR-12
    
- Widely used in Laravel and modern PHP development
    
