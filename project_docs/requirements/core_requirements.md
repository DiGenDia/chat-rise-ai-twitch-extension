# Core Requirements for Twitch AI Integration

## Functional Requirements
### Command Creation
- REQ-FR-CC-1: The system shall allow streamers to create custom commands.
- REQ-FR-CC-2: Each command shall be associated with a prompt template.
- REQ-FR-CC-3: Streamers shall be able to define parameters within the prompt templates.
- REQ-FR-CC-4: The system shall support different AI models.
- REQ-FR-CC-5: Streamers shall be able to specify the desired format for the AI's response.
- REQ-FR-CC-6: Streamers shall be able to configure a user cooldown for each command.
- REQ-FR-CC-7: Streamers shall be able to configure a session cooldown for each command.


### Command Execution
- REQ-FR-CE-1: Viewers shall be able to trigger commands via chat.
- REQ-FR-CE-2: The system shall send the appropriate parameters to the AI model based on the triggered command.
- REQ-FR-CE-3: The system shall display the formatted AI response in the chat.
- REQ-FR-CE-4: The system shall enforce user cooldowns for commands.
- REQ-FR-CE-5: The system shall enforce session cooldowns for commands.


### Bit Integration
- REQ-FR-BI-1: The system shall allow streamers to set a bit cost for command execution.
- REQ-FR-BI-2: The system shall only execute commands if the viewer has spent the required number of bits.

