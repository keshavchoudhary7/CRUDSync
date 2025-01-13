# CRUDSync Dashboard

CRUDSync is a web application that demonstrates fetching data from a dummy API and performing CRUD (Create, Read, Update, Delete) operations using Axios. This project is ideal for understanding how to interact with APIs effectively in a modern web application.

## Features

- **Fetch Data**: Retrieve and display data from a dummy API.
- **Create New Entries**: Add new data to the API.
- **Edit Existing Entries**: Update data seamlessly.
- **Delete Entries**: Remove data with ease.
- **User-Friendly Interface**: Intuitive UI for performing CRUD operations.

## Technologies Used

- **Frontend**: React.js with Vite
- **HTTP Client**: Axios
- **API**: Dummy API for testing purposes

## Getting Started

### Prerequisites

- Basic understanding of React.js.
- Node.js installed on your machine.

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/crudsync.git
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Start the development server:
   ```bash
   npm run dev
   ```

## Usage

1. Open the application in your web browser.
2. View data fetched from the dummy API.
3. Use the provided interface to create, update, or delete entries.

## File Structure

```
CRUDSync/
|-- public/             # Static assets
|-- src/                # Source code directory
    |-- components/     # React components
    |-- services/       # Axios logic for API interactions
    |-- App.jsx         # Main React component
    |-- main.jsx        # Entry point for the application
|-- vite.config.js      # Vite configuration
|-- tailwind.config.js  # Tailwind CSS configuration
|-- package.json        # Project dependencies and scripts
|-- README.md           # Project documentation
```

## API Reference

Using a dummy API, such as [JSONPlaceholder](https://jsonplaceholder.typicode.com/):

- **GET**: `/posts` - Retrieve all posts.
- **POST**: `/posts` - Create a new post.
- **PUT**: `/posts/:id` - Update an existing post.
- **DELETE**: `/posts/:id` - Delete a specific post.

## Contributing

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-branch-name
   ```
3. Commit your changes:
   ```bash
   git commit -m 'Add some feature'
   ```
4. Push to the branch:
   ```bash
   git push origin feature-branch-name
   ```
5. Submit a pull request.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

## Acknowledgments

- Thanks to [JSONPlaceholder](https://jsonplaceholder.typicode.com/) for the free dummy API.
- Inspired by learning CRUD operations using Axios and React.js.
