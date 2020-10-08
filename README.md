# PHP Rocket Notes

## Concept
I found with large projects, it was an insurmountable task to product unit tests for them, so I thought what if I recognised a stable version then from there could generate tests based on the results, storing them in dir and file hashes in a .rocket directory

## Steps
Initially you would run `rocket snapshot {directory}` this would run the code and the methods and try to gauge what their responses are in a production setting. 

Then you would run `rocket generate` This would then create tests based on the values generated in step one. 
