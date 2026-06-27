# 🌍 WanderLust - Full Stack Airbnb Clone

WanderLust ek modern, fully-responsive full-stack web application hai jo users ko alag-alag categories (jaise Rooms, Mountains, Castles, Amazing Pools, etc.) ke hisab se hotels aur homes explore, create, aur rent karne ki suvidha deta hai. 

Aap isme listings dekh sakte hain, apni khud ki property rent par chadha sakte hain, aur listings par ratings ke sath reviews chhod sakte hain.

---

## 🚀 Live Demo
🔗 **Project Link:** https://major-project-1-1zr2.onrender.com/listings

---

## ✨ Features

- **User Authentication:** Sign Up, Log In, aur Log Out functionalities (Session management ke sath).
- **CRUD Operations on Listings:** Authenticated users nayi listings create kar sakte hain, unhe edit kar sakte hain, aur delete kar sakte hain.
- **Dynamic Category Filters:** Airbnb ki tarah top horizontal-scrollable filter choices (Trending, Rooms, Arctic, Farms, etc.).
- **Interactive Tax Toggle Switch:** Real-time +18% GST display calculation badalne ke liye mobile-responsive interactive switch toggle.
- **Review System:** Users star ratings (using Starability CSS) aur text comments ke sath property reviews de ya delete kar sakte hain.
- **Secure File Uploads:** Storage optimization ke liye Cloudinary integration se direct images upload options.
- **Flash Messages:** User actions par instant dynamic response alerts (Success & Danger popups).
- **100% Mobile Responsive Layout:** Modern UI framework breaks jo Mobile, Tablet, Laptop, aur Desktop par seamless experience deta hai.

---

## 🛠️ Tech Stack

**Frontend:**
- HTML5 & Embedded JavaScript Templates (EJS)
- CSS3 (Custom Glassmorphism elements & layouts)
- Bootstrap 5 (Responsive components & grid utility layouts)
- FontAwesome (Premium UI vector icons vectors)

**Backend:**
- Node.js (Runtime environment)
- Express.js (Web application framework)
- Passport.js (Authentication strategy management)

**Database & Cloud Storage:**
- MongoDB Atlas (NoSQL cloud database storage)
- Mongoose (Object Data Modeling node dependency)
- Cloudinary (Cloud-based image storage management)

---

## 📂 Project Structure

```text
WanderLust/
├── controllers/       # MVC architecture controllers log
├── models/            # Mongoose Schemas (Listing, Review, User)
├── routes/            # Express endpoints routing logic
├── public/            # Static assets (Custom CSS & Client JS)
├── views/             # EJS Template files frontend
│   ├── includes/      # Reusable boilerplate templates (Navbar, Footer, Flash alerts)
│   ├── layouts/       # Main skeleton template layouts
│   └── listings/      # Core listing interface components (Index, Show, Edit, New)
├── utils/             # Error handling utilities wrappers
├── app.js             # Server initialization file points
└── package.json       # Project dependencies specifications
```

---

## 🔧 Installation & Local Setup

Apne computer par is project ko run karne ke liye in simple steps ko follow karein:

### 1. Clone the repository
```bash
git clone https://github.com
cd WanderLust
```

### 2. Install Dependencies
```bash
npm install
```

### 3. Setup Environment Variables
Project ke root directory me ek `.env` file banayein aur usme apne credentials dalein:
```env
CLOUD_NAME=your_cloudinary_name
CLOUD_API_KEY=your_cloudinary_api_key
CLOUD_API_SECRET=your_cloudinary_api_secret
ATLASDB_URL=your_mongodb_atlas_connection_string
SECRET=your_session_encryption_secret_key
```

### 4. Run the Project
```bash
node app.js
# or if you have nodemon installed:
nodemon app.js
```
Ab apna browser kholein aur URL me type karein: `http://localhost:8080`

---

## 🛡️ Validation & Security
- **Joi Validation Schema:** API pipelines break hone se bachane ke liye backend levels par model object schema validation checks handle kiye gaye hain.
- **Restricted Access Authorization:** Sirf property ka original owner hi listing ko Modify ya Delete kar sakta hai, aur reviews ko delete karne ka access bhi uske author ke pas hi reserved hai.

---

## 🤝 Contributing
Agar aap isme kuch naye features add karna chahte hain (jaise Mapbox integration ya payment gateways):
1. Is repo ko **Fork** karein.
2. Ek naya feature branch banayein (`git checkout -b feature/NewFeature`).
3. Apne changes ko **Commit** karein (`git commit -m 'Add NewFeature'`).
4. Branch ko **Push** karein (`git push origin feature/NewFeature`).
5. Ek **Pull Request** open karein.

Developed with ❤️ by Pari Rastogi.
