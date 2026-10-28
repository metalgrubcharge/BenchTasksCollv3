# BenchTasksCollv3 Final Pool

This directory contains the final pool of tasks from BenchTasksCollv3 that have been
verified as fully implemented.

Each task is organized in its own directory following the standard task structure:
- docs/                 : task description and system prompt documents
- evaluation/           : evaluation script
- preprocess/           : preprocessing script (optional)
- groundtruth_workspace/: groundtruth reference data (optional)
- initial_workspace/    : initial workspace (optional)

A task is considered implemented when its required files (docs/task.md,
docs/agent_system_prompt.md, docs/user_system_prompt.md if present, evaluation/main.py)
are present and the prompt documents are non-empty and written in English.
