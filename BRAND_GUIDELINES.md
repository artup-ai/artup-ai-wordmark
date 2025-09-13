# Brand Guidelines - Artup AI Wordmark

## 📋 Document Purpose

This document provides comprehensive guidelines for the proper use of Artup AI textual brand elements. These guidelines ensure consistent brand presentation across all platforms and communications.

---

## 🎯 Brand Positioning

### Brand Promise
"Artup AI empowers creativity and productivity for everyone with accessible, intuitive, and innovative AI tools."

### Target Audience
- **Primary**: Creative professionals (designers, writers, artists)
- **Secondary**: Entrepreneurs and small business owners
- **Tertiary**: General consumers interested in AI-powered creativity

### Brand Personality
- **Innovative**: Cutting-edge technology made accessible
- **Empowering**: Enabling users to achieve their creative goals
- **Approachable**: Friendly and non-intimidating AI
- **Reliable**: Consistent, high-quality results

---

## 🔤 Wordmark Specifications

### Primary Wordmark
```
Artup AI
```

**Spacing Rules:**
- Always maintain one space between "Artup" and "AI"
- Never hyphenate: ~~"Artup-AI"~~
- Never combine without space: ~~"ArtupAI"~~ (except in URLs/domains)

### Capitalization Variations

#### Standard Case (Preferred)
```
Artup AI
```

#### All Caps (Headlines/Logos)
```
ARTUP AI
```

#### Lowercase (URLs/Social)
```
artup ai
```

#### Domain Style (Technical)
```
Artup.AI
artup.ai
```

### Minimum Size Requirements
- **Digital**: Minimum 12px font size
- **Print**: Minimum 8pt font size
- **Maintain readability at all sizes**

---

## 🎨 Color Implementation

### Primary Brand Colors

#### Deep Black (Primary)
```css
/* CSS Variables */
--artup-primary: #0D0D0D;

/* RGB */
rgb(13, 13, 13)

/* HSL */
hsl(0, 0%, 5%)

/* CMYK (Print) */
C:0 M:0 Y:0 K:95
```

**Usage:** Core neutral brand anchor for headers, primary CTAs, and foundational UI surfaces; chosen for versatility and theming extensibility.

#### Electric Blue (Accent)
```css
/* CSS Variables */
--artup-accent: #3B82F6;

/* RGB */
rgb(59, 130, 246)

/* HSL */
hsl(217, 91%, 60%)

/* CMYK (Print) */
C:70 M:45 Y:0 K:0
```

**Usage:** Interactive elements, highlights, secondary CTAs

#### Bright Purple (Innovation)
```css
/* CSS Variables */
--artup-secondary: #8B5CF6;

/* RGB */
rgb(139, 92, 246)

/* HSL */
hsl(262, 87%, 66%)

/* CMYK (Print) */
C:55 M:65 Y:0 K:0
```

**Usage:** AI-related content, innovation messaging

### Color Combinations

#### High Contrast Pairings
- **Primary on White**: #0D0D0D on #FFFFFF
- **White on Primary**: #FFFFFF on #0D0D0D
- **Accent on Dark**: #3B82F6 on #0D0D0D (ensure sufficient contrast; passes WCAG AA for normal text)

#### Gradient Applications
```css
/* Primary Gradient */
background: linear-gradient(135deg, #0D0D0D 0%, #3B82F6 100%);

/* AI Theme Gradient */
background: linear-gradient(135deg, #3B82F6 0%, #8B5CF6 100%);

/* Full Brand Spectrum */
background: linear-gradient(135deg, #0D0D0D 0%, #3B82F6 50%, #8B5CF6 100%);
```

### Wordmark Color Usage (Monochrome Standard)

The wordmark itself is intentionally restricted to monochrome usage for consistency, evidence continuity, and future extensibility.

**Primary (Light Backgrounds)**
- Text color: `#0D0D0D` (Deep Black)
- Minimum contrast ratio preferred: 7:1 (must be ≥ 4.5:1)

**Inverse (Dark / Accent Backgrounds)**
- Text color: `#FFFFFF`
- Background must maintain ≥ 4.5:1 contrast vs surrounding interface region

**Not Recommended / Prohibited Treatments**
- Internal gradients or multi-color letter treatments
- Per-letter color cycling
- Outline / stroke pseudo-3D effects
- Texture / image masking fills
- Applying accent colors (Blue / Purple) directly to the full wordmark in standard contexts

**Accent Colors Usage Scope**
- `#3B82F6` and `#8B5CF6` are reserved for: interactive states, feature emphasis zones, AI-related UI modules, highlight elements (buttons, links, badges)
- They are not used as the primary wordmark fill in baseline branding

**Rationale**
Maintaining a neutral, single-color core:
1. Ensures stable recognition across themes and surfaces
2. Prevents premature chromatic lock-in before symbol/logomark introduction
3. Simplifies accessibility contrast validation
4. Preserves accent palette semantic clarity

**Implementation Tip**
When placing the wordmark over imagery, apply either: (a) a subtle overlay scrim (e.g., 40–60% black on image) for black text, or (b) a dark gradient / soft shadow for white text to preserve legibility.


---

## 📝 Typography System

### Font Hierarchy

#### Primary Typeface: Inter
```css
font-family: "Inter", -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
```

**Characteristics:**
- Modern, clean, highly legible
- Excellent for digital applications
- Wide range of weights available
- Optimized for UI/UX

#### Fallback System Fonts
```css
/* macOS */
font-family: "SF Pro Display", "SF Pro Text", system-ui;

/* Windows */
font-family: "Segoe UI", system-ui;

/* Universal Fallback */
font-family: system-ui, -apple-system, sans-serif;
```

### Font Weight Usage

| Weight | Value | Usage | Example |
|--------|-------|-------|---------|
| Light | 300 | Large display text | Hero headlines |
| Regular | 400 | Body text, paragraphs | Content areas |
| Medium | 500 | Emphasized text | Subheadings |
| Semibold | 600 | Section headers | Card titles |
| Bold | 700 | Strong emphasis | Important CTAs |

### Typography Scale

```css
/* Display (Hero) */
font-size: 3.5rem; /* 56px */
line-height: 1.1;
font-weight: 300;

/* Heading 1 */
font-size: 2.5rem; /* 40px */
line-height: 1.2;
font-weight: 600;

/* Heading 2 */
font-size: 2rem; /* 32px */
line-height: 1.25;
font-weight: 600;

/* Heading 3 */
font-size: 1.5rem; /* 24px */
line-height: 1.3;
font-weight: 500;

/* Body Large */
font-size: 1.125rem; /* 18px */
line-height: 1.6;
font-weight: 400;

/* Body Regular */
font-size: 1rem; /* 16px */
line-height: 1.6;
font-weight: 400;

/* Body Small */
font-size: 0.875rem; /* 14px */
line-height: 1.5;
font-weight: 400;

/* Caption */
font-size: 0.75rem; /* 12px */
line-height: 1.4;
font-weight: 400;
```

---

## 💬 Messaging Framework

### Core Messages

#### Primary Value Proposition
"Artup AI empowers creativity and productivity for everyone with accessible, intuitive, and innovative AI tools."

#### Key Benefits
1. **Accessibility**: Advanced AI made simple for everyone
2. **Creativity**: Enhance and amplify creative potential
3. **Productivity**: Streamline creative workflows
4. **Innovation**: Cutting-edge technology, practical applications

### Tagline Variations

#### Primary Tagline
```
"Empowering creativity and productivity for everyone"
```

#### Context-Specific Taglines
- **Product Launch**: "Turn ideas into reality with AI"
- **Marketing**: "Where creativity meets artificial intelligence"
- **Community**: "Democratizing creativity through AI"
- **Technical**: "Accessible, intuitive, innovative AI tools"

### Tone of Voice

#### Brand Personality Traits
- **Innovative** but not intimidating
- **Professional** but approachable
- **Confident** but humble
- **Empowering** but supportive

#### Communication Guidelines
- Use active voice and present tense
- Focus on user benefits, not features
- Avoid technical jargon unless necessary
- Celebrate user achievements and creativity
- Maintain optimistic and encouraging tone

---

## 🚫 Usage Restrictions

### Don't Do This
- ❌ Alter spacing: ~~"ArtupAI"~~ or ~~"Artup-AI"~~
- ❌ Use non-approved colors
- ❌ Combine with competitor brand elements
- ❌ Use in ways that imply endorsement without permission
- ❌ Modify typography proportions or tracking
- ❌ Use low-contrast color combinations

### Do This
- ✅ Maintain consistent spacing: "Artup AI"
- ✅ Use approved color palette
- ✅ Follow typography guidelines
- ✅ Ensure adequate contrast ratios
- ✅ Test readability at various sizes
- ✅ Keep brand elements clean and uncluttered

---

## 📐 Technical Specifications

### Digital Applications
- **Minimum font size**: 12px
- **Line height**: 1.4-1.6 for body text
- **Color contrast**: Minimum 4.5:1 for accessibility
- **Touch targets**: Minimum 44px for interactive elements

### Print Applications
- **Minimum font size**: 8pt
- **Resolution**: 300 DPI minimum
- **Color mode**: CMYK for print, RGB for digital
- **Bleed area**: 3mm for printed materials

---

## 📞 Contact Information

For brand usage questions or licensing inquiries:
- **Repository**: https://github.com/artup-ai/artup-ai-wordmark
- **Documentation**: See README.md and CHANGELOG.md
- **Legal Questions**: legal@artup.ai
- **Usage Policy**: See TRADEMARK_POLICY.md for permitted / restricted usage definitions

---

*Guidelines version 1.0 - Established September 13, 2025*