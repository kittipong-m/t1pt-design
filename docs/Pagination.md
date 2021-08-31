# Pagination

---

Request Parameters

| Query Param | Default | Minimum |
| ----------- | ------- | ------- |
| page        | 1       | 1       |
| limit       | 10      | 0       |

Response Template

```json
{
  "successful": true,
  "code": "00",
  "message": "Successful",
  "data": {
    "total": 1,
    "currentPage": 1,
    "totalPages": 1,
    .
    .
    .
  }
}
```

| Property    | Default (No data) | Minimum |
| ----------- | ----------------- | ------- |
| total       | 0                 | 0       |
| currentPage | 1                 | 1       |
| totalPages  | 1                 | 1       |
