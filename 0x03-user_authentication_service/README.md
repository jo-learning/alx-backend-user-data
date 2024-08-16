# 0x03. User authentication service

## Routes
- `GET /`: returns logout message when user is logged out
- `GET /profile` returns email of logged in user
- `POST /users`: creates new user (Form data: `email`, `password`)
- `POST /sessions`: logs in existing user(Form data: `email`, `password`)
- `POST /reset_password`: returns password reset token (Form data: `email`)
- `PUT /reset_password`: updates existing user's password (Form data: `email`, `new_password`, `reset_token`)
- `DELETE /sessions`: logs out user
