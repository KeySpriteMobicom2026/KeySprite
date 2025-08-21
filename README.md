# Multi-Agent Conversation Dataset

This repository contains a dataset of multi-agent conversations generated using DeepSeek and ChatGPT-4, featuring diverse agent profiles and their interactions.

## Dataset Overview

This dataset consists of three main components:

1. **Agent Profiles (Human Readable)** - Detailed character descriptions in text format
2. **Agent Profiles (JSON)** - Structured agent data in JSON format
3. **Cleaned Conversations** - Multi-turn conversations between different agent pairs

## Directory Structure

```
├── agent_profiles_human_readable/    # Human-readable agent profiles (.txt)
├── agent_profiles_json/              # Structured agent profiles (.json)
└── cleaned_conversations/            # Multi-agent conversation data (.txt)
```

## Data Description

### Agent Profiles

The dataset contains 50 unique agent profiles (ID: 01-50), each with:

- **Basic Information**: Name, age, profession
- **Personality & Hobbies**: Detailed character traits and interests
- **Language Portrait**:
  - Native language
  - Code-switching frequency (中频/低频/高频)
  - Detailed language habits including emoji usage patterns

#### Example Agent Profile (ID: 01)
- **Name**: Ethan Carter
- **Profession**: Linguistics Research Assistant
- **Personality**: Curious and analytical individual with passion for languages
- **Language Habit**: Frequent code-switching between English and Chinese, strategic emoji usage

### Conversations

The conversation files follow the naming pattern: `{conversation_id}_{AgentA}_vs_{AgentB}.txt`

Each conversation contains:
- Multi-turn dialogues between two agents
- Natural language interactions reflecting agent personalities
- Code-switching between English and Chinese
- Emoji usage patterns
- Topic diversity ranging from casual chat to academic discussions

#### Example Conversation Topics
- Mobile games and digital entertainment
- Academic discussions and research
- Personal interests and hobbies
- Cultural references and language learning

## Data Format

### Agent Profiles (JSON)
```json
{
  "name": "Agent Name",
  "profession": "Professional Role",
  "personalityAndHobbies": "Detailed description...",
  "codeSwitchFrequency": "中频/低频/高频",
  "languageHabit": "Detailed language behavior description..."
}
```

### Agent Profiles (Human Readable)
Text files with structured sections including:
- Basic information
- Language portrait
- Detailed personality descriptions

### Conversations
Plain text files with turn-based dialogue format:
```
[A]: Speaker A's message
[B]: Speaker B's response
```

## Generation Notes
- Dialogues were produced using both DeepSeek and ChatGPT-4.
- Profiles were authored to encourage personality-driven, code-switching dialogues.

## License
This dataset is provided for research purposes. Please respect the terms of use and attribution requirements.

## Contact
For questions or collaboration opportunities, please contact the KeySprite research team.
