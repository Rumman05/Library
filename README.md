# Personal Library Manager

A beautiful, brutalist-style library management app to track your personal book collection with a bold, modern design.

## What it does

- Add books with title, author, page count, optional description, and reading status
- View all your books displayed as stylish cards with a distinctive brutalist aesthetic
- Toggle read/unread status with dedicated buttons on each book
- Remove books from your collection
- Responsive grid layout that adapts to different screen sizes

## How to use

1. Open `index.html` in your browser
2. Click "Add New Book" in the header to add a book
3. Fill out the form with book details (description is optional)
4. Click "Add Book" to save it to your library
5. Use the yellow "Mark as Read/Unread" button to toggle reading status
6. Use the pink "Remove Book" button to delete books from your collection

## Features

- **Bold brutalist design** with thick borders, drop shadows, and vibrant colors
- **Responsive layout** that works beautifully on desktop, tablet, and mobile
- **Modal dialog** for adding new books with smooth animations
- **Unique book IDs** generated using `crypto.randomUUID()`
- **Prototype-based functionality** for toggling read status
- **Space Mono font** for a distinctive monospace aesthetic
- **Sticky header** that stays visible while scrolling
- **Local storage persistence** - your library is automatically saved and restored between browser sessions

## Design Credits

The card design is inspired by the brutalist/neubrutalism web design trend, featuring bold borders, vibrant colors (yellow, pink, black), and distinctive drop shadows that create a modern, eye-catching aesthetic.

Original: https://codepen.io/rustcode/pen/MYYMrVQ

## Built with

- **HTML5** with semantic elements and modern dialog API
- **CSS3** with Grid layout, custom properties, and smooth transitions
- **Vanilla JavaScript** with ES6+ features and prototype methods
- **Google Fonts** (Space Mono) for typography
- No frameworks or libraries required

## Browser Support

- Modern web browsers (Chrome 88+, Firefox 78+, Safari 14+, Edge 88+)
- Requires support for:
  - `crypto.randomUUID()`
  - HTML `<dialog>` element
  - CSS Grid
  - ES6+ JavaScript features
  - `localStorage` API for data persistence

## Files

- `index.html` - Complete single-file application with embedded CSS and JavaScript

## Installation

No installation required! Simply:

1. Download or clone this repository
2. Open `index.html` in any modern web browser
3. Start building your personal library

## Future Enhancements

Potential features to add:
- ~~Local storage persistence~~ ✅ **Completed**
- Book search and filtering
- Reading progress tracking
- Book ratings and reviews
- Export/import functionality
- Dark mode toggle
- Data backup and sync across devices

---

*Built as a learning project to practice DOM manipulation, CSS design, and JavaScript prototypes.*