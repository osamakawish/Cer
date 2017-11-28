
# Contribution Guidelines

The majority of the guidelines for contributing here can all be determined by analyzing the original code and version control. It is not entirely necessary therefore, that you read this. You must simply go over the same notation of everything else you've read.

## Code

### Structure

#### Programming

#### SQL

##### Bookkeeping

For assets, use name `+AssetName`, and for liabilities, use `-LiabilityName`. This keeps things intuitive and easy to analyze.

### Documentation

## Version Control

### Structure

### Original Code

For direct changes to the original code, use the branch corresponding to the appropriate class.

### Tests

Tests belong to their own branch. If I want to test method `method(x,y)` in class `someClass`, I'd go under the `someClass` branch then the method branch and create a test branch. **DO NOT MERGE THE TEST BRANCH WITH THE ORIGINAL METHOD BRANCH - THAT IS FOR THE METHOD ITSELF.**

### Ideas

For your own ideas, create your own branch starting with your name. If your name is John Smith, and you want a new idea for a company logo, your notation should be `JohnSmith-company-logo`. Alternatively, you may create a branch under your own name within an appropriate branch, and then create a `company-logo` branch under that.
