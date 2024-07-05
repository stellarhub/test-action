# Combine Files Action

This action combines two input files into a single output file.

## Inputs

- `file1`: Path to the first input file
- `file2`: Path to the second input file
- `output`: Path for the output file

## Usage

```yaml
steps:
- uses: yourusername/combine-files-action@v1
  with:
    file1: 'path/to/file1.txt'
    file2: 'path/to/file2.txt'
    output: 'path/to/output.txt'
