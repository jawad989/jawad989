# Hi, I'm Jawad!

### Full Stack Web Developer | MERN & Electron

I'm a passionate web developer specializing in **full stack development** with the **MERN stack** (MongoDB, Express, React, Node.js). My main programming language is **JavaScript**, and I love building robust, dynamic applications—both for the web and desktop using **Electron**.

---

## 🛠️ Tech Stack

- **Languages:** JavaScript (main), TypeScript (learning)
- **Frameworks:** MERN (MongoDB | Express | React | Node.js), Electron
- **Libraries:** Framer Motion, Redux, Axios
- **Tools:** Git & GitHub, VS Code, REST APIs

---

## 📚 Featured Projects

### 1. [Almukhtara Group (Frontend Static Site)](https://almokhtaragroup.com/)
A visually engaging static website built with React and **Framer Motion** for subtle, smooth animations and transitions.  
*Role: Developed the frontend; focused on aesthetic and interactive user experience.*

**Performance Optimization:**  
Implemented asset preloading directly in the HTML, allowing React to use direct paths for hero section images. This guarantees smooth initial UI rendering and prevents flicker or sluggish loading of visuals after site load.

---

### 2. [High Tribe – Chef Meal Booking & Services Platform (Admin Dashboard)](https://admin.hightribe.cloud/)
A dynamic platform where users can book chef-prepared meals based on live availability and access additional services like **Tours** and **Events**.

**Backend & Admin Dashboard Highlights:**
- Architected and implemented the backend and dashboard for managing chef availability, reservations, and service bookings.
- Solved race conditions in the reservation system for reliable bookings.
- Built robust payment handling: addressed edge cases where Stripe payment succeeds but API reservation fails.
- Designed and implemented a flexible discount module:
  - **Default Discount:** Automatically applied
  - **Code Discount:** User-entered codes for percentage-based discounts

---

### 3. **TDCP – Electronic Ticketing System (Electron App)**
A cross-platform desktop app deployed locally at tourist spots, built with **Electron**, **Vite + React**, and **Node.js**:

- **Backend Services Architecture:**
  1. **E-Ticketing App Backend:** Built with Node.js + SQLite; manages reservations and ticket assignments.
  2. **Queue Management System (QMS):** Assigns queue numbers to bookings from the e-ticketing app.
  3. **Central Cloud Service:** Hosted on cPanel with Node.js + SQL; serves as the source of truth and synchronizes data between local apps.

- **Technical Challenges & Solutions:**
  - Handled **data syncing issues** between local SQLite databases and the cloud SQL database.
  - Resolved database errors and foreign key conflicts by dropping FK constraints on the cloud DB and enforcing **business rules at the application/service layer**.
  - Implemented a **Role-Based Access System** allowing the admin to create, read, update, and delete permissions for different roles, ensuring secure and flexible access management.
  - Ensured **seamless synchronization** between offline desktop apps and the central cloud.

*Role: Led the development and management of all three services, ensuring smooth operation across local and cloud systems.*

---

## ⚡ About Me

- 🧑‍💻 Always eager to learn new technologies and frameworks
- 🏗️ Love architecting scalable, maintainable systems
- 👨‍💼 Focused on delivering impactful solutions for real-world problems

---

> *"Code is like humor. When you have to explain it, it’s bad."* – Cory House

---

### 📬 Let's Connect!

Feel free to reach out for collaboration, coding chats, or just to say hi!
