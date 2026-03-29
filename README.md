# Hieroglyphica

## Project Overview
Hieroglyphica is a web-based application designed to explore and display ancient Egyptian hieroglyphics. This project provides an interactive interface for users to learn about and engage with one of the world's oldest writing systems.

## Author & Developer
**Alaa Mohammed Eltantawy**  
📧 Phone: +20 112 224 9208

## Features

### 🎨 **Core Editing Features**
- **140+ Ancient Egyptian Hieroglyphs** - Comprehensive library organized by categories (People, Animals, Nature, Objects, Signs & Symbols, Numerals)
- **Visual Canvas Editor** - Real-time WYSIWYG editing of hieroglyphic compositions
- **MdC Notation Support** - Text-based editor using Manchester University Digraphic Code standard
- **Grouping System**:
  - Horizontal Groups (H-Group) - Side-by-side arrangement
  - Vertical Groups (V-Group) - Stacked arrangement
  - Ligatures - Overlapping combined glyphs
- **Royal Cartouches** - Create traditional oval name cartouches
- **Advanced Selection** - Multi-select with Ctrl+click for group operations

### 🎯 **Formatting Tools**
- **Color Customization**:
  - Color picker with custom presets
  - Quick paint tools (Red, Gold, White, Green, Blue)
  - Apply colors to individual glyphs or selections
- **Size Control**:
  - Global size slider (16px - 120px)
  - Individual glyph scaling up/down
  - Per-glyph size properties
- **Shade Zones (JSesh-compatible)**:
  - Gray unreadable zones
  - Red highlight zones
  - Blue shade zones
  - Gold highlights
- **Layout Controls**:
  - Adjustable spacing between glyphs
  - Alignment options (Left, Center, Right, Spread)

### 📋 **Clipboard Operations**
- Cut, Copy, Paste functionality
- Duplicate selected glyphs
- Rich text export for Word/Pages integration
- Drag-and-drop support

### ↩️ **History Management**
- Full undo/redo system (80+ steps history)
- Non-destructive editing workflow

### 🔍 **Symbol Library**
- Searchable database of 140+ glyphs
- Category-based organization
- Recent glyphs quick access panel
- Real-time filtering

### 💾 **Export Options**
- PNG image export (high-quality rendering)
- Rich text copy for Word processing software
- Direct clipboard integration

### ⌨️ **Keyboard Shortcuts**
Comprehensive shortcut system for power users:
- Navigation: Arrow keys, Esc, Ctrl+A
- History: Ctrl+Z (Undo), Ctrl+Y (Redo)
- Clipboard: Ctrl+X/C/V/D (Cut/Copy/Paste/Duplicate)
- Grouping: Ctrl+G (H-Group), Ctrl+Shift+G (V-Group), Ctrl+K (Cartouche)
- Formatting: Ctrl+P (Paint), Ctrl+[/] (Scale), Ctrl+E (Export)
- Movement: Shift+Arrow keys

### 🖼️ **User Interface**
- Professional ribbon-style toolbar
- Collapsible side panels
- Properties inspector panel
- Real-time status bar with token count and selection info
- Toast notifications for user feedback
- Dark theme with gold accents inspired by ancient Egyptian aesthetics
- Fully responsive design

## Technologies Used
- **HTML5** - Semantic structure and canvas rendering
- **CSS3** - Advanced styling with CSS Grid, Flexbox, custom properties
- **Vanilla JavaScript** - No frameworks, pure ES6+ implementation
- **Google Fonts Integration**:
  - Cinzel Decorative (headings)
  - Cinzel (UI text)
  - JetBrains Mono (code/properties)
  - Noto Sans Egyptian Hieroglyphs (glyph rendering)

## Getting Started

### Installation
No installation required! This is a standalone web application.

### Running the Application
1. Navigate to your project folder: `c:\Users\Alaa\OneDrive\Desktop\hieroglyphica`
2. Open `hieroglyphica-v3.html` in any modern web browser:
   - Google Chrome (recommended)
   - Microsoft Edge
   - Firefox
   - Safari

### Quick Start Tutorial

#### Adding Your First Glyphs
1. **Browse the Symbol Library** on the left panel
2. **Click any glyph** to add it to the canvas
3. **Use the search bar** to find specific symbols
4. **Filter by category** using the category tabs

#### Creating Compositions
1. **Add multiple glyphs** by clicking them in sequence
2. **Select glyphs** by clicking on them (they'll highlight)
3. **Multi-select** by holding Ctrl while clicking
4. **Group horizontally**: Select 2+ glyphs → Click "H-Group" or press `Ctrl+G`
5. **Group vertically**: Select 2+ glyphs → Click "V-Group" or press `Ctrl+Shift+G`
6. **Create a cartouche**: Select glyphs → Click "Cartouche" or press `Ctrl+K`

#### Formatting Your Work
1. **Change color**: 
   - Pick a color from the color picker
   - Select glyphs you want to paint
   - Click "Paint" button or press `Ctrl+P`
   
2. **Resize glyphs**:
   - Use the global Size slider in the toolbar
   - Or select individual glyphs and use Scale+/Scale− buttons
   
3. **Adjust spacing**: Use the Spacing slider to control gaps between glyphs

4. **Add shade zones**: Select glyphs and click one of the shade zone buttons (Gray/Red/Blue/Gold)

#### Using the Text Editor (MdC Notation)
The editor panel supports text-based entry:
- `[A+B]` = Horizontal group (A next to B)
- `[A/B]` = Vertical group (A over B)
- `[A*B]` = Ligature (A overlapping B)
- `(A B C)` = Cartouche containing A, B, C
- `_` = Spacer symbol
- New line = Line break

Type directly in the editor and click "Apply to Canvas" or press `Ctrl+Enter`

#### Exporting Your Work
- **As PNG Image**: Click "PNG" button or press `Ctrl+E`
- **For Word Documents**: Click "→Word" button or press `Ctrl+Shift+C`, then paste into Word/Pages

### Advanced Features

#### Group Edit Mode
1. Select a group or cartouche
2. Click "Edit Group" or double-click the group
3. Edit individual child elements within the group
4. Click "Exit Group Edit" or press Esc when done

#### Working with Layers
- Groups can contain other groups (nested structures)
- Each level can be edited independently
- Use the status bar to see your current editing level

#### Efficient Workflow Tips
- Use keyboard shortcuts extensively for faster work
- Keep the Properties panel open for quick adjustments
- Use the Recent glyphs panel for frequently used symbols
- Save your work regularly by exporting as PNG

## License
This project is proprietary software developed by Alaa Mohammed Eltantawy. All rights reserved.

## Contact
For inquiries or support, please contact the developer at the phone number provided above.

---
*Developed with passion for preserving and sharing ancient Egyptian heritage*
