# tms-foundation-architecture-assignment

# 🧠 TMS Foundation – Strategic & Technical Assignment

**Name:** Atharva Chaudhari  
**Role:** Full Stack Developer  
**Tech Stack:** React, Django, REST APIs, Node.js  
**Submission Type:** GitHub Repository  

---

## 📌 Task 1: Strategic Analysis & Audit

### (a) Benefits of Decoupled Architecture  
**React Frontend + Django REST Backend**

A decoupled architecture separates the user interface from backend logic, enabling independent development, deployment, and scaling. For a non-profit organization like TMS Foundation, this approach offers long-term sustainability with lower operational risk.

React provides a fast, responsive, and accessible user experience, improving engagement for donors, volunteers, and beneficiaries. Django REST Framework ensures secure, reliable API services with strong authentication, permissions, and data validation.

This architecture also allows future expansion such as mobile applications, third-party integrations, or analytics tools without rewriting the core system. Compared to monolithic or CMS-based solutions, a decoupled setup is more flexible, maintainable, and future-ready.

---

### (b) UI/UX Audit – Key Issues Identified (dev.bharatyuva.org)

1. **Weak Visual Hierarchy**  
   Primary actions like “Donate”, “Join”, or “Contact” are not visually emphasized, making navigation less intuitive.

2. **Inconsistent Spacing & Typography**  
   Uneven margins, font sizes, and alignment reduce readability and overall polish, especially across different sections.

3. **Mobile Responsiveness Gaps**  
   Certain layouts do not adapt well to smaller screens, impacting accessibility for mobile and low-bandwidth users.

---

### (d) Redesign Vision – Modern React Feature

**Interactive Admin & Impact Dashboard**

A React-based dashboard can provide real-time insights such as:
- Donation and funding analytics  
- Volunteer engagement metrics  
- Program performance tracking  

This improves transparency, decision-making, and operational efficiency across the foundation.

---

## 📌 Task 2: Technical Proficiency

### (a) Handling CORS in Django + React

CORS issues arise when the frontend and backend operate on different domains or ports.

**Recommended Approach:**
- Use `django-cors-headers`
- Whitelist trusted frontend origins only
- Configure environment-based CORS settings

**Best Practices:**
- Avoid allowing all origins in production
- Restrict HTTP methods and headers
- Enable secure cookies and tokens

This ensures secure and seamless communication between React and Django services.

---

### (c) Handling Migration Conflicts in Django

Migration conflicts commonly occur when multiple developers modify database models simultaneously.

**Resolution Steps:**
1. Pull the latest code from the repository  
2. Run `python manage.py makemigrations`  
3. Inspect conflicting migration files  
4. Merge compatible changes carefully  
5. Apply migrations using `python manage.py migrate`

**Best Practices:**
- Coordinate schema changes within the team  
- Keep migrations small and isolated  
- Review migrations before merging branches  

This approach ensures database consistency and smooth deployments.

---

## 🚀 Why This Architecture Suits TMS Foundation

- Scales efficiently with growing users and data  
- Reduces maintenance overhead  
- Enables modern UI/UX experiences  
- Supports future integrations and mobile apps  

---

## 📎 Notes

- This submission focuses on strategy, architecture, and best practices  
- No proprietary or sensitive data has been used  

---

### ⭐ Conclusion

The proposed decoupled architecture and frontend improvements align with TMS Foundation’s mission by enabling scalability, transparency, and long-term digital sustainability.
