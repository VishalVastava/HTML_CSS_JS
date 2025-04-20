# 🔍 Advanced LinkedIn Talent Search Tool

An advanced LinkedIn profile search tool that utilizes **Google Programmable Search Engine** and **Google Custom Search API** to fetch potential candidate profiles based on multiple criteria like skills, job titles, location, experience, education, certifications, and more.

![screenshot](https://github.com/user-attachments/assets/944d5c6e-8593-421d-a2a7-e59df6cca9ab)


---

## 🚀 Features

- Search LinkedIn profiles using **20+ custom filters**
- Sleek, responsive UI with clean layout
- Fetches data using Google Custom Search API
- Easily customizable & deployable on any static hosting service

---

## 🌐 Demo

Coming soon! (Or host it yourself in under 5 mins. Instructions below 👇)

---

## 📦 Technologies Used

- HTML5, CSS3
- JavaScript (Vanilla)
- Google Programmable Search Engine
- Google Custom Search API

---

## ⚙️ Setup Instructions

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/advanced-linkedin-search.git
cd advanced-linkedin-search
```

### 2️⃣ Create a Google Custom Search Engine

1. Go to [Programmable Search Engine](https://programmablesearchengine.google.com/)
2. Click on `+ Add` to create a new search engine
3. In **Sites to search**, enter:
   ```
   linkedin.com/in
   ```
4. Name your search engine and click `Create`
5. After creating, go to **Control Panel** and copy your **Search Engine ID**

---

### 3️⃣ Get Google Custom Search API Key

1. Visit [Google Cloud Console](https://console.cloud.google.com/)
2. Create a new project (or use an existing one)
3. Navigate to **APIs & Services > Enabled APIs & services**
4. Click **+ ENABLE APIS AND SERVICES**
5. Search for `Custom Search API` and enable it
6. Then, go to **Credentials** > **+ Create Credentials** > **API Key**
7. Copy the **API Key**

---

### 4️⃣ Update Your Keys in HTML

Open `index.html` and replace the placeholders:

```js
const API_KEY = "YOUR_API_KEY_HERE";
const SEARCH_ENGINE_ID = "YOUR_SEARCH_ENGINE_ID_HERE";
```

---

### 5️⃣ Run the Project

Just open `index.html` in any browser, and you're ready to go!

---

## 🖼️ Screenshot

![screenshot](https://github.com/user-attachments/assets/aac3b681-9172-447a-8bb3-8aa68b284cc2)


---

## 🙋‍♂️ Who is this for?

- Recruiters looking for targeted LinkedIn profiles
- HR professionals seeking passive candidates
- Developers wanting to learn about Google Search APIs
- Anyone interested in creative LinkedIn search tools

---

## 📌 Important Notes

- This tool only works for **public LinkedIn profiles**
- API has a **daily quota limit** (100 free requests/day by default)
- You can increase limits by enabling billing on Google Cloud

---

## 📜 License

This project is licensed under the [GNU General Public License v3.0](https://www.gnu.org/licenses/gpl-3.0.html).

```

---

## ✨ Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you’d like to change.

---

## 📫 Contact

Made with ❤️ by Vishal Vastava (https://github.com/VishalVastava)

Feel free to fork, star ⭐, and share!
