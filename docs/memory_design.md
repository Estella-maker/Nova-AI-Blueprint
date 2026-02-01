# Nova AI – Memory System Design

## Memory Types

### 1. Short-Term Memory
- Stores recent conversation context
- Cleared after session ends

### 2. Long-Term Memory
- Stores:
  - User preferences
  - Past important commands
  - Personal assistant behavior settings

## Storage Format

### Option A: JSON
```json
{
  "user_profile": {
    "name": "User",
    "preferred_language": "English",
    "voice": "Male"
  },
  "memories": [
    {
      "timestamp": "2026-02-01",
      "type": "preference",
      "content": "User prefers dark mode."
    }
  ]
}
