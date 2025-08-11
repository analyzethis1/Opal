# 💎 Opal - Intelligent Data Visualization Platform

> Transform your data with iridescent brilliance

**Opal** is a sophisticated, web-based intelligent data visualization platform designed specifically for a Business Operations team. Built with React and TypeScript, it transforms CSV and Excel data into interactive, presentation-ready visualizations with professional styling and advanced AI-powered features.

![Opal demo](images/Opal%20demo1.png)

## ✨ Features

### ✨ **Smart Chart Suggestions (NEW!)**
- **AI-Powered Analysis** - Intelligent data structure analysis (100% client-side)
- **Multiple Suggestions** - 3-4 smart chart options based on your data
- **Live Chart Previews** - See actual miniature charts before choosing
- **Data-Aware Intelligence** - Automatically detects dates, categories, and numeric patterns
- **One-Click Application** - Instantly apply suggested chart configurations
- **Smart Titles** - Auto-generated descriptive chart titles
- **Optimal Chart Types** - Recommends best visualization for your data relationships

- ![Opal demo](images/Opal%20demo8.png)

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

![Opal demo](images/Opal%20demo3.png)

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

![Opal demo](images/Opal%20demo5.png)


## 📚 Usage Guide

### Basic Workflow

1. **📂 Upload Data** - Drag and drop CSV/Excel files
2. **🔄 Merge (Optional)** - Combine multiple datasets if needed
3. **📊 Configure Chart** - Select chart type and axes
4. **🎨 Customize** - Apply styling, colors, and advanced options
5. **🎯 Interact** - Explore data with filtering and drill-down
6. **📄 Export** - Generate high-resolution outputs

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

### Advanced Features

#### Data Merging
- **Concatenate** - Stack datasets vertically with source file tracking
    ![Opal demo](images/Opal%20demo6.png)
- **Join** - Merge datasets on common column values
    ![Opal demo](images/Opal%20demo7.png)
- **Column Mapping** - Rename columns before charting
  ![Opal demo](images/Opal%20demo2.png)

#### Mixed Charts
- Combine bar and line series in a single visualization
- Assign different series to left/right Y-axes
- Independent scaling for different data ranges

#### Styling System
- Individual color control for each data series
- Line tension adjustment for smooth curves
- Area fill toggles for enhanced visualization
- Professional color palette with 16 opal-inspired hues

  ![Opal demo](images/Opal%20demo4.png)

#### Interactive Features
- Click any chart element to filter data
- Visual filter breadcrumbs with individual removal
- Zoom and pan for detailed exploration
- Configurable hover effects and tooltips


## 🎨 Design Philosophy

Opal's visual design draws inspiration from natural opal gemstones, featuring:

- **Iridescent Color Palette** - 16 carefully selected colors mimicking opal's natural brilliance
- **Fluid Animations** - Smooth transitions that capture gemstone luminosity
- **Glass-morphism Effects** - Modern, professional aesthetic
- **Consistent Branding** - Cohesive visual identity throughout the application

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
- **Frontend**: React 18 + TypeScript
- **Charts**: Chart.js + react-chartjs-2
- **File Processing**: Papa Parse (CSV), SheetJS (Excel)
- **Export**: jsPDF + html2canvas
- **Styling**: CSS-in-JS with animations
- **State Management**: React Hooks + Context

### Key Components

```
src/
├── components/
│   ├── EnhancedChartConfig.tsx     # Main configuration interface
│   ├── EnhancedChartComponent.tsx  # Chart rendering with Chart.js
│   ├── SmartCharts.tsx             # AI-powered chart suggestions with previews
│   ├── FileUpload.tsx              # Drag-and-drop file handling
│   ├── DataPreview.tsx             # Data preview and column mapping
│   ├── DataMerger.tsx              # Multi-file merging logic
│   └── ExportComponent.tsx         # PDF/PNG export functionality
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

- **Client-Side Processing** - No server dependencies
- **Optimized Rendering** - Chart.js canvas-based performance
- **Lazy Loading** - Components loaded on demand
- **Memory Efficient** - Proper cleanup and garbage collection
- **Responsive Design** - Mobile and desktop optimized

## 🔒 Security & Privacy

- **No Data Transmission** - All processing happens locally
- **Client-Side Only** - Files never leave the user's browser
- **No External Dependencies** - Charts generated without external APIs
- **LocalStorage Only** - Presets stored locally, no server persistence

### Code Style
- TypeScript for type safety
- Functional React components with hooks
- CSS-in-JS for styling
- Comprehensive prop interfaces
- JSDoc comments for complex functions

### Commit Guidelines
- Use descriptive commit messages
- Include component/feature context
- Test changes before committing
- Update documentation for new features

## 📖 Changelog

### v2.1.0 - Smart Intelligence Update (Current)
- ✨ **Smart Chart Suggestions** - AI-powered chart recommendations
- ✨ **Live Chart Previews** - See actual miniature charts before choosing
- ✨ Data structure analysis and intelligent chart type selection
- ✨ Multiple suggestion options with reasoning explanations
- ✨ One-click application of smart configurations
- ✨ Auto-generated descriptive chart titles
- 🔧 Improved dark theme text visibility
- 🔧 Removed jarring section collapse animations
- 🔧 Fixed pie chart color rendering for proper category visualization

### v2.0.0 - Enhanced Opal
- ✨ Multi-series chart support
- ✨ Mixed chart types with dual Y-axes
- ✨ Advanced styling controls
- ✨ Interactive drill-down filtering
- ✨ Save/load preset system
- ✨ Iridescent opal-inspired design
- ✨ Simple/Advanced mode toggle
- ✨ Professional export capabilities

### v1.0.0 - Initial Release
- 📊 Basic chart types (bar, line, pie, scatter)
- 📂 CSV/Excel file upload
- 🎨 Simple styling options
- 📄 PDF export functionality

## 📞 Support

### Internal Support
- **Primary Contact**: Chris Karim
- **Feature Requests**: Internal GitHub Issues

### Documentation
- **User Guide**: Available in application help section
- **API Reference**: Component prop documentation in code
- **Troubleshooting**: Common issues resolved in FAQ

---

**Built with 💎 for PMO Business Operations**

*Transform your data with iridescent brilliance*
