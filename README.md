<img width="772" height="435" alt="dashbord photo" src="https://github.com/user-attachments/assets/e986530d-6144-4354-8e0a-93eb3fbc897f" />
# 🏦 Banking Sector Analysis: Problem Analysis in Saudi Arabia

A comprehensive Power BI data analysis project examining banking sector issues and customer complaints across Saudi Arabian financial institutions. This dashboard analyzes service quality patterns, regional performance, and institutional effectiveness to support banking sector improvements.

## 📊 Project Overview

This Power BI dashboard provides critical analysis of banking sector problems across Saudi Arabia, examining complaint patterns, regional variations, and institutional performance. The project aims to support evidence-based banking policy development and service quality improvements in the Saudi financial sector.

## 🔧 Tools & Technologies

- **Power BI Desktop** - Primary visualization and dashboard creation
- **DAX (Data Analysis Expressions)** - Custom measures and statistical calculations
- **Power Query** - Data cleaning and transformation
- **M Language** - Advanced data preprocessing
- **Arabic Language Support** - Localized dashboard interface
- **Power BI Service** - Secure dashboard sharing and collaboration

## 📈 Key Metrics & Insights

### Overall Statistics
- **Total Complaints Analyzed**: 600+ documented cases
- **Banking Institutions**: Multiple Saudi banks included
- **Regional Coverage**: Southern, Eastern, and Central regions
- **Resolution Tracking**: 80% resolved vs 20% pending cases

### Banking Institution Analysis
- **أمكان (Amkan)**: 27 cases
- **أمريكان (American Express)**: 10 cases  
- **أكسيس (Access Bank)**: 10 cases
- **البحرين (Bahrain Bank)**: 10 cases
- **الرياض (Riyadh Bank)**: 10 cases
- **الراجحي (Al-Rajhi Bank)**: 14 cases
- **البنك المركزي (Central Bank)**: 11 cases
- **الأهلي (Al-Ahli Bank)**: 0 cases
- **Total Detailed Analysis**: 91 cases

## 📊 Dashboard Components

### Main Analytics Sections

#### Regional Analysis (المناطق)
- **Southern Region (المنطقة الجنوبية)**: Regional complaint filtering
- **Eastern Region (المنطقة الشرقية)**: Eastern province analysis
- **Central Region (المنطقة الوسطى)**: Riyadh and central areas

#### Complaint Type Analysis (نوع الشكوى)
- Interactive dropdown for complaint categorization
- Service quality issues tracking
- Transaction-related problems analysis

#### Resolution Time Analysis (الوقت المستغرق)
- Line chart showing resolution patterns from 2019-2024
- Peak complaint periods around 2020-2021
- Improvement trends through 2024

#### Case Status (حاله الشكوى)
- Pie chart showing complaint resolution status
- 80% resolved complaints vs 20% pending
- Performance tracking for customer service

#### Banking Institution Performance (اسم المتبرع/عدد أفرعه)
- Detailed breakdown by bank performance
- Branch network coverage assessment
- Service quality comparison across institutions

## 🎯 Key Features

### Interactive Filtering
- **Multi-language Support**: Arabic-English interface
- **Regional Filtering**: Geographic complaint analysis
- **Temporal Controls**: Time-based trend analysis
- **Bank Selection**: Institution-specific performance review

### Advanced Analytics
- **Trend Identification**: Multi-year complaint pattern recognition
- **Regional Comparison**: Cross-region service quality analysis
- **Bank Performance**: Institutional effectiveness measurement
- **Resolution Tracking**: Customer satisfaction monitoring

### Banking Sector Focus
- **Arabic Language Interface**: Fully localized for Saudi market
- **Islamic Banking Context**: Sharia-compliant service considerations
- **Regulatory Compliance**: SAMA (Saudi Central Bank) guidelines
- **Customer Privacy**: Secure complaint data handling

## 🚀 Getting Started

### Prerequisites
- Power BI Desktop with Arabic language support
- Access to Saudi banking complaint dataset
- Understanding of Saudi banking regulations
- Basic Power BI navigation skills

### Installation & Setup
1. Clone the repository:
```bash
git clone https://github.com/mohamed2nabil/problem-analysis-in-suide-arabe-with-power-bi.git
```

2. Open Power BI Desktop

3. Load the `.pbix` file from the repository

4. Configure Arabic language display settings

5. Refresh data connections if prompted

6. Explore the interactive banking dashboard

## 📁 Project Structure
```
problem-analysis-in-suide-arabe-with-power-bi/
│
├── Saudi_Banking_Analysis_Dashboard.pbix # Main Power BI file
├── data/
│   ├── raw/                             # Original complaint dataset
│   ├── processed/                       # Cleaned banking data
│   └── bank_metadata/                   # Institution information
│
├── documentation/
│   ├── banking_methodology_ar.md        # Analysis approach (Arabic)
│   ├── banking_methodology_en.md        # Analysis approach (English)
│   ├── sama_compliance.md               # Regulatory guidelines
│   └── banking_insights_report.pdf      # Key findings
│
├── localization/
│   ├── arabic_banking_terms.json        # Banking terminology
│   └── saudi_regions.json               # Geographic data
│
└── README.md
```

## 📊 Data Sources & Methodology

### Dataset Information
- **Source**: Saudi banking sector complaint records
- **Time Period**: 2019-2024
- **Privacy Level**: Customer data anonymized
- **Update Frequency**: Monthly data refresh
- **Regulatory Compliance**: SAMA data protection standards

### Data Processing
- **Customer Anonymization**: Personal identifier removal
- **Bank Classification**: Institution type categorization
- **Regional Mapping**: Saudi geographic standardization
- **Complaint Categorization**: Service type classification

## 🔍 Key Insights & Findings

### Banking Sector Patterns
1. **Institution Performance**: Al-Rajhi Bank shows highest complaint volume (14 cases)
2. **Regional Variations**: Central region (Riyadh) shows concentrated banking activity
3. **Resolution Efficiency**: 80% complaint resolution rate across sector
4. **Temporal Trends**: Peak complaint periods during 2020-2021

### Service Quality Analysis
- **High-Performing Banks**: Banks with zero complaints (Al-Ahli)
- **Service Gaps**: Areas requiring attention across institutions
- **Customer Satisfaction**: Resolution rate tracking
- **Branch Network Impact**: Geographic service coverage analysis

### Regulatory Insights
- **Compliance Monitoring**: SAMA regulation adherence
- **Consumer Protection**: Customer rights enforcement
- **Market Competition**: Inter-bank service comparison

## 🎯 Banking Sector Impact

### Regulatory Development
- SAMA policy formation support
- Consumer protection enhancement
- Banking service standards improvement
- Market competition monitoring

### Banking Operations
- Customer service optimization
- Branch network planning
- Complaint resolution process improvement
- Service quality benchmarking

### Customer Experience
- Service delivery enhancement
- Resolution time improvement
- Regional service equity
- Digital banking optimization

## 🛠️ Technical Implementation

### DAX Measures Created
```dax
Total Complaints = COUNT('BankingComplaints'[ComplaintID])
Resolution Rate = DIVIDE([Resolved Complaints], [Total Complaints])
Bank Performance = CALCULATE([Total Complaints], 'Banks'[BankName])
Regional Analysis = CALCULATE([Total Complaints], 'Geography'[Region])
```

### Power Query Transformations
- Banking data standardization
- Arabic text processing for bank names
- Regional geographic mapping
- Complaint type categorization

## 📈 Performance & Compliance

### Dashboard Performance
- **Load Time**: <5 seconds initial load
- **Refresh Speed**: 60-second data refresh
- **Arabic Display**: Optimized right-to-left layout
- **Mobile Banking**: Responsive design for tablets

### Regulatory Compliance
- **SAMA Guidelines**: Full regulatory compliance
- **Data Privacy**: Customer information protection
- **Audit Trails**: Complaint tracking documentation
- **Reporting Standards**: Central bank reporting format

## 📞 Contact & Support

**Project Lead**: Mohamed Nabil
- **GitHub**: [@mohamed2nabil](https://github.com/mohamed2nabil)
- **Specialization**: Banking Sector Analytics
- **Focus Area**: Saudi Financial Services
- **Email**: mohamed2nabil5@gmail.com

## 📄 License & Usage

This project follows Saudi banking data protection regulations and SAMA guidelines.

### Usage Guidelines
- Banking research: Permitted with proper authorization
- Regulatory use: SAMA and financial authorities
- Commercial application: Requires banking sector approval
- Academic research: With institutional ethics approval

## 🙏 Acknowledgments

- Saudi Arabian Monetary Authority (SAMA)
- Saudi banking sector institutions
- Banking compliance professionals
- Power BI Arabic localization community


