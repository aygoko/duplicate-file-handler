# Duplicate File Handler
Duplicate File Handler is a command-line tool that allows the user to find and delete duplicate files. The program is written in Go and utilizes the MD5 hash to compare file contents for duplicates.

## Installation
To install the application, you will need to have [Go](https://go.dev/) installed on your machine. Once you have installed Go, follow the steps below:

Clone the repository to your machine:

```
git clone https://github.com/username/duplicate-file-handler.git
```
Replace username with your GitHub username.


Navigate to the cloned repository:

```
cd duplicate-file-handler
```
Build the application:
```
go build
```
Run the application:

```
./duplicate-file-handler
```
## Usage 
When you run the application, you will be prompted to enter a directory path and a file extension to search for. 

After entering the required information, Duplicate File Handler will display the indexed files and prompt you to select a sorting option. 
Once you have selected a sorting option, application  will sort the remaining files based on their size and display them to you.

You can choose to check for duplicates by entering 'yes' or 'no' when prompted. 

If you choose to check for duplicates, Duplicate File Handler will calculate an MD5 hash of each file's contents to find duplicate files.

It will then display the duplicate files to you and prompt you to select which files to delete. 

Finally, the program will delete the selected files and display the amount of disk space that was freed up.

## License
Duplicate File Handler is open-source software released under the MIT license.
