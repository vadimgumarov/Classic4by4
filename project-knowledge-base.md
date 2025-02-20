# Classic4x4.com Redesign - Project Knowledge Base

*Last Updated: February 19, 2025*

## Table of Contents
1. [Project Overview](#project-overview)
2. [Current Status](#current-status)
3. [Implementation Progress](#implementation-progress)
4. [Technical Details](#technical-details)
5. [Dependencies](#dependencies)
6. [Challenges & Solutions](#challenges--solutions)
7. [Design Decisions](#design-decisions)
8. [Next Steps](#next-steps)
9. [Resources](#resources)

## Project Overview
The Classic4x4.com redesign project involves transforming the existing Wix website to implement the Retrokraft brand identity with a premium, sophisticated aesthetic inspired by ClassicCarStudio.com. The project timeline is 5 weeks with a 2-hour daily commitment (50 total hours).

**Key Project Details:**
- **Platform:** Wix (enhancing existing site)
- **Brand Identity:** Retrokraft (Navy, Burnt Orange, Light Pink, Golden Yellow, Peach Cream)
- **Typography:** Poppins (headings), Roboto (body)
- **Target Audience:** High-end classic 4x4 collectors and enthusiasts
- **Primary Reference:** ClassicCarStudio.com

## Current Status
**Phase:** Analysis & Planning (Week 1)
**Completed Tasks:**
- Created project repository structure
- Developed revised master plan for Wix implementation
- Created brand implementation guide for Wix
- Established documentation templates

**In Progress:**
- Site audit of current Wix implementation
- Assessment of Wix customization capabilities
- Content inventory

## Implementation Progress

### Phase 1: Analysis & Planning
- [x] Repository structure created
- [x] Project plan revised for Wix implementation
- [x] Documentation templates established
- [ ] Site audit of current template
- [ ] Wix customization capabilities assessment
- [ ] Content inventory
- [ ] Brand implementation planning

### Phase 2: Brand Implementation
- [ ] Logo implementation
- [ ] Color palette application
- [ ] Typography implementation
- [ ] Button and UI element styling
- [ ] Visual identity review

### Phase 3: Layout Enhancement
- [ ] Homepage hero section
- [ ] Vehicle listing grid
- [ ] Vehicle detail pages
- [ ] About/services pages
- [ ] Navigation and footer

### Phase 4: Content Enhancement
- [ ] Gallery functionality
- [ ] Vehicle card presentation
- [ ] Specifications display
- [ ] Forms and interactions
- [ ] Call-to-action placement

### Phase 5: Testing & Refinement
- [ ] Mobile responsiveness
- [ ] Cross-browser compatibility
- [ ] Content review
- [ ] Performance optimization
- [ ] Final review

## Technical Details

### Wix Site Information
- **Current Template:** [To be documented after audit]
- **Editor Type:** [Standard Wix Editor/Editor X - to be confirmed]
- **Premium Plan Features:** [To be documented]
- **Connected Domain:** classic4x4.com

### Brand Implementation Details
**Color Codes:**
- Primary Navy Blue: #1D3E69 (RGB: 29, 62, 105)
- Burnt Orange: #D95F02 (RGB: 217, 95, 2)
- Light Pink: #FFC0CB (RGB: 255, 192, 203)
- Golden Yellow: #FFBB00 (RGB: 255, 187, 0)
- Peach Cream: #FFE2C6 (RGB: 255, 226, 198)
- White: #FFFFFF
- Black: #000000

**Typography:**
- Primary Font: Poppins (weights: 400, 500, 600, 700)
- Secondary Font: Roboto (weights: 300, 400, 500, 700)
- Heading scales: H1: 42px, H2: 32px, H3: 24px, H4: 20px
- Body: 16px, Small: 14px, Caption: 12px

### Wix Collection Structure
**Vehicles Collection Schema:**
```
Collection: Vehicles
Fields:
- Name (text)
- Year (number)
- Make (text)
- Model (text)
- Price (number)
- Mileage (number)
- Engine (text)
- Transmission (text)
- Drivetrain (text)
- ExteriorColor (text)
- InteriorColor (text)
- VIN (text)
- Featured (boolean)
- Restored (boolean)
- VehicleStory (rich text)
- RestorationJourney (rich text)
- InvestmentPotential (rich text)
- Specifications (rich text)
- Images (gallery)
```

## Dependencies

### External Dependencies
- Wix Premium Plan subscription (active)
- Google Fonts access through Wix
- Retrokraft logo files (all versions needed)
- Vehicle photography (high-resolution)

### Internal Dependencies
- Completion of site audit before implementation
- Brand guide approval before color/typography implementation
- Content template approval before content enhancement

## Challenges & Solutions

### Current Challenges
1. **Wix Template Limitations:**
   - [To be documented after audit]
   - *Potential solution:* [To be determined]

2. **Content Migration:**
   - [To be documented after content inventory]
   - *Potential solution:* [To be determined]

3. **Timeline Constraints:**
   - 50-hour total implementation window
   - *Solution:* Prioritized enhancement plan with focus on highest-impact elements

### Resolved Challenges
*[To be populated as challenges are resolved]*

## Design Decisions

### Key Decisions Made
1. **Platform Selection:**
   - Decision: Enhance existing Wix site rather than rebuild
   - Rationale: Preserves content/SEO, fits timeline constraints, maintains familiarity

2. **Content Structure:**
   - Decision: Implement standardized vehicle description template
   - Rationale: Ensures consistent premium presentation while maintaining technical details

### Pending Decisions
1. **Header Layout:**
   - Options: [To be determined after template audit]
   - Considerations: Brand visibility, navigation usability, mobile presentation

2. **Vehicle Card Design:**
   - Options: [To be determined after template capabilities assessment]
   - Considerations: Consistent sizing, information hierarchy, premium presentation

## Next Steps

### Immediate Actions (Next 1-3 Days)
1. Complete site audit of current Wix implementation
2. Document template capabilities and limitations
3. Finalize color palette implementation plan for Wix
4. Begin content inventory of vehicle listings

### Week 1 Goals
1. Complete all analysis and planning documentation
2. Create mockups for key page enhancements
3. Finalize implementation approach for brand elements
4. Develop content enhancement plan

## Required Files

### Critical Files Needed
The following files are required but not yet added to the repository:

1. **Logo Files:**
   - [ ] Retrokraft logo - Navy Blue version (PNG and SVG)
   - [ ] Retrokraft logo - White version (PNG and SVG)
   - [ ] Retrokraft icon for favicon (ICO, PNG)
   - Location to add: `/Assets/Logos/`

2. **Brand Assets:**
   - [ ] Retrokraft official brand guide PDF
   - [ ] Color swatch files (.ase or similar)
   - Location to add: `/Documentation/PlanningDocs/BrandImplementation/`

3. **Reference Materials:**
   - [ ] Screenshots of ClassicCarStudio.com key pages (Homepage, Vehicle Listings, Vehicle Detail)
   - [ ] Screenshots of current Classic4x4.com site (all main sections)
   - Location to add: `/Assets/ReferenceScreenshots/`

4. **Content Templates:**
   - [ ] Vehicle data spreadsheet template (for consistent collection data)
   - [ ] Photography shot list and requirements
   - Location to add: `/Documentation/ContentGuides/`

5. **Wix-Specific:**
   - [ ] Wix site editor access credentials (store securely, not in repository)
   - [ ] Wix premium plan details and limitations
   - Document in: Knowledge Base only (do not store credentials in repository)

### Additional Files for Enhancement
These files would improve the project but aren't critical for initial implementation:

1. **Design Assets:**
   - [ ] Mockups of enhanced pages (Figma or similar)
   - [ ] UI component design specifications
   - Location to add: `/Documentation/DesignAssets/Mockups/`

2. **Content Examples:**
   - [ ] Sample premium vehicle descriptions
   - [ ] High-quality placeholder images
   - Location to add: `/Documentation/ContentGuides/VehicleDescriptions/`

## Resources

### Project Documentation
- [Revised Master Plan](Documentation/PlanningDocs/revised-master-plan.md)
- [Brand Implementation Guide](Documentation/PlanningDocs/BrandImplementation/retrokraft-brand-guide-for-wix.md)
- [Daily Progress Template](Documentation/ProgressReports/daily-progress-template.md)
- [Vehicle Description Template](Documentation/ContentGuides/VehicleDescriptions/vehicle-description-template.md)

### Reference Sites
- [ClassicCarStudio.com](https://classiccarstudio.com)
- [Current Classic4x4.com](https://classic4x4.com)

### Brand Assets
- [Location of logo files - to be populated]
- [Color palette documentation - to be populated]
- [Typography guide - to be populated]

---

## Update Log

### February 19, 2025
- Created project repository structure
- Developed revised master plan for 5-week Wix implementation
- Created brand implementation guide for Wix constraints
- Established documentation templates
- Created Project Knowledge Base document
- Added Required Files tracking section to Knowledge Base

*[Future updates will be added here chronologically]*
