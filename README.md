# File Helper
A single class library item written in C# that performs file related functions such as indexing, search, and moving. 

## Features
- Recursively index a directory of files.
- Search a directory of files.
- Access and write meta data.
- Move and rename a file.
- Requires no external libraries or dependencies.

## Examples
```
File testFile = new File("c://data/test.txt");
bool search = testFile.Search("cat");
bool index = testFile.Index();
bool rename = testFile.Rename("c://data/test-2.txt");
bool move = testFile.Move("c://data-2/"):
File testFile2 = new File();
testFile.InputString = "c://data/test.txt"
```

## Screenshots


## How It Works
- 

## Limitations

- Bad naming convention, conflicts with .Net File class