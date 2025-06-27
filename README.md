# FluentBridge - Bengali-First IELTS Learning Platform

🌉 **Bengali-first English learning LMS designed specifically for IELTS preparation in Bangladesh**

## 🎯 Project Overview

FluentBridge is a comprehensive learning management system that addresses the unique needs of Bengali speakers preparing for IELTS. Unlike traditional platforms, we start with phonics foundation and provide Bengali-first explanations throughout the learning journey.

### 🚀 Key Features
- **Phonics Foundation**: Mandatory Track 0 addressing sound mapping from Bengali to English
- **6-Part Assessment System**: Comprehensive skill evaluation with Bengali hints
- **Bengali-First Methodology**: Native language explanations, not just interface translation
- **Community Learning**: Study groups and speaking partner matching
- **Mock Testing**: Integrated practice tests with culturally relevant content
- **Mobile-First PWA**: Optimized for Bangladesh's mobile-centric market

## 🛠️ Tech Stack

- **Frontend**: React + TypeScript + Tailwind CSS
- **Backend**: Supabase (PostgreSQL + Authentication + Real-time)
- **Additional**: Node.js + Express for extended services
- **Deployment**: Vercel/Netlify + Supabase Cloud

## 🏗️ Project Structure

```
fluentbridge/
├── frontend/              # React TypeScript frontend
│   ├── src/
│   │   ├── components/    # Reusable UI components
│   │   ├── pages/         # Page components
│   │   ├── services/      # API and external services
│   │   └── types/         # TypeScript definitions
│   └── package.json
├── database/              # Database schemas and migrations
├── docs/                  # Project documentation
│   └── implementation-guides/
└── README.md
```

## 🎨 Brand Colors

- **Bridge Blue**: `#3B82F6` - Primary navigation, trust
- **Growth Green**: `#22C55E` - Progress, success indicators  
- **Warm Gold**: `#F59E0B` - Achievements, celebrations
- **Bengal Green**: `#059669` - Cultural connection
- **Calm Gray**: `#64748B` - Content, professional elements

## 📋 Development Status

### Current Phase: Foundation Development (Week 1-3)
- [ ] Project setup and authentication
- [ ] Database schema implementation
- [ ] Basic content management
- [ ] Assessment system foundation

### Upcoming Phases:
- **Phase 2** (Week 4-6): Assessment System
- **Phase 3** (Week 7-9): Learning Experience  
- **Phase 4** (Week 10-12): Polish & Launch

## 🚀 Getting Started

### Prerequisites
- Node.js 18+
- npm or yarn
- Supabase account

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/fluentbridge.git
   cd fluentbridge
   ```

2. **Set up frontend**
   ```bash
   cd frontend
   npm install
   ```

3. **Environment setup**
   ```bash
   cp .env.example .env.local
   # Add your Supabase credentials
   ```

4. **Start development server**
   ```bash
   npm start
   ```

## 🎯 Target Market

**Primary**: Bangladesh (starting with Khulna)
**Audience**: IELTS aspirants seeking Bengali-first learning approach
**Goal**: Replace traditional coaching centers with affordable, accessible online platform

## 📚 Learning Approach

### 3 Learning Tracks:
1. **Track 0**: Phonics Foundation (Prerequisites)
2. **Track 1**: IELTS Preparation (Core Offering)  
3. **Track 2**: Grammar Foundations (Supporting)

### Content Hierarchy:
**Track → Course → Module → Lesson**

## 🤝 Contributing

This project is currently in active development. Please see the implementation guides in `/docs/` for detailed development plans.

## 📄 License

[MIT License](LICENSE)

## 📞 Contact

For questions about this project, please refer to the documentation in `/docs/implementation-guides/`.

---

**Status**: Phase 1 - Foundation Development  
**Last Updated**: June 2025  
**Version**: 0.1.0-dev

