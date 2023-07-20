# Homepage

For full documentation visit [mkdocs.org](https://www.mkdocs.org).

## CI/CD Pipeline

**CI/CD Pipeline**
# **Application**
url: <https://us-east-1.console.aws.amazon.com/codesuite/codedeploy/applications?region=us-east-1>

AWS CodeDeploy has two deployment groups. These groups have been created to facilitate different stages of a software deployment process. One of the deployment groups is designated for the QA phase, while the other is meant for the Staging phase.

<https://us-east-1.console.aws.amazon.com/codesuite/codedeploy/applications/AE20QA?region=us-east-1>


# **Deployment history**
url: <https://us-east-1.console.aws.amazon.com/codesuite/codedeploy/deployments?region=us-east-1>

# **Pipeline**
url: <https://us-east-1.console.aws.amazon.com/codesuite/codepipeline/pipelines?region=us-east-1>

# **Source definition**
url: <https://us-east-1.console.aws.amazon.com/codesuite/codepipeline/pipelines/AE20QA/edit?region=us-east-1>

# **Repo and branch:**

# **Deployment steps:**


# **Some useful links:** 

pipeline definition https://us-east-1.console.aws.amazon.com/codesuite/codepipeline/start?region=us-east-1

deployments https://us-east-1.console.aws.amazon.com/codesuite/codedeploy/deployments?region=us-east-1

app definition https://us-east-1.console.aws.amazon.com/codesuite/codedeploy/applications?region=us-east-1


## Code Annotation Examples

### Codeblocks

Some `code` goes here.

### Plain codeblock

A plain codeblock:

```
Some code here
def myfunction()
// some comment
```

#### Code for a specific language

Some more code with the `py` at the start:

``` py
import tensorflow as tf
def whatever()
```

#### With a title

``` py title="bubble_sort.py"
def bubble_sort(items):
    for i in range(len(items)):
        for j in range(len(items) - 1 - i):
            if items[j] > items[j + 1]:
                items[j], items[j + 1] = items[j + 1], items[j]
```

#### With line numbers

``` py linenums="1"
def bubble_sort(items):
    for i in range(len(items)):
        for j in range(len(items) - 1 - i):
            if items[j] > items[j + 1]:
                items[j], items[j + 1] = items[j + 1], items[j]
```

#### Highlighting lines

``` py hl_lines="2 3"
def bubble_sort(items):
    for i in range(len(items)):
        for j in range(len(items) - 1 - i):
            if items[j] > items[j + 1]:
                items[j], items[j + 1] = items[j + 1], items[j]
```

## Icons and Emojs

:smile: 

:fontawesome-regular-face-laugh-wink:

:fontawesome-brands-twitter:{ .twitter }

:octicons-heart-fill-24:{ .heart }