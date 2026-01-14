# SQL Designer

> Visual database schema builder with smart import, auto-layout, and phpMyAdmin-level control.

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![No Dependencies](https://img.shields.io/badge/dependencies-none-green.svg)](/)
[![Single File](https://img.shields.io/badge/file-single%20HTML-orange.svg)](/)

## Why SQL Designer?

**Stop writing SQL by hand.** Design visually, export instantly.

- 🎯 **Import existing databases** - Paste SQL, get instant visual layout
- 🎨 **Drag-and-drop everything** - Tables, fields, relationships
- 🚀 **Auto-arrange** - Smart grid layout for clean schemas
- 💾 **Export production SQL** - Ready for MySQL/MariaDB
- ⚡ **Zero setup** - Open HTML file, start designing

## Core Features

### Smart Import/Export
```sql
-- Paste your CREATE TABLE statements
-- Get organized visual schema instantly
-- Modify visually, export back to SQL
```

**Import**: Upload .sql or paste code → Auto-arranged grid layout  
**Export**: Customize options → Production-ready SQL script

### Visual Design

- **Auto-Arrange**: Perfect grid layout with one click
- **Drag & Drop**: Position tables anywhere on infinite canvas
- **Relationships**: Visual lines between foreign keys
- **Zoom Controls**: In, out, reset view
- **Dark Theme**: Easy on the eyes for long sessions

### Complete Database Control

**Tables**
- InnoDB, MyISAM, Memory, Archive, CSV engines
- utf8mb4, collations, row formats, AUTO_INCREMENT
- Comments and full documentation

**Fields** (30+ types)
- INT, VARCHAR, TEXT, BLOB, JSON, ENUM, spatial types
- UNSIGNED, ZEROFILL, NULL/NOT NULL
- DEFAULT values, ON UPDATE triggers
- PRIMARY KEY, UNIQUE, INDEX

**Advanced**
- Foreign keys with CASCADE, RESTRICT, SET NULL
- Composite indexes (FULLTEXT, SPATIAL)
- Multi-field primary keys
- Named constraints

## Quick Start

**Create new schema:**
```
1. Open sql-designer.html
2. Click "New Table"
3. Add fields, set properties
4. Export SQL
```

**Import existing:**
```
1. Click "Import SQL"
2. Paste CREATE TABLE code
3. Tables auto-arranged in grid
4. Modify and export
```

## Interface

```
┌─────────────┬──────────────────────┬─────────────────┐
│   Sidebar   │       Canvas         │  Properties     │
│             │                      │                 │
│ New Table   │  [Table] [Table]     │  Table Name     │
│             │         ↓↓           │  Engine         │
│ Tables      │  [Table] [Table]     │  Fields         │
│  • users    │                      │   • id          │
│  • orders   │  Auto-Arrange        │   • name        │
│             │  Zoom In/Out         │                 │
│ Import SQL  │                      │  Foreign Keys   │
│ Export SQL  │                      │  Indexes        │
└─────────────┴──────────────────────┴─────────────────┘
```

## Tech Stack

- Pure vanilla JavaScript
- Single HTML file
- Zero dependencies
- localStorage persistence
- Works offline

## Perfect For

- Database architects designing complex schemas
- Developers prototyping new projects
- Teams collaborating on database structure
- Students learning SQL relationships
- Anyone who needs visual schema tools

## Browser Support

Chrome, Firefox, Safari, Edge (any modern browser)

## License

MIT - Free for personal and commercial use

---

**Built by [David Sangouard](https://github.com/davidsangouard)**  
*Architect of digital solutions*
