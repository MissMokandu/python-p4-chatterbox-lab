# TODO for Fixing SQLAlchemy Warnings

- [x] Add `from flask import abort` to server/app.py
- [x] Update the `update_message` route in server/app.py to use `db.session.get(Message, id)` and manual 404 check with `abort(404)`
- [x] Update the `delete_message` route in server/app.py to use `db.session.get(Message, id)` and manual 404 check with `abort(404)`
- [x] Update the `messages_by_id` route in server/app.py to use `db.session.get(Message, id)` and manual 404 check with `abort(404)`
- [ ] Run `python -m pytest` to verify tests pass without warnings
