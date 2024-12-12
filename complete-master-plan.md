# Classic Car Restoration Website - Complete Master Plan

- Project Version: 1.0
- Last Updated: December 11, 2024
- Project Duration: 9 weeks

## Table of Contents
1. [Project Plan](#1-project-plan)
2. [Detailed WIX Website Plan](#2-detailed-wix-website-plan)
3. [Project Schedule](#3-project-schedule)
4. [GIT Progress Tracking](#4-git-progress-tracking)
5. [Project Structure](#5-project-structure)

## 1. Project Plan

### 1.1 Overview
A sophisticated portfolio website showcasing restored vehicles, targeting high-end clients including collectors, classic car enthusiasts, and 4x4 enthusiasts. The website serves as a gallery of completed works with direct auction platform integration.

### 1.2 Project Scope
**Total Timeline:** 9 weeks (189-230 hours with buffer)  
**Daily Commitment:** 2 hours (3PM - 5PM)  
**Primary Platform:** Wix  
**Testing Framework:** Playwright

### 1.3 Target Audience
- Wealthy, middle-aged automotive enthusiasts
- Classic car collectors
- 4x4 enthusiasts
- Potential restoration clients
- Automotive investment community

### 1.4 Development Phases

#### Phase 1: Learning & Setup (15-20 hours)
- Web development fundamentals
- Wix platform mastery
- Git basics
- Testing framework setup

#### Phase 2: Foundation (30-35 hours)
- Website structure implementation
- Basic design system setup
- Homepage development
- Portfolio grid layout

#### Phase 3: Core Features (40-45 hours)
- Photo gallery implementation
- Filtering system
- Auction integration
- Contact form setup

#### Phase 4: Content & Testing (40-45 hours)
- Content population
- Image optimization
- Performance testing
- Mobile responsiveness verification

#### Buffer Time (44-53 hours)
- 30% additional time allocated for learning curve
- Issue resolution
- Unexpected challenges

## 2. Detailed WIX Website Plan

### 2.1 Technical Specifications

#### Color Palette
- Primary Background: #F5F5F5 (Light Grey)
- Secondary Background: #E0E0E0 (Medium Grey)
- Text and UI: #2C2C2C (Dark Grey)
- Subtle Accents: #9B9B9B (Warm Grey)
- Hover States: #8A8A8A
- Text Overlay: rgba(0,0,0,0.6)
- White: #FFFFFF (For contrast)

#### Typography
- Clean, modern sans-serif fonts
- Hierarchical type scale for headings
- Emphasis on readability

### 2.2 Page Structure

#### Homepage
- Full-width hero section with featured vehicles
- Alternating layout between full-width features and grid displays
- Minimal, sophisticated animations on scroll
- Newsletter signup integration
- Social media integration
- Contact form section

#### Vehicle Grid Layout
- Clean, responsive grid system
- Minimal text overlay showing vehicle name
- Hover state with "View Project" text
- Filtering capabilities:
  - Vehicle type (4x4, classic cars)
  - Year of manufacture
  - Brand
  - Restoration completion date

#### Individual Vehicle Pages
- Large feature image
- Comprehensive photo gallery
- Auction link button
- Detailed specifications table
- Vehicle description and history
- Related vehicles section

### 2.3 Content Management
- Wix CMS setup for vehicle entries
- Image optimization guidelines
- Content update procedures
- Blog post management

## 3. Project Schedule

### Week 1-2: Learning Phase
- Monday: Web development basics
- Tuesday: HTML/CSS fundamentals
- Wednesday: Wix platform basics
- Thursday: Wix advanced features
- Friday: Git basics & setup
- Weekend: Review & practice

### Week 3-4: Main Development
- Portfolio page layout
- Section templates
- Navigation system
- Mobile responsiveness
- Content structure

### Week 5-6: Detail Pages
- Template development
- Navigation implementation
- Content structure
- Mobile testing

### Week 7-8: Testing & Content
- Test case creation
- Playwright implementation
- Content population
- Cross-browser testing

### Week 9: Launch
- Final QA testing
- Documentation updates
- Performance optimization
- Launch preparation

### Daily Structure (3PM - 5PM)
- 15 min: Review & planning
- 90 min: Main task work
- 15 min: Documentation & commits

## 4. GIT Progress Tracking

### 4.1 Branch Structure
```
main           # Production-ready code
├── development # Working branch
└── content     # Content updates
```

### 4.2 Branching Conventions
- Feature branches: `feature/[section-name]-[detail]`
- Content branches: `content/[portfolio-item-number]`
- Test branches: `test/[feature]-[test-type]`
- Fix branches: `fix/[bug-identifier]`

### 4.3 Commit Message Format
```
[type]: [brief description]

[detailed description]

Progress: [X/Y hours spent]/[estimated hours]
```

Types:
- `setup`: Environment changes
- `feat`: New features
- `content`: Content updates
- `test`: Testing changes
- `fix`: Bug fixes
- `docs`: Documentation

### 4.4 Daily Progress Template
```
docs: daily progress [date]

Tasks Completed:
- [task description]

In Progress:
- [task description] ([X]% complete)

Time Spent: [hours] hours
Remaining Estimate: [hours] hours
```

### 4.5 Progress Review Points

#### Daily Review
- End-of-day commit with progress summary
- Task estimate updates
- Blocker identification

#### Weekly Review
- Progress markdown creation
- Timeline updates
- Estimate adjustments

## 5. Project Structure

### 5.1 Wix Site Structure
```
📦 Classic Car Restoration Website
├── 📂 Pages
│   ├── Home
│   ├── Vehicle Grid (Portfolio)
│   ├── Vehicle Detail Template
│   ├── About
│   ├── Blog
│   └── Contact
│
├── 📂 Databases (Wix Collections)
│   ├── Vehicles
│   │   ├── Basic Info (make, model, year)
│   │   ├── Specifications
│   │   ├── Gallery Images
│   │   ├── Auction Links
│   │   └── Restoration Details
│   ├── Blog Posts
│   ├── Newsletter Subscribers
│   └── Contact Form Submissions
│
├── 📂 Components
│   ├── 📂 Layout
│   │   ├── Header
│   │   ├── Footer
│   │   └── Navigation
│   │
│   ├── 📂 Vehicle Components
│   │   ├── Vehicle Card
│   │   ├── Vehicle Gallery
│   │   ├── Vehicle Specs Table
│   │   └── Before/After Slider
│   │
│   └── 📂 Common Components
│       ├── Newsletter Signup
│       ├── Contact Form
│       ├── Social Share Buttons
│       └── Filter Bar
│
└── 📂 Assets
    ├── 📂 Images
    │   ├── Vehicle Photos
    │   ├── Logo Files
    │   └── UI Elements
    │
    └── 📂 Documents
        └── Vehicle Documentation
```

### 5.2 Component Specifications

#### Vehicle Collection Schema
```javascript
{
  // Basic Information
  make: String,
  model: String,
  year: Number,
  
  // Details
  engineSpecs: String,
  transmission: String,
  mileage: Number,
  
  // Restoration
  restorationDate: Date,
  restorationDetails: Text,
  beforeImages: [Image],
  afterImages: [Image],
  
  // Auction
  auctionLink: String,
  auctionDate: Date,
  estimatedValue: Number,
  
  // Meta
  featured: Boolean,
  category: ["Classic", "4x4"],
  dateAdded: Date,
  lastUpdated: Date
}
```

### 5.3 Integration Points

#### External Services
- Newsletter Service
- Contact Form Handler
- Auction Platform Links
- Social Media Integration
- Analytics Integration

#### Data Flow
```
User Input → Wix Forms → Database Collections → Dynamic Pages
                      ↓
              Email Notifications
                      ↓
            Analytics Tracking
```

### 5.4 Responsive Breakpoints
- Mobile: < 768px
- Tablet: 768px - 1024px
- Desktop: > 1024px
- Large Desktop: > 1440px

### 5.5 Asset Guidelines
- Images
  - Thumbnails: 400x300px
  - Gallery: 1200x800px
  - Hero: 1920x1080px
  - Format: WebP with JPEG fallback
  - Max file size: 200KB for thumbnails, 1MB for full-size
- Icons
  - Format: SVG
  - Size: 24x24px base
  - Style: Single color, configurable

### 5.6 Performance Targets
- Page Load: < 3s
- Time to Interactive: < 4s
- First Contentful Paint: < 2s
- Core Web Vitals
  - LCP: < 2.5s
  - FID: < 100ms
  - CLS: < 0.1

---

*Note: This master plan is a living document. Updates and revisions will be tracked through Git following the outlined version control procedures.*
