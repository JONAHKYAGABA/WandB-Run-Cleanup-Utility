# WandB-Run-Cleanup-Utility
WandB Run Cleanup Utility
This Python script automates the management of experiment runs logged in Weights & Biases. It allows users to iterate over all runs in a given project and delete those that are in a failed or crashed state, based on creator identity.

✅ Features
🔍 Lists all runs for a specific WandB project

🧠 Filters runs by:

Run state (failed, crashed)

Creator username (matches the user running the script)

🗑️ Automatically deletes filtered runs

🔐 Uses secure API authentication via wandb.login()
