Event Contract Field Notes

| Field | Type | Required | Validation |
|---|---|---|---|
| eventName | String | Yes | Must be SubmitStudentFile |
| submissionId | String | Yes | Must not be empty |
| studentId | String | Yes | Must use a synthetic student ID |
| fileName | String | Yes | Must contain a filename |
| fileType | String | Yes | Must be an allowed file type |
| fileSize | Number | Yes | Must be greater than 0 |
| submittedAt | String | Yes | Must contain a valid date/time |

Success Response

The system returns a submission ID and status when the file is accepted.

Error Response

The system returns an error message when the submission is invalid.
