# Homepage

For full documentation visit [mkdocs.org](https://www.mkdocs.org).

**CI/CD Pipeline**
# **Application**
url: <https://us-east-1.console.aws.amazon.com/codesuite/codedeploy/applications?region=us-east-1>
![CICD_07](https://github.com/AmericanaExchange/RareBookHub/assets/817567/2ef166c8-1674-45aa-9df8-c4efcc4b4e95)

AWS CodeDeploy has two deployment groups. These groups have been created to facilitate different stages of a software deployment process. One of the deployment groups is designated for the QA phase, while the other is meant for the Staging phase.

<https://us-east-1.console.aws.amazon.com/codesuite/codedeploy/applications/AE20QA?region=us-east-1>
![CICD_06](https://github.com/AmericanaExchange/RareBookHub/assets/817567/202c8ec8-15aa-45d4-93e3-bad3ba1e1256)

# **Deployment history**
url: <https://us-east-1.console.aws.amazon.com/codesuite/codedeploy/deployments?region=us-east-1>
![CICD_05](https://github.com/AmericanaExchange/RareBookHub/assets/817567/0782d025-43de-4f82-bdc4-29d0524eb707)
# **Pipeline**
url: <https://us-east-1.console.aws.amazon.com/codesuite/codepipeline/pipelines?region=us-east-1>
![CICD_04](https://github.com/AmericanaExchange/RareBookHub/assets/817567/61498073-33f6-4b88-8c43-dcc8f8c67b89)
# **Source definition**
url: <https://us-east-1.console.aws.amazon.com/codesuite/codepipeline/pipelines/AE20QA/edit?region=us-east-1>
![CICD_03](https://github.com/AmericanaExchange/RareBookHub/assets/817567/1a905658-128c-4610-89b3-23650c58cfcd)
# **Repo and branch:**
![CICD_02](https://github.com/AmericanaExchange/RareBookHub/assets/817567/74b10349-5713-4230-b66e-ca0b8afc4a33)
# **Deployment steps:**
![CICD_01](https://github.com/AmericanaExchange/RareBookHub/assets/817567/012401d4-93d8-4eba-a5c4-7a786392a4f2)

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