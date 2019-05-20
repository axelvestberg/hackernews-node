# hackernews-node

## notes
- In chapter 3 there is an option to add crud for links, go back and try this out after finishing the barebones tutorial.
- I'm getting errors in chapter 8. Says createdAt_ASC is not a type LinkOrderByInput, but it is. Solve this before moving on.
> Error: Variable '$orderBy' expected value of type 'LinkOrderByInput' but got: "createdAt_ASC". Reason: Enum value 'createdAt_ASC' is undefined in enum type 'LinkOrderByInput'. Known values are: id_ASC, id_DESC, description_ASC, description_DESC, url_ASC, url_DESC. (line 1, column 57):
query ($where: LinkWhereInput, $skip: Int, $first: Int, $orderBy: LinkOrderByInput)