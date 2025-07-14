# AsaRepo

Collection of Portainer stack templates.

## Structure

- `templates.json`: Portainer template configuration referencing stack files in `templates/`.
- Templates are stored under `templates/<template>/docker-compose.yml`.

## Templates

- **MyLora**: AsaTyrs MyLora-Interface als Docker Stack.
- **One-Shot Dataset Prep**: OneShot Dataset Prep creates a small training set from a single image. The application consists of a Flask based web interface with optional user management. All binary dependencies are installed via the supplied maintainer.sh script.
- **VisionVault**: VisionVault is a lightweight image board tailored for AI-generated artwork. Uploaded files have their embedded metadata parsed automatically so you can search and organise creations by prompt, model and other parameters. The interface uses Bootstrap 5 for a responsive gallery experience.

Docker images will be added later.
