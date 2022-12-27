
# INotebook - Backend

It is built on top of Nodejs whis is used to server [front-end](https://github.com/vikas-viki/iNotebook-client/blob/master/README.md) with all the required data.

It has the Google login functionality and fetching the user specific notes and to do CRUD operation of note, it sotes the data in the mongodb local database (development).

### Technologies
- `express` -> For integrating backend.
- `bcryptjs` -> For storing the hashed passwords in the database.
- `mongoose` -> For storing the data.
- `jsonwebtoken` -> for validating the user.

### Endpoints

- `url/api/auth/createuser`
    
    Used for signing up a new user.
- `url/api/auth/login`

    For logging in the existing user.
- `url/api/auth/getuser`

    For getting all the notes details of the user.
- `url/api/notes/fetchallnotes`

    For fetching all the notes of the loggen in user.
- `url/api/notes/:name`

    For searching a specific note of the user.
- `url/api/notes/addnote`

    For creating a new note for the user.
- `url/api/notes/updatenote/:id`

    For updating a note of the user. 
- `url/api/notes/deletenote/:id`

    For deleting a specified note of the user.

## Contributing

Contributions are always welcome!

For front-end documentaion visit [docs](https://github.com/vikas-viki/iNotebook-client)

Thankyou!

