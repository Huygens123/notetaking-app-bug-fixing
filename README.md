# notetaking-app-bug-fixing

## Bug Fixes and Improvements:

	Added GET method to the route decorator to handle both GET and POST requests.
	Changed request.args.get("note") to request.form.get("note") to correctly retrieve form data.
	Added a check to ensure that notes are only appended if the note is not empty.
	Updated the HTML template to use the correct form method and action.
	Displayed notes in an unordered list (<ul>) for better readability.
