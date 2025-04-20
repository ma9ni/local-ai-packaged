# n8n Credentials

This directory stores n8n credential configurations. These are securely stored by n8n and encrypted with the encryption key specified in your environment variables.

**Important:** Do not manually edit credential files unless you know what you're doing.

When exporting/importing credentials between environments:
1. Use the n8n CLI export/import commands
2. Ensure the same encryption key is used in both environments
3. Check that all dependent services (APIs, databases, etc.) are accessible from the new environment 