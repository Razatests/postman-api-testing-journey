# Postman API Testing – My QA Learning Journey

This repo documents my progress learning API testing using Postman as part of my QA career development.

---

## 🔧 What I Have Learned So Far

### ✅ Basic Postman Usage
- Installed and set up Postman
- Sent GET and POST requests
- Used headers and parameters
- Created and saved collections
- Wrote basic test scripts:
  ```js
  pm.test("Status code is 200", function () {
      pm.response.to.have.status(200);
  });
