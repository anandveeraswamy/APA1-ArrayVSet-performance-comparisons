# JavaScript Arrays vs Sets Learning Repository

## Learning Objectives 📒
- Understand the fundamental differences between Arrays and Sets in JavaScript
- Learn when to use each data structure effectively
- Apply knowledge through practical examples

## Repository Contents 📁

### Core Learning Files

#### 1. Basic Concepts
- **`1Arrays101.js`**: Introduction to JavaScript Arrays
  - Basic array operations and methods
  - Common array manipulation techniques
  - Understanding array behavior and usage

- **`2Sets101.js`**: Introduction to JavaScript Sets
  - Basic Set operations and methods
  - Set-specific features (uniqueness, has(), add(), delete())
  - Understanding Set behavior and usage

#### 2. Practical Application
- **`practicalApplication.js`**: Real-world example demonstrating Arrays vs Sets
  - Username validation and storage system
  - Side-by-side performance comparison
  - Demonstrates when to choose Arrays vs Sets in real scenarios

## Key Concepts to Understand 🗝️

### Arrays
- Ordered collection with index-based access
- Allows duplicate values
- Best for: ordered data, positional access, iteration
- Common operations: push, pop, slice, map, filter, reduce

### Sets
- Unordered collection of unique values
- Automatic duplicate removal
- Fast membership checking (O(1))
- Best for: uniqueness enforcement, fast lookups, set operations

### When to Use What
- **Use Arrays when:**
  - Order matters
  - You need duplicate values
  - You need index-based access
  - You're iterating sequentially

- **Use Sets when:**
  - You need guaranteed uniqueness
  - You frequently check if items exist
  - You perform set operations (union, intersection)
  - Order doesn't matter

## Running the Files 🚀
```bash
node 1Arrays101.js
node 2Sets101.js
node practicalApplication.js
```

## Learning Path 📚
1. Start with `1Arrays101.js` to understand arrays
2. Move to `2Sets101.js` to learn about sets
3. Explore `practicalApplication.js` to see real-world usage
4. Experiment by modifying the code and observing results