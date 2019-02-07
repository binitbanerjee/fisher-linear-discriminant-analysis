# fisher-linear-discriminant-analysis
A sample program showing the LDA approach to classify the Iris data set.
Algo:
Seperate the patterns into three subsets of 1 vs all:
calculate the Sw and Sb matrix to get the eigen value relations to the Weight matrix w.
take the eigen value corresponing to the largest eigen vector and treat it as the new weight vector.
project the class data onto the eigen vector to get the classification.


Observation:
setosa is easily classified.
versicolor and verginica gives error.

Instruction:
Run the code in Jupyter notebook.
update the file path to reflect your local location of the iris.csv dataset.
select the class you want to classify in one vs all by updating the variable.
verify results in plot.

