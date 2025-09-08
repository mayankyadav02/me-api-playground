# ME API Playground

A full-stack project with separate **Frontend** and **Backend** repositories for testing and learning API integrations.

---

## Project Links

- **Frontend Repository:** [Frontend GitHub Repo](https://github.com/mayankyadav02/me-api-playground-frontend.git)
- **Backend Repository:** [Backend GitHub Repo](https://github.com/mayankyadav02/me-api-playground-backend.git)
- **Live Frontend:** [Vercel Link](https://me-api-playground-frontend-nxpqawizw-mayankyadav02s-projects.vercel.app)
- **Live Backend:** [Render Link](https://me-api-playground-backend-93ef.onrender.com)

---

## 1. Frontend Setup

```bash
# Navigate to frontend folder
cd frontend

# Install dependencies
npm install

# Start the development server
npm run dev
```

VITE_API_URL=https://me-api-playground-backend-93ef.onrender.com


## Backend Setup

<pre class="overflow-visible!" data-start="1221" data-end="1340"><div class="contain-inline-size rounded-2xl relative bg-token-sidebar-surface-primary"><div class="sticky top-9"><div class="absolute end-0 bottom-0 flex h-9 items-center pe-2"><div class="bg-token-bg-elevated-secondary text-token-text-secondary flex items-center gap-4 rounded-sm px-2 font-sans text-xs"></div></div></div><div class="overflow-y-auto p-4" dir="ltr"><code class="whitespace-pre! language-bash"><span><span># Navigate to backend folder</span><span>
</span><span>cd</span><span> backend

</span><span># Install dependencies</span><span>
npm install

</span><span># Start the server</span><span>
npm run dev
</span></span></code></div></div></pre>

* Ensure `.env` contains your database connection string, e.g.:

<pre class="overflow-visible!" data-start="1408" data-end="1469"><div class="contain-inline-size rounded-2xl relative bg-token-sidebar-surface-primary"><div class="sticky top-9"><div class="absolute end-0 bottom-0 flex h-9 items-center pe-2"><div class="bg-token-bg-elevated-secondary text-token-text-secondary flex items-center gap-4 rounded-sm px-2 font-sans text-xs"></div></div></div><div class="overflow-y-auto p-4" dir="ltr"><code class="whitespace-pre! language-env"><span>MONGO_URI=your_mongodb_connection_string
PORT=5000</span></code></div></div></pre>


## 3. Database Schema

**Collections / Tables:**

1. **Users**
   * `name` (string)
   * `email` (string, unique)
   * `password` (string, hashed)
2. **Posts / APIs**
   * `title` (string)
   * `description` (string)
   * `createdAt` (date)
   * `updatedAt` (date)
3. **Other collections as per your backend requirements**
