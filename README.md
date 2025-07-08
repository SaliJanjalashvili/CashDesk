# MoneyMate - Banking Dashboard

A responsive banking dashboard built with pure HTML and CSS, featuring modern design, dark/light theme toggle, and mobile-first responsive design.

## Features

### 🏦 Dashboard Page (`index.html`)

- **User Profile Section**: Displays user information with profile picture and details
- **Account Overview**: Shows multiple bank accounts (Primary, Savings, Credit Card) with balances
- **Spending Tracker**: Visual progress bar showing monthly spending with category breakdown
- **Quick Actions**: Easy access buttons for common banking operations

### 💳 Transactions Page (`transactions.html`)

- **Transaction History**: Comprehensive list of all transactions with dates, amounts, and categories
- **Search & Filter**: Search transactions and filter by account, category, or date range
- **Transaction Categories**: Visual icons for different transaction types (Food, Shopping, Transportation, etc.)
- **Load More**: Pagination-style loading for better performance

### 🎨 Design Features

- **Responsive Design**: Optimized for desktop, tablet, and mobile devices
- **Dark/Light Theme**: Toggle between themes with smooth transitions
- **Modern UI**: Clean, professional design with subtle shadows and gradients
- **Accessibility**: Proper focus states, reduced motion support, and semantic HTML
- **Icons**: Emoji-based icons for better visual hierarchy

## File Structure

```
firstTask/
├── index.html          # Main dashboard page
├── transactions.html   # Transaction history page
├── styles.css         # Complete styling with responsive design
└── README.md          # This file
```

## Getting Started

1. **Clone or download** the project files
2. **Open `index.html`** in your web browser to view the dashboard
3. **Navigate** between pages using the navigation menu
4. **Toggle theme** using the sun/moon switch in the top navigation

## Responsive Breakpoints

- **Desktop**: 1200px and above (full layout)
- **Tablet**: 768px - 1199px (adjusted grid layouts)
- **Mobile**: 480px - 767px (single column, stacked elements)
- **Small Mobile**: Below 480px (compact spacing, minimal UI)

## Browser Support

- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## Technical Details

### CSS Features Used

- **CSS Custom Properties (Variables)**: For theme switching and consistent design tokens
- **CSS Grid**: For responsive layouts and card arrangements
- **Flexbox**: For component alignment and navigation
- **Media Queries**: For responsive design across devices
- **CSS Transitions**: For smooth theme switching and hover effects
- **Pseudo-elements**: For decorative elements and theme toggle functionality

### No JavaScript Required

The entire project works without JavaScript, including:

- Theme switching (CSS-only using checkbox hack)
- Responsive navigation
- Interactive elements (hover states, focus states)
- Form styling and interactions

## Customization

### Colors

Edit the CSS custom properties in `:root` to change the color scheme:

```css
:root {
  --primary-color: #2563eb;
  --secondary-color: #1e40af;
  --success-color: #059669;
  /* ... more color variables */
}
```

### Content

- Update user information in the HTML files
- Modify account balances and transaction data
- Add or remove transaction categories
- Customize spending categories and amounts

### Layout

- Adjust grid layouts in `.accounts-grid` and `.actions-grid`
- Modify spacing using the CSS custom properties
- Change component sizes and proportions

## Performance Optimizations

- **Minimal CSS**: Optimized selectors and efficient property usage
- **System Fonts**: Uses system font stack for better performance
- **Efficient Animations**: Hardware-accelerated transforms and opacity changes
- **Responsive Images**: Emoji icons instead of image files
- **Print Styles**: Optimized for printing financial documents

## Accessibility Features

- **Semantic HTML**: Proper heading hierarchy and landmark elements
- **Focus Management**: Visible focus indicators for keyboard navigation
- **Color Contrast**: WCAG AA compliant color combinations
- **Reduced Motion**: Respects user's motion preferences
- **Screen Reader Support**: Proper labels and ARIA attributes where needed

## Future Enhancements

While this project uses only HTML and CSS, potential JavaScript enhancements could include:

- Real-time data updates
- Interactive charts and graphs
- Advanced filtering and search
- Form validation
- Local storage for theme preferences
- Progressive Web App features

## Credits

- **Design Inspiration**: Modern banking apps and financial dashboards
- **Icons**: Unicode emoji for universal compatibility
- **Typography**: System font stack for optimal readability
- **Color Palette**: Carefully selected for accessibility and modern aesthetics

---

**Note**: This is a demonstration project for educational purposes. Do not use with real financial data or in production environments without proper security measures.
