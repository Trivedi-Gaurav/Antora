# git.io

This is the build folder that the system generates when you run `npx antora --fetch antora-playbook.yml`. For the source content review [git-content](https://github.com/Trivedi-Gaurav/git-content) repository.

= Setting Up an FBC-Compatible Git Repository

== Example of an FBC-Compatible Git Repository Structure:

.Project Root
|
+-- Dockerfile (e.g., catalog.Dockerfile)
|
+-- Directory for the Targeted OCP Version (e.g., 4.12)
|   +-- devfile.yaml
|   +-- catalog
|       +-- catalog.yaml
|
+-- Directory for the Targeted OCP Version (e.g., 4.13)
|   +-- devfile.yaml
|   +-- catalog
|       +-- catalog.yaml
|
+-- README.md
