# Genezio FaaS Getting Started

In the index.mjs file, you will see the implementation of a function that writes something to the console and returns a 200 page with a simple message.

You can preview the function and add a ?name= URL parameter to see how it works.

Each function is exposed as an HTTP endpoint and can be called from a third-party application.

You can add new functions (new mjs files), but you'll need to add them in the functions section of genezio.yaml to ensure they are deployed and exposed.
