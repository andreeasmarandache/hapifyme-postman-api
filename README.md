# HapifyMe Postman API Project 📨

A **Postman API automation project** demonstrating automated API testing for the HapifyMe application using Postman collections and environments.

---

## 🌟 Overview

This project is part of my portfolio and showcases my skills in:

- Creating **Postman collections** and **environments**  
- Automating **user lifecycle API tests**  
- Using **Pre-request Scripts** and **Tests scripts** to generate dynamic data and extract values  
- Managing environment variables for **dynamic and reusable API requests**  
- Testing core API operations: registration, login, profile retrieval, and deletion  

---

## 🧪 What the project covers

1. **Registration**  
   - POST request to `/user/register.php`  
   - Unique emails generated dynamically using JavaScript timestamp in Pre-request Script  
   - Extracts `api_key` from the response to use in subsequent requests  

2. **Login**  
   - POST request to `/user/login.php` using the dynamically generated email  
   - Verifies successful login and extracts JWT token and user ID  

3. **Profile Retrieval**  
   - GET request to `/user/get_profile.php` using `api_key`  
   - Ensures the returned email matches the one used during registration  

4. **Cleanup / Deletion**  
   - DELETE request to `/user/delete_profile.php` using Bearer token  
   - Verifies successful deletion (status 200)  

---

## 💡 Highlights

- Demonstrates **API automation workflow** entirely within Postman  
- Uses **environment variables** for dynamic and reusable requests  
- Includes Pre-request scripts and test scripts for **realistic E2E API testing**  
- Collection and environment exported as `.json` files for reproducibility  
- Perfect example of **API testing skills** for portfolio presentation  

---

This project is a concrete example from my portfolio, showing **how I structure and automate API tests using Postman**, covering dynamic data, environment management, and full user lifecycle testing. 🎯
