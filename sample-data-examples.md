# Sample Data Examples for Dashboard Testing

This file contains sample data in various formats that you can use to test the Data Visualization Dashboard.

## CSV Examples

### Example 1: Sales Data
Save as `sales-data.csv`:
```csv
Product,Sales,Revenue,Region
Laptop,150,45000,North
Phone,280,28000,South
Tablet,95,19000,East
Monitor,120,24000,West
Keyboard,340,6800,North
Mouse,425,4250,South
Headphones,180,9000,East
Webcam,75,5250,West
```

### Example 2: Student Grades
Save as `student-grades.csv`:
```csv
Name,Math,Science,English,Average
Alice Johnson,95,88,92,91.67
Bob Smith,78,82,85,81.67
"Chen, Wei",90,95,88,91.00
Diana Lopez,85,90,93,89.33
```

### Example 3: Monthly Revenue
Save as `monthly-revenue.csv`:
```csv
Month,Revenue,Expenses,Profit
January,50000,35000,15000
February,52000,36000,16000
March,48000,34000,14000
April,55000,37000,18000
May,58000,38000,20000
June,60000,39000,21000
```

## JSON Examples

### Example 1: Company Structure
Save as `company.json`:
```json
{
  "company": {
    "name": "Tech Corp",
    "founded": 2020,
    "headquarters": "San Francisco, CA",
    "departments": [
      {
        "name": "Engineering",
        "employees": 50,
        "teams": [
          {
            "name": "Frontend",
            "members": 20,
            "technologies": ["React", "Vue", "Angular"]
          },
          {
            "name": "Backend",
            "members": 30,
            "technologies": ["Node.js", "Python", "Java"]
          }
        ]
      },
      {
        "name": "Sales",
        "employees": 25,
        "regions": ["North", "South", "East", "West"]
      },
      {
        "name": "Marketing",
        "employees": 15,
        "channels": ["Social Media", "Email", "Events"]
      }
    ],
    "products": {
      "software": ["App A", "App B", "Service C"],
      "hardware": ["Device X", "Device Y"]
    }
  }
}
```

### Example 2: Restaurant Menu
Save as `menu.json`:
```json
{
  "restaurant": "The Gourmet Kitchen",
  "menu": {
    "appetizers": [
      {
        "name": "Bruschetta",
        "price": 8.99,
        "vegetarian": true
      },
      {
        "name": "Calamari",
        "price": 12.99,
        "vegetarian": false
      }
    ],
    "entrees": [
      {
        "name": "Grilled Salmon",
        "price": 24.99,
        "sides": ["Rice", "Vegetables"]
      },
      {
        "name": "Pasta Carbonara",
        "price": 18.99,
        "sides": ["Garlic Bread", "Salad"]
      }
    ],
    "desserts": [
      {
        "name": "Tiramisu",
        "price": 7.99
      },
      {
        "name": "Chocolate Lava Cake",
        "price": 8.99
      }
    ]
  }
}
```

### Example 3: Book Collection
Save as `library.json`:
```json
{
  "library": {
    "name": "City Public Library",
    "collections": {
      "fiction": [
        {
          "title": "The Great Novel",
          "author": "Jane Doe",
          "year": 2020,
          "available": true
        },
        {
          "title": "Mystery at Midnight",
          "author": "John Smith",
          "year": 2019,
          "available": false
        }
      ],
      "non-fiction": [
        {
          "title": "History of Science",
          "author": "Dr. Alan Brown",
          "year": 2021,
          "available": true
        }
      ]
    }
  }
}
```

## XML Examples

### Example 1: Book Library
Save as `library.xml`:
```xml
<?xml version="1.0" encoding="UTF-8"?>
<library>
  <book id="1" category="programming">
    <title>JavaScript: The Complete Guide</title>
    <author>John Doe</author>
    <year>2023</year>
    <price currency="USD">49.99</price>
    <chapters>
      <chapter number="1">Introduction</chapter>
      <chapter number="2">Variables and Data Types</chapter>
      <chapter number="3">Functions</chapter>
      <chapter number="4">Objects and Arrays</chapter>
    </chapters>
  </book>
  <book id="2" category="web-development">
    <title>Modern Web Development</title>
    <author>Jane Smith</author>
    <year>2024</year>
    <price currency="USD">59.99</price>
    <chapters>
      <chapter number="1">HTML Basics</chapter>
      <chapter number="2">CSS Styling</chapter>
      <chapter number="3">JavaScript Fundamentals</chapter>
    </chapters>
  </book>
  <book id="3" category="database">
    <title>Database Design Patterns</title>
    <author>Bob Johnson</author>
    <year>2022</year>
    <price currency="USD">45.00</price>
  </book>
</library>
```

### Example 2: Product Catalog
Save as `products.xml`:
```xml
<?xml version="1.0" encoding="UTF-8"?>
<catalog>
  <product id="P001" featured="true">
    <name>Wireless Mouse</name>
    <category>Electronics</category>
    <price>29.99</price>
    <stock>150</stock>
    <specifications>
      <spec name="Battery Life">12 months</spec>
      <spec name="DPI">1600</spec>
      <spec name="Color">Black</spec>
    </specifications>
  </product>
  <product id="P002" featured="false">
    <name>USB-C Cable</name>
    <category>Accessories</category>
    <price>12.99</price>
    <stock>300</stock>
    <specifications>
      <spec name="Length">2m</spec>
      <spec name="Color">White</spec>
    </specifications>
  </product>
</catalog>
```

### Example 3: Employee Directory
Save as `employees.xml`:
```xml
<?xml version="1.0" encoding="UTF-8"?>
<company>
  <employees>
    <employee id="E001">
      <name>Alice Johnson</name>
      <department>Engineering</department>
      <position>Senior Developer</position>
      <email>alice.johnson@company.com</email>
      <skills>
        <skill level="expert">JavaScript</skill>
        <skill level="advanced">Python</skill>
        <skill level="intermediate">Java</skill>
      </skills>
    </employee>
    <employee id="E002">
      <name>Bob Smith</name>
      <department>Marketing</department>
      <position>Marketing Manager</position>
      <email>bob.smith@company.com</email>
      <skills>
        <skill level="expert">Social Media</skill>
        <skill level="advanced">Content Creation</skill>
      </skills>
    </employee>
  </employees>
</company>
```

## RDF/Turtle Examples

### Example 1: People and Organizations
Save as `people.rdf`:
```turtle
@prefix ex: <http://example.org/> .
@prefix rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#> .
@prefix foaf: <http://xmlns.com/foaf/0.1/> .

ex:Person1 rdf:type foaf:Person .
ex:Person1 foaf:name "Alice Johnson" .
ex:Person1 ex:age "30" .
ex:Person1 ex:worksAt ex:Company1 .
ex:Person1 ex:email "alice@example.com" .

ex:Person2 rdf:type foaf:Person .
ex:Person2 foaf:name "Bob Smith" .
ex:Person2 ex:age "35" .
ex:Person2 ex:worksAt ex:Company1 .

ex:Company1 rdf:type ex:Organization .
ex:Company1 ex:name "TechCorp" .
ex:Company1 ex:location "San Francisco" .
ex:Company1 ex:industry "Technology" .
```

### Example 2: Product Information
Save as `products.rdf`:
```turtle
@prefix ex: <http://example.org/product/> .
@prefix rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#> .

ex:Product1 rdf:type ex:ElectronicDevice .
ex:Product1 ex:name "Laptop Pro" .
ex:Product1 ex:price "1299.99" .
ex:Product1 ex:manufacturer "TechBrand" .
ex:Product1 ex:inStock "true" .

ex:Product2 rdf:type ex:ElectronicDevice .
ex:Product2 ex:name "Wireless Mouse" .
ex:Product2 ex:price "29.99" .
ex:Product2 ex:manufacturer "GadgetCo" .
ex:Product2 ex:inStock "true" .

ex:Product3 rdf:type ex:Book .
ex:Product3 ex:name "Programming Guide" .
ex:Product3 ex:price "49.99" .
ex:Product3 ex:author "John Doe" .
```

## How to Use These Examples

1. Copy the content of any example
2. Save it to a file with the appropriate extension (.csv, .json, .xml, .rdf)
3. Open `data-visualization-dashboard.html` in your browser
4. Upload the file using drag-and-drop or the file picker
5. Explore the visualizations and use the filters!

## Tips

- **CSV**: Best for tabular data with rows and columns
- **JSON**: Ideal for nested hierarchical data structures
- **XML**: Good for document-oriented data with attributes
- **RDF**: Perfect for semantic web data and relationships

## Testing Filters

- Try filtering CSV data by different products or categories
- Search for specific terms in the data tables
- Expand/collapse tree nodes in JSON/XML visualizations
- Use the search in tree feature to find specific nodes
