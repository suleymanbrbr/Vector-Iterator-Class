# Vector-Iterator-Class

In this project, you are required to design and implement a templated vector class, myVector<T1, T2>, along with its corresponding iterator class, myVector<T1, T2>::Iterator, in C++. The myVector class should enable a variety of operations, utilizing a pair of template parameters: T1 for the value type and T2 for the unique key type. These operations will be driven by commands read from an input file.

<img width="658" alt="Screenshot 2024-01-22 at 14 46 31" src="https://github.com/suleymanbrbr/Vector-Iterator-Class/assets/111366311/69c58994-551c-4fcd-b928-d2cdc4b53f2f">

• A templated class myVector<T1, T2> which modifies std::vector and supports:

– Default and copy constructors.
– Adding and removing elements.
– Accessing and changing values of elements via subscript operator. 
– Copying a vector into another vector.
– Checking whether two vectors are equal or not.
– Processing the data according to the value type of the vector:
  ∗ If the value is string: calculate most frequent word and character for all values of the vector.
  ∗ If the value is arithmetic: calculate the mean, median, standard deviation, max and mode values for all values of the vector.
  
• An inner Iterator class for myVector which modifies std::vector::iterator and supports:

– A parametric constructor.
– Functions to print individual elements and the entire vector.
– Find any element of a myVector object given the key.
– Replace the current key of a given element in a myVector object with a new key.
