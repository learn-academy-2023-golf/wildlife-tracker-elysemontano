# Rails API

- API (Application Programming Interface): responsible for transmitting info across the internet as JSON

- JSON(JavaScript Object Notation): Data structure that is supported by most programming languages.  Array of objects.

## RESTful Routes

- Index: Gets a list of all data
- Show: Shows a single instance
- New: Gets form
- Create: Creates new instance
- Edit: Gets form
- Update: Updaate an instance
- Destroy: deletes an instance


## API RESTful Routes
- Index: Gets a list of all data
- Show: Shows a single instance
- Create: Creates new instance
- Update: Update an instance
- Destroy: deletes an instance


### Index
- Create index method in controller
- run server
- open postman
- Set request to GET
- URL: localhost:3000/students
- Ensure format is set to JSON

### Show
- Create show method in controller
- Set request to GET
- URL: localhost:3000/students/1

### Create
- Create the create method in controller
- Set request to POST
- URL: localhost:3000/students
- Provide content in body section of Postman
- Select: Body, Raw, Text -> JSON
- Disable authenticity token so Postman and Rails can interact

### Update
- Create the update method in controller
- Set request to PATCH or PUT
- URL: localhost:3000/students/4
- Provide content in body section of Postman

### Destroy
- Create the destroy method in controller
- Set request to DELETE
- URL: localhost:3000/students/4
- If successful, I should see the student
- Double check by running the index method to see instance has been removed