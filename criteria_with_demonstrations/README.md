# Data
Each line in a `.jsonl` file represents an aspect for that task. The data format is like the following:
```json
{
  "aspect_id": "<The aspect ID>",
  "aspect_guideline": "<The section text taken from the original guideline>",
  "criteria": "<The criteria string>",
  "demonstrations": "<Our constructed four demonstrations>"
}
```
For the paper introduction task, we constructed four demonstrations, but due to the limited length of the models' context, we only used the first and second demonstrations.