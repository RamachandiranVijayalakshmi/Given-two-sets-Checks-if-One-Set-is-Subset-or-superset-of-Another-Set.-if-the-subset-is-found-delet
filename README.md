## Given-two-sets-Checks-if-One-Set-is-Subset-or-superset-of-Another-Set.-if-the-subset-is-found-delete
## Sample code to check the details for gthe subset
```sh
print("First set is subset of second set -", firstSet.issubset(secondSet))
print("Second set is subset of First set - ", secondSet.issubset(firstSet))

```
## Example output
First Set  {57, 83, 29}
Second Set  {67, 73, 43, 48, 83, 57, 29}

First set is subset of second set - True
Second set is subset of First set -  False

First set is Super set of second set -  False
Second set is Super set of First set -  True

First Set  set()
Second Set  {67, 73, 43, 48, 83, 57, 29}
