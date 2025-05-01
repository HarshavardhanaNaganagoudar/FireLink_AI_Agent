
**FireLink** is an AI-powered wildfire mapping tool that links recent fire detections to nearby **water bodies** and **fire stations**, then displays everything on an interactive map.

Just ask a question like:

> _"Show fires in California with brightness above 300 and confidence greater than 80"_

...and FireLink will return a live HTML map using real-time satellite and geospatial data.

---

## 🌟 Features

- 🔥 Detects **wildfires** from NASA FIRMS satellite feeds (MODIS & VIIRS).
- 💧 Maps **nearby water bodies** using Google Earth Engine water occurrence data.
- 🚒 Shows **closest fire stations** from OpenStreetMap.
- 🧠 Uses an **AI agent** to interpret natural language prompts.
- 🗺️ Displays results on a clean, **interactive map** via Gradio.

---

## 🌍 Live Demo

[![Hugging Face Spaces](https://img.shields.io/badge/Try%20Live%20on-Hugging%20Face-blue?logo=huggingface)](https://huggingface.co/spaces/nharshavardhana/FireLink)

> 💬 Try prompts like:
> - _"Fires in Alberta with confidence over 60"_
> - _"Map wildfires in Australia with brightness > 310"_

---
## 🌐 Real-Life Use Cases

FireLink goes beyond just wildfire detection — it maps each fire incident in relation to critical nearby infrastructure like **water sources** and **fire stations**, enabling smarter preparedness and response strategies.

- 🚨 **Emergency Response Planning**  
  Help local authorities quickly assess whether a fire is close to accessible water or a nearby fire station — a crucial factor in dispatching teams effectively.

- 🧯 **Resource Allocation**  
  Visualize which fires are underserved by nearby firefighting infrastructure, helping prioritize deployment of mobile resources or equipment in remote areas.

- 🌲 **Forest & Wildlife Protection**  
  Identify high-risk zones near protected forests or wildlife reserves where fire suppression resources are scarce and water access is limited.

- 🧑‍🤝‍🧑 **Community Risk Awareness**  
  Inform rural and at-risk communities about the relative proximity of support infrastructure in the event of nearby wildfires.

- 📍 **Infrastructure Gap Analysis**  
  Use FireLink to spot regions where fire incidents regularly occur but nearby water sources or fire stations are missing — guiding investment in new infrastructure.


## 🧠 How It Works

| Component           | Technology |
|--------------------|------------|
| Fire Detection      | NASA FIRMS (MODIS/VIIRS) API |
| Water Body Mapping  | JRC Global Surface Water via Google Earth Engine |
| Fire Station Data   | OpenStreetMap via Overpass API |
| Natural Language AI | Mistral via LangGraph agent |
| Mapping             | Folium for interactive maps |
| UI Framework        | Gradio |
| Deployment          | Hugging Face Spaces |

---
