# Bus Transit Analytics Dashboard

Interactive visualization dashboard showing bus delay patterns and passenger data.

## Files Overview

### Main Dashboard (Full Featured)
- **`index.html`** - Full dashboard with advanced filters and 3 coordinated charts
- **`main.js`** - Complete implementation with performance optimizations
- **`style.css`** - Comprehensive styling with responsive design

### Minimal Dashboard (MVP)
- **`index-minimal.html`** - Streamlined 2-chart dashboard
- **`main-minimal.js`** - Focused implementation under 350 lines

## Features

### ✅ Core Requirements Met
- **Visual Encodings**: Bar chart (position + color), Scatter plot (position + size + color)
- **Color Channels**: RdYlGn scale for delays, categorical colors for weather
- **Brushing & Linking**: Click route bars to filter scatter plot
- **Details-on-Demand**: Hover tooltips with contextual information

### 📊 Data
- **20 records** across 4 bus routes (7, 42, 43, 50)
- **Delay range**: 2-21 minutes
- **Weather conditions**: Sunny, Rainy, Snowy, Cloudy
- **Passenger range**: 450-1,450 per day

## Usage
1. Open `index.html` for full dashboard
2. Open `index-minimal.html` for MVP version
3. Click on route bars to filter data
4. Hover over elements for detailed information

## Performance
- Responsive design works on desktop and mobile
- Debounced interactions for smooth performance
- Cached data processing for faster updates

---

## Navigation
- **🏠 Stage 3:** [Build Phase Overview](../README.md)
- **📁 Build Log:** [Development Process](../3.2-Build-Log.md)
- **🔄 Live Demo:** [Open Dashboard](index.html)
- **⚡ MVP Demo:** [Open Minimal Version](index-minimal.html)
- **📚 Case Study:** [Transport Example](../../Training-Materials/Case-Studies/README.md)
