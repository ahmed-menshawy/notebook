## Leisch: Creating R Packages: A Tutorial
#### For creating an R *package* then your code must met some conditions:
1. Prettier formating of results.
2. Add utilities for fitted model like a _summary()_ to test the significance of the parameters.
3. Handling special cases i.e. in the case of linear regression you need to handle the categorical predictors
4. using convenient ways for users to provide input like using formulas for model specification in this case.

#### Using the power of object oriented programming in R:

- ***generic functions* or *method dispatch*:** make the function act based on the classes of the passed arguments.
- ***S3 and S4:*** objects, classes, and methods. ** S4 ** can help a lot in writing clean and consistent code, automatic checks if objects conform to class definitions. ** S3 ** has lesser features and hence easy to learn.

#### The S3 System:
