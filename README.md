# BasketQuest Drills JSON

A JSON database of basketball training drills for the **BasketQuest** Android app.

This repository contains drill data including:

- Drill name
- Description
- Duration (minutes)
- Video URL (optional)

The app fetches this JSON dynamically, so new drills can be added without updating the app.

---

## Example Drill Entry

```json
{
  "id": 1,
  "name": "Free Throw Practice",
  "description": "Shoot 20 free throws, focus on form.",
  "duration": 5,
  "videoUrl": "https://example.com/free_throw.mp4"
}
