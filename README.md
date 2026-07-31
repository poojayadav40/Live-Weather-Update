
# 🌤️ Live Weather Update App

A responsive, real-time weather web application built using **React**, **Vite**, and **JavaScript**. This app fetches dynamic weather data (temperature, humidity, wind speed, weather conditions) for any searched city using an external weather API service.

---

## 🚀 Features

* **Real-time Weather Data:** Search for any city worldwide to get instant weather updates.
* **Key Metrics:** Displays temperature in °C, weather condition icons, humidity levels, and wind speed.
* **Modern UI:** Clean, responsive card design centered for optimal mobile and desktop views.
* **Fast Performance:** Built with **Vite** for fast build times and seamless development.

---

## 🛠️ Tech Stack

* **Frontend:** React.js, HTML5, CSS3, JavaScript (ES6+)
* **Build Tool:** Vite
* **API Integration:** OpenWeatherMap API (or custom external Weather API)

# Screenshots

![Screenshot (75)](https://github.com/user-attachments/assets/82f577cb-09f6-4785-9e64-98e743d9263b)



![Screenshot (76)](https://github.com/user-attachments/assets/9a44d4b5-02f2-4223-b385-0084306d6164)



![Screenshot (77)](https://github.com/user-attachments/assets/bf2039c7-e507-4517-bf75-b32469d8a954)



![Screenshot (78)](https://github.com/user-attachments/assets/9b55a1e0-dce2-49d9-8885-fbf7394bceec)


![Screenshot (79)](https://github.com/user-attachments/assets/499d941f-9c8d-461a-932f-d05dd477ed77)



---

## 🔑 Environment Variables Setup

To run this project, you need to get your own API Key from your weather service provider (e.g., [OpenWeatherMap](https://openweathermap.org/)):

1. Create an account on the weather API platform using your Gmail.
2. Navigate to your account dashboard and copy your **API Key**.
3. In the root directory of this project, create a file named `.env`.
4. Add your API key in the `.env` file like this:

```env
VITE_WEATHER_API_KEY=your_api_key_here
Note: Make sure .env is listed in your .gitignore file so your secret API key isn't exposed publicly.

⚙️ How to Run the Project Locally
Follow these steps to set up and run the app locally on your machine:
1. Clone the repository
git clone [https://github.com/poojayadav40/Live-Weather-Update.git](https://github.com/poojayadav40/Live-Weather-Update.git)
cd Live-Weather-Update
2. Install dependencies
npm install
3. Start the development server
npm run dev
Open your browser and navigate to http://localhost:5173 (or the local URL provided in your terminal).
📸 Preview
---

### 💡 Quick Tip for your `.env` File
When using **Vite**, remember that your variable names inside the `.env` file **must start with `VITE_`** (e.g., `VITE_WEATHER_API_KEY=...`), otherwise React won't be able to access it!
