# Data Visualization Dashboard

A comprehensive, interactive web application for visualizing CSV data as charts and hierarchical data (JSON, XML, RDF) as tree structures.

## Features

### 📈 CSV Data Visualization

- **File Upload**: Drag-and-drop or click to upload CSV files
- **Summary Statistics**: Displays total rows, columns, numeric columns, and calculated averages
- **Interactive Charts**:
  - **Bar Chart**: Visual representation of numeric data by categories
  - **Line Chart**: Shows trends across data points
  - **Pie Chart**: Distribution visualization with percentages and legend
- **Data Filters**:
  - Dropdown filter by first column values
  - Real-time search across all columns
- **Data Table**: Displays all CSV data in a structured table format
- **Export/Import**: Export filtered data back to CSV format

### 🌳 Tree Visualization

- **Multi-Format Support**: Upload and visualize JSON, XML, and RDF files
- **Hierarchical Display**: 
  - Expandable/collapsible tree nodes
  - Visual indicators for data types (Object, Array, values)
  - Nested structure visualization
- **Tree Controls**:
  - Expand All / Collapse All buttons
  - Search/filter functionality to find specific nodes
- **XML Support**: Properly handles XML attributes and text content
- **RDF Support**: Parses RDF/Turtle format triples
- **Export**: Save tree data as JSON

## Quick Start

Simply open `data-visualization-dashboard.html` in any modern web browser. No build process or dependencies required!

```bash
# Open in your default browser
open data-visualization-dashboard.html

# Or use a local server
python -m http.server 8000
# Then navigate to http://localhost:8000/data-visualization-dashboard.html
```

## Usage Guide

### CSV Visualization

1. Click the "CSV Charts" tab
2. Upload a CSV file using drag-and-drop or file picker
3. View automatic summary statistics
4. Use filters to narrow down data:
   - Select specific values from the dropdown
   - Search across all columns with the search box
5. Interact with the generated charts
6. Export filtered data if needed

### Tree Visualization

1. Click the "Tree Visualization" tab
2. Upload a JSON, XML, or RDF file
3. Use "Expand All" to view the entire structure
4. Click individual nodes to expand/collapse them
5. Use the search box to filter nodes
6. Export the structure as JSON

## Accessibility Features

The dashboard is built with accessibility in mind:

- ✅ ARIA labels and roles throughout the interface
- ✅ Keyboard navigation support (arrow keys for tabs, Enter/Space for actions)
- ✅ Focus management with visible focus indicators
- ✅ Semantic HTML structure
- ✅ High contrast mode support
- ✅ Screen reader friendly announcements
- ✅ Proper heading hierarchy
- ✅ Alternative text for visual elements

## Technology Stack

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with gradients, flexbox, and grid
- **Vanilla JavaScript**: No frameworks, pure ES6+
- **SVG**: Custom charts without external libraries

## Browser Support

Works in all modern browsers:
- Chrome/Edge (latest 2 versions)
- Firefox (latest 2 versions)
- Safari (latest 2 versions)
- Opera (latest 2 versions)

## Example Data Formats

### CSV Format
```csv
Product,Sales,Revenue,Region
Laptop,150,45000,North
Phone,280,28000,South
Tablet,95,19000,East
```

### JSON Format
```json
{
  "company": {
    "name": "Tech Corp",
    "departments": [
      {
        "name": "Engineering",
        "employees": 50
      }
    ]
  }
}
```

### XML Format
```xml
<?xml version="1.0" encoding="UTF-8"?>
<library>
  <book id="1">
    <title>JavaScript Guide</title>
    <author>John Doe</author>
  </book>
</library>
```

### RDF Format (Turtle)
```turtle
@prefix ex: <http://example.org/> .

ex:Person1 ex:name "Alice" .
ex:Person1 ex:age "30" .
```

## File Structure

```
data-visualization-dashboard.html  # Single-file application
```

## Features Breakdown

### CSV Tab
- File upload with validation
- Automatic data parsing
- Statistical calculations
- Dynamic chart generation (SVG-based)
- Real-time filtering
- Responsive data table

### Tree Tab
- Multi-format file parsing (JSON, XML, RDF)
- Recursive tree rendering
- Interactive node expansion
- Search functionality
- Data type annotations

## Design Principles

1. **Self-contained**: No external dependencies or build process
2. **Accessible**: WCAG compliant with proper ARIA labels
3. **Responsive**: Works on desktop and mobile devices
4. **Interactive**: Real-time filtering and updates
5. **Visual**: Clear, professional design with gradients and animations

## Customization

The application uses CSS custom properties and can be easily customized by modifying the styles in the `<style>` section:

- Colors: Gradient backgrounds, chart colors, text colors
- Spacing: Padding and margin values
- Typography: Font families, sizes, and weights
- Breakpoints: Mobile responsive design triggers

## Performance

- Lightweight: No external libraries loaded
- Fast rendering: Efficient SVG chart generation
- Optimized DOM manipulation
- Minimal memory footprint

## Security

- Client-side only processing (no server uploads)
- No external API calls
- Safe file parsing with error handling
- XSS prevention with proper text encoding

## Future Enhancements

Potential additions:
- More chart types (scatter, area, radar)
- Data export to multiple formats (Excel, PDF)
- Chart customization options
- Data sorting and pagination
- Dark mode toggle
- Chart animation options
- Multiple file comparison
- Data validation rules

## License

This project is open source and available for free use.

## Credits

Created as a comprehensive data visualization tool for analyzing structured data and hierarchical formats.

---

**Last Updated**: 2025-10-30

For questions, suggestions, or contributions, please open an issue or pull request.
