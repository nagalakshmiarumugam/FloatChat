# 🌊 FloatChat – AI-Powered ARGO Ocean Data Assistant

FloatChat is an AI-powered conversational platform that enables users to explore and understand ARGO oceanographic datasets through natural language. Instead of writing Python or MATLAB code to analyze scientific ocean data, users can simply ask questions and receive meaningful insights, charts, and visualizations.

---

## 📌 Problem Statement

ARGO floats continuously collect oceanographic data such as temperature, salinity, and depth across the world's oceans. Although this data is valuable for climate research, marine studies, and environmental monitoring, it is typically stored in complex scientific formats like NetCDF and requires programming knowledge to access.

FloatChat bridges this gap by providing a conversational AI interface that allows non-technical users to interact with ARGO datasets using plain English.

---

## 🚀 Features

* 🤖 AI-powered chatbot for ocean data exploration
* 🌊 Natural language querying of ARGO datasets
* 📍 Location-based ocean analysis
* 🌡️ Temperature profile visualization
* 🧂 Salinity trend analysis
* 📊 Interactive charts and dashboards
* 🗺️ Ocean region exploration
* 📂 Dataset management interface
* ⚙️ User settings and customization

---

## 🛠️ Tech Stack

### Frontend

* Next.js (App Router)
* React
* TypeScript
* Tailwind CSS

### Backend

* FastAPI / Python
* Pandas
* NumPy
* Xarray

### AI & NLP

* OpenAI API / Gemini API
* Natural Language Processing (NLP)

### Visualization

* Plotly
* Recharts
* Interactive Maps

---

## 📂 Project Structure

```text
app/
├── maps/
├── datasets/
├── analytics/
├── chat/
├── regions/
├── settings/

components/
├── dashboard/
├── ui/

hooks/
lib/
public/
styles/
types/
```

---

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/your-username/floatchat.git
cd floatchat
```

### Install Dependencies

Using PNPM:

```bash
pnpm install
```

Or using NPM:

```bash
npm install
```

### Start Development Server

```bash
pnpm dev
```

Open:

```text
http://localhost:3000
```

---

## 🔑 Environment Variables

Create a `.env.local` file in the project root:

```env
OPENAI_API_KEY=your_api_key
ARGO_DATA_PATH=./data
```

---

## 💬 Example Questions

* What is the temperature of the Indian Ocean at 500m depth?
* Show salinity trends in the Pacific Ocean.
* Compare surface and deep ocean temperatures.
* Is the ocean warming near India?
* What changes occurred in ocean temperature over the last five years?

---

## 🏗️ System Architecture

```text
User Query
     ↓
NLP Processing
     ↓
Parameter Extraction
     ↓
ARGO Dataset Retrieval
     ↓
Data Analysis
     ↓
Visualization Generation
     ↓
AI Response
```

---

## 📊 Dashboard Modules

### Maps

Interactive ocean region visualization.

### Datasets

Browse and manage ARGO datasets.

### Analytics

Explore trends, comparisons, and ocean insights.

### Chat

Ask questions using natural language.

### Regions

Analyze specific ocean regions.

### Settings

Manage preferences and configurations.

---

## 🎯 Project Goals

* Make ARGO data accessible to everyone.
* Eliminate the need for programming knowledge.
* Support climate and environmental research.
* Enable data-driven decision-making.
* Improve ocean data literacy.

---

## 🔮 Future Enhancements

* Real-time ARGO data synchronization
* Voice-enabled chatbot
* Multi-language support
* Climate anomaly detection
* Predictive ocean analytics
* Mobile application support

---

## 👨‍💻 Developed By

Nagalakshmi A

AI-Powered Ocean Data Exploration Platform

---

## 📄 License

This project is licensed under the MIT License.
