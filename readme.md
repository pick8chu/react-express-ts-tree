docker compose up

## Backend:
#### endpoint
1. add new node
2. get all child nodes of a given node from the tree (only 1 layer) 
3. change the parent node of a given node

## Frontend:
#### basic UI
1. visualize the tree
2. adding new nodes to the tree

## etc.
node structure:
```json
{
    id: number,
    name: string,
    parentId: number,
    height: number,
} & ({
    role: "manager",
    department: string,
} | {
    role: "developer",
    programmingLanguage: string,
})
```