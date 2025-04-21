# SHACL Validation Example

This project demonstrates how to use PySHACL for validating RDF data against SHACL shapes. It includes a simple library system example with books and authors.

## Project Structure

- `ontology.ttl` - Defines the classes and properties for our library system
- `data.ttl` - Contains sample RDF data about books and authors
- `shapes.ttl` - Contains SHACL shapes for validating the data
- `jupyter-notebook.ipynb` - Interactive notebook demonstrating the validation process

## Requirements

- Python 3.6+
- rdflib
- pyshacl
- jupyter

## Installation

1. Clone the repository:
   ```bash
   git clone [your-repo-url]
   cd validation-using-pyshacl
   ```

2. Create and activate a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Start Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

2. Open `jupyter-notebook.ipynb` and run the cells to see the validation in action.

## Example Data

The example includes:
- A simple library ontology with Books and Authors
- Sample data with both valid and invalid entries
- SHACL shapes that validate:
  - Required properties
  - Data types
  - Value ranges
  - Pattern matching

## License

[Your chosen license]
