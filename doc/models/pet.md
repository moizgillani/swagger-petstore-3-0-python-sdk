
# Pet

## Structure

`Pet`

## Fields

| Name | Type | Tags | Description |
|  --- | --- | --- | --- |
| `name` | `string` | Required | - |
| `photo_urls` | `List of string` | Required | - |
| `id` | `long\|int` | Optional | - |
| `category` | [`Category`](../../doc/models/category.md) | Optional | - |
| `tags` | [`List of Tag`](../../doc/models/tag.md) | Optional | - |
| `pet_status` | [`PetStatusEnum`](../../doc/models/pet-status-enum.md) | Optional | pet status in the store |

## Example (as JSON)

```json
{
  "name": "doggie",
  "photoUrls": [
    "photoUrls5",
    "photoUrls6",
    "photoUrls7"
  ],
  "id": 10,
  "category": {
    "id": 232,
    "name": "name2"
  },
  "tags": [
    {
      "id": 239,
      "name": "name5"
    },
    {
      "id": 240,
      "name": "name6"
    }
  ],
  "petStatus": "pending"
}
```

