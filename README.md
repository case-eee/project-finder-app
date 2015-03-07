### Basic Overview of Application
- A user can create many projects.
- A project can have many users working on it
- A user can work on many projects
- A user and project are connected through a 'committment'
- A user can comment on many projects.
- A project has many comments.

### Methods we want access to (by creating associations):
- `project.creator`
- `project.collaborators`
- `project.comments`
- `user.collaborations`
- `user.comments`
- `user.created_projects`
- `comment.author`
- `comment.project`

### Create User Authentication & Validations
be sure to implement user authentication using BCrypt
 a user must login in order to see their profile page - a page of all their created projects and committments
 validations on a user's name, email, and password (length of 6)

Create basic routes. What would the RESTful way of creating your routes be? Don't spend time fully building this application, but just build a few of the routes. How about a user viewing all of their projects (both created and committed to on the same page)? What route would indicate this?
