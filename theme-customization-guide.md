# Wix Theme Customization Guide for Classic4x4.com Redesign

## Introduction
This guide provides step-by-step instructions for customizing the Wix theme to implement the Retrokraft brand identity on Classic4x4.com. It addresses specific Wix Editor capabilities and workarounds for common limitations.

## Table of Contents
1. [Theme Manager Setup](#theme-manager-setup)
2. [Color Palette Configuration](#color-palette-configuration)
3. [Typography Implementation](#typography-implementation)
4. [Header & Navigation Customization](#header--navigation-customization)
5. [Component Styling](#component-styling)
6. [Section Backgrounds](#section-backgrounds)
7. [Button & Form Styling](#button--form-styling)
8. [Mobile Responsiveness Adjustments](#mobile-responsiveness-adjustments)
9. [Advanced Customizations & Workarounds](#advanced-customizations--workarounds)

## Theme Manager Setup

### Creating a New Theme Variant
1. Log in to Wix Dashboard → Navigate to site editor
2. Select "Theme" from the top menu
3. Click "Theme Manager"
4. Click "+" to create a new theme variation
5. Name it "Retrokraft Premium"
6. Click "Edit Theme" to begin customization

### Saving Theme Settings
1. After completing all customizations, click "Save Theme"
2. Publish the theme to make it active
3. Document all settings in this repository for future reference

### Exporting Theme (if available)
1. From Theme Manager, select "..." next to your theme
2. Select "Export Theme" if available
3. Save the exported theme file in repository under: `/Assets/WixTheme/`

## Color Palette Configuration

### Accessing Color Settings
1. In Theme Manager, navigate to "Colors" tab
2. Create a new color palette or modify existing

### Primary Colors Setup
Configure these exact colors:
1. **Primary**: #1D3E69 (Navy Blue)
2. **Secondary**: #D95F02 (Burnt Orange)
3. **Accent**: #FFBB00 (Golden Yellow)
4. **Light Accent**: #FFC0CB (Light Pink)
5. **Background**: #FFE2C6 (Peach Cream)
6. **Text Color Dark**: #000000
7. **Text Color Light**: #FFFFFF

### Extended Palette Setup
If your theme allows additional color slots, add:
1. **Dark Primary**: #142C4C (Darker Navy)
2. **Light Primary**: #2E5E9E (Lighter Navy)
3. **Dark Accent**: #B14D02 (Darker Orange)
4. **Light Background**: #FFEBD5 (Lighter Peach)
5. **Grey Light**: #F7F9FA
6. **Grey Medium**: #ADB5BD
7. **Grey Dark**: #495057

### Color Application Guide
Configure these standard elements:
1. **Page Background**: White (#FFFFFF)
2. **Headers Background**: Navy Blue (#1D3E69)
3. **Footer Background**: Navy Blue (#1D3E69)
4. **Primary Buttons**: Burnt Orange (#D95F02)
5. **Secondary Buttons**: Navy Blue (#1D3E69)
6. **Links**: Navy Blue (#1D3E69)
7. **Primary Text**: Black (#000000)
8. **Heading Text**: Navy Blue (#1D3E69)

### Wix Color Limitations & Workarounds
Some themes have limited color slots. If needed:
1. Use "Custom CSS" option if available in your Wix plan
2. Use Wix "Section Background" settings for additional color application
3. For elements that can't be controlled through theme settings, use individual element color controls

## Typography Implementation

### Adding Google Fonts
1. In Wix Editor, click "Text" in the left sidebar
2. Click "Manage Fonts" (or "Add Fonts" depending on interface)
3. Select "Google Fonts" tab
4. Search and add:
   - Poppins (weights: 400, 500, 600, 700)
   - Roboto (weights: 300, 400, 500, 700)

### Creating Text Themes
Configure these text styles:
1. **Page Title** (H1):
   - Font: Poppins
   - Weight: Bold (700)
   - Size: 42px (desktop) / 32px (mobile)
   - Color: #1D3E69
   - Line Height: 1.2
   - Save as default for H1

2. **Section Heading** (H2):
   - Font: Poppins
   - Weight: SemiBold (600)
   - Size: 32px (desktop) / 28px (mobile)
   - Color: #1D3E69
   - Line Height: 1.25
   - Save as default for H2

3. **Subsection Heading** (H3):
   - Font: Poppins
   - Weight: Medium (500)
   - Size: 24px (desktop) / 20px (mobile)
   - Color: #1D3E69
   - Line Height: 1.3
   - Save as default for H3

4. **Card Heading** (H4):
   - Font: Poppins
   - Weight: Regular (400)
   - Size: 20px (desktop) / 18px (mobile)
   - Color: #1D3E69
   - Line Height: 1.4
   - Save as default for H4

5. **Body Text**:
   - Font: Roboto
   - Weight: Regular (400)
   - Size: 16px
   - Color: #000000
   - Line Height: 1.625
   - Save as default paragraph style

6. **Small Text**:
   - Font: Roboto
   - Weight: Light (300)
   - Size: 14px
   - Color: #495057
   - Line Height: 1.5
   - Save as additional text style

7. **Button Text**:
   - Font: Poppins
   - Weight: Medium (500)
   - Size: 14px
   - Color: #FFFFFF
   - Letter Spacing: 0.5px
   - Save as button text style

### Typography Application
Apply these styles consistently:
1. Update all existing headings with new styles
2. Create text style presets for special cases:
   - Price Display: Poppins SemiBold, 20px, #D95F02
   - Caption: Roboto Light, 12px, #6C757D
   - Quote: Poppins Italic, 18px, #1D3E69

### Typography Limitations & Workarounds
For typography limitations:
1. If certain elements resist styling, recreate them using Text elements
2. For consistent spacing, use guidelines or spacer elements
3. Document any elements that can't be styled properly for alternative approaches

## Header & Navigation Customization

### Header Configuration
1. Go to "Site" → "Header" in Wix Editor
2. Select a header layout that supports:
   - Logo on left
   - Navigation in center/right
   - Clean, minimal design
3. Apply these settings:
   - Background: Navy Blue (#1D3E69)
   - Text/Links: White (#FFFFFF)
   - Active Link: Burnt Orange (#D95F02)
   - Height: 80px (desktop) / 60px (mobile)
   - Logo Height: 50px maximum
   - Padding: 24px horizontal

### Navigation Menu Styling
Configure menu with:
1. Font: Poppins
2. Weight: Medium (500) 
3. Size: 14px
4. Letter Spacing: 0.5px
5. Text Transform: None
6. Hover Effect: Subtle underline or color shift to Burnt Orange
7. Active Page Indicator: Burnt Orange underline or highlight

### Mobile Header Adjustments
Configure mobile header:
1. Collapse points: Set at 768px
2. Hamburger icon: White, right-aligned
3. Mobile menu background: Navy Blue
4. Mobile menu text: White
5. Submenu indicators: White with Burnt Orange hover

### Sticky Header (if supported)
If sticky header is available:
1. Enable sticky header feature
2. Adjust sticky header height: 60px
3. Add subtle shadow on scroll: rgba(0,0,0,0.1) 0 2px 10px
4. Ensure logo resizes appropriately

## Component Styling

### Wix Collection List Styling
For vehicle listings:
1. Go to vehicle collection page
2. Select collection list element
3. Configure:
   - Layout: Grid (3 columns desktop, 2 columns tablet, 1 column mobile)
   - Item Spacing: 24px (desktop) / 16px (mobile)
   - Item Aspect Ratio: 1:1.2 (approximate)
   - Border Radius: 8px
   - Box Shadow: 0 2px 8px rgba(0,0,0,0.05)
   - Hover Effect: Transform scale(1.02) with shadow increase

### Item Card Configuration
Style cards with:
1. Image Container:
   - Aspect Ratio: 4:3
   - Overflow: Hidden
   - Border Radius: 8px 8px 0 0
   
2. Content Container:
   - Background: White
   - Padding: 24px
   - Border Radius: 0 0 8px 8px

3. Typography:
   - Vehicle Name: Card Heading style
   - Details: Small Text style
   - Price: Price Display style

4. Hover Effects:
   - Scale: 1.02
   - Shadow Increase: 0 8px 16px rgba(0,0,0,0.1)
   - Transition: all 0.3s ease

### Dynamic Item Page Styling
For vehicle detail pages:
1. Configure hero section:
   - Full-width image
   - Overlay gradient: rgba(29,62,105,0.7) to transparent
   - Title positioning: Left-aligned, bottom-aligned
   - Padding: 48px bottom

2. Gallery configuration:
   - Gallery type: Grid or Masonry
   - Lightbox enabled
   - Thumbnails: Consistent size
   - Navigation: Custom arrows in Navy/White

3. Content sections:
   - Max width: 1200px
   - Section spacing: 48px vertical
   - Background alternating: White / Peach Cream
   - Dividers: Subtle, 1px #E9ECEF

## Section Backgrounds

### Creating Premium Section Breaks
1. Use Wix Section tools to:
   - Create full-width sections
   - Apply alternating backgrounds
   - Add subtle dividers between sections

2. Configure these background patterns:
   - Hero Sections: Dark image with Navy Blue overlay gradient
   - Feature Sections: White (#FFFFFF)
   - Content Sections: Peach Cream (#FFE2C6)
   - Testimonial Sections: Navy Blue (#1D3E69)
   - Call-to-Action Sections: Navy Blue with subtle pattern

### Section Spacing System
Implement consistent spacing:
1. Section Padding: 80px top/bottom (desktop), 40px (mobile)
2. Inner Section Padding: 48px top