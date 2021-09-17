# Analysis Of Pumpkin Market In US Using Scikit-learn:Linear Regression & Polynomial Regression

## Pumpkin Recipe

! [recipes] [recipes.png]

\_Preparation
As a reminder, you are loading this data so as to ask questions of it.

When is the best time to buy pumpkins?
What price can I expect of a case of miniature pumpkins?
Should I buy them in half-bushel baskets or by the 1 1/9 bushel box? Let's keep digging into this data.\_

A linear regression line

Show variable relationships. Show the relationship between variables
Make predictions. Make accurate predictions on where a new datapoint would fall in relationship to that line.

    STEP TAKEN

> 1. Prepare your data for regression
> 2. Building a linear model.

- Drop any null data and check once more what the data looks like.
- create a new dataframe from this minimal set and print it out:
  - 1 Now you can assign your X and y coordinate data:
  - 2 Next, start the regression model-building routines:
  - 3 You can visualize the line that's drawn in the process:
  - 4 Test the model against a hypothetical variety:

> A polynomial Regression

> Another type of linear regression is polynomial regression. While sometimes there's a linear relationship between variables - the bigger the pumpkin in volume, the higher the price - sometimes these relationships can't be plotted as a plane or straight line.

    STEP TAKEN

1.  Let's recreate a dataframe populated with a segment of the original pumpkin data:
2.  Use the Background_gradient() method with coolwarm as its argument value:
3.  Create a pipeline
    Scikit-learn includes a helpful API for building polynomial regression models - the make_pipeline API. A 'pipeline' is created which is a chain of estimators. In this case, the pipeline includes polynomial features, or predictions that form a nonlinear path.
    - Build out the X and y columns:
    - Create the pipeline by calling the make_pipeline() method:
4.  Create a sequence
    At this point, you need to create a new dataframe with sorted data so that the pipeline can create a sequence.
5.  Let's check the model's accuracy:
6.  Do a prediction, last step

Final Heatmap
! [poly] [heatmap.png]

## Example of Linear and polynomial Regression

! [poly] [linear-polynomial.png]
