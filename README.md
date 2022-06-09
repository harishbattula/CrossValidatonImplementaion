# Trian-Test-Split
Splitting Dataset for k fold cross validation from scratch using NumPy and Python.

# Stratified split: 
    1. It is way of splitting dataset into subsets such that each subset has same distribution of classes.
    2. For suppose let's say we have dataset 100 samples with 35 yes's and 65 no's as a targer values, 
        and let's say we want to devide dataset into 5 subsets.
    3. In a normal way we can split the dataset into 5 subsets each having 20 samples and we don't consider
        the number of yes's and no's in each subset.
    4. Example subsets may be (5, 15), (2, 18), (9, 11), (7, 13), (12, 8) --> (no of Yes's , no's). 
        And there are chances of getting 0 yes's and 20 no's or 20 yes's and 0 no's.
    5. To avoid this we use stratified splitting technique.
    6. We can split given dataset into into 5 equally distributed target subsets.
    7. e.g (7, 13), (7, 13), (7, 13), (7, 13), (7, 13).
# Why Stratified?
    Stratified random sampling ensures that each subgroup of a given population is adequately represented 
    within the whole sample population of a research study.
    
