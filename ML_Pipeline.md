Pipelines are a simple way to keep your data preprocessing and modeling code organized. <br/>
Specifically, a pipeline bundles preprocessing and modeling steps so you can use the whole bundle as if it were a single step.<br/>

Pipelines have some important benefits. Those include:

**Cleaner Code:** Accounting for data at each step of preprocessing can get messy. With a pipeline, you won't need to manually keep track of your training and validation data at each step.<br/>
**Fewer Bugs:** There are fewer opportunities to misapply a step or forget a preprocessing step.<br/>
**Easier to Productionize:** It can be surprisingly hard to transition a model from a prototype to something deployable at scale. We won't go into the many related concerns here, but pipelines can help.<br/>
**More ways to Validate:**<br/>


**Machine Learning Pipeline:**<br/>

    Define Problem
        ML type of problem

    Prepare Data
        Data Visualization methos ...
        Data Selection
        Feature Selection methods ..
        Feature Engineering methods ..
        Data Transormation methods ..

    Spot Check Algorithm
        Test Harness ...
        Perform Measure ...
        Evaluate accuracy of different algorithms

    Improve Results
        Algorithms Turning methids
        ensemble methods

    Present Results
