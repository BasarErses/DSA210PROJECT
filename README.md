## Optimizing Battery Efficiency Across Devices and Usage Patterns

### Project Proposal Outline
This project analyzes battery efficiency across multiple device types—laptops, tablets, and smartphones—under various common computing tasks. The study investigates how battery life, CPU utilization, device temperature, memory usage, and screen brightness correlate with tasks such as gaming, video editing, streaming, coding, and idle states. The aim is to identify practical usage patterns and device-specific recommendations for maximizing battery life and performance.

### Motivation
Understanding battery efficiency is crucial as devices become more central to daily life, impacting productivity, entertainment, and communication. Optimizing battery performance can significantly enhance user experience by reducing device downtime and prolonging hardware lifespan. This project provides insights and actionable recommendations that directly benefit device users seeking optimal performance.

### Dataset
The dataset includes:
- **Date of Measurement**
- **Device Model** (laptop, tablet, smartphone)
- **Operating System Version**
- **Task Type** (Gaming, Video Editing, Streaming, Coding, Idle)
- **Brightness Level (%)**
- **Battery Life** (hours:minutes)
- **Battery Health (%)** (to assess degradation over time)
- **Device Temperature (°C)**
- **CPU Utilization (%)**
- **Memory Usage (% RAM)**

### Data Source and Collection Method
Data will be collected systematically using built-in device diagnostics tools and third-party applications capable of monitoring battery performance, CPU usage, memory consumption, and temperature. The data collection will span several weeks to ensure consistency, reliability, and representation across multiple scenarios and conditions.

### Data Analysis Plan
The analysis will be conducted in several stages:

1. **Data Collection and Preprocessing:**
   - Standardize and preprocess raw data, addressing missing values and normalizing measurements.

2. **Exploratory Data Analysis (EDA):**
   - Visualizations and correlation analyses to identify initial patterns and relationships.

3. **Hypothesis Testing:**
   - Broad hypotheses to encompass multiple factors:
     - **H₀:** Device performance metrics (brightness, CPU usage, temperature, memory usage) do not significantly affect battery life across different tasks and device types.
     - **H₁:** One or more device performance metrics significantly influence battery life, varying across different tasks and device types.

4. **Comparative Analysis:**
   - Compare performance across device models and operating systems to pinpoint the most efficient hardware and software combinations.

5. **Trend and Longitudinal Analysis:**
   - Evaluate battery health trends over time to understand degradation impacts related to task intensity and device usage patterns.

### Findings (Anticipated)
The project expects to identify clear correlations between screen brightness, CPU utilization, memory usage, device temperature, and battery longevity. It also aims to highlight specific devices that excel in battery efficiency under intensive usage conditions. Results will include concrete recommendations on optimal usage settings for users seeking to extend device battery life.

### Limitations and Future Work
Potential limitations include variability in battery health across devices, device-specific measurement discrepancies, and environmental factors affecting battery performance. Future work might include expanding the dataset to cover additional device brands and models, implementing automated monitoring solutions, and exploring machine learning techniques to predict battery lifespan and performance.

### Expected Outcomes
- Specific recommendations for brightness settings, CPU and memory usage, and task prioritization.
- Identification of the most battery-efficient device categories and models.
- Practical strategies for users to prolong battery life and device longevity.

### AI Assistance Disclosure
This project has made use of AI tools in accordance with the academic integrity guidelines of the DSA210 course. 

Specifically:
- Tool Used: ChatGPT (OpenAI GPT-4).
Purpose of Use:
- Refining code snippets and analysis structure
- Improving documentation format (e.g., README layout)
- Analyzing .gitignore content based on standard practices
- Drafting helper texts and clarifications



