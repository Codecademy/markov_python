# markov_python
Markov Chain text generator module

## How to add this to your project
1. Clone this repository into your Python project folder. Alternatively, you can download the zip archive
2. Import this to your main project script `from markov_python.cc_markov import MarkovChain`


## How to use the Markov Chain text generator
1. After importing this module into your main project script, create an instance of MarkovChain and assign it to a variable. For example `mc = MarkovChain()`
2. Use one of the methods to read a local text file or a string. You can call this method multiple times to add additional data.
3. Call the `generate_text()` function to create text from the Markov Chain
