### To clean venv and node_modules from specific folders

for /d /r . %d in (.venv node_modules) do @if exist "%d" rd /s /q "%d"

for /d /r . %d in (.venv node_modules) do @if exist "%d" echo "%d"
