# Wiki Project

Wiki is a simple web-based encyclopedia that allows users to create, edit, and search for articles. Built using Django, it mimics the core functionality of Wikipedia, enabling users to contribute and manage content efficiently.

## Features

- **Create Articles**: Users can create new pages with Markdown-formatted content.
- **Edit Articles**: Existing pages can be edited directly through an intuitive interface.
- **Search Functionality**: Users can search for articles by title and receive a list of relevant results.
- **Random Page**: A feature that takes users to a random article.
- **Markdown to HTML Conversion**: Articles are stored in Markdown format and rendered as HTML.

## Technologies Used

- **Backend**: Django (Python)
- **Frontend**: HTML, CSS, Bootstrap

## Installation

To set up and run the project locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/theowla/wiki.git
   cd wiki
   ```

2. Create and activate a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Start the development server:
   ```bash
   python manage.py runserver
   ```

5. Open your browser and visit:
   ```
   http://127.0.0.1:8000
   ```

## Usage

- Navigate to the homepage to view existing articles.
- Use the search bar to find articles by title.
- Click on "Create New Page" to add a new article.
- Edit an existing article using the "Edit" button.
- Click "Random Page" to view a random article.

## Contributing

Contributions are welcome! If you'd like to improve this project:

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-branch
   ```
3. Make your changes and commit:
   ```bash
   git commit -m "Add new feature"
   ```
4. Push to your branch:
   ```bash
   git push origin feature-branch
   ```
5. Open a pull request!

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


