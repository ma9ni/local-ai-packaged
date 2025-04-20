# n8n Workflows

This directory stores your n8n workflow configurations in JSON format. These files are automatically loaded by n8n at startup.

## Workflow File Format

Each workflow is stored as a JSON file with the following key properties:
- `name`: The name of the workflow (appears in the UI)
- `nodes`: Array of nodes in the workflow
- `connections`: How the nodes are connected
- `active`: Whether the workflow is active (set to true to auto-activate)
- `settings`: Workflow-specific settings
- `tags`: Optional tags for organization

## Importing/Exporting

Workflows can be:
1. Imported through the n8n UI
2. Created directly in the UI and they'll be saved here
3. Exported to these files for version control or backup
4. Copied between environments

## Example

This directory includes a sample "Hello World" workflow to demonstrate the format.
You can edit it in n8n UI after starting the service. 