# Search-Format
While working on a task to align properties values from all environments and reduce the need for specific env values, I realized I need a script and just got a training on Python (Google tutorial); so here we go experimenting with Python while solving a problem.

Context:
Dev properties are contained in flat files in the code repo and used at build time to create configuration files (for JEE applications) that get loaded by the application at run time.
Prod properties are stored in DB and used during production release process to generate new flat files that get loaded by the application at run time.
