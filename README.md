# matrix-factorize-dimsum
### Matrix Factorization in Distributed Settings

Implementation of the matrix factorization techniques in distributed settings using MapReduce paradigm. 

Main Reference: [Dimension Independent Matrix Square using
MapReduce (DIMSUM)](https://arxiv.org/pdf/1304.1467.pdf)


## Dependencies

The code has been written using Python 3.6 and following dependencies:
- pyspark: 3.0.0
- findspark: 1.4.2
- scipy: 1.5.1
- numpy: 1.19.0

## Instructions

### Code Execution 
The main code is in `pyspark-main.ipynb` 
- Execution of the code should be carried out sequentially as there is severe re-referencing
- The notebooks contains helpful comments wherever required

### Generating Dataset
Clone the repository in a place which doesn't require permissions to write data. The code in the notebook starts with generating some directories and then place the required dataset files inside them. 

