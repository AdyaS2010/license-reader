# License Plate Reader

## Description
This project is a license plate reader written in C. It reads license plate numbers from a file and stores them in an array. The program then prints the license plate numbers and frees the allocated memory.

## Features
- Read license plate numbers from a file
- Store license plate numbers in an array
- Print the license plate numbers
- Free allocated memory

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/license-reader.git
   ```
2. Navigate to the project directory:
   ```bash
   cd license
   ```
3. Compile the code:
   ```bash
   make license
   ```

## Usage
1. Run the application:
   ```bash
   ./license infile
   ```
   Replace `infile` with the path to the input file containing the license plate numbers.

## Example
```bash
$ ./license plates.txt
11ZT00
1KAD21
78ZZ01
99ZZ11
72ZZ21
98ZZ31
44ZW41
34ZZ51
```

![image](https://github.com/user-attachments/assets/0d7d7d2b-a052-4aee-95b1-13cf85c6f037)

![image](https://github.com/user-attachments/assets/e19296ea-f156-4e51-9455-caf4dd94f566)
*Reads data from the infile, and outputs it, as shown!*

## Contributing
1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. Make your changes and commit them:
   ```bash
   git commit -m 'Add some feature'
   ```
4. Push to the branch:
   ```bash
   git push origin feature/your-feature-name
   ```
5. Open a pull request.

## License
This project is not licensed under any License currently.
