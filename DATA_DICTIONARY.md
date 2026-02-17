# Data Dictionary — YouTube Travel Videos Metadata (Verified Index)

This dataset preserves all fields from the source JSONL/CSV without deleting or rewriting any values.

| Field | Type (CSV dtype) | Description |
|---|---|---|
| row_id | int64 | Field preserved from source metadata. |
| year | int64 | Field preserved from source metadata. |
| region | object | Field preserved from source metadata. |
| region_norm | object | Field preserved from source metadata. |
| title | object | Video title. |
| url | object | Canonical URL. |
| videoId | object | YouTube video identifier (primary join key). |
| videoId_is_valid | bool | YouTube video identifier (primary join key). |
| videoId_occurrences | int64 | YouTube video identifier (primary join key). |
| is_duplicate_videoId | bool | YouTube video identifier (primary join key). |
| views | float64 | View count (if captured). |
| views_raw | float64 | View count (if captured). |
| views_is_missing | bool | View count (if captured). |
| views_snapshot_date | object | Publish/upload date/time (as provided by source). |
| tags_list | object | Tags/keywords associated with the video. |
| tags | object | Tags/keywords associated with the video. |
| tags_raw | object | Tags/keywords associated with the video. |
| tag1 | object | Tags/keywords associated with the video. |
| tag2 | object | Tags/keywords associated with the video. |
| tag3 | object | Tags/keywords associated with the video. |
| tag4 | object | Tags/keywords associated with the video. |
| tag5 | object | Tags/keywords associated with the video. |
