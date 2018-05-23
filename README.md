I ran `nano README.md` to create an empty README file.

This is the second edit to my file.

README files are typically used to tell people what this 
project is for.
Try to be helpful to your future self and others.

Many times you'll have setup instructions and how to run 
the code in there.

the md extention here refers to "markdown" which is a 
short way of writing HTML, to make this think look 
"prettier".

# a quick intro to markdown:

# header 1
## header 2
### header 3
###### header 6

- bullet
* bullet
    - 4 spaces for a nested bullet

1. enum 1
2. enum 2
1. enum 3
1. enum 4

`inline code`

```r
v <- c(1, 2, 3, 4)
print(v)
```


# Intro to git branching

- use `git branch BRANCH_NAME` or `git checkout -b BRANCH_NAME` to create a branch.
    - if you use `git branch BRANCH_NAME` you also need to run `git checkout BRANCH_NAME`
    - `git branch -b BRANCH_NAME` will create and checkout at the same time
- use `git branch -a` to see all your branches

