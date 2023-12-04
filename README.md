## MongoDB Random Data Generator

This script generates random data and inserts it into a MongoDB collection using Compass.

### Prerequisites

- MongoDB installed and running
- Compass installed

### Usage

1. Clone this repository or download the script file.
2. Open Compass and connect to your MongoDB server.
3. Select the target database in the left panel of Compass.
4. In the top panel of Compass, select the "Collection" tab and choose your target collection.
5. In the right panel of Compass, click on "Script" (the icon with the pencil).
6. In the script editor, replace `"your_collection_name"` with the name of your collection.
7. Specify the number of documents you want to generate by modifying the `numDocuments` variable.
8. Click the "Run" button (the green triangle) to execute the script and insert the generated data into the collection.

### Script Explanation

The script uses JavaScript to generate random data and insert it into the MongoDB collection. Here's a breakdown of the script:

- The `generateRandomData` function generates random data for each document.
- The `getRandomValue` function generates a random value for each field.
- The `numDocuments` variable specifies the number of documents to generate and insert.
- The script loops through the specified number of documents and inserts the generated data into the collection.

Please make sure you have the correct database and collection selected before running the script.

### License

This script is licensed under the [MIT License](LICENSE). Feel free to modify and use it according to your needs.

### Contributing

Contributions are welcome! If you have any suggestions or improvements for this script, please submit a pull request.

### Acknowledgements

This script was created with the help of MongoDB and Compass.

### Disclaimer

This script is provided as is without any warranty. Use it at your own risk.

### Contact

For any questions or inquiries, please contact [your_email@example.com](mailto:your_email@example.com).
