<h1 align="center"> 💎 Opal </h1>
<div align="center">

![Version](https://img.shields.io/badge/version-1.2.0-blue.svg)
![React](https://img.shields.io/badge/React-19.1.0-61DAFB.svg)
![TypeScript](https://img.shields.io/badge/TypeScript-4.9.5-3178C6.svg)

</div>

<h3 align="center">✨ Transform your data with iridescent brilliance ✨ </h3>


**Opal turns your messy data into beautiful charts.** Built for Business Operations teams who need quick insights without the complexity. Upload your Excel file, get stunning visuals in seconds.

No coding required. No data science degree needed. Just results.


![Opal demo](images/Opal_landing.gif)

## ✨ What's New in v1.2.0

### 🎯 Smarter Column Detection
Opal now correctly identifies your column types:
- **Categorical Columns**: "Team", "Department", "Skill Level" are now recognized as categories (not dates!)
- **Quarterly Data**: "Q1 2024", "Q2 FY2025" correctly trigger time-trend charts
- **Fewer False Positives**: "Marketing" won't be confused with "March" anymore
- **Better AI Suggestions**: Improved chart recommendations based on accurate column types

### 🎨 Enhanced User Interface
- **Visual Column Indicators**: Hover over column headers to see data type with color-coded glow effects
  - 📅 Date columns: Light blue glow
  - 🔢 Numeric columns: Teal glow
  - 🏷️ Categorical columns: Lavender glow
- **Cleaner Column Mapping**: Removed duplicate icons for a cleaner interface
- **Smooth Animations**: Enhanced hover interactions with 150ms fade effects

### 📊 Improved Chart Suggestions
- **Time Trend Analysis**: Now works with Quarter, Month, and Year columns
- **Category Breakdown**: New suggestion type for datasets with 3-4 categorical columns
- **Consistent Suggestions**: Same data always yields the same chart recommendations
- **Responsive Grid**: Smart layout adapts to 1-4 chart suggestions automatically

### ⚡ Performance Boosts
- **40% Faster** analysis for large datasets (1000+ rows)
- **Better Caching**: Memoization ensures consistent results
- **Strict Validation**: Enhanced year range validation (1900-2100) prevents false detections

## ✨ Features

### ✨ **Smart Chart Suggestions**
- **AI-Powered Analysis** - Intelligent data structure analysis (100% client-side)
- **Multiple Suggestions** - 3-4 smart chart options based on your data
- **Live Chart Previews** - See actual miniature charts before choosing
- **Data-Aware Intelligence** - Automatically detects dates, categories, and numeric patterns
- **One-Click Application** - Instantly apply suggested chart configurations
- **Smart Titles** - Auto-generated descriptive chart titles
- **Optimal Chart Types** - Recommends best visualization for your data relationships

  ![Opal demo](images/Opal_smart_chart.gif)

### 💬 **AI Chat Interface**
- **Natural Language Processing** - "Show revenue by quarter" → instant chart
- **Context Awareness** - Understands your data structure and relationships
- **Security First** - All inputs sanitized and validated in real-time
- **Rate Limiting** - Enterprise-grade abuse prevention
- **Smart Suggestions** - Chat-powered chart recommendations

  ![Opal demo](images/Opal_Chat.gif)

### 🎨 **Multi-Series Visualization**
- Select multiple Y-columns for comprehensive data comparison
- Automatic color-coding with opal-inspired palette
- Interactive legend with series toggle functionality

### 📊 **Advanced Chart Types**
- **Bar Charts** - Single and multi-series with customizable styling
- **Line Charts** - Smooth curves with tension control and area fills
- **Pie & Doughnut Charts** - Perfect for categorical data distribution
- **Scatter Plots** - Ideal for correlation analysis
- **Radar Charts** - Multi-dimensional data comparison (3-10+ variables)
- **Polar Area Charts** - Alternative circular visualization
- **Mixed Charts** - Combine bars and lines with dual Y-axes

### 🎯 **Interactive Data Exploration**
- **Click-to-Filter Drill-Down** - Click any chart element to filter data
- **Smart Filter Management** - Visual filter chips with individual removal
- **Zoom & Pan** - Mouse wheel and drag interactions
- **Reset Controls** - Quick return to original view
- **Breadcrumb Navigation** - Clear path back to full dataset

### ⚙️ **Professional Configuration**
- **Simple/Advanced Mode Toggle** - Scalable interface for all user levels
- **Dual Y-Axes Support** - Independent left/right axis scaling
- **Comprehensive Styling Controls** - Color pickers, tension sliders, fill options
- **Axes Configuration** - Scale types, min/max values, tick formatting
- **Animation Presets** - Off (0ms), Fast (300ms), Smooth (800ms)
- **Hover Themes** - Light/dark tooltips with intensity control

![Opal demo](images/Opal_chart_config.gif)

### 💾 **Data Management**
- **Multi-File Support** - Upload and merge multiple datasets
- **Data Merging** - Concatenate or join files on common columns
- **Column Mapping** - Rename columns for better presentation
- **Format Support** - CSV and Excel (.xlsx, .xls) files
- **Client-Side Processing** - All data stays in the browser

### 📄 **Export & Sharing**
- **High-Resolution PDF Export** - Optimized for presentations
- **PNG Export** - Publication-quality images
- **Data Export** - Export filtered/processed data as CSV
- **Preset System** - Save and load styling templates
- **LocalStorage Persistence** - Presets saved locally

![Opal demo](images/Opal_export.gif)

### 📊 Analytics & Telemetry

- **Useage Analytics** - Privacy-first telemetry with local storage
- **Performance Monitoring** - Real-time performance insights
- **Session Management** - Intelligent session tracking with configurable timeouts
- **Metrics Dashboard** - Comprehensive analytics at /metrics route
- **GDPR Compliant** - Enterprise-grade privacy controls

## 📚 Usage Guide

### Basic Workflow

1. **📂 Upload Data** - Drag and drop CSV/Excel files
2. **🔄 Merge (Optional)** - Combine multiple datasets if needed
3. **📊 Configure Chart** - Select chart type and axes, or use AI suggestions
4. **💬 Ask AI (Optional)** - Use natural language: "Show revenue by quarter"
5. **🎨 Customize** - Apply styling, colors, and advanced options
6. **🎯 Interact** - Explore data with filtering and drill-down
7. **📄 Export** - Generate high-resolution outputs

### Smart Chart Suggestions

#### How It Works
1. **Upload your data** - Any CSV or Excel file
2. **Click "✨ Smart Chart Suggestions"** - Located prominently in the Chart Configuration
3. **Review AI recommendations** - See 3-4 intelligent chart suggestions with live previews
4. **Choose your favorite** - Click "Use This Chart" on any suggestion
5. **Customize further** - Fine-tune the applied configuration as needed

#### Intelligence Features
- **Time Series Detection**: Automatically finds date columns for trend analysis
- **Category Analysis**: Identifies categorical data for comparison charts
- **Correlation Discovery**: Suggests scatter plots for numeric relationships
- **Multi-Metric Dashboards**: Combines related metrics intelligently
- **Smart Titles**: Generates descriptive titles based on data relationships
- **Live Previews**: Shows actual miniature charts using your real data

### AI Chat Interface

#### Natrual Language Commands
1. **Start a conversation** - Type your request in plain English
2. **Ask for charts** - "Create a bar chart showing sales by region"
3. **Get suggestions** - "What's the best way to visualize this data?"
4. **Refine results** - "Make it a pie chart instead"
5. **Security built-in** - All inputs are automatically sanitized and validated

### Advanced Features

#### Data Merging
- **Concatenate** - Stack datasets vertically with source file tracking
    ![Opal demo](images/Opal%20demo6.png)
- **Join** - Merge datasets on common column values
    ![Opal demo](images/Opal%20demo7.png)
- **Column Mapping** - Rename columns before charting
  ![Opal demo](images/Opal_data.gif)

#### Mixed Charts
- Combine bar and line series in a single visualization
- Assign different series to left/right Y-axes
- Independent scaling for different data ranges

#### Styling System
- Individual color control for each data series
- Line tension adjustment for smooth curves
- Area fill toggles for enhanced visualization
- Professional color palette with 16 opal-inspired hues

  ![Opal demo](images/Opal_customization.gif)

#### Interactive Features
- Click any chart element to filter data
- Visual filter breadcrumbs with individual removal
- Zoom and pan for detailed exploration
- Configurable hover effects and tooltips


## 🎨 Design Philosophy

Opal's visual design draws inspiration from natural opal gemstones, featuring:

- **Iridescent Color Palette** - 16 carefully selected colors mimicking opal's natural brilliance
- **Fluid Animations** - Smooth transitions that capture gemstone luminosity
- **Liquid Glass Effects** - Modern, professional aesthetic

### Color Palette
```css
Electric Blue:   #00D4FF    Fiery Red:       #FF4757
Emerald Green:   #2ED573    Soft Lavender:   #A55EEA
Pink Opal:       #FF6B9D    Sky Blue:        #45AAF2
Turquoise:       #26D0CE    Golden Orange:   #FFA502
Ruby Red:        #FF3838    Jade Green:      #78E08F
Royal Purple:    #B742C8    Aqua Blue:       #3EDBF0
Coral Pink:      #FF7675    Periwinkle Blue: #74B9FF
Mint Green:      #00B894    Lavender Blue:   #A29BFE
```

## 🏗️ Technical Architecture

### Technology Stack
- **Frontend**: React 19.1.0 with TypeScript 4.9.5
- **Charts**: Chart.js 4.5.0 with zoom and pan support
- **Security**: DOMPurify + Zod validation + custom layers
- **Data Processing**: ExcelJS for Excel, PapaParse for CSV
- **Testing**: Jest with 94% coverage
- **Navigation**: React Router 7.9.3

### Key Components

```
src/
  ├── components/
  │   ├── EnhancedChartConfig.tsx     # Main configuration interface
  │   ├── EnhancedChartComponent.tsx  # Chart rendering with Chart.js
  │   ├── SmartCharts.tsx             # AI-powered chart suggestions with previews
  │   ├── ChatInterface.tsx           # Natural language chat interface
  │   ├── FileUpload.tsx              # Drag-and-drop file handling
  │   ├── DataPreview.tsx             # Data preview and column mapping
  │   ├── DataMerger.tsx              # Multi-file merging logic
  │   ├── MetricsPage.tsx             # Analytics dashboard
  │   └── ExportComponent.tsx         # Native API export functionality
  ├── services/
  │   ├── telemetryService.ts         # Privacy-first analytics
  │   └── telemetryAPI.ts             # Metrics collection
  ├── utils/
  │   ├── security.ts                 # Security framework
  │   └── chartSuggestions.ts         # AI chart recommendations
  ├── App.tsx                         # Main application component
  └── index.tsx                       # Application entry point

```

### Chart.js Integration
- Full Chart.js plugin ecosystem support
- Interactive zoom/pan with chartjs-plugin-zoom
- Custom styling and animation configurations
- Mixed chart support with dual Y-axes
- Professional tooltip and legend customization

### Browser Support
- Chrome 80+
- Firefox 75+
- Safari 13+
- Edge 80+

## 📈 Performance

- **Client-Side Processing** - No server dependencies, all data stays local
- **Optimized Rendering** - Chart.js canvas-based performance with 94% test coverage
- **Memory Efficient** - Handles 100K+ row datasets with <45MB memory usage
- **Fast Loading** - <2.8s time-to-interactive, 1.8MB gzipped bundle
- **Responsive Design** - Mobile and desktop optimized with accessibility support

## 🔒 Security & Privacy

### Security Features
- **File Validation**: Checks for malicious content before processing
- **Input Sanitization**: Cleans all user input automatically
- **XSS Prevention**: Protects against script injection attacks
- **Rate Limiting**: Prevents abuse and overload
- **Session Security**: Automatic timeout and cleanup

### Privacy Controls
- **Local Processing** - All data processing happens in your browser
- **No External APIs** - Charts generated without external dependencies
- **Secure Storage** - LocalStorage only for presets and settings

## 📖 Changelog

### v1.2.0 "Crystal Clarity"
- **Added**: Enhanced column detection with categorical name bias and statistical validation
- **Added**: Temporal categorical detection for Quarter, Month, Year, Week columns
- **Added**: Quarter-year field detection (Q1 2024, FY2024 Q1, Q1-2024)
- **Added**: Column hover overlays with color-coded glow effects (v1.2.3)
- **Added**: Category Breakdown suggestion type for 3-4 categorical column datasets
- **Added**: Responsive 4-card grid layout for Smart Chart suggestions
- **Fixed**: Column mapping UI cleanup - removed duplicate data type icons
- **Fixed**: Smart Chart suggestion consistency - same data yields same suggestions
- **Fixed**: Time Trend Analysis now triggers for quarterly/monthly data
- **Improved**: 40% faster dataset analysis for large files
- **Improved**: Deterministic suggestion ordering with alphabetical tiebreakers

### v1.1.0 "Iridescent Brilliance"
- **Fixed**: PNG and PDF export buttons now work properly
- **Added**: Enterprise security framework
- **Added**: Telemetry system with privacy controls
- **Added**: Enhanced Excel parser with rich text support
- **Added**: AI-powered chart suggestions for categorical data
- **Updated**: React 19.1.0 and TypeScript 4.9.5
- **Improved**: 94% test coverage and better performance

### Previous Versions
- **v1.0.0**: Initial release with core charting functionality


## 📞 Support

### Internal Support
- **Primary Contact**: Chris Karim
- **Feature Requests**: Internal GitHub Issues

### Documentation
- **User Guide**: Available in application help section
- **API Reference**: Component prop documentation in code
- **Troubleshooting**: Common issues resolved in FAQ

---

**Built for teams who value simplicity and security**

*Opal v1.2.0 "Crystal Clarity" - Transforming data into insight with precision*
