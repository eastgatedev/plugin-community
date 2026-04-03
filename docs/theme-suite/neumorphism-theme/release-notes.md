# Release Notes - Neumorphism Theme Collection

> 🌐 **Language / 语言**: [🇺🇸 English](release-notes.md) | [🇨🇳 简体中文](release-notes.zh.md)

## Version 2025.2.2 <small>(2026-04-03)</small>

**Full Web Stack Semantic Highlighting** — 110 new attributes covering JavaScript, TypeScript, HTML, XML, CSS, SASS/SCSS, and Angular across all 11 themes.

### JavaScript & TypeScript (50 attributes)

Semantic highlighting now covers the complete JS/TS surface area that IntelliJ exposes:

- **Variables:** local variables, parameters, global variables, exported variables — each visually distinct
- **Functions:** local functions, global functions, exported functions — with exported symbols rendered **bold** to signal public API boundaries at a glance
- **Classes & Types:** class names, interfaces, type aliases, type parameters, enums, enum members, type guards (TypeScript)
- **Members:** instance and static member functions, instance and static member variables
- **React/JSX/TSX:** JSX client components get dedicated highlighting; works in `.jsx`, `.tsx`, and inline JSX in `.ts`
- **Other:** decorators, module names, primitive types, regexp literals, labels, JSDoc tags and type paths

**Cross-language consistency:** decorators in JS/TS use the same palette slot as annotations in Kotlin and Java. Exported symbols are bold in both JS and TS, making public API surface immediately visible without reading the code.

### HTML, XML, CSS & SASS/SCSS (50 attributes)

**HTML (5):** tag names, attribute names, attribute values, custom elements, entity references.

**XML (7):** tag names, attribute names, attribute values, custom elements, namespace prefixes, entity references, XML prologue.

**CSS (15):** property names, class selectors, tag selectors, ID selectors, pseudo-classes, functions, `!important`, keywords, values, URLs, color values, unit values, attribute selectors, `&` parent selector.

**SASS/SCSS (23):** variables, property names, identifiers, tag/class/ID selectors, mixins, functions, `@if`/`@each`/`@for` keywords, `!important`, value colors, pseudo-classes, URLs, units, `@extend`, interpolation `#{}`, `!default`/`!global`/`!optional` flags, `&` parent selector.

### Angular (10 attributes)

Comprehensive Angular template semantic highlighting — the most complete Angular coverage available in any IntelliJ theme:

- **Signals (Angular 16+):** signal reads and writes distinguished from regular variables
- **Template variables:** `#templateRef` variable declarations
- **Bindings:** two-way `[(ngModel)]`, event `(click)`, property `[value]` — each binding type gets a distinct color
- **Structural directives:** `*ngIf`, `*ngFor`
- **Control flow (Angular 17+):** new `@if`, `@for`, `@switch` block syntax
- **Interpolation:** `{{ }}` delimiters highlighted separately from the expression content
- **::ng-deep:** pseudo-element for component style encapsulation

### Platform & Compatibility

- **Kotlin:** Added `KOTLIN_CONTEXT_ARGUMENT` (new in IntelliJ 2026.1) for context receiver highlighting
- **Build range:** `sinceBuild` updated from 241 to 251 (IntelliJ 2025.1+)
- Legacy XML/CSS attribute entries corrected to current dot-notation names used by IntelliJ

### Quality

- **1,210 new XML entries** — 110 attributes x 11 themes
- **2,317 validated attribute-color pairs** — up from 1,096 in 2025.2.1
- **100% WCAG AA** — 363/363 contrast tests pass across all 11 themes
- **0 consistency mismatches** — all themes share the same structural palette logic
- **Zero performance impact** — uses IntelliJ's built-in color scheme system, no custom annotators

### Languages Now Covered

| Language | Attributes |
|---|---|
| Kotlin | 65 |
| Java | 34 |
| JavaScript / TypeScript | 50 (shared + TS-unique) |
| SASS / SCSS | 23 |
| CSS | 15 |
| XML | 7 |
| HTML | 5 |
| Angular | 10 |
| Foundation | 32 |
| **Total** | **241** |

---

## Version 2025.2.1 <small>(2026-02-09)</small>

**Java Semantic Highlighting** - 34 dedicated Java attributes across all 11 themes.

### Java Attributes by Category (34 total)
- **Fields (7):** instance field, static field, static final field, enum constant, parameter, local variable, reassigned local variable
- **Methods (8):** method call, method declaration, static method call, static method declaration, constructor call, constructor declaration, abstract method, inherited method
- **Types (8):** class name, abstract class, interface, enum, annotation type, type parameter, generic type, record class
- **Annotations (2):** annotation name, annotation attribute
- **Visibility Modifiers (4):** public, protected, package-private, private
- **Other (5):** import statement, label, doc comment tag, doc comment tag value, doc markup

### Smart Font Styles
- **Bold** for declarations and constants
- **Italic** for static members, abstract methods, and interfaces
- **Underline** for reassigned variables

### Quality
- **130 total semantic attributes**: Kotlin (64) + Java (34) + Foundation (32)
- **100% WCAG AA validated**: All 363 Java attribute tests passed across 11 themes
- **11 unique Java palettes**: Every theme gets distinct, professionally designed Java colors
- **Zero performance impact**: Uses IntelliJ built-in color scheme system, no custom annotators

## Version 2025.2.0 <small>(2026-01-10)</small>

- **Production-Ready Semantic Highlighting** - 96 total attributes across all 11 themes
- **64 Kotlin Attributes** - Comprehensive coverage for modern Kotlin development
- **32 Foundation Attributes** - Cascade to all languages (Java, Python, JavaScript, etc.)
- **11 Unique Semantic Palettes** - Professionally designed per theme
- **100% WCAG AA Compliance** - Color-blind validated
- **Zero Performance Impact** - No custom annotators
- **Improved Trial Messaging** - Warmer, indie-friendly notifications

## Version 2025.1.0 <small>(2025-10-04)</small>

- **🎨 11 Premium Neumorphism Themes:** Complete collection with soft shadows and 3D depth effects designed for extended coding sessions
- **👁️ Eye-Friendly Design Philosophy:** WCAG AAA compliant color contrasts with neumorphic soft shadows to reduce eye strain during 8+ hour coding marathons
- **🆓 3 Free Themes Forever:** Ocean Breeze, Classic Plus, and Deep Space - no strings attached, no trial limits
- **💎 8 Premium Themes:** Arctic Frost, Rose Gold, Forest, Lavender, Midnight, Recording Studio, Recording Studio Live, and Sunset
- **⏱️ Silent Discovery Trial System:** 30-minute taste test for all premium themes without interruptions or popup spam
- **💰 One-Time Payment Forever:** $5 (Individual) / $10 (Organization) gets you lifetime access to all 8 premium themes - no subscription fatigue, no renewal fees
- **🎯 Professional Trial Experience:** Clean, respectful trial system with non-intrusive timer in settings and tool window
- **🌈 Diverse Visual Aesthetics:** From calming ocean blues to energetic sunset oranges - find your perfect coding vibe
- **♿ Accessibility First:** Every theme tested against WCAG AAA standards for text readability and color blindness compatibility
- **🚀 IntelliJ 2025.1+ Support:** Built on the latest platform APIs for optimal performance and compatibility
- **⚡ Instant Theme Switching:** Switch between themes seamlessly through IDE settings or dedicated tool window
- **🎨 Complete IDE Coverage:** Consistent neumorphic design across editor, UI components, tool windows, and dialogs

**Revolutionary Design for Developers:** No more harsh flat UIs or eye-burning color schemes. Neumorphism brings soft, tactile depth to your IDE with gentle shadows that make your workspace feel alive while keeping your eyes comfortable. Try all 8 premium themes risk-free for 30 minutes each, then unlock them forever for the price of a fancy coffee!

## What is Neumorphism?

**Neumorphism** (soft UI design) creates subtle 3D effects through carefully calculated shadows and highlights that make UI elements appear to rise from or sink into the background. Unlike harsh flat design or heavily shadowed material design, neumorphism provides gentle visual depth that:

- **Reduces Eye Strain:** Soft shadows create natural depth perception without harsh contrasts
- **Enhances Focus:** Subtle elevation helps distinguish active elements without visual noise
- **Feels Tactile:** Elements appear touchable and responsive, improving spatial awareness
- **Looks Professional:** Modern aesthetic that feels polished without being overwhelming

For developers spending 8+ hours staring at code, neumorphism's gentle approach to visual hierarchy means less eye fatigue and more comfortable long coding sessions.

## Theme Showcase

### Free Themes (Always Yours)

**🌊 Ocean Breeze**
- Soft ocean blues and seafoam greens
- Calming palette perfect for focused work
- Light theme with gentle wave-like depth

**🌟 Classic Plus**
- Enhanced version of classic IntelliJ light theme
- Familiar comfort with neumorphic refinement
- Professional and universally readable

**🌌 Deep Space**
- Dark theme with cosmic depth
- Deep purples and midnight blues
- Perfect for late-night coding sessions

### Premium Themes ($5 Individual / $10 Organization - Unlocks All 8 Forever)

**❄️ Arctic Frost**
- Cool whites and icy blues
- Crisp, clean, minimalist aesthetic
- High-contrast readability with soft depth

**🌸 Rose Gold**
- Warm rose and champagne tones
- Elegant and stylish workspace
- Reduces blue light exposure

**🌲 Forest**
- Natural greens and earth tones
- Organic, grounded coding environment
- Eye-friendly natural color palette

**💜 Lavender**
- Soft purples and gentle violets
- Creative and inspiring atmosphere
- Balances warmth and coolness

**🌙 Midnight**
- True dark theme with deep blacks
- Maximum contrast for OLED displays
- Late-night coding perfection

**🎵 Recording Studio**
- Professional dark theme inspired by audio workstations
- Optimized for focus and precision
- Sophisticated charcoal and silver tones

**🎸 Recording Studio Live**
- Variant with warmer accent colors
- Energetic while maintaining professionalism
- Perfect for creative coding sessions

**🌅 Sunset**
- Warm oranges and coral tones
- Energizing and vibrant atmosphere
- Golden hour coding vibes

## Trial System Features

**30-Minute Taste Test Per Theme:**
- Try each premium theme individually for 30 minutes
- No interruptions during trial - code in peace
- Timer visible only in settings and tool window
- Seamlessly switches to free themes when trial expires
- All trial periods are independent - try all 8 themes risk-free

**Professional Experience:**
- No popup spam or countdown overlays
- Silent countdown respects your flow state
- Clear messaging about trial status
- One-click purchase to unlock forever
- Instant activation after purchase

## Accessibility & Standards

**WCAG AAA Compliance:**
- All text meets 7:1 contrast ratio standards
- Tested across common color vision deficiencies
- Readable for developers with visual impairments
- Professional accessibility without compromising aesthetics

**Eye Health Features:**
- Reduced blue light in warm themes (Rose Gold, Sunset)
- Optimized contrast prevents eye strain
- Soft shadows reduce harsh visual boundaries
- Multiple brightness options (light/dark themes)

## Platform Compatibility

- **IntelliJ IDEA:** 2025.1+
- **Android Studio:** 2025.1+
- **PyCharm:** 2025.1+
- **WebStorm:** 2025.1+
- **PhpStorm:** 2025.1+
- **All JetBrains IDEs:** 2025.1+ with Java 17 runtime

## What's Next?

**Planned Future Enhancements:**
- Python semantic highlighting
- Additional theme color variations
- Customization options for shadow intensity
- Community-requested color schemes

**Community Feedback Welcome:**
Share your favorite themes, request new color schemes, or suggest improvements at eastgate3194@gmail.com
