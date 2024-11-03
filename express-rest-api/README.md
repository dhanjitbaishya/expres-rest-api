# Express T-Shirt API
A simple REST API built with Express.js that allows users to get information about t-shirts and customize them by adding logos.

## Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```
2. Navigate into the project folder:
   ```bash
   cd express-tshirt-api
   ```
3. Install dependencies:
   ```bash
   npm install
   ```

## Usage

Start the server:
```bash
npm start


### 4. **API Endpoints**
- Document each endpoint with details on how to use it, request parameters, and responses.

```markdown
## API Endpoints

### GET /tshirt
- **Description**: Returns information about a default t-shirt.
- **Response**:
  ```json
  {
    "tshirt": "👕",
    "size": "large"
  }
  ```

### POST /tshirt/:id
- **Description**: Adds a custom logo to a t-shirt with the specified ID.
- **Parameters**:
  - `id` (URL parameter): The ID of the t-shirt.
  - `logo` (in JSON body): The logo text.
- **Example Request**:
  ```json
  POST /tshirt/123
  {
    "logo": "Nike"
  }
  ```
- **Example Response**:
  ```json
  {
    "tshirt": "👕 with your Nike and ID of 123"
  }
  ```

## Technologies Used
- Node.js
- Express.js

## Contributing
Contributions are welcome! Feel free to open an issue or submit a pull request.

