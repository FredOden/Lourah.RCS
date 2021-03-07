<h1>Lourah Revision Control System</h1>
A Simple Revision Control System to manage simple project

A Middleware is in charge to interface actual project file tree
with the repository's history  management

Middleware interface:
<ul>
<li> Middleware(middlewareImplementation) where middlewareImplementation is a physical layer (http, https, filesystem, cloud ...)
in charge to manage the following functionalities
</li><li>create(repository) throws error if repositoty already exists
</li><li>delete(repository) throws error if repository do not exist
</li><li>use(repository) throws error if repository do not exist return a Repository object
</li>
Proof of concept: Sun Mar  7 16:31:28 CET 2021
</ul>
