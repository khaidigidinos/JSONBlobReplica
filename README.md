# JSONBlobReplica

## Steps to run
1. Clone this repository
2. Ensure that Node.js have been installed on your machine.
3. Open CMD then direct to the working directory of the cloned code.
4. Run `npm install` to download all dependencies.
5. Then, run `node replicate-jsonblob-api.js`. Now, your application is serving on http://localhost:3000

## Note: There are only 4 available routes:
1. POST /api - create a new JSON document and save it into a file having a unique id, return the id
2. GET /api/:id - retrieve a JSON document from a file
3. PUT /api/:id - update the content of a JSON document with new content and store it into the same file  
4. DELETE /api/:id - reset the content of the JSON document
