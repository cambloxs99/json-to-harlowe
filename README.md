# JSON-to-Harlowe
Convert a JSON file to Twine Harlowe variables. Only unnested data is treated as variables.
# Usage
Use command line with an input JSON file and an output text file.<br>
Arguments:<br>
`input` - The `JSON` file to be converted<br>
`output` - A `.txt/.tw` file to write into. (Warning: Inside contents will be replaced)<br>
`vartype (optional)` - Either: "global" or "temp" variables (defaults to "temp")<br>
Example:
```bash
python convert_json_to_harlowe.py input.json output.tw temp
```
